# Comparing `tmp/jcmutils-1.5.9.tar.gz` & `tmp/jcmutils-1.6.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "jcmutils-1.5.9.tar", last modified: Tue May 23 11:11:52 2023, max compression
+gzip compressed data, was "jcmutils-1.6.0.tar", last modified: Wed Jun 28 06:12:50 2023, max compression
```

## Comparing `jcmutils-1.5.9.tar` & `jcmutils-1.6.0.tar`

### file list

```diff
@@ -1,18 +1,18 @@
-drwxrwxr-x   0 junquan   (1002) junquan   (1003)        0 2023-05-23 11:11:51.999141 jcmutils-1.5.9/
--rw-rw-r--   0 junquan   (1002) junquan   (1003)     1073 2023-04-15 12:55:54.000000 jcmutils-1.5.9/LICENSE
--rw-rw-r--   0 junquan   (1002) junquan   (1003)      332 2023-05-23 11:11:51.999141 jcmutils-1.5.9/PKG-INFO
--rw-rw-r--   0 junquan   (1002) junquan   (1003)     3044 2023-05-17 04:08:25.000000 jcmutils-1.5.9/README.md
-drwxrwxr-x   0 junquan   (1002) junquan   (1003)        0 2023-05-23 11:11:51.999141 jcmutils-1.5.9/jcmutils/
--rw-rw-r--   0 junquan   (1002) junquan   (1003)      165 2023-05-17 04:08:25.000000 jcmutils-1.5.9/jcmutils/__init__.py
--rw-rw-r--   0 junquan   (1002) junquan   (1003)    13888 2023-05-23 11:11:08.000000 jcmutils-1.5.9/jcmutils/dataset_utils.py
--rw-rw-r--   0 junquan   (1002) junquan   (1003)     2151 2023-04-15 12:55:54.000000 jcmutils-1.5.9/jcmutils/gen_sources.py
--rw-rw-r--   0 junquan   (1002) junquan   (1003)     1496 2023-05-17 04:08:25.000000 jcmutils-1.5.9/jcmutils/logger.py
--rw-rw-r--   0 junquan   (1002) junquan   (1003)     8780 2023-05-17 04:08:25.000000 jcmutils-1.5.9/jcmutils/solver.py
-drwxrwxr-x   0 junquan   (1002) junquan   (1003)        0 2023-05-23 11:11:51.999141 jcmutils-1.5.9/jcmutils.egg-info/
--rw-rw-r--   0 junquan   (1002) junquan   (1003)      332 2023-05-23 11:11:51.000000 jcmutils-1.5.9/jcmutils.egg-info/PKG-INFO
--rw-rw-r--   0 junquan   (1002) junquan   (1003)      294 2023-05-23 11:11:51.000000 jcmutils-1.5.9/jcmutils.egg-info/SOURCES.txt
--rw-rw-r--   0 junquan   (1002) junquan   (1003)        1 2023-05-23 11:11:51.000000 jcmutils-1.5.9/jcmutils.egg-info/dependency_links.txt
--rw-rw-r--   0 junquan   (1002) junquan   (1003)       38 2023-05-23 11:11:51.000000 jcmutils-1.5.9/jcmutils.egg-info/requires.txt
--rw-rw-r--   0 junquan   (1002) junquan   (1003)        9 2023-05-23 11:11:51.000000 jcmutils-1.5.9/jcmutils.egg-info/top_level.txt
--rw-rw-r--   0 junquan   (1002) junquan   (1003)       38 2023-05-23 11:11:51.999141 jcmutils-1.5.9/setup.cfg
--rw-rw-r--   0 junquan   (1002) junquan   (1003)      539 2023-05-23 11:11:25.000000 jcmutils-1.5.9/setup.py
+drwxrwxr-x   0 junquan   (1002) junquan   (1003)        0 2023-06-28 06:12:50.342671 jcmutils-1.6.0/
+-rw-rw-r--   0 junquan   (1002) junquan   (1003)     1073 2023-04-15 12:55:54.000000 jcmutils-1.6.0/LICENSE
+-rw-rw-r--   0 junquan   (1002) junquan   (1003)      332 2023-06-28 06:12:50.342671 jcmutils-1.6.0/PKG-INFO
+-rw-rw-r--   0 junquan   (1002) junquan   (1003)     3044 2023-05-17 04:08:25.000000 jcmutils-1.6.0/README.md
+drwxrwxr-x   0 junquan   (1002) junquan   (1003)        0 2023-06-28 06:12:50.342671 jcmutils-1.6.0/jcmutils/
+-rw-rw-r--   0 junquan   (1002) junquan   (1003)      165 2023-05-17 04:08:25.000000 jcmutils-1.6.0/jcmutils/__init__.py
+-rw-rw-r--   0 junquan   (1002) junquan   (1003)    15916 2023-06-28 06:11:57.000000 jcmutils-1.6.0/jcmutils/dataset_utils.py
+-rw-rw-r--   0 junquan   (1002) junquan   (1003)     2151 2023-04-15 12:55:54.000000 jcmutils-1.6.0/jcmutils/gen_sources.py
+-rw-rw-r--   0 junquan   (1002) junquan   (1003)     1496 2023-05-17 04:08:25.000000 jcmutils-1.6.0/jcmutils/logger.py
+-rw-rw-r--   0 junquan   (1002) junquan   (1003)     8780 2023-05-17 04:08:25.000000 jcmutils-1.6.0/jcmutils/solver.py
+drwxrwxr-x   0 junquan   (1002) junquan   (1003)        0 2023-06-28 06:12:50.342671 jcmutils-1.6.0/jcmutils.egg-info/
+-rw-rw-r--   0 junquan   (1002) junquan   (1003)      332 2023-06-28 06:12:50.000000 jcmutils-1.6.0/jcmutils.egg-info/PKG-INFO
+-rw-rw-r--   0 junquan   (1002) junquan   (1003)      294 2023-06-28 06:12:50.000000 jcmutils-1.6.0/jcmutils.egg-info/SOURCES.txt
+-rw-rw-r--   0 junquan   (1002) junquan   (1003)        1 2023-06-28 06:12:50.000000 jcmutils-1.6.0/jcmutils.egg-info/dependency_links.txt
+-rw-rw-r--   0 junquan   (1002) junquan   (1003)       38 2023-06-28 06:12:50.000000 jcmutils-1.6.0/jcmutils.egg-info/requires.txt
+-rw-rw-r--   0 junquan   (1002) junquan   (1003)        9 2023-06-28 06:12:50.000000 jcmutils-1.6.0/jcmutils.egg-info/top_level.txt
+-rw-rw-r--   0 junquan   (1002) junquan   (1003)       38 2023-06-28 06:12:50.342671 jcmutils-1.6.0/setup.cfg
+-rw-rw-r--   0 junquan   (1002) junquan   (1003)      539 2023-06-28 06:12:10.000000 jcmutils-1.6.0/setup.py
```

### Comparing `jcmutils-1.5.9/LICENSE` & `jcmutils-1.6.0/LICENSE`

 * *Files identical despite different names*

### Comparing `jcmutils-1.5.9/README.md` & `jcmutils-1.6.0/README.md`

 * *Files identical despite different names*

### Comparing `jcmutils-1.5.9/jcmutils/dataset_utils.py` & `jcmutils-1.6.0/jcmutils/dataset_utils.py`

 * *Files 15% similar despite different names*

```diff
@@ -59,48 +59,48 @@
 
         # 保存超分辨（原图）
         cv2.imwrite(target_filename + "_origin.jpg",afield)
 
         # 通过每个像素点代表的实际物理尺寸来计算缩放比比例
         scale_factor =source_density*1.0/target_density
         # 缩放电场/光强场到对应的大小
-        scaled_field = cv2.resize(output_image, None, fx=scale_factor,# type: ignore
+        scaled_field = cv2.resize(afield, None, fx=scale_factor,# type: ignore
                                   fy=scale_factor, interpolation=cv2.INTER_LINEAR)  
 
         # 绘图
         logger.debug(f"printing max value of results:{np.max(total_results)}")
         cv2.imwrite(target_filename + ".jpg",scaled_field)
         logger.info("all target image saved completed!")
 
 
 
-    def export_dataset(self, num_of_result, source_density, target_density,target_filename,phi0,defect_size, vmax, is_light_intense=True, is_symmetry=False):
+    def export_dataset(self, num_of_result, source_density, target_density,target_filename,phi0,defect_size, vmax,signal_level=0.4,noise_level = 5, is_light_intense=True, is_symmetry=False):
         # 路径预处理
         if not os.path.exists(os.path.dirname(target_filename)):
             os.makedirs(os.path.dirname(target_filename))
         yamlpath =os.path.join(os.path.dirname(self.jcmp_path),"properties.yaml")
         
         # 解析YAML，准备必须的数据
         with open(yamlpath) as f:
             data = yaml.load(f,Loader=yaml.FullLoader)
-        lattice_vector_length = data['latticeVector']['latticeVectorLength']
-        lattice_angle = data['latticeVector']['latticeAngle']
-        center_pos = data['centerPos']
-        shift = data['shift']
+        # lattice_vector_length = data['latticeVector']['latticeVectorLength']
+        # lattice_angle = data['latticeVector']['latticeAngle']
+        # center_pos = data['centerPos']
+        # shift = data['shift']
         nodefect_phi0_0 = data['nodefect']['phi0-0']
         nodefect_phi0_90 = data['nodefect']['phi0-90']
-        origin_size = data['originSize'] 
+        # origin_size = data['originSize'] 
         
         # 获取模板图像
         if phi0 == 90:
             template_path = nodefect_phi0_90
         else:
             template_path = nodefect_phi0_0
         template_image = cv2.imread(template_path,cv2.IMREAD_GRAYSCALE)
-        origin_image_size = template_image.shape
+        # origin_image_size = template_image.shape
         
         # 确定缺陷类别
         defect_class = 2
         if "instruction" in target_filename:
             defect_class = 0
         elif "particle" in target_filename:
             defect_class = 1
@@ -127,64 +127,113 @@
                 logger.debug("key was rotated for symmetry")
         
         # 合并最终结果
         vmaxa = np.max(total_results) if vmax is None else vmax
         afield = (total_results/ vmaxa)*235
         afield = np.rot90(afield)
 
-        # # 确定缺陷在原始图像中的位置
-        # xpos = (self.keys[0]['defectpos'][0] - origin_size['x'][0])* 1.0/( origin_size['x'][1] - origin_size['x'][0]) * origin_image_size[0]
-        # ypos = origin_image_size[1]-((self.keys[0]['defectpos'][1] - origin_size['y'][0]) * 1.0/(origin_size['y'][1] - origin_size['y'][0]) * origin_image_size[1])
-        # shift_pix = defect_size*1.0/source_density
-        # roi = [xpos - shift_pix , xpos + shift_pix, ypos - shift_pix ,ypos + shift_pix]
-        # roi = np.ceil(roi)
-        # roi = roi.astype(np.int32)
+        (output_image,(xpos,ypos,width,height)) = self.__process_image(afield,template_image,signal_level)
 
-        (output_image,(xpos,ypos,width,height)) = self.__process_image(afield,template_image)
-        # # 保存
-        # defect_image = afield
-        # output_image = template_image
-        # output_image[roi[2]:roi[3],roi[0]:roi[1]] = defect_image[roi[2]:roi[3],roi[0]:roi[1]]
-        label_name = target_filename + ".txt"
-        with open(label_name,"w") as f:
-            f.write(f"{defect_class} {xpos} {ypos} {width} {height}")
-        
-        # 保存超分辨（原图）
-        cv2.imwrite(target_filename + "_origin.jpg",output_image)
-
-        # 通过每个像素点代表的实际物理尺寸来计算缩放比比例
+        # #####
+        # 重要
+        # ! 在此行开始，进行数据增广处理
+        # ! 增广方式为：
+        # ! 微位移方式出图
+        # ! 旋转出图
+        # ! 添加噪声
+        ###########
+
+        # 1.微位移
+        image_size = output_image.shape
+        stored_images = []
+        move_length = np.linspace(0,4,3)
+        for i in range(len(move_length)):
+            for j in range(len(move_length)):
+                M = np.array([[1,0,i],[0,1,j]],dtype=np.float32)
+                stored_images.append(cv2.warpAffine(output_image,M,output_image.shape))
+
+        for i in range(len(stored_images)):
+            stored_images[i] = stored_images[i][5:image_size[0]-5,5:image_size[1]-5]
+        
+        # 缩放并旋转
+        backup_positions = (
+            (xpos,ypos,width,height),
+            (1-ypos,xpos,height,width),
+            (1-xpos,1-ypos,width,height),
+            (ypos,1-xpos,height,width),
+        )
+        positions = []
+        scaled_images = []
         scale_factor =source_density*1.0/target_density
-        # 缩放电场/光强场到对应的大小
-        scaled_field = cv2.resize(output_image, None, fx=scale_factor,# type: ignore
-                                  fy=scale_factor, interpolation=cv2.INTER_LINEAR)  
+        for i in range(len(stored_images)):
+            temp_img = cv2.resize(stored_images[i],None,fx=scale_factor,fy=scale_factor,interpolation=cv2.INTER_LINEAR)
+
+            scaled_images.append(temp_img)
+            scaled_images.append(cv2.rotate(temp_img,cv2.ROTATE_90_CLOCKWISE))
+            scaled_images.append(cv2.rotate(temp_img,cv2.ROTATE_180))
+            scaled_images.append(cv2.rotate(temp_img,cv2.ROTATE_90_COUNTERCLOCKWISE))
+            positions.append(backup_positions[0])
+            positions.append(backup_positions[1])
+            positions.append(backup_positions[2])
+            positions.append(backup_positions[3])
+        
+        # 现在缩放并旋转之后的图像和对应的方位信息存在scaled_images和positions里面了
+        # 接下来向图像中添加噪声
+        final_images = []
+        final_positions = []
+        # 高斯噪声参数
+        mean = 0
+        sigma = noise_level
+        image_shape= (scaled_images[0].shape[0],scaled_images[0].shape[1])
+        for i in range(len(scaled_images)):
+            for j in range(3):
+                gauss = np.random.normal(mean,sigma,image_shape)
+                temp_image = scaled_images[i] + gauss
+                temp_image = np.clip(temp_image,0,255)
+                final_images.append(temp_image)
+                final_positions.append(positions[i])
+        
+        # # 保存
+        for i in range(len(final_images)):
+            label_name = target_filename + f"-{i}.txt"
+            with open(label_name,"w") as f:
+                f.write(f"{defect_class} {final_positions[i][0]} {final_positions[i][1]} {final_positions[i][2]} {final_positions[i][3]} ")
 
         # 绘图
         logger.debug(f"printing max value of results:{np.max(total_results)}")
-        cv2.imwrite(target_filename + ".jpg",scaled_field)
+        for i in range(len(final_images)):
+            file_name = target_filename + f"-{i}.jpg"
+            cv2.imwrite(file_name,final_images[i])
         logger.info("all target image saved completed!")
         
-    def __process_image(self,defect_img,template_img,gap_length=10):
+    def __process_image(self,defect_img,template_img,signal_level,smooth_length=30,extend_length = 15):
         diff_img = defect_img.astype(np.float32) - template_img.astype(np.float32)
         image_shape = template_img.shape
         # diff_img = (diff_img + 125)
         # diff_img = np.clip(diff_img, 0, 255).astype(np.uint8)
 
         gradX = cv2.Sobel(diff_img, ddepth=cv2.CV_32F, dx=1, dy=0, ksize=-1)
         gradY = cv2.Sobel(diff_img, ddepth=cv2.CV_32F, dx=0, dy=1, ksize=-1)
         
         # subtract the y-gradient from the x-gradient
         gradient = cv2.subtract(gradX, gradY)
         gradient = cv2.convertScaleAbs(gradient)        
-        defect_lowborder = np.max(gradient) * 0.35
-        blurred = cv2.blur(gradient, (5, 5),borderType=cv2.BORDER_REFLECT) 
-        (_, thresh) = cv2.threshold(blurred, defect_lowborder, 255, cv2.THRESH_BINARY)
-        kernel = cv2.getStructuringElement(cv2.MORPH_ELLIPSE, (11, 11))
-        closed = cv2.morphologyEx(thresh, cv2.MORPH_CLOSE, kernel,iterations=2,borderType=cv2.BORDER_ISOLATED)
+        defect_lowborder = np.max(gradient) * signal_level
+        # blurred = cv2.blur(gradient, (5, 5),borderType=cv2.BORDER_REFLECT) 
+        (_, thresh) = cv2.threshold(gradient, defect_lowborder, 255, cv2.THRESH_BINARY)
+
+        kernel = cv2.getStructuringElement(cv2.MORPH_ELLIPSE, (3,3))
+        thresh = cv2.morphologyEx(thresh, cv2.MORPH_CLOSE, kernel,iterations=2,borderType=cv2.BORDER_ISOLATED)
+        thresh = cv2.erode(thresh,None,iterations=1)
+        thresh = cv2.dilate(thresh,None,iterations=2)
+
+        kernel = cv2.getStructuringElement(cv2.MORPH_ELLIPSE, (7, 7))
+        closed = cv2.morphologyEx(thresh, cv2.MORPH_CLOSE, kernel,iterations=3,borderType=cv2.BORDER_ISOLATED)
         closed = cv2.erode(closed, None, iterations=4)
-        closed = cv2.dilate(closed, None, iterations=5)
+        closed = cv2.dilate(closed, None, iterations=6)
 
         # 找距离图像中心点最近的一个封闭区域
         (cnts, _) = cv2.findContours(closed.copy(), cv2.RETR_EXTERNAL, cv2.CHAIN_APPROX_SIMPLE)
         # c = sorted(cnts, key=cv2.contourArea, reverse=True)[0]
         min_dist = -1
         c = cnts[0]
         for conners in cnts:
@@ -205,35 +254,42 @@
             dist = min(distances)
             if dist < min_dist or min_dist == -1 :
                 min_dist = dist
                 c = conners
 
         # compute the rotated bounding box of the largest contour
         x,y,w,h=cv2.boundingRect(c)
+
+        # 延伸扩展边界，避免强截断
+        x += extend_length
+        y -= extend_length
+        w += extend_length*2
+        h += extend_length*2
+        
         # img=cv2.rectangle(defect_img,(x,y),(x+w,y+h),(0,255,0),2)
         # 根据左上角坐标和长宽计算矩形的四个角点坐标
         rect_points = [(x, y),
                     (x + w, y),
                     (x + w, y + h),
                     (x, y + h)]
 
         # 开始扩展拼接缺陷图像
-        outer_points = [(x-gap_length,y-gap_length),
-                        (x+w+gap_length,y-gap_length),
-                        (x+w+gap_length,y+h+gap_length),
-                        (x-gap_length,y+h+gap_length)]
+        outer_points = [(x-smooth_length,y-smooth_length),
+                        (x+w+smooth_length,y-smooth_length),
+                        (x+w+smooth_length,y+h+smooth_length),
+                        (x-smooth_length,y+h+smooth_length)]
 
         output_img = template_img
         output_img[y:y+h,x:x+w] = defect_img[y:y+h,x:x+w]
 
         diff_img = diff_img
-        x_lower_border = max(0,x - gap_length)
-        x_upper_border = min(image_shape[1] - 1,x + w + gap_length - 1)
-        y_lower_border = max(0,y - gap_length)
-        y_upper_border = min(image_shape[0] - 1,y + h + gap_length - 1)
+        x_lower_border = max(0,x - smooth_length)
+        x_upper_border = min(image_shape[1] - 1,x + w + smooth_length - 1)
+        y_lower_border = max(0,y - smooth_length)
+        y_upper_border = min(image_shape[0] - 1,y + h + smooth_length - 1)
         for i in range(x_lower_border,x_upper_border):
             for j in range(y_lower_border,y_upper_border):
                 if not (np.abs(i - x - w/2 + 0.5) < w/2 and np.abs(j - y - h/2 +0.5) < h/2):
                     # 计算点到矩形边界的距离
                     distances = []
                     distances2 = []
                     for k in range(4):
```

### Comparing `jcmutils-1.5.9/jcmutils/gen_sources.py` & `jcmutils-1.6.0/jcmutils/gen_sources.py`

 * *Files identical despite different names*

### Comparing `jcmutils-1.5.9/jcmutils/logger.py` & `jcmutils-1.6.0/jcmutils/logger.py`

 * *Files identical despite different names*

### Comparing `jcmutils-1.5.9/jcmutils/solver.py` & `jcmutils-1.6.0/jcmutils/solver.py`

 * *Files identical despite different names*

### Comparing `jcmutils-1.5.9/setup.py` & `jcmutils-1.6.0/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 from setuptools import setup,find_packages
 
-VERSION = '1.5.9'
+VERSION = '1.6.0'
 DESCRIPTION = "A general utils for jcmsuite"
 
 setup(
     name="jcmutils",
     version=VERSION,
     author="crafter-z",
     author_email="crafterz@163.com",
```

