# Comparing `tmp/nonebot_plugin_chatrecorder-0.2.3.tar.gz` & `tmp/nonebot_plugin_chatrecorder-0.2.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "nonebot_plugin_chatrecorder-0.2.3.tar", max compression
+gzip compressed data, was "nonebot_plugin_chatrecorder-0.2.4.tar", max compression
```

## Comparing `nonebot_plugin_chatrecorder-0.2.3.tar` & `nonebot_plugin_chatrecorder-0.2.4.tar`

### file list

```diff
@@ -1,12 +1,18 @@
--rw-r--r--   0        0        0     2979 2023-03-07 04:26:32.204415 nonebot_plugin_chatrecorder-0.2.3/README.md
--rw-r--r--   0        0        0     4889 2023-03-07 04:26:32.204415 nonebot_plugin_chatrecorder-0.2.3/nonebot_plugin_chatrecorder/__init__.py
--rw-r--r--   0        0        0      223 2023-03-07 04:26:32.204415 nonebot_plugin_chatrecorder-0.2.3/nonebot_plugin_chatrecorder/config.py
--rw-r--r--   0        0        0     2088 2023-03-07 04:26:32.204415 nonebot_plugin_chatrecorder-0.2.3/nonebot_plugin_chatrecorder/message.py
--rw-r--r--   0        0        0     1703 2023-03-07 04:26:32.204415 nonebot_plugin_chatrecorder-0.2.3/nonebot_plugin_chatrecorder/migrations/2cad88d938f1_init_db.py
--rw-r--r--   0        0        0     3725 2023-03-07 04:26:32.204415 nonebot_plugin_chatrecorder-0.2.3/nonebot_plugin_chatrecorder/migrations/7228a3a08576_ob12.py
--rw-r--r--   0        0        0     1517 2023-03-07 04:26:32.204415 nonebot_plugin_chatrecorder-0.2.3/nonebot_plugin_chatrecorder/migrations/9bca28bcb998_msg_type.py
--rw-r--r--   0        0        0     1731 2023-03-07 04:26:32.204415 nonebot_plugin_chatrecorder-0.2.3/nonebot_plugin_chatrecorder/model.py
--rw-r--r--   0        0        0     6753 2023-03-07 04:26:32.204415 nonebot_plugin_chatrecorder-0.2.3/nonebot_plugin_chatrecorder/record.py
--rw-r--r--   0        0        0     2814 2023-03-07 04:26:32.204415 nonebot_plugin_chatrecorder-0.2.3/nonebot_plugin_chatrecorder/record.pyi
--rw-r--r--   0        0        0     1101 2023-03-07 04:26:32.204415 nonebot_plugin_chatrecorder-0.2.3/pyproject.toml
--rw-r--r--   0        0        0     3851 1970-01-01 00:00:00.000000 nonebot_plugin_chatrecorder-0.2.3/PKG-INFO
+-rw-r--r--   0        0        0     2979 2023-06-28 02:43:20.338192 nonebot_plugin_chatrecorder-0.2.4/README.md
+-rw-r--r--   0        0        0      602 2023-06-28 02:43:20.338192 nonebot_plugin_chatrecorder-0.2.4/nonebot_plugin_chatrecorder/__init__.py
+-rw-r--r--   0        0        0       37 2023-06-28 02:43:20.338192 nonebot_plugin_chatrecorder-0.2.4/nonebot_plugin_chatrecorder/adapters/__init__.py
+-rw-r--r--   0        0        0     4631 2023-06-28 02:43:20.338192 nonebot_plugin_chatrecorder-0.2.4/nonebot_plugin_chatrecorder/adapters/onebot_v11.py
+-rw-r--r--   0        0        0     3327 2023-06-28 02:43:20.338192 nonebot_plugin_chatrecorder-0.2.4/nonebot_plugin_chatrecorder/adapters/onebot_v12.py
+-rw-r--r--   0        0        0      317 2023-06-28 02:43:20.338192 nonebot_plugin_chatrecorder-0.2.4/nonebot_plugin_chatrecorder/config.py
+-rw-r--r--   0        0        0      483 2023-06-28 02:43:20.338192 nonebot_plugin_chatrecorder-0.2.4/nonebot_plugin_chatrecorder/consts.py
+-rw-r--r--   0        0        0      402 2023-06-28 02:43:20.338192 nonebot_plugin_chatrecorder-0.2.4/nonebot_plugin_chatrecorder/exception.py
+-rw-r--r--   0        0        0     1859 2023-06-28 02:43:20.338192 nonebot_plugin_chatrecorder-0.2.4/nonebot_plugin_chatrecorder/message.py
+-rw-r--r--   0        0        0     1703 2023-06-28 02:43:20.338192 nonebot_plugin_chatrecorder-0.2.4/nonebot_plugin_chatrecorder/migrations/2cad88d938f1_init_db.py
+-rw-r--r--   0        0        0     3732 2023-06-28 02:43:20.338192 nonebot_plugin_chatrecorder-0.2.4/nonebot_plugin_chatrecorder/migrations/7228a3a08576_ob12.py
+-rw-r--r--   0        0        0     1517 2023-06-28 02:43:20.338192 nonebot_plugin_chatrecorder-0.2.4/nonebot_plugin_chatrecorder/migrations/9bca28bcb998_msg_type.py
+-rw-r--r--   0        0        0     1731 2023-06-28 02:43:20.338192 nonebot_plugin_chatrecorder-0.2.4/nonebot_plugin_chatrecorder/model.py
+-rw-r--r--   0        0        0     6206 2023-06-28 02:43:20.338192 nonebot_plugin_chatrecorder-0.2.4/nonebot_plugin_chatrecorder/record.py
+-rw-r--r--   0        0        0     2587 2023-06-28 02:43:20.338192 nonebot_plugin_chatrecorder-0.2.4/nonebot_plugin_chatrecorder/record.pyi
+-rw-r--r--   0        0        0      365 2023-06-28 02:43:20.338192 nonebot_plugin_chatrecorder-0.2.4/nonebot_plugin_chatrecorder/utils.py
+-rw-r--r--   0        0        0     1183 2023-06-28 02:43:20.342192 nonebot_plugin_chatrecorder-0.2.4/pyproject.toml
+-rw-r--r--   0        0        0     3789 1970-01-01 00:00:00.000000 nonebot_plugin_chatrecorder-0.2.4/PKG-INFO
```

### Comparing `nonebot_plugin_chatrecorder-0.2.3/README.md` & `nonebot_plugin_chatrecorder-0.2.4/README.md`

 * *Files identical despite different names*

### Comparing `nonebot_plugin_chatrecorder-0.2.3/nonebot_plugin_chatrecorder/__init__.py` & `nonebot_plugin_chatrecorder-0.2.4/nonebot_plugin_chatrecorder/adapters/onebot_v12.py`

 * *Files 26% similar despite different names*

```diff
@@ -1,142 +1,104 @@
 from datetime import datetime
-from typing import Any, Dict, Optional
+from typing import Any, Dict, Optional, Type
 
-from nonebot import get_driver, require
 from nonebot.adapters import Bot as BaseBot
-from nonebot.adapters.onebot.v11 import Bot as V11Bot
-from nonebot.adapters.onebot.v11 import GroupMessageEvent as V11GMEvent
-from nonebot.adapters.onebot.v11 import Message as V11Msg
-from nonebot.adapters.onebot.v11 import MessageEvent as V11MEvent
-from nonebot.adapters.onebot.v12 import Bot as V12Bot
-from nonebot.adapters.onebot.v12 import ChannelMessageEvent as V12CMEvent
-from nonebot.adapters.onebot.v12 import GroupMessageEvent as V12GMEvent
-from nonebot.adapters.onebot.v12 import Message as V12Msg
-from nonebot.adapters.onebot.v12 import MessageEvent as V12MEvent
 from nonebot.message import event_postprocessor
-
-require("nonebot_plugin_datastore")
+from nonebot.typing import overrides
 from nonebot_plugin_datastore import create_session
 
-from .config import Config
-from .message import serialize_message
-from .model import MessageRecord
-from .record import get_message_records, get_messages, get_messages_plain_text
-
-plugin_config = Config.parse_obj(get_driver().config.dict())
-
-
-@event_postprocessor
-async def record_recv_msg_v11(bot: V11Bot, event: V11MEvent):
-    record = MessageRecord(
-        bot_type=bot.type,
-        bot_id=bot.self_id,
-        platform="qq",
-        time=datetime.utcfromtimestamp(event.time),
-        type=event.post_type,
-        detail_type=event.message_type,
-        message_id=str(event.message_id),
-        message=serialize_message(event.message),
-        plain_text=event.message.extract_plain_text(),
-        user_id=str(event.user_id),
-        group_id=str(event.group_id) if isinstance(event, V11GMEvent) else None,
-    )
-
-    async with create_session() as session:
-        session.add(record)
-        await session.commit()
-
-
-@event_postprocessor
-async def record_recv_msg_v12(bot: V12Bot, event: V12MEvent):
-    record = MessageRecord(
-        bot_type=bot.type,
-        bot_id=bot.self_id,
-        platform=bot.platform,
-        time=event.time,
-        type=event.type,
-        detail_type=event.detail_type,
-        message_id=event.message_id,
-        message=serialize_message(event.message),
-        plain_text=event.message.extract_plain_text(),
-        user_id=event.user_id,
-        group_id=event.group_id if isinstance(event, V12GMEvent) else None,
-        guild_id=event.guild_id if isinstance(event, V12CMEvent) else None,
-        channel_id=event.channel_id if isinstance(event, V12CMEvent) else None,
+from ..config import plugin_config
+from ..consts import SupportedAdapter
+from ..message import (
+    MessageDeserializer,
+    MessageSerializer,
+    register_deserializer,
+    register_serializer,
+    serialize_message,
+)
+from ..model import MessageRecord
+
+try:
+    from nonebot.adapters.onebot.v12 import (
+        Bot,
+        ChannelMessageEvent,
+        GroupMessageEvent,
+        Message,
+        MessageEvent,
     )
 
-    async with create_session() as session:
-        session.add(record)
-        await session.commit()
-
-
-if plugin_config.chatrecorder_record_send_msg:
-
-    @V11Bot.on_called_api
-    async def record_send_msg_v11(
-        bot: BaseBot,
-        e: Optional[Exception],
-        api: str,
-        data: Dict[str, Any],
-        result: Optional[Dict[str, Any]],
-    ):
-        if e or not result:
-            return
-        if api not in ["send_msg", "send_private_msg", "send_group_msg"]:
-            return
-
-        message = V11Msg(data["message"])
+    @event_postprocessor
+    async def record_recv_msg(bot: Bot, event: MessageEvent):
         record = MessageRecord(
             bot_type=bot.type,
             bot_id=bot.self_id,
-            platform="qq",
-            time=datetime.utcnow(),
-            type="message_sent",
-            detail_type="group"
-            if api == "send_group_msg"
-            or (api == "send_msg" and data["message_type"] == "group")
-            else "private",
-            message_id=str(result["message_id"]),
-            message=serialize_message(message),
-            plain_text=message.extract_plain_text(),
-            user_id=str(bot.self_id),
-            group_id=str(data.get("group_id", "")) or None,
+            platform=bot.platform,
+            time=event.time,
+            type=event.type,
+            detail_type=event.detail_type,
+            message_id=event.message_id,
+            message=serialize_message(bot, event.message),
+            plain_text=event.message.extract_plain_text(),
+            user_id=event.user_id,
+            group_id=event.group_id if isinstance(event, GroupMessageEvent) else None,
+            guild_id=event.guild_id if isinstance(event, ChannelMessageEvent) else None,
+            channel_id=event.channel_id
+            if isinstance(event, ChannelMessageEvent)
+            else None,
         )
 
         async with create_session() as session:
             session.add(record)
             await session.commit()
 
-    @V12Bot.on_called_api
-    async def record_send_msg_v12(
-        bot: BaseBot,
-        e: Optional[Exception],
-        api: str,
-        data: Dict[str, Any],
-        result: Optional[Dict[str, Any]],
-    ):
-        if e or not result:
-            return
-        if api not in ["send_message"]:
-            return
-        assert isinstance(bot, V12Bot)
+    if plugin_config.chatrecorder_record_send_msg:
 
-        message = V12Msg(data["message"])
-        record = MessageRecord(
-            bot_type=bot.type,
-            bot_id=bot.self_id,
-            platform=bot.platform,
-            time=datetime.utcfromtimestamp(result["time"]),
-            type="message_sent",
-            detail_type=data["detail_type"],
-            message_id=result["message_id"],
-            message=serialize_message(message),
-            plain_text=message.extract_plain_text(),
-            user_id=str(bot.self_id),
-            group_id=data.get("group_id"),
-            guild_id=data.get("guild_id"),
-            channel_id=data.get("channel_id"),
-        )
+        @Bot.on_called_api
+        async def record_send_msg(
+            bot: BaseBot,
+            e: Optional[Exception],
+            api: str,
+            data: Dict[str, Any],
+            result: Optional[Dict[str, Any]],
+        ):
+            if e or not result:
+                return
+            if api not in ["send_message"]:
+                return
+            assert isinstance(bot, Bot)
+
+            message = Message(data["message"])
+            record = MessageRecord(
+                bot_type=bot.type,
+                bot_id=bot.self_id,
+                platform=bot.platform,
+                time=datetime.utcfromtimestamp(result["time"]),
+                type="message_sent",
+                detail_type=data["detail_type"],
+                message_id=result["message_id"],
+                message=serialize_message(bot, message),
+                plain_text=message.extract_plain_text(),
+                user_id=str(bot.self_id),
+                group_id=data.get("group_id"),
+                guild_id=data.get("guild_id"),
+                channel_id=data.get("channel_id"),
+            )
+
+            async with create_session() as session:
+                session.add(record)
+                await session.commit()
+
+    class Serializer(MessageSerializer[Message]):
+        pass
+
+    class Deserializer(MessageDeserializer[Message]):
+        @classmethod
+        @overrides(MessageDeserializer)
+        def get_message_class(cls) -> Type[Message]:
+            return Message
+
+    adapter = SupportedAdapter.onebot_v12
+    register_serializer(adapter, Serializer)
+    register_deserializer(adapter, Deserializer)
 
-        async with create_session() as session:
-            session.add(record)
-            await session.commit()
+except ImportError:
+    pass
```

### Comparing `nonebot_plugin_chatrecorder-0.2.3/nonebot_plugin_chatrecorder/migrations/2cad88d938f1_init_db.py` & `nonebot_plugin_chatrecorder-0.2.4/nonebot_plugin_chatrecorder/migrations/2cad88d938f1_init_db.py`

 * *Files identical despite different names*

### Comparing `nonebot_plugin_chatrecorder-0.2.3/nonebot_plugin_chatrecorder/migrations/7228a3a08576_ob12.py` & `nonebot_plugin_chatrecorder-0.2.4/nonebot_plugin_chatrecorder/migrations/7228a3a08576_ob12.py`

 * *Files 1% similar despite different names*

```diff
@@ -7,15 +7,15 @@
 """
 import sqlalchemy as sa
 from alembic import op
 from sqlalchemy import select
 from sqlalchemy.ext.automap import automap_base
 from sqlalchemy.orm import Session
 
-from nonebot_plugin_chatrecorder import plugin_config
+from nonebot_plugin_chatrecorder.config import plugin_config
 
 # revision identifiers, used by Alembic.
 revision = "7228a3a08576"
 down_revision = "2cad88d938f1"
 branch_labels = None
 depends_on = None
```

### Comparing `nonebot_plugin_chatrecorder-0.2.3/nonebot_plugin_chatrecorder/migrations/9bca28bcb998_msg_type.py` & `nonebot_plugin_chatrecorder-0.2.4/nonebot_plugin_chatrecorder/migrations/9bca28bcb998_msg_type.py`

 * *Files identical despite different names*

### Comparing `nonebot_plugin_chatrecorder-0.2.3/nonebot_plugin_chatrecorder/model.py` & `nonebot_plugin_chatrecorder-0.2.4/nonebot_plugin_chatrecorder/model.py`

 * *Files identical despite different names*

### Comparing `nonebot_plugin_chatrecorder-0.2.3/nonebot_plugin_chatrecorder/record.py` & `nonebot_plugin_chatrecorder-0.2.4/nonebot_plugin_chatrecorder/record.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,14 +1,11 @@
 from datetime import datetime, timezone
-from typing import Iterable, List, Literal, Optional, Sequence, Union, overload
+from typing import Iterable, List, Literal, Optional, Sequence
 
-from nonebot.adapters.onebot.v11 import Bot as V11Bot
-from nonebot.adapters.onebot.v11 import Message as V11Msg
-from nonebot.adapters.onebot.v12 import Bot as V12Bot
-from nonebot.adapters.onebot.v12 import Message as V12Msg
+from nonebot.adapters import Bot, Message
 from nonebot_plugin_datastore import create_session
 from sqlalchemy import or_, select
 
 from .message import deserialize_message
 from .model import MessageRecord
 
 
@@ -120,42 +117,28 @@
 
     statement = select(MessageRecord).where(*whereclause)
     async with create_session() as session:
         records = (await session.scalars(statement)).all()
     return records
 
 
-@overload
-async def get_messages(bot: V11Bot, **kwargs) -> List[V11Msg]:
-    ...
-
-
-@overload
-async def get_messages(bot: V12Bot, **kwargs) -> List[V12Msg]:
-    ...
-
-
-async def get_messages(
-    bot: Union[V11Bot, V12Bot], **kwargs
-) -> Union[List[V11Msg], List[V12Msg]]:
+async def get_messages(bot: Bot, **kwargs) -> List[Message]:
     """获取消息记录的消息列表
 
     参数:
-      * ``bot: Union[V11Bot, V12Bot]``: Nonebot `Bot` 对象，用于判断消息类型
+      * ``bot: Bot``: Nonebot `Bot` 对象，用于判断消息类型
       * ``**kwargs``: 筛选参数，具体查看 `get_message_records` 中的定义
 
     返回值:
-      * ``Union[List[V11Msg], List[V12Msg]]``: 消息列表
+      * ``List[Message]``: 消息列表
     """
-    kwargs.update({"bot_types": [bot.adapter.get_name()]})
+    adapter_name = bot.adapter.get_name()
+    kwargs.update({"bot_types": [adapter_name]})
     records = await get_message_records(**kwargs)
-    if isinstance(bot, V11Bot):
-        return [deserialize_message(record.message, V11Msg) for record in records]
-    else:
-        return [deserialize_message(record.message, V12Msg) for record in records]
+    return [deserialize_message(bot, record.message) for record in records]
 
 
 async def get_messages_plain_text(**kwargs) -> List[str]:
     """获取消息记录的纯文本消息列表
 
     参数:
       * ``**kwargs``: 筛选参数，具体查看 `get_message_records` 中的定义
```

### Comparing `nonebot_plugin_chatrecorder-0.2.3/nonebot_plugin_chatrecorder/record.pyi` & `nonebot_plugin_chatrecorder-0.2.4/nonebot_plugin_chatrecorder/record.pyi`

 * *Files 21% similar despite different names*

```diff
@@ -1,14 +1,11 @@
 from datetime import datetime
-from typing import Iterable, List, Literal, Optional, Union
+from typing import Iterable, List, Literal, Optional
 
-from nonebot.adapters.onebot.v11 import Bot as V11Bot
-from nonebot.adapters.onebot.v11 import Message as V11Msg
-from nonebot.adapters.onebot.v12 import Bot as V12Bot
-from nonebot.adapters.onebot.v12 import Message as V12Msg
+from nonebot.adapters import Bot, Message
 
 from .model import MessageRecord
 
 async def get_message_records(
     *,
     bot_types: Optional[Iterable[str]] = None,
     bot_ids: Optional[Iterable[str]] = None,
@@ -23,15 +20,15 @@
     channel_ids: Optional[Iterable[str]] = None,
     exclude_user_ids: Optional[Iterable[str]] = None,
     exclude_group_ids: Optional[Iterable[str]] = None,
     exclude_guild_ids: Optional[Iterable[str]] = None,
     exclude_channel_ids: Optional[Iterable[str]] = None,
 ) -> List[MessageRecord]: ...
 async def get_messages(
-    bot: Union[V11Bot, V12Bot],
+    bot: Bot,
     *,
     bot_ids: Optional[Iterable[str]] = None,
     platforms: Optional[Iterable[str]] = None,
     time_start: Optional[datetime] = None,
     time_stop: Optional[datetime] = None,
     types: Optional[Iterable[Literal["message", "message_sent"]]] = None,
     detail_types: Optional[Iterable[str]] = None,
@@ -39,15 +36,15 @@
     group_ids: Optional[Iterable[str]] = None,
     guild_ids: Optional[Iterable[str]] = None,
     channel_ids: Optional[Iterable[str]] = None,
     exclude_user_ids: Optional[Iterable[str]] = None,
     exclude_group_ids: Optional[Iterable[str]] = None,
     exclude_guild_ids: Optional[Iterable[str]] = None,
     exclude_channel_ids: Optional[Iterable[str]] = None,
-) -> Union[List[V11Msg], List[V12Msg]]: ...
+) -> List[Message]: ...
 async def get_messages_plain_text(
     *,
     bot_types: Optional[Iterable[str]] = None,
     bot_ids: Optional[Iterable[str]] = None,
     platforms: Optional[Iterable[str]] = None,
     time_start: Optional[datetime] = None,
     time_stop: Optional[datetime] = None,
```

### Comparing `nonebot_plugin_chatrecorder-0.2.3/pyproject.toml` & `nonebot_plugin_chatrecorder-0.2.4/pyproject.toml`

 * *Files 7% similar despite different names*

```diff
@@ -1,36 +1,41 @@
 [tool.poetry]
 name = "nonebot_plugin_chatrecorder"
-version = "0.2.3"
+version = "0.2.4"
 description = "适用于 Nonebot2 的聊天记录插件"
 authors = ["meetwq <meetwq@gmail.com>"]
 license = "MIT"
 readme = "README.md"
 homepage = "https://github.com/noneplugin/nonebot-plugin-chatrecorder"
 repository = "https://github.com/noneplugin/nonebot-plugin-chatrecorder"
 
 [tool.poetry.dependencies]
 python = "^3.8"
-nonebot2 = { version = "^2.0.0-rc.1", extras = ["fastapi"] }
-nonebot-adapter-onebot = "^2.2.0"
-nonebot-plugin-datastore = "^0.6.0a0"
+nonebot2 = { version = "^2.0.0", extras = ["fastapi"] }
+nonebot-plugin-datastore = "^1.0.0"
 
 [tool.poetry.group.dev.dependencies]
 nb-cli = "^1.0.0"
 black = "^22.8.0"
 
 [tool.poetry.group.test.dependencies]
 pytest-cov = "^4.0.0"
 pytest-xdist = "^3.0.2"
 pytest-asyncio = "^0.20.0"
 nonebug = "^0.3.0"
 nonebot2 = { version = "^2.0.0-rc.1", extras = ["fastapi"] }
 asyncpg = "^0.27.0"
 aiomysql = "^0.1.0"
 
+[tool.poetry.group.adapters]
+optional = true
+
+[tool.poetry.group.adapters.dependencies]
+nonebot-adapter-onebot = "^2.2.0"
+
 [tool.pytest.ini_options]
 asyncio_mode = "auto"
 addopts = "--cov=nonebot_plugin_chatrecorder --cov-report=term-missing"
 
 [tool.nonebot]
 plugins = ["nonebot_plugin_chatrecorder"]
```

### Comparing `nonebot_plugin_chatrecorder-0.2.3/PKG-INFO` & `nonebot_plugin_chatrecorder-0.2.4/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,25 +1,24 @@
 Metadata-Version: 2.1
 Name: nonebot-plugin-chatrecorder
-Version: 0.2.3
+Version: 0.2.4
 Summary: 适用于 Nonebot2 的聊天记录插件
 Home-page: https://github.com/noneplugin/nonebot-plugin-chatrecorder
 License: MIT
 Author: meetwq
 Author-email: meetwq@gmail.com
 Requires-Python: >=3.8,<4.0
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
-Requires-Dist: nonebot-adapter-onebot (>=2.2.0,<3.0.0)
-Requires-Dist: nonebot-plugin-datastore (>=0.6.0a0,<0.7.0)
-Requires-Dist: nonebot2[fastapi] (>=2.0.0-rc.1,<3.0.0)
+Requires-Dist: nonebot-plugin-datastore (>=1.0.0,<2.0.0)
+Requires-Dist: nonebot2[fastapi] (>=2.0.0,<3.0.0)
 Project-URL: Repository, https://github.com/noneplugin/nonebot-plugin-chatrecorder
 Description-Content-Type: text/markdown
 
 ## nonebot-plugin-chatrecorder
 
 适用于 [Nonebot2](https://github.com/nonebot/nonebot2) 的聊天记录插件。
```

