# Comparing `tmp/thingsboard-gateway-3.2.tar.gz` & `tmp/thingsboard-gateway-3.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "thingsboard-gateway-3.2.tar", last modified: Thu Oct 27 14:36:16 2022, max compression
+gzip compressed data, was "thingsboard-gateway-3.3.tar", last modified: Wed Jun 28 10:44:14 2023, max compression
```

## Comparing `thingsboard-gateway-3.2.tar` & `thingsboard-gateway-3.3.tar`

### file list

```diff
@@ -1,228 +1,238 @@
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.667582 thingsboard-gateway-3.2/
--rw-rw-r--   0 z         (1000) z         (1000)    11357 2020-11-22 10:05:56.000000 thingsboard-gateway-3.2/LICENSE
--rw-rw-r--   0 z         (1000) z         (1000)       49 2021-08-27 07:07:07.000000 thingsboard-gateway-3.2/MANIFEST.in
--rw-rw-r--   0 z         (1000) z         (1000)     5443 2022-10-27 14:36:16.667582 thingsboard-gateway-3.2/PKG-INFO
--rw-rw-r--   0 z         (1000) z         (1000)     4967 2022-08-11 08:44:36.000000 thingsboard-gateway-3.2/README.md
--rw-rw-r--   0 z         (1000) z         (1000)       38 2022-10-27 14:36:16.667582 thingsboard-gateway-3.2/setup.cfg
--rw-rw-r--   0 z         (1000) z         (1000)     3894 2022-10-27 13:25:36.000000 thingsboard-gateway-3.2/setup.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.651583 thingsboard-gateway-3.2/thingsboard_gateway/
--rw-rw-r--   0 z         (1000) z         (1000)      693 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/__init__.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.655583 thingsboard-gateway-3.2/thingsboard_gateway/config/
--rw-rw-r--   0 z         (1000) z         (1000)     1435 2021-10-28 14:52:44.000000 thingsboard-gateway-3.2/thingsboard_gateway/config/bacnet.json
--rw-rw-r--   0 z         (1000) z         (1000)     2003 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/config/ble.json
--rw-rw-r--   0 z         (1000) z         (1000)     2217 2020-11-22 10:05:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/config/can.json
--rw-rw-r--   0 z         (1000) z         (1000)      685 2021-10-13 08:00:17.000000 thingsboard-gateway-3.2/thingsboard_gateway/config/custom_serial.json
--rw-rw-r--   0 z         (1000) z         (1000)     1304 2021-08-27 07:07:07.000000 thingsboard-gateway-3.2/thingsboard_gateway/config/ftp.json
--rw-rw-r--   0 z         (1000) z         (1000)       77 2022-01-05 17:33:22.000000 thingsboard-gateway-3.2/thingsboard_gateway/config/grpc_connector_1.json
--rw-rw-r--   0 z         (1000) z         (1000)     2475 2022-10-27 11:54:00.000000 thingsboard-gateway-3.2/thingsboard_gateway/config/logs.conf
--rw-rw-r--   0 z         (1000) z         (1000)     5929 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/config/modbus.json
--rw-rw-r--   0 z         (1000) z         (1000)      615 2020-11-22 10:05:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/config/modbus_serial.json
--rw-rw-r--   0 z         (1000) z         (1000)     4457 2022-10-27 11:54:00.000000 thingsboard-gateway-3.2/thingsboard_gateway/config/mqtt.json
--rw-rw-r--   0 z         (1000) z         (1000)     1434 2022-10-27 11:54:00.000000 thingsboard-gateway-3.2/thingsboard_gateway/config/ocpp.json
--rw-rw-r--   0 z         (1000) z         (1000)     1260 2021-10-13 08:00:17.000000 thingsboard-gateway-3.2/thingsboard_gateway/config/odbc.json
--rw-rw-r--   0 z         (1000) z         (1000)     1302 2022-02-16 10:06:41.000000 thingsboard-gateway-3.2/thingsboard_gateway/config/opcua.json
--rw-rw-r--   0 z         (1000) z         (1000)     4134 2021-10-28 14:52:44.000000 thingsboard-gateway-3.2/thingsboard_gateway/config/request.json
--rw-rw-r--   0 z         (1000) z         (1000)     4609 2022-05-09 12:12:34.000000 thingsboard-gateway-3.2/thingsboard_gateway/config/rest.json
--rw-rw-r--   0 z         (1000) z         (1000)     3259 2020-11-22 10:05:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/config/snmp.json
--rw-rw-r--   0 z         (1000) z         (1000)     1222 2022-05-09 12:12:34.000000 thingsboard-gateway-3.2/thingsboard_gateway/config/socket.json
--rw-rw-r--   0 z         (1000) z         (1000)      789 2022-05-24 08:38:49.000000 thingsboard-gateway-3.2/thingsboard_gateway/config/statistics.json
--rw-rw-r--   0 z         (1000) z         (1000)     2674 2022-10-27 11:54:00.000000 thingsboard-gateway-3.2/thingsboard_gateway/config/tb_gateway.yaml
--rw-rw-r--   0 z         (1000) z         (1000)     1112 2022-06-13 11:01:36.000000 thingsboard-gateway-3.2/thingsboard_gateway/config/xmpp.json
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.655583 thingsboard-gateway-3.2/thingsboard_gateway/connectors/
--rw-rw-r--   0 z         (1000) z         (1000)      616 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/__init__.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.655583 thingsboard-gateway-3.2/thingsboard_gateway/connectors/bacnet/
--rw-rw-r--   0 z         (1000) z         (1000)      616 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/bacnet/__init__.py
--rw-rw-r--   0 z         (1000) z         (1000)    16209 2022-08-11 08:44:36.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/bacnet/bacnet_connector.py
--rw-rw-r--   0 z         (1000) z         (1000)      816 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/bacnet/bacnet_converter.py
--rw-rw-r--   0 z         (1000) z         (1000)      876 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/bacnet/bacnet_downlink_converter.py
--rw-rw-r--   0 z         (1000) z         (1000)     2842 2022-08-11 08:44:36.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/bacnet/bacnet_uplink_converter.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.655583 thingsboard-gateway-3.2/thingsboard_gateway/connectors/bacnet/bacnet_utilities/
--rw-rw-r--   0 z         (1000) z         (1000)      616 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/bacnet/bacnet_utilities/__init__.py
--rw-rw-r--   0 z         (1000) z         (1000)    10614 2022-05-09 12:12:34.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/bacnet/bacnet_utilities/tb_gateway_bacnet_application.py
--rw-rw-r--   0 z         (1000) z         (1000)      834 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/bacnet/bacnet_utilities/tb_gateway_bacnet_device.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.655583 thingsboard-gateway-3.2/thingsboard_gateway/connectors/ble/
--rw-rw-r--   0 z         (1000) z         (1000)      616 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/ble/__init__.py
--rw-rw-r--   0 z         (1000) z         (1000)     6748 2022-08-11 08:44:36.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/ble/ble_connector.py
--rw-rw-r--   0 z         (1000) z         (1000)      811 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/ble/ble_uplink_converter.py
--rw-rw-r--   0 z         (1000) z         (1000)     3802 2022-08-11 08:44:36.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/ble/bytes_ble_uplink_converter.py
--rw-rw-r--   0 z         (1000) z         (1000)    11601 2022-08-11 08:44:36.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/ble/device.py
--rw-rw-r--   0 z         (1000) z         (1000)      516 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/ble/error_handler.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.655583 thingsboard-gateway-3.2/thingsboard_gateway/connectors/can/
--rw-rw-r--   0 z         (1000) z         (1000)      616 2021-10-13 08:00:17.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/can/__init__.py
--rw-rw-r--   0 z         (1000) z         (1000)     3212 2022-08-11 08:44:36.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/can/bytes_can_downlink_converter.py
--rw-rw-r--   0 z         (1000) z         (1000)     3554 2022-08-11 08:44:36.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/can/bytes_can_uplink_converter.py
--rw-rw-r--   0 z         (1000) z         (1000)    31562 2022-05-24 08:41:27.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/can/can_connector.py
--rw-rw-r--   0 z         (1000) z         (1000)      792 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/can/can_converter.py
--rw-rw-r--   0 z         (1000) z         (1000)     1120 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/connector.py
--rw-rw-r--   0 z         (1000) z         (1000)      801 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/converter.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.655583 thingsboard-gateway-3.2/thingsboard_gateway/connectors/ftp/
--rw-rw-r--   0 z         (1000) z         (1000)      616 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/ftp/__init__.py
--rw-rw-r--   0 z         (1000) z         (1000)     2002 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/ftp/file.py
--rw-rw-r--   0 z         (1000) z         (1000)    13478 2022-08-11 08:44:36.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/ftp/ftp_connector.py
--rw-rw-r--   0 z         (1000) z         (1000)      799 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/ftp/ftp_converter.py
--rw-rw-r--   0 z         (1000) z         (1000)    11059 2022-08-11 08:44:36.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/ftp/ftp_uplink_converter.py
--rw-rw-r--   0 z         (1000) z         (1000)     5603 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/ftp/path.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.659583 thingsboard-gateway-3.2/thingsboard_gateway/connectors/modbus/
--rw-rw-r--   0 z         (1000) z         (1000)      616 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/modbus/__init__.py
--rw-rw-r--   0 z         (1000) z         (1000)     3512 2022-09-27 10:37:08.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/modbus/backward_compability_adapter.py
--rw-rw-r--   0 z         (1000) z         (1000)     6015 2022-08-11 08:44:36.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/modbus/bytes_modbus_downlink_converter.py
--rw-rw-r--   0 z         (1000) z         (1000)     8279 2022-08-11 08:44:36.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/modbus/bytes_modbus_uplink_converter.py
--rw-rw-r--   0 z         (1000) z         (1000)     2017 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/modbus/constants.py
--rw-rw-r--   0 z         (1000) z         (1000)    33037 2022-10-27 14:22:31.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/modbus/modbus_connector.py
--rw-rw-r--   0 z         (1000) z         (1000)      807 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/modbus/modbus_converter.py
--rw-rw-r--   0 z         (1000) z         (1000)     4868 2022-08-11 08:44:36.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/modbus/slave.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.659583 thingsboard-gateway-3.2/thingsboard_gateway/connectors/mqtt/
--rw-rw-r--   0 z         (1000) z         (1000)      616 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/mqtt/__init__.py
--rw-rw-r--   0 z         (1000) z         (1000)     2576 2022-10-27 11:54:00.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/mqtt/bytes_mqtt_uplink_converter.py
--rw-rw-r--   0 z         (1000) z         (1000)     7061 2022-10-27 11:54:00.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/mqtt/json_mqtt_uplink_converter.py
--rw-rw-r--   0 z         (1000) z         (1000)    41604 2022-10-27 11:54:00.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/mqtt/mqtt_connector.py
--rw-rw-r--   0 z         (1000) z         (1000)      436 2022-08-11 08:44:36.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/mqtt/mqtt_decorators.py
--rw-rw-r--   0 z         (1000) z         (1000)      812 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/mqtt/mqtt_uplink_converter.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.659583 thingsboard-gateway-3.2/thingsboard_gateway/connectors/ocpp/
--rw-rw-r--   0 z         (1000) z         (1000)      616 2022-10-27 11:54:00.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/ocpp/__init__.py
--rw-rw-r--   0 z         (1000) z         (1000)     4267 2022-10-27 11:54:00.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/ocpp/charge_point.py
--rw-rw-r--   0 z         (1000) z         (1000)    12869 2022-10-27 11:54:00.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/ocpp/ocpp_connector.py
--rw-rw-r--   0 z         (1000) z         (1000)      805 2022-10-27 11:54:00.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/ocpp/ocpp_converter.py
--rw-rw-r--   0 z         (1000) z         (1000)     6496 2022-10-27 11:54:00.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/ocpp/ocpp_uplink_converter.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.659583 thingsboard-gateway-3.2/thingsboard_gateway/connectors/odbc/
--rw-rw-r--   0 z         (1000) z         (1000)      616 2021-10-13 08:00:17.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/odbc/__init__.py
--rw-rw-r--   0 z         (1000) z         (1000)    21655 2022-08-11 08:44:36.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/odbc/odbc_connector.py
--rw-rw-r--   0 z         (1000) z         (1000)      788 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/odbc/odbc_converter.py
--rw-rw-r--   0 z         (1000) z         (1000)     2431 2022-08-11 08:44:36.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/odbc/odbc_uplink_converter.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.659583 thingsboard-gateway-3.2/thingsboard_gateway/connectors/opcua/
--rw-rw-r--   0 z         (1000) z         (1000)      616 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/opcua/__init__.py
--rw-rw-r--   0 z         (1000) z         (1000)    36558 2022-09-27 10:37:08.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/opcua/opcua_connector.py
--rw-rw-r--   0 z         (1000) z         (1000)      818 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/opcua/opcua_converter.py
--rw-rw-r--   0 z         (1000) z         (1000)     4055 2022-08-11 08:44:36.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/opcua/opcua_uplink_converter.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.659583 thingsboard-gateway-3.2/thingsboard_gateway/connectors/opcua_asyncio/
--rw-rw-r--   0 z         (1000) z         (1000)        0 2022-05-24 08:38:49.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/opcua_asyncio/__init__.py
--rw-rw-r--   0 z         (1000) z         (1000)     2022 2022-10-27 11:54:00.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/opcua_asyncio/device.py
--rw-rw-r--   0 z         (1000) z         (1000)    23044 2022-10-27 11:54:00.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/opcua_asyncio/opcua_connector.py
--rw-rw-r--   0 z         (1000) z         (1000)      805 2022-05-24 08:38:49.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/opcua_asyncio/opcua_converter.py
--rw-rw-r--   0 z         (1000) z         (1000)     3073 2022-10-27 11:54:00.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/opcua_asyncio/opcua_uplink_converter.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.659583 thingsboard-gateway-3.2/thingsboard_gateway/connectors/request/
--rw-rw-r--   0 z         (1000) z         (1000)      616 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/request/__init__.py
--rw-rw-r--   0 z         (1000) z         (1000)     3587 2022-08-11 08:44:36.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/request/json_request_downlink_converter.py
--rw-rw-r--   0 z         (1000) z         (1000)     6912 2022-08-11 08:44:36.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/request/json_request_uplink_converter.py
--rw-rw-r--   0 z         (1000) z         (1000)    13391 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/request/request_connector.py
--rw-rw-r--   0 z         (1000) z         (1000)      808 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/request/request_converter.py
--rw-rw-r--   0 z         (1000) z         (1000)      810 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/request/request_uplink_converter.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.659583 thingsboard-gateway-3.2/thingsboard_gateway/connectors/rest/
--rw-rw-r--   0 z         (1000) z         (1000)      616 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/rest/__init__.py
--rw-rw-r--   0 z         (1000) z         (1000)     3296 2022-08-11 08:44:36.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/rest/json_rest_downlink_converter.py
--rw-rw-r--   0 z         (1000) z         (1000)     6434 2022-08-11 08:44:36.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/rest/json_rest_uplink_converter.py
--rw-rw-r--   0 z         (1000) z         (1000)    26623 2022-09-27 10:37:08.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/rest/rest_connector.py
--rw-rw-r--   0 z         (1000) z         (1000)      770 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/rest/rest_converter.py
--rw-rw-r--   0 z         (1000) z         (1000)     2610 2021-10-13 08:00:17.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/rest/ssl_generator.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.659583 thingsboard-gateway-3.2/thingsboard_gateway/connectors/snmp/
--rw-rw-r--   0 z         (1000) z         (1000)      626 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/snmp/__init__.py
--rw-rw-r--   0 z         (1000) z         (1000)    12437 2022-06-13 11:01:36.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/snmp/snmp_connector.py
--rw-rw-r--   0 z         (1000) z         (1000)     1093 2022-08-11 08:44:36.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/snmp/snmp_downlink_converter.py
--rw-rw-r--   0 z         (1000) z         (1000)     2289 2022-08-11 08:44:36.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/snmp/snmp_uplink_converter.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.659583 thingsboard-gateway-3.2/thingsboard_gateway/connectors/socket/
--rw-rw-r--   0 z         (1000) z         (1000)      616 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/socket/__init__.py
--rw-rw-r--   0 z         (1000) z         (1000)     2588 2022-08-11 08:44:36.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/socket/bytes_socket_uplink_converter.py
--rw-rw-r--   0 z         (1000) z         (1000)    16935 2022-09-27 10:37:08.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/socket/socket_connector.py
--rw-rw-r--   0 z         (1000) z         (1000)      436 2022-08-11 08:44:36.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/socket/socket_decorators.py
--rw-rw-r--   0 z         (1000) z         (1000)      814 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/socket/socket_uplink_converter.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.659583 thingsboard-gateway-3.2/thingsboard_gateway/connectors/xmpp/
--rw-rw-r--   0 z         (1000) z         (1000)      616 2022-06-13 11:01:36.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/xmpp/__init__.py
--rw-rw-r--   0 z         (1000) z         (1000)    10445 2022-08-11 08:44:36.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/xmpp/xmpp_connector.py
--rw-rw-r--   0 z         (1000) z         (1000)      804 2022-06-13 11:01:36.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/xmpp/xmpp_converter.py
--rw-rw-r--   0 z         (1000) z         (1000)     7774 2022-08-11 08:44:36.000000 thingsboard-gateway-3.2/thingsboard_gateway/connectors/xmpp/xmpp_uplink_converter.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.663583 thingsboard-gateway-3.2/thingsboard_gateway/extensions/
--rw-rw-r--   0 z         (1000) z         (1000)      616 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/extensions/__init__.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.663583 thingsboard-gateway-3.2/thingsboard_gateway/extensions/bacnet/
--rw-rw-r--   0 z         (1000) z         (1000)      616 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/extensions/bacnet/__init__.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.663583 thingsboard-gateway-3.2/thingsboard_gateway/extensions/ble/
--rw-rw-r--   0 z         (1000) z         (1000)      616 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/extensions/ble/__init__.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.663583 thingsboard-gateway-3.2/thingsboard_gateway/extensions/can/
--rw-rw-r--   0 z         (1000) z         (1000)      616 2021-10-13 08:00:17.000000 thingsboard-gateway-3.2/thingsboard_gateway/extensions/can/__init__.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.663583 thingsboard-gateway-3.2/thingsboard_gateway/extensions/ftp/
--rw-rw-r--   0 z         (1000) z         (1000)        0 2021-08-27 07:07:07.000000 thingsboard-gateway-3.2/thingsboard_gateway/extensions/ftp/__init__.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.663583 thingsboard-gateway-3.2/thingsboard_gateway/extensions/modbus/
--rw-rw-r--   0 z         (1000) z         (1000)      616 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/extensions/modbus/__init__.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.663583 thingsboard-gateway-3.2/thingsboard_gateway/extensions/mqtt/
--rw-rw-r--   0 z         (1000) z         (1000)      616 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/extensions/mqtt/__init__.py
--rw-rw-r--   0 z         (1000) z         (1000)     2664 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/extensions/mqtt/custom_mqtt_uplink_converter.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.663583 thingsboard-gateway-3.2/thingsboard_gateway/extensions/ocpp/
--rw-rw-r--   0 z         (1000) z         (1000)      616 2022-10-27 11:54:00.000000 thingsboard-gateway-3.2/thingsboard_gateway/extensions/ocpp/__init__.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.663583 thingsboard-gateway-3.2/thingsboard_gateway/extensions/odbc/
--rw-rw-r--   0 z         (1000) z         (1000)      616 2021-10-13 08:00:17.000000 thingsboard-gateway-3.2/thingsboard_gateway/extensions/odbc/__init__.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.663583 thingsboard-gateway-3.2/thingsboard_gateway/extensions/opcua/
--rw-rw-r--   0 z         (1000) z         (1000)      616 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/extensions/opcua/__init__.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.663583 thingsboard-gateway-3.2/thingsboard_gateway/extensions/opcua_asyncio/
--rw-rw-r--   0 z         (1000) z         (1000)      616 2022-06-13 11:01:36.000000 thingsboard-gateway-3.2/thingsboard_gateway/extensions/opcua_asyncio/__init__.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.663583 thingsboard-gateway-3.2/thingsboard_gateway/extensions/request/
--rw-rw-r--   0 z         (1000) z         (1000)      616 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/extensions/request/__init__.py
--rw-rw-r--   0 z         (1000) z         (1000)     3676 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/extensions/request/custom_request_uplink_converter.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.663583 thingsboard-gateway-3.2/thingsboard_gateway/extensions/rest/
--rw-rw-r--   0 z         (1000) z         (1000)      616 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/extensions/rest/__init__.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.663583 thingsboard-gateway-3.2/thingsboard_gateway/extensions/serial/
--rw-rw-r--   0 z         (1000) z         (1000)      616 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/extensions/serial/__init__.py
--rw-rw-r--   0 z         (1000) z         (1000)    10913 2022-08-11 08:44:36.000000 thingsboard-gateway-3.2/thingsboard_gateway/extensions/serial/custom_serial_connector.py
--rw-rw-r--   0 z         (1000) z         (1000)     2433 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/extensions/serial/custom_serial_converter.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.663583 thingsboard-gateway-3.2/thingsboard_gateway/extensions/snmp/
--rw-rw-r--   0 z         (1000) z         (1000)      618 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/extensions/snmp/__init__.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.663583 thingsboard-gateway-3.2/thingsboard_gateway/extensions/socket/
--rw-rw-r--   0 z         (1000) z         (1000)      635 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/extensions/socket/__init__.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.663583 thingsboard-gateway-3.2/thingsboard_gateway/extensions/xmpp/
--rw-rw-r--   0 z         (1000) z         (1000)      635 2022-06-13 11:01:36.000000 thingsboard-gateway-3.2/thingsboard_gateway/extensions/xmpp/__init__.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.663583 thingsboard-gateway-3.2/thingsboard_gateway/gateway/
--rw-rw-r--   0 z         (1000) z         (1000)      616 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/gateway/__init__.py
--rw-rw-r--   0 z         (1000) z         (1000)    17309 2022-01-05 17:33:22.000000 thingsboard-gateway-3.2/thingsboard_gateway/gateway/configuration_wizard.py
--rw-rw-r--   0 z         (1000) z         (1000)     1102 2022-06-15 07:52:39.000000 thingsboard-gateway-3.2/thingsboard_gateway/gateway/constant_enums.py
--rw-rw-r--   0 z         (1000) z         (1000)     1487 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/gateway/constants.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.663583 thingsboard-gateway-3.2/thingsboard_gateway/gateway/grpc_service/
--rw-rw-r--   0 z         (1000) z         (1000)        0 2022-01-05 17:33:22.000000 thingsboard-gateway-3.2/thingsboard_gateway/gateway/grpc_service/__init__.py
--rw-rw-r--   0 z         (1000) z         (1000)     2512 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/gateway/grpc_service/grpc_connector.py
--rw-rw-r--   0 z         (1000) z         (1000)     8579 2022-06-15 15:19:55.000000 thingsboard-gateway-3.2/thingsboard_gateway/gateway/grpc_service/grpc_downlink_converter.py
--rw-rw-r--   0 z         (1000) z         (1000)     4713 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/gateway/grpc_service/grpc_uplink_converter.py
--rw-rw-r--   0 z         (1000) z         (1000)    14368 2022-06-15 13:43:26.000000 thingsboard-gateway-3.2/thingsboard_gateway/gateway/grpc_service/tb_grpc_manager.py
--rw-rw-r--   0 z         (1000) z         (1000)     2610 2022-01-05 17:33:22.000000 thingsboard-gateway-3.2/thingsboard_gateway/gateway/grpc_service/tb_grpc_server.py
--rw-rw-r--   0 z         (1000) z         (1000)     1916 2022-06-13 11:01:36.000000 thingsboard-gateway-3.2/thingsboard_gateway/gateway/hot_reloader.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.663583 thingsboard-gateway-3.2/thingsboard_gateway/gateway/proto/
--rw-rw-r--   0 z         (1000) z         (1000)     1093 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/gateway/proto/__init__.py
--rw-rw-r--   0 z         (1000) z         (1000)    84155 2022-10-27 11:52:22.000000 thingsboard-gateway-3.2/thingsboard_gateway/gateway/proto/messages_pb2.py
--rw-rw-r--   0 z         (1000) z         (1000)     2542 2022-06-15 13:52:13.000000 thingsboard-gateway-3.2/thingsboard_gateway/gateway/proto/messages_pb2_grpc.py
--rw-rw-r--   0 z         (1000) z         (1000)     4443 2022-08-11 08:44:36.000000 thingsboard-gateway-3.2/thingsboard_gateway/gateway/statistics_service.py
--rw-rw-r--   0 z         (1000) z         (1000)     8164 2022-10-27 11:54:00.000000 thingsboard-gateway-3.2/thingsboard_gateway/gateway/tb_client.py
--rw-rw-r--   0 z         (1000) z         (1000)    67247 2022-10-27 11:54:00.000000 thingsboard-gateway-3.2/thingsboard_gateway/gateway/tb_gateway_service.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.663583 thingsboard-gateway-3.2/thingsboard_gateway/storage/
--rw-rw-r--   0 z         (1000) z         (1000)      616 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/storage/__init__.py
--rw-rw-r--   0 z         (1000) z         (1000)     1152 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/storage/event_storage.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.663583 thingsboard-gateway-3.2/thingsboard_gateway/storage/file/
--rw-rw-r--   0 z         (1000) z         (1000)        0 2021-10-13 08:00:17.000000 thingsboard-gateway-3.2/thingsboard_gateway/storage/file/__init__.py
--rw-rw-r--   0 z         (1000) z         (1000)      977 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/storage/file/event_storage_files.py
--rw-rw-r--   0 z         (1000) z         (1000)     8869 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/storage/file/event_storage_reader.py
--rw-rw-r--   0 z         (1000) z         (1000)     1115 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/storage/file/event_storage_reader_pointer.py
--rw-rw-r--   0 z         (1000) z         (1000)     5573 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/storage/file/event_storage_writer.py
--rw-rw-r--   0 z         (1000) z         (1000)     4053 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/storage/file/file_event_storage.py
--rw-rw-r--   0 z         (1000) z         (1000)     1459 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/storage/file/file_event_storage_settings.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.663583 thingsboard-gateway-3.2/thingsboard_gateway/storage/memory/
--rw-rw-r--   0 z         (1000) z         (1000)        0 2021-10-13 08:00:17.000000 thingsboard-gateway-3.2/thingsboard_gateway/storage/memory/__init__.py
--rw-rw-r--   0 z         (1000) z         (1000)     2027 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/storage/memory/memory_event_storage.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.663583 thingsboard-gateway-3.2/thingsboard_gateway/storage/sqlite/
--rw-rw-r--   0 z         (1000) z         (1000)        0 2021-10-13 08:00:17.000000 thingsboard-gateway-3.2/thingsboard_gateway/storage/sqlite/__init__.py
--rw-rw-r--   0 z         (1000) z         (1000)     4370 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/storage/sqlite/database.py
--rw-rw-r--   0 z         (1000) z         (1000)      763 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/storage/sqlite/database_action_type.py
--rw-rw-r--   0 z         (1000) z         (1000)     2581 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/storage/sqlite/database_connector.py
--rw-rw-r--   0 z         (1000) z         (1000)      951 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/storage/sqlite/database_request.py
--rw-rw-r--   0 z         (1000) z         (1000)     2924 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/storage/sqlite/sqlite_event_storage.py
--rw-rw-r--   0 z         (1000) z         (1000)      908 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/storage/sqlite/storage_settings.py
--rw-rw-r--   0 z         (1000) z         (1000)     1319 2022-06-13 11:01:36.000000 thingsboard-gateway-3.2/thingsboard_gateway/tb_gateway.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.667582 thingsboard-gateway-3.2/thingsboard_gateway/tb_utility/
--rw-rw-r--   0 z         (1000) z         (1000)      616 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/tb_utility/__init__.py
--rw-rw-r--   0 z         (1000) z         (1000)    16303 2022-02-16 10:06:46.000000 thingsboard-gateway-3.2/thingsboard_gateway/tb_utility/tb_gateway_remote_configurator.py
--rw-rw-r--   0 z         (1000) z         (1000)     3555 2022-08-11 08:44:36.000000 thingsboard-gateway-3.2/thingsboard_gateway/tb_utility/tb_loader.py
--rw-rw-r--   0 z         (1000) z         (1000)     3812 2022-10-27 11:54:00.000000 thingsboard-gateway-3.2/thingsboard_gateway/tb_utility/tb_logger.py
--rw-rw-r--   0 z         (1000) z         (1000)     5039 2022-02-02 09:45:56.000000 thingsboard-gateway-3.2/thingsboard_gateway/tb_utility/tb_remote_shell.py
--rw-rw-r--   0 z         (1000) z         (1000)     4323 2022-09-27 10:37:08.000000 thingsboard-gateway-3.2/thingsboard_gateway/tb_utility/tb_updater.py
--rw-rw-r--   0 z         (1000) z         (1000)     8879 2022-10-27 11:54:00.000000 thingsboard-gateway-3.2/thingsboard_gateway/tb_utility/tb_utility.py
-drwxrwxr-x   0 z         (1000) z         (1000)        0 2022-10-27 14:36:16.655583 thingsboard-gateway-3.2/thingsboard_gateway.egg-info/
--rw-rw-r--   0 z         (1000) z         (1000)     5443 2022-10-27 14:36:16.000000 thingsboard-gateway-3.2/thingsboard_gateway.egg-info/PKG-INFO
--rw-rw-r--   0 z         (1000) z         (1000)     9328 2022-10-27 14:36:16.000000 thingsboard-gateway-3.2/thingsboard_gateway.egg-info/SOURCES.txt
--rw-rw-r--   0 z         (1000) z         (1000)        1 2022-10-27 14:36:16.000000 thingsboard-gateway-3.2/thingsboard_gateway.egg-info/dependency_links.txt
--rw-rw-r--   0 z         (1000) z         (1000)      164 2022-10-27 14:36:16.000000 thingsboard-gateway-3.2/thingsboard_gateway.egg-info/entry_points.txt
--rw-rw-r--   0 z         (1000) z         (1000)      127 2022-10-27 14:36:16.000000 thingsboard-gateway-3.2/thingsboard_gateway.egg-info/requires.txt
--rw-rw-r--   0 z         (1000) z         (1000)       20 2022-10-27 14:36:16.000000 thingsboard-gateway-3.2/thingsboard_gateway.egg-info/top_level.txt
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.897214 thingsboard-gateway-3.3/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)    11357 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/LICENSE
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)       49 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/MANIFEST.in
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     5443 2023-06-28 10:44:14.897214 thingsboard-gateway-3.3/PKG-INFO
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     4967 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/README.md
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)       38 2023-06-28 10:44:14.897214 thingsboard-gateway-3.3/setup.cfg
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     4050 2023-06-28 09:44:19.000000 thingsboard-gateway-3.3/setup.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.881213 thingsboard-gateway-3.3/thingsboard_gateway/
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.885213 thingsboard-gateway-3.3/thingsboard_gateway/config/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     1435 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/config/bacnet.json
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     2003 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/config/ble.json
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     2217 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/config/can.json
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      685 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/config/custom_serial.json
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     1304 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/config/ftp.json
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)       77 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/config/grpc_connector_1.json
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      288 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/config/list.json
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     2475 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/config/logs.conf
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     5993 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/config/modbus.json
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     1816 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/config/modbus_serial.json
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     4633 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/config/mqtt.json
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     1434 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/config/ocpp.json
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     1260 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/config/odbc.json
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     1302 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/config/opcua.json
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     4199 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/config/request.json
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     4609 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/config/rest.json
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     3259 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/config/snmp.json
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     1222 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/config/socket.json
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.885213 thingsboard-gateway-3.3/thingsboard_gateway/config/statistics/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      744 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/config/statistics/statistics_linux.json
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      801 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/config/statistics/statistics_macos.json
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      765 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/config/statistics/statistics_windows.json
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     2780 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/config/tb_gateway.yaml
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     1112 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/config/xmpp.json
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.885213 thingsboard-gateway-3.3/thingsboard_gateway/connectors/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      616 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/__init__.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.885213 thingsboard-gateway-3.3/thingsboard_gateway/connectors/bacnet/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      616 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/bacnet/__init__.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)    16265 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/bacnet/bacnet_connector.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      816 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/bacnet/bacnet_converter.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      876 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/bacnet/bacnet_downlink_converter.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     2842 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/bacnet/bacnet_uplink_converter.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.885213 thingsboard-gateway-3.3/thingsboard_gateway/connectors/bacnet/bacnet_utilities/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      616 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/bacnet/bacnet_utilities/__init__.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)    10614 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/bacnet/bacnet_utilities/tb_gateway_bacnet_application.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      834 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/bacnet/bacnet_utilities/tb_gateway_bacnet_device.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.885213 thingsboard-gateway-3.3/thingsboard_gateway/connectors/ble/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      616 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/ble/__init__.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     6804 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/ble/ble_connector.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      811 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/ble/ble_uplink_converter.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     3764 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/ble/bytes_ble_uplink_converter.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)    14077 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/ble/device.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      516 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/ble/error_handler.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     2458 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/ble/hex_bytes_ble_uplink_converter.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.885213 thingsboard-gateway-3.3/thingsboard_gateway/connectors/can/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      616 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/can/__init__.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     3212 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/can/bytes_can_downlink_converter.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     3554 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/can/bytes_can_uplink_converter.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)    31649 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/can/can_connector.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      792 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/can/can_converter.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     1504 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/connector.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      801 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/converter.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.885213 thingsboard-gateway-3.3/thingsboard_gateway/connectors/ftp/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      616 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/ftp/__init__.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     2002 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/ftp/file.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)    13164 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/ftp/ftp_connector.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      799 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/ftp/ftp_converter.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)    11112 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/ftp/ftp_uplink_converter.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     5603 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/ftp/path.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.885213 thingsboard-gateway-3.3/thingsboard_gateway/connectors/modbus/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      616 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/modbus/__init__.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     3512 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/modbus/backward_compability_adapter.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     6013 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/modbus/bytes_modbus_downlink_converter.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     8457 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/modbus/bytes_modbus_uplink_converter.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     2017 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/modbus/constants.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)    35463 2023-06-28 09:37:28.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/modbus/modbus_connector.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      807 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/modbus/modbus_converter.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     4906 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/modbus/slave.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.889213 thingsboard-gateway-3.3/thingsboard_gateway/connectors/mqtt/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      616 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/mqtt/__init__.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     2721 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/mqtt/bytes_mqtt_uplink_converter.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     7401 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/mqtt/json_mqtt_uplink_converter.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)    47087 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/mqtt/mqtt_connector.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      436 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/mqtt/mqtt_decorators.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      812 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/mqtt/mqtt_uplink_converter.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.889213 thingsboard-gateway-3.3/thingsboard_gateway/connectors/ocpp/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      616 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/ocpp/__init__.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     4267 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/ocpp/charge_point.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)    12981 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/ocpp/ocpp_connector.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      805 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/ocpp/ocpp_converter.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     6496 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/ocpp/ocpp_uplink_converter.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.889213 thingsboard-gateway-3.3/thingsboard_gateway/connectors/odbc/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      616 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/odbc/__init__.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)    22776 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/odbc/odbc_connector.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      788 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/odbc/odbc_converter.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     2431 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/odbc/odbc_uplink_converter.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.889213 thingsboard-gateway-3.3/thingsboard_gateway/connectors/opcua/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      616 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/opcua/__init__.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)    37709 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/opcua/opcua_connector.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      818 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/opcua/opcua_converter.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     4200 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/opcua/opcua_uplink_converter.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.889213 thingsboard-gateway-3.3/thingsboard_gateway/connectors/opcua_asyncio/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)        0 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/opcua_asyncio/__init__.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     2018 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/opcua_asyncio/device.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)    24786 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/opcua_asyncio/opcua_connector.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      805 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/opcua_asyncio/opcua_converter.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     3073 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/opcua_asyncio/opcua_uplink_converter.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.889213 thingsboard-gateway-3.3/thingsboard_gateway/connectors/request/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      616 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/request/__init__.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     3653 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/request/json_request_downlink_converter.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     6912 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/request/json_request_uplink_converter.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)    14939 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/request/request_connector.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      808 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/request/request_converter.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      810 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/request/request_uplink_converter.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.889213 thingsboard-gateway-3.3/thingsboard_gateway/connectors/rest/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      616 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/rest/__init__.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     3296 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/rest/json_rest_downlink_converter.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     6434 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/rest/json_rest_uplink_converter.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)    26699 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/rest/rest_connector.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      770 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/rest/rest_converter.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     2610 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/rest/ssl_generator.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.889213 thingsboard-gateway-3.3/thingsboard_gateway/connectors/snmp/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      626 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/snmp/__init__.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)    12454 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/snmp/snmp_connector.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     1093 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/snmp/snmp_downlink_converter.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     2289 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/snmp/snmp_uplink_converter.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.889213 thingsboard-gateway-3.3/thingsboard_gateway/connectors/socket/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      616 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/socket/__init__.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     2702 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/socket/bytes_socket_uplink_converter.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)    16991 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/socket/socket_connector.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      436 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/socket/socket_decorators.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      814 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/socket/socket_uplink_converter.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.889213 thingsboard-gateway-3.3/thingsboard_gateway/connectors/xmpp/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      616 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/xmpp/__init__.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)    10501 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/xmpp/xmpp_connector.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      804 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/xmpp/xmpp_converter.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     7774 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/connectors/xmpp/xmpp_uplink_converter.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.889213 thingsboard-gateway-3.3/thingsboard_gateway/extensions/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      616 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/extensions/__init__.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.889213 thingsboard-gateway-3.3/thingsboard_gateway/extensions/bacnet/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      616 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/extensions/bacnet/__init__.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.889213 thingsboard-gateway-3.3/thingsboard_gateway/extensions/ble/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      616 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/extensions/ble/__init__.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.889213 thingsboard-gateway-3.3/thingsboard_gateway/extensions/can/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      616 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/extensions/can/__init__.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.889213 thingsboard-gateway-3.3/thingsboard_gateway/extensions/ftp/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)        0 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/extensions/ftp/__init__.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.889213 thingsboard-gateway-3.3/thingsboard_gateway/extensions/modbus/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      616 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/extensions/modbus/__init__.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.893214 thingsboard-gateway-3.3/thingsboard_gateway/extensions/mqtt/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      616 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/extensions/mqtt/__init__.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     2699 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/extensions/mqtt/custom_mqtt_uplink_converter.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.893214 thingsboard-gateway-3.3/thingsboard_gateway/extensions/ocpp/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      616 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/extensions/ocpp/__init__.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.893214 thingsboard-gateway-3.3/thingsboard_gateway/extensions/odbc/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      616 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/extensions/odbc/__init__.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.893214 thingsboard-gateway-3.3/thingsboard_gateway/extensions/opcua/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      616 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/extensions/opcua/__init__.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.893214 thingsboard-gateway-3.3/thingsboard_gateway/extensions/opcua_asyncio/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      616 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/extensions/opcua_asyncio/__init__.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.893214 thingsboard-gateway-3.3/thingsboard_gateway/extensions/request/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      616 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/extensions/request/__init__.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     3640 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/extensions/request/custom_request_uplink_converter.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.893214 thingsboard-gateway-3.3/thingsboard_gateway/extensions/rest/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      616 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/extensions/rest/__init__.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.893214 thingsboard-gateway-3.3/thingsboard_gateway/extensions/serial/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      616 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/extensions/serial/__init__.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)    10913 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/extensions/serial/custom_serial_connector.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     2426 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/extensions/serial/custom_serial_converter.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.893214 thingsboard-gateway-3.3/thingsboard_gateway/extensions/snmp/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      618 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/extensions/snmp/__init__.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.893214 thingsboard-gateway-3.3/thingsboard_gateway/extensions/socket/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      635 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/extensions/socket/__init__.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.893214 thingsboard-gateway-3.3/thingsboard_gateway/extensions/xmpp/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      635 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/extensions/xmpp/__init__.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.893214 thingsboard-gateway-3.3/thingsboard_gateway/gateway/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      616 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/gateway/__init__.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)    17309 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/gateway/configuration_wizard.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     1148 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/gateway/constant_enums.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     1810 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/gateway/constants.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      958 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/gateway/device_filter.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     5853 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/gateway/duplicate_detector.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.893214 thingsboard-gateway-3.3/thingsboard_gateway/gateway/grpc_service/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)        0 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/gateway/grpc_service/__init__.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     2512 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/gateway/grpc_service/grpc_connector.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     8579 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/gateway/grpc_service/grpc_downlink_converter.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     4713 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/gateway/grpc_service/grpc_uplink_converter.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)    14368 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/gateway/grpc_service/tb_grpc_manager.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     2610 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/gateway/grpc_service/tb_grpc_server.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     1916 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/gateway/hot_reloader.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.893214 thingsboard-gateway-3.3/thingsboard_gateway/gateway/proto/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     1093 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/gateway/proto/__init__.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)    84155 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/gateway/proto/messages_pb2.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     2542 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/gateway/proto/messages_pb2_grpc.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.893214 thingsboard-gateway-3.3/thingsboard_gateway/gateway/shell/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)        0 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/gateway/shell/__init__.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     2507 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/gateway/shell/proxy.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     6932 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/gateway/shell/shell.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     4530 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/gateway/statistics_service.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)    12262 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/gateway/tb_client.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)    72963 2023-06-28 09:37:51.000000 thingsboard-gateway-3.3/thingsboard_gateway/gateway/tb_gateway_service.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.893214 thingsboard-gateway-3.3/thingsboard_gateway/storage/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      616 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/storage/__init__.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     1205 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/storage/event_storage.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.893214 thingsboard-gateway-3.3/thingsboard_gateway/storage/file/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)        0 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/storage/file/__init__.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      977 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/storage/file/event_storage_files.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     8869 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/storage/file/event_storage_reader.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     1115 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/storage/file/event_storage_reader_pointer.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     5573 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/storage/file/event_storage_writer.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     4123 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/storage/file/file_event_storage.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     1459 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/storage/file/file_event_storage_settings.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.893214 thingsboard-gateway-3.3/thingsboard_gateway/storage/memory/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)        0 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/storage/memory/__init__.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     2090 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/storage/memory/memory_event_storage.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.893214 thingsboard-gateway-3.3/thingsboard_gateway/storage/sqlite/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)        0 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/storage/sqlite/__init__.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     4370 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/storage/sqlite/database.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      763 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/storage/sqlite/database_action_type.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     2581 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/storage/sqlite/database_connector.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      951 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/storage/sqlite/database_request.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     2951 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/storage/sqlite/sqlite_event_storage.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      908 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/storage/sqlite/storage_settings.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     1319 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/tb_gateway.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.897214 thingsboard-gateway-3.3/thingsboard_gateway/tb_utility/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      616 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/tb_utility/__init__.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)    16303 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/tb_utility/tb_gateway_remote_configurator.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     3582 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/tb_utility/tb_loader.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     3739 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/tb_utility/tb_logger.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     5039 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/tb_utility/tb_remote_shell.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     4323 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/tb_utility/tb_updater.py
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     9138 2023-05-26 10:21:57.000000 thingsboard-gateway-3.3/thingsboard_gateway/tb_utility/tb_utility.py
+drwxrwxr-x   0 imbeacon  (1001) imbeacon  (1002)        0 2023-06-28 10:44:14.881213 thingsboard-gateway-3.3/thingsboard_gateway.egg-info/
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     5443 2023-06-28 10:44:14.000000 thingsboard-gateway-3.3/thingsboard_gateway.egg-info/PKG-INFO
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)     9768 2023-06-28 10:44:14.000000 thingsboard-gateway-3.3/thingsboard_gateway.egg-info/SOURCES.txt
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)        1 2023-06-28 10:44:14.000000 thingsboard-gateway-3.3/thingsboard_gateway.egg-info/dependency_links.txt
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      222 2023-06-28 10:44:14.000000 thingsboard-gateway-3.3/thingsboard_gateway.egg-info/entry_points.txt
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)      155 2023-06-28 10:44:14.000000 thingsboard-gateway-3.3/thingsboard_gateway.egg-info/requires.txt
+-rw-rw-r--   0 imbeacon  (1001) imbeacon  (1002)       20 2023-06-28 10:44:14.000000 thingsboard-gateway-3.3/thingsboard_gateway.egg-info/top_level.txt
```

### Comparing `thingsboard-gateway-3.2/LICENSE` & `thingsboard-gateway-3.3/LICENSE`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/PKG-INFO` & `thingsboard-gateway-3.3/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,16 +1,16 @@
 Metadata-Version: 2.1
 Name: thingsboard-gateway
-Version: 3.2
+Version: 3.3
 Summary: Thingsboard Gateway for IoT devices.
 Home-page: https://github.com/thingsboard/thingsboard-gateway
 Author: ThingsBoard
 Author-email: info@thingsboard.io
 License: Apache Software License (Apache Software License 2.0)
-Download-URL: https://github.com/thingsboard/thingsboard-gateway/archive/3.2.tar.gz
+Download-URL: https://github.com/thingsboard/thingsboard-gateway/archive/3.3.tar.gz
 Platform: UNKNOWN
 Requires-Python: >=3.7
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 # ThingsBoard IoT Gateway
```

### Comparing `thingsboard-gateway-3.2/README.md` & `thingsboard-gateway-3.3/README.md`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/setup.py` & `thingsboard-gateway-3.3/setup.py`

 * *Files 5% similar despite different names*

```diff
@@ -13,34 +13,35 @@
 #     WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 #     See the License for the specific language governing permissions and
 #     limitations under the License.
 
 from setuptools import setup
 from os import path
 
-this_directory = path.abspath(path.dirname(__file__))
-with open(path.join(this_directory, 'README.md'), encoding='utf-8') as f:
+
+current_directory = path.abspath(path.dirname(__file__))
+with open(path.join(current_directory, 'README.md'), encoding='utf-8') as f:
     long_description = f.read()
 
-VERSION = "3.2"
+VERSION = "3.3"
 
 setup(
     version=VERSION,
     name="thingsboard-gateway",
     author="ThingsBoard",
     author_email="info@thingsboard.io",
     license="Apache Software License (Apache Software License 2.0)",
     description="Thingsboard Gateway for IoT devices.",
     url="https://github.com/thingsboard/thingsboard-gateway",
     long_description=long_description,
     long_description_content_type="text/markdown",
     include_package_data=True,
     python_requires=">=3.7",
     packages=['thingsboard_gateway', 'thingsboard_gateway.gateway', 'thingsboard_gateway.gateway.proto', 'thingsboard_gateway.gateway.grpc_service',
-              'thingsboard_gateway.storage', 'thingsboard_gateway.storage.memory',
+              'thingsboard_gateway.storage', 'thingsboard_gateway.storage.memory', 'thingsboard_gateway.gateway.shell',
               'thingsboard_gateway.storage.file', 'thingsboard_gateway.storage.sqlite',
               'thingsboard_gateway.connectors', 'thingsboard_gateway.connectors.ble', 'thingsboard_gateway.connectors.socket',
               'thingsboard_gateway.connectors.mqtt',  'thingsboard_gateway.connectors.opcua_asyncio', 'thingsboard_gateway.connectors.xmpp',
               'thingsboard_gateway.connectors.opcua', 'thingsboard_gateway.connectors.request', 'thingsboard_gateway.connectors.ocpp',
               'thingsboard_gateway.connectors.modbus', 'thingsboard_gateway.connectors.can', 'thingsboard_gateway.connectors.bacnet',
               'thingsboard_gateway.connectors.bacnet.bacnet_utilities', 'thingsboard_gateway.connectors.odbc',
               'thingsboard_gateway.connectors.rest', 'thingsboard_gateway.connectors.snmp', 'thingsboard_gateway.connectors.ftp',
@@ -55,22 +56,24 @@
     install_requires=[
         'cryptography',
         'jsonpath-rw',
         'regex',
         'pip',
         'PyYAML',
         'simplejson',
-        'requests',
+        'requests>=2.31.0',
         'PyInquirer',
         'pyfiglet',
         'termcolor',
         'grpcio<=1.43.0',
         'protobuf',
-        'cachetools'
+        'cachetools',
+        'tb-mqtt-client>=1.5'
     ],
     download_url='https://github.com/thingsboard/thingsboard-gateway/archive/%s.tar.gz' % VERSION,
     entry_points={
         'console_scripts': [
             'thingsboard-gateway = thingsboard_gateway.tb_gateway:daemon',
-            'tb-gateway-configurator = thingsboard_gateway.gateway.configuration_wizard:configure'
+            'tb-gateway-configurator = thingsboard_gateway.gateway.configuration_wizard:configure',
+            'tb-gateway-shell = thingsboard_gateway.gateway.shell:main'
         ]
     })
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/__init__.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/odbc/odbc_converter.py`

 * *Files 10% similar despite different names*

```diff
@@ -8,8 +8,14 @@
 #
 #     Unless required by applicable law or agreed to in writing, software
 #     distributed under the License is distributed on an "AS IS" BASIS,
 #     WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 #     See the License for the specific language governing permissions and
 #     limitations under the License.
 
-from thingsboard_gateway.gateway.tb_gateway_service import TBGatewayService
+from thingsboard_gateway.connectors.converter import ABC, abstractmethod
+
+
+class OdbcConverter(ABC):
+    @abstractmethod
+    def convert(self, config, data):
+        pass
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/config/bacnet.json` & `thingsboard-gateway-3.3/thingsboard_gateway/config/bacnet.json`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/config/ble.json` & `thingsboard-gateway-3.3/thingsboard_gateway/config/ble.json`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/config/can.json` & `thingsboard-gateway-3.3/thingsboard_gateway/config/can.json`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/config/custom_serial.json` & `thingsboard-gateway-3.3/thingsboard_gateway/config/custom_serial.json`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/config/ftp.json` & `thingsboard-gateway-3.3/thingsboard_gateway/config/ftp.json`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/config/logs.conf` & `thingsboard-gateway-3.3/thingsboard_gateway/config/logs.conf`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/config/modbus.json` & `thingsboard-gateway-3.3/thingsboard_gateway/config/modbus.json`

 * *Files 3% similar despite different names*

#### Pretty-printed

 * *Similarity: 0.9598214285714286%*

 * *Differences: {"'master'": "{'slaves': {0: {'byteOrder': 'LITTLE', 'wordOrder': 'LITTLE'}}}",*

 * * "'slave'": "{'byteOrder': 'LITTLE', 'wordOrder': 'LITTLE'}"}*

```diff
@@ -67,15 +67,15 @@
                         "address": 13,
                         "functionCode": 4,
                         "objectsCount": 4,
                         "tag": "64int_read",
                         "type": "64int"
                     }
                 ],
-                "byteOrder": "BIG",
+                "byteOrder": "LITTLE",
                 "connectAttemptCount": 5,
                 "connectAttemptTimeMs": 5000,
                 "deviceName": "Temp Sensor",
                 "host": "127.0.0.1",
                 "method": "socket",
                 "pollPeriod": 5000,
                 "port": 5021,
@@ -163,20 +163,21 @@
                         "objectsCount": 4,
                         "tag": "64float_read",
                         "type": "64float"
                     }
                 ],
                 "type": "tcp",
                 "unitId": 1,
-                "waitAfterFailedAttemptsMs": 300000
+                "waitAfterFailedAttemptsMs": 300000,
+                "wordOrder": "LITTLE"
             }
         ]
     },
     "slave": {
-        "byteOrder": "BIG",
+        "byteOrder": "LITTLE",
         "deviceName": "Modbus Slave Example",
         "deviceType": "default",
         "host": "127.0.0.1",
         "method": "socket",
         "pollPeriod": 5000,
         "port": 5026,
         "sendDataToThingsBoard": false,
@@ -237,10 +238,11 @@
                             "tag": "smm",
                             "type": "int",
                             "value": "12334"
                         }
                     ]
                 }
             ]
-        }
+        },
+        "wordOrder": "LITTLE"
     }
 }
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/config/mqtt.json` & `thingsboard-gateway-3.3/thingsboard_gateway/config/mqtt.json`

 * *Files 6% similar despite different names*

#### Pretty-printed

 * *Similarity: 0.9890341553287981%*

 * *Differences: {"'broker'": "{'sendDataOnlyOnChange': False}",*

 * * "'mapping'": "{0: {'converter': {'sendDataOnlyOnChange': False}}, 1: {'converter': "*

 * *              "{'sendDataOnlyOnChange': False}}, 2: {'converter': {'sendDataOnlyOnChange': "*

 * *              "False}}, 3: {'converter': {'cached': True}}}"}*

```diff
@@ -26,14 +26,15 @@
         "name": "Default Local Broker",
         "port": 1883,
         "security": {
             "password": "password",
             "type": "basic",
             "username": "user"
         },
+        "sendDataOnlyOnChange": false,
         "version": 5
     },
     "connectRequests": [
         {
             "deviceNameJsonExpression": "${SerialNumber}",
             "topicFilter": "sensor/connect"
         },
@@ -65,14 +66,15 @@
                         "key": "${sensorModel}",
                         "type": "string",
                         "value": "on"
                     }
                 ],
                 "deviceNameJsonExpression": "${serialNumber}",
                 "deviceTypeJsonExpression": "${sensorType}",
+                "sendDataOnlyOnChange": false,
                 "timeout": 60000,
                 "timeseries": [
                     {
                         "key": "temperature",
                         "type": "double",
                         "value": "${temp}"
                     },
@@ -98,14 +100,15 @@
                         "key": "model",
                         "type": "string",
                         "value": "${sensorModel}"
                     }
                 ],
                 "deviceNameTopicExpression": "(?<=sensor/)(.*?)(?=/data)",
                 "deviceTypeTopicExpression": "Thermometer",
+                "sendDataOnlyOnChange": false,
                 "timeout": 60000,
                 "timeseries": [
                     {
                         "key": "temperature",
                         "type": "double",
                         "value": "${temp}"
                     },
@@ -126,28 +129,30 @@
                         "key": "rawData",
                         "type": "raw",
                         "value": "[:]"
                     }
                 ],
                 "deviceNameExpression": "[0:4]",
                 "deviceTypeExpression": "default",
+                "sendDataOnlyOnChange": false,
                 "timeout": 60000,
                 "timeseries": [
                     {
                         "key": "temp",
                         "type": "raw",
                         "value": "[4:]"
                     }
                 ],
                 "type": "bytes"
             },
             "topicFilter": "/sensor/raw_data"
         },
         {
             "converter": {
+                "cached": true,
                 "extension": "CustomMqttUplinkConverter",
                 "extension-config": {
                     "batteryLevelBytes": 1,
                     "humidityBytes": 2,
                     "temperatureBytes": 2
                 },
                 "type": "custom"
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/config/ocpp.json` & `thingsboard-gateway-3.3/thingsboard_gateway/config/ocpp.json`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/config/odbc.json` & `thingsboard-gateway-3.3/thingsboard_gateway/config/odbc.json`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/config/opcua.json` & `thingsboard-gateway-3.3/thingsboard_gateway/config/opcua.json`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/config/request.json` & `thingsboard-gateway-3.3/thingsboard_gateway/config/request.json`

 * *Files 5% similar despite different names*

#### Pretty-printed

 * *Similarity: 0.9600649350649352%*

 * *Differences: {"'attributeUpdates'": "{0: {'requestValueExpression': "*

 * *                       '\'{"${attributeKey}":"${attributeValue}"}\', delete: '*

 * *                       "['valueExpression']}}",*

 * * "'serverSideRpc'": "{0: {'requestValueExpression': '${params}', 'responseValueExpression': "*

 * *                    "'${temp}', delete: ['valueExpression']}, 1: {'requestValueExpression': "*

 * *                    "'${params}', delete: ['valueExpression']}}"}*

```diff
@@ -6,17 +6,17 @@
             "attributeFilter": "send_data",
             "deviceNameFilter": "SD.*",
             "httpHeaders": {
                 "CONTENT-TYPE": "application/json"
             },
             "httpMethod": "POST",
             "requestUrlExpression": "sensor/${deviceName}/${attributeKey}",
+            "requestValueExpression": "{\"${attributeKey}\":\"${attributeValue}\"}",
             "timeout": 0.5,
-            "tries": 3,
-            "valueExpression": "{\"${attributeKey}\":\"${attributeValue}\"}"
+            "tries": 3
         }
     ],
     "host": "http://127.0.0.1:5000",
     "mapping": [
         {
             "allowRedirects": true,
             "content": {
@@ -145,24 +145,25 @@
             "deviceNameFilter": ".*",
             "httpHeaders": {
                 "Content-Type": "application/json"
             },
             "httpMethod": "GET",
             "methodFilter": "echo",
             "requestUrlExpression": "sensor/${deviceName}/request/${methodName}/${requestId}",
+            "requestValueExpression": "${params}",
             "responseTimeout": 1,
+            "responseValueExpression": "${temp}",
             "timeout": 0.5,
-            "tries": 3,
-            "valueExpression": "${params}"
+            "tries": 3
         },
         {
             "deviceNameFilter": ".*",
             "httpHeaders": {
                 "Content-Type": "application/json"
             },
             "httpMethod": "POST",
             "methodFilter": "no-reply",
             "requestUrlExpression": "sensor/${deviceName}/request/${methodName}/${requestId}",
-            "valueExpression": "${params}"
+            "requestValueExpression": "${params}"
         }
     ]
 }
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/config/rest.json` & `thingsboard-gateway-3.3/thingsboard_gateway/config/rest.json`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/config/snmp.json` & `thingsboard-gateway-3.3/thingsboard_gateway/config/snmp.json`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/config/socket.json` & `thingsboard-gateway-3.3/thingsboard_gateway/config/socket.json`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/config/statistics.json` & `thingsboard-gateway-3.3/thingsboard_gateway/config/statistics/statistics_macos.json`

 * *Files 10% similar despite different names*

#### Pretty-printed

 * *Similarity: 0.9583333333333334%*

 * *Differences: {'2': "{'command': {insert: [(2, 'hostname -I')], delete: [2]}}",*

 * * '3': '{\'command\': {insert: [(2, \'cat /etc/*-release | grep "PRETTY_NAME" | sed '*

 * *      "\\'s/PRETTY_NAME=//g\\'')], delete: [2]}}",*

 * * '5': "{'command': {insert: [(2, 'lsusb')], delete: [2]}}"}*

```diff
@@ -18,24 +18,24 @@
         "timeout": 100
     },
     {
         "attributeOnGateway": "IP address",
         "command": [
             "/bin/sh",
             "-c",
-            "ipconfig getifaddr en0"
+            "hostname -I"
         ],
         "timeout": 100
     },
     {
         "attributeOnGateway": "OS",
         "command": [
             "/bin/sh",
             "-c",
-            "sw_vers -productName"
+            "cat /etc/*-release | grep \"PRETTY_NAME\" | sed 's/PRETTY_NAME=//g'"
         ],
         "timeout": 100
     },
     {
         "attributeOnGateway": "Uptime",
         "command": [
             "/bin/sh",
@@ -45,12 +45,12 @@
         "timeout": 100
     },
     {
         "attributeOnGateway": "USBs",
         "command": [
             "/bin/sh",
             "-c",
-            "system_profiler SPUSBDataType"
+            "lsusb"
         ],
         "timeout": 100
     }
 ]
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/config/tb_gateway.yaml` & `thingsboard-gateway-3.3/thingsboard_gateway/config/tb_gateway.yaml`

 * *Files 2% similar despite different names*

```diff
@@ -1,18 +1,22 @@
 thingsboard:
   host: thingsboard.cloud
   port: 1883
   remoteShell: false
   remoteConfiguration: false
   statistics:
     enable: true
-    statsSendPeriodInSeconds: 3600
-    configuration: statistics.json
+    statsSendPeriodInSeconds: 60
+#    configuration: statistics/statistics_linux.json
+  deviceFiltering:
+    enable: false
+    filterFile: list.json
   maxPayloadSizeBytes: 1024
-  minPackSendDelayMS: 0
+  minPackSendDelayMS: 200
+  minPackSizeToSend: 500
   checkConnectorsConfigurationInSeconds: 60
   handleDeviceRenaming: true
   checkingDeviceActivity:
     checkDeviceInactivity: false
     inactivityTimeoutSeconds: 120
     inactivityCheckPeriodSeconds: 10
   security:
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/config/xmpp.json` & `thingsboard-gateway-3.3/thingsboard_gateway/config/xmpp.json`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/__init__.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/__init__.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/bacnet/__init__.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/bacnet/__init__.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/bacnet/bacnet_connector.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/bacnet/bacnet_connector.py`

 * *Files 0% similar despite different names*

```diff
@@ -307,7 +307,10 @@
             request_config = {
                 "method": request["method"],
                 "iocb": (self._application.form_iocb, kwarg_dict),
                 "config": request
             }
             result["server_side_rpc"].append(request_config)
         return result
+
+    def get_config(self):
+        return self.__config
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/bacnet/bacnet_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/bacnet/bacnet_converter.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/bacnet/bacnet_downlink_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/bacnet/bacnet_downlink_converter.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/bacnet/bacnet_uplink_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/bacnet/bacnet_uplink_converter.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/bacnet/bacnet_utilities/__init__.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/bacnet/bacnet_utilities/__init__.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/bacnet/bacnet_utilities/tb_gateway_bacnet_application.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/bacnet/bacnet_utilities/tb_gateway_bacnet_application.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/bacnet/bacnet_utilities/tb_gateway_bacnet_device.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/bacnet/bacnet_utilities/tb_gateway_bacnet_device.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/ble/__init__.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/ble/__init__.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/ble/ble_connector.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/ble/ble_connector.py`

 * *Files 5% similar despite different names*

```diff
@@ -55,15 +55,15 @@
 
         self.__devices = []
         self.__configure_and_load_devices()
 
     async def __show_map(self):
         scanner = self.__config.get('scanner', {})
         devices = await BleakScanner(
-            scanning_mode='active' if self.__config.get('passiveScanMode', True) else 'passive').discover(
+            scanning_mode='passive' if self.__config.get('passiveScanMode', True) else 'active').discover(
             timeout=scanner.get('timeout', 10000) / 1000)
 
         log.info('FOUND DEVICES')
         if scanner.get('deviceName'):
             found_devices = [x.__str__() for x in filter(lambda x: x.name == scanner['deviceName'], devices)]
             if found_devices:
                 log.info(', '.join(found_devices))
@@ -160,7 +160,10 @@
                             result = device.scan_self(return_result)
                         if return_result:
                             self.__gateway.send_rpc_reply(content['device'], content['data']['id'], str(result))
 
                         return
         except IndexError:
             log.error('Device not found')
+
+    def get_config(self):
+        return self.__config
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/ble/ble_uplink_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/ble/ble_uplink_converter.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/ble/bytes_ble_uplink_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/ble/bytes_ble_uplink_converter.py`

 * *Files 8% similar despite different names*

```diff
@@ -30,27 +30,29 @@
 from thingsboard_gateway.connectors.ble.ble_uplink_converter import BLEUplinkConverter, log
 from thingsboard_gateway.gateway.statistics_service import StatisticsService
 
 
 class BytesBLEUplinkConverter(BLEUplinkConverter):
     def __init__(self, config):
         self.__config = config
-        self.dict_result = {"deviceName": config['deviceName'],
-                            "deviceType": config['deviceType']
-                            }
 
     @StatisticsService.CollectStatistics(start_stat_type='receivedBytesFromDevices',
                                          end_stat_type='convertedBytesFromDevice')
     def convert(self, config, data):
         if data is None:
             return {}
 
+        dict_result = {
+            "deviceName": self.__config['deviceName'],
+            "deviceType": self.__config['deviceType']
+        }
+
         try:
-            self.dict_result["telemetry"] = []
-            self.dict_result["attributes"] = []
+            dict_result["telemetry"] = []
+            dict_result["attributes"] = []
 
             for section in ('telemetry', 'attributes'):
                 for item in data[section]:
                     try:
                         expression_arr = findall(r'\[[^\s][0-9:]*]', item['valueExpression'])
                         converted_data = item['valueExpression']
 
@@ -67,19 +69,19 @@
                                     data_to_replace += str(sub_item)
                             else:
                                 data_to_replace += str(item['data'][int(indexes[0])])
 
                             converted_data = converted_data.replace(exp, data_to_replace)
 
                         if item.get('key') is not None:
-                            self.dict_result[section].append({item['key']: converted_data})
+                            dict_result[section].append({item['key']: converted_data})
                         else:
                             log.error('Key for %s not found in config: %s', config['type'], config[section])
                     except Exception as e:
                         log.error('\nException caught when processing data for %s\n\n', pformat(config))
                         log.exception(e)
 
         except Exception as e:
             log.exception(e)
 
-        log.debug(self.dict_result)
-        return self.dict_result
+        log.debug(dict_result)
+        return dict_result
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/ble/device.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/ble/device.py`

 * *Files 12% similar despite different names*

```diff
@@ -25,15 +25,15 @@
 #     limitations under the License.
 
 from threading import Thread
 from platform import system
 from time import time, sleep
 import asyncio
 
-from bleak import BleakClient
+from bleak import BleakClient, BleakScanner
 
 from thingsboard_gateway.connectors.connector import log
 from thingsboard_gateway.gateway.statistics_service import StatisticsService
 from thingsboard_gateway.tb_utility.tb_loader import TBModuleLoader
 from thingsboard_gateway.connectors.ble.error_handler import ErrorHandler
 
 MAC_ADDRESS_FORMAT = {
@@ -64,57 +64,82 @@
             self.client = BleakClient(self.mac_address)
         except ValueError as e:
             self.client = None
             self.stopped = True
             log.error(e)
 
         self.poll_period = config.get('pollPeriod', 5000) / 1000
-        self.config = {
-            'extension': config.get('extension', DEFAULT_CONVERTER_CLASS_NAME),
-            'telemetry': config.get('telemetry', []),
-            'attributes': config.get('attributes', []),
-            'attributeUpdates': config.get('attributeUpdates', []),
-            'serverSideRpc': config.get('serverSideRpc', [])
-        }
+        self.config = self._generate_config(config)
+        self.adv_only = self._check_adv_mode()
         self.callback = config['callback']
         self.last_polled_time = self.poll_period + 1
 
         self.notifying_chars = []
 
-        self.__converter = None
-        self.__load_converter()
-
         self.start()
 
+    def _check_adv_mode(self):
+        if len(self.config['characteristic']['telemetry']) or len(self.config['characteristic']['attributes']):
+            return False
+
+        return True
+
+    def _generate_config(self, config):
+        new_config = {
+            'characteristic': {
+                'extension': self.__load_converter(config.get('extension', DEFAULT_CONVERTER_CLASS_NAME if config.get(
+                    'type', 'bytes') == 'bytes' else 'HexBytesBLEUplinkConverter')),
+                'telemetry': [],
+                'attributes': []
+            },
+            'advertisement': {
+                'extension': self.__load_converter(config.get('extension', 'HexBytesBLEUplinkConverter' if config.get(
+                    'type', 'hex') == 'hex' else DEFAULT_CONVERTER_CLASS_NAME)),
+                'telemetry': [],
+                'attributes': []
+            },
+            'attributeUpdates': config.get('attributeUpdates', []),
+            'serverSideRpc': config.get('serverSideRpc', [])
+        }
+
+        for section in ('telemetry', 'attributes'):
+            for section_config in config[section]:
+                if section_config.get('dataSourceType', 'characteristic') == 'characteristic':
+                    new_config['characteristic'][section].append(section_config)
+                else:
+                    new_config['advertisement'][section].append(section_config)
+
+        return new_config
+
     @staticmethod
     def validate_mac_address(mac_address):
         os_name = system()
 
         if MAC_ADDRESS_FORMAT[os_name if os_name == 'Darwin' else 'other'] not in mac_address:
             raise ValueError(f'Mac-address is invalid for {os_name} os')
 
         return mac_address.upper()
 
-    def __load_converter(self):
-        converter_class_name = self.config['extension']
-        module = TBModuleLoader.import_module(self.__connector_type, converter_class_name)
+    def __load_converter(self, name):
+        module = TBModuleLoader.import_module(self.__connector_type, name)
 
         if module:
-            log.debug('Converter %s for device %s - found!', converter_class_name, self.name)
-            self.__converter = module
+            log.debug('Converter %s for device %s - found!', name, self.name)
+            return module
         else:
             log.error("Cannot find converter for %s device", self.name)
             self.stopped = True
 
     async def timer(self):
         while True:
             try:
                 if time() - self.last_polled_time >= self.poll_period:
                     self.last_polled_time = time()
                     await self.__process_self()
+                    await self._process_adv_data()
                 else:
                     await asyncio.sleep(.2)
             except Exception as e:
                 log.error('Problem with connection')
                 log.debug(e)
 
                 try:
@@ -132,38 +157,37 @@
 
                     sleep(self.connect_retry_in_seconds)
                     sleep(.2)
 
     async def notify_callback(self, sender: int, data: bytearray):
         not_converted_data = {'telemetry': [], 'attributes': []}
         for section in ('telemetry', 'attributes'):
-            for item in self.config[section]:
+            for item in self.config['characteristic'][section]:
                 if item.get('handle') and item['handle'] == sender:
                     not_converted_data[section].append({'data': data, **item})
 
                     data_for_converter = {
                         'deviceName': self.name,
                         'deviceType': self.device_type,
-                        'converter': self.__converter,
+                        'converter': self.config['characteristic']['extension'],
                         'config': {
-                            'attributes': self.config['attributes'],
-                            'telemetry': self.config['telemetry']
+                            **self.config['characteristic']
                         },
                         'data': not_converted_data
                     }
 
                     self.callback(data_for_converter)
 
     async def notify(self, char_id):
         await self.client.start_notify(char_id, self.notify_callback)
 
     async def __process_self(self):
         not_converted_data = {'telemetry': [], 'attributes': []}
         for section in ('telemetry', 'attributes'):
-            for item in self.config[section]:
+            for item in self.config['characteristic'][section]:
                 char_id = item['characteristicUUID']
 
                 if item['method'] == 'read':
                     try:
                         data = await self.client.read_gatt_char(char_id)
                         not_converted_data[section].append({'data': data, **item})
                     except Exception as e:
@@ -186,50 +210,92 @@
                         else:
                             raise e
 
         if len(not_converted_data['telemetry']) > 0 or len(not_converted_data['attributes']) > 0:
             data_for_converter = {
                 'deviceName': self.name,
                 'deviceType': self.device_type,
-                'converter': self.__converter,
+                'converter': self.config['characteristic']['extension'],
                 'config': {
-                    'attributes': self.config['attributes'],
-                    'telemetry': self.config['telemetry']
+                    **self.config['characteristic']
                 },
                 'data': not_converted_data
             }
             self.callback(data_for_converter)
 
     def __set_char_handle(self, item, char_id):
         for serv in self.client.services:
             for char in serv.characteristics:
                 if char.uuid == char_id:
                     item['handle'] = char.handle
                     return
 
-    async def connect_to_device(self):
+    async def _connect_to_device(self):
         try:
             log.info('Trying to connect to %s with %s MAC address', self.name, self.mac_address)
             await self.client.connect(timeout=self.timeout)
         except Exception as e:
             log.error(e)
 
-    async def run_client(self):
+    def filter_macaddress(self, device):
+        macaddress, device = device
+        if macaddress == self.mac_address:
+            return True
+
+        return False
+
+    async def _process_adv_data(self):
+        devices = await BleakScanner(scanning_mode="active").discover(timeout=self.timeout, return_adv=True)
+
+        try:
+            device = tuple(filter(self.filter_macaddress, devices.items()))[0][-1]
+        except IndexError:
+            log.error('Device with MAC address %s not found!', self.mac_address)
+            return
+
+        try:
+            advertisement_data = list(device[-1].manufacturer_data.values())[0]
+        except (IndexError, AttributeError):
+            log.error('Device %s haven\'t advertisement data', self.name)
+            return
+
+        data_for_converter = {
+            'deviceName': self.name,
+            'deviceType': self.device_type,
+            'converter': self.config['advertisement']['extension'],
+            'config': {
+                **self.config['advertisement']
+            },
+            'data': advertisement_data
+        }
+
+        self.callback(data_for_converter)
+
+    async def connect_to_device(self):
         while not self.stopped and not self.client.is_connected:
-            await self.connect_to_device()
+            await self._connect_to_device()
 
             sleep(.2)
 
-        if self.client and self.client.is_connected:
-            log.info('Connected to %s device', self.name)
+    async def run_client(self):
+        if not self.adv_only or self.show_map:
+            # default mode
+            await self.connect_to_device()
+
+            if self.client and self.client.is_connected:
+                log.info('Connected to %s device', self.name)
 
-            if self.show_map:
-                await self.__show_map()
+                if self.show_map:
+                    await self.__show_map()
 
-            await self.timer()
+                await self.timer()
+        else:
+            while not self.stopped:
+                await self._process_adv_data()
+                sleep(self.poll_period)
 
     def run(self):
         self.loop = asyncio.new_event_loop()
         self.loop.run_until_complete(self.run_client())
 
     async def __show_map(self, return_result=False):
         result = f'MAP FOR {self.name.upper()}'
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/ble/error_handler.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/ble/error_handler.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/can/__init__.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/can/__init__.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/can/bytes_can_downlink_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/can/bytes_can_downlink_converter.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/can/bytes_can_uplink_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/can/bytes_can_uplink_converter.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/can/can_connector.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/can/can_connector.py`

 * *Files 0% similar despite different names*

```diff
@@ -66,14 +66,15 @@
     def __init__(self, gateway, config, connector_type):
         self.statistics = {'MessagesReceived': 0,
                            'MessagesSent': 0}
         super().__init__()
         self.setName(config.get("name", 'CAN Connector ' + ''.join(choice(ascii_lowercase) for _ in range(5))))
         self.__gateway = gateway
         self._connector_type = connector_type
+        self.__config = config
         self.__bus_conf = {}
         self.__bus = None
         self.__reconnect_count = 0
         self.__reconnect_conf = {}
         self.__devices = {}
         self.__nodes = {}
         self.__commands = {}
@@ -593,14 +594,17 @@
                 return BytesCanUplinkConverter() if uplink is None \
                     else TBModuleLoader.import_module(self._connector_type, uplink)
             else:
                 downlink = config.get("downlink")
                 return BytesCanDownlinkConverter() if downlink is None \
                     else TBModuleLoader.import_module(self._connector_type, downlink)
 
+    def get_config(self):
+        return self.__config
+
 
 class Poller(Thread):
     def __init__(self, connector: CanConnector):
         super().__init__()
         self.connector = connector
         self.scheduler = sched.scheduler(time.time, time.sleep)
         self.events = []
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/can/can_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/can/can_converter.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/connector.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/connector.py`

 * *Files 23% similar despite different names*

```diff
@@ -10,14 +10,15 @@
 #     distributed under the License is distributed on an "AS IS" BASIS,
 #     WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 #     See the License for the specific language governing permissions and
 #     limitations under the License.
 
 import logging
 from abc import ABC, abstractmethod
+from thingsboard_gateway.gateway.constants import DEFAULT_SEND_ON_CHANGE_INFINITE_TTL_VALUE, DEFAULT_SEND_ON_CHANGE_VALUE
 
 log = logging.getLogger("connector")
 
 
 class Connector(ABC):
 
     @abstractmethod
@@ -29,17 +30,27 @@
         pass
 
     @abstractmethod
     def get_name(self):
         pass
 
     @abstractmethod
+    def get_config(self):
+        pass
+
+    @abstractmethod
     def is_connected(self):
         pass
 
     @abstractmethod
     def on_attributes_update(self, content):
         pass
 
     @abstractmethod
     def server_side_rpc_handler(self, content):
         pass
+
+    def is_filtering_enable(self, device_name):
+        return DEFAULT_SEND_ON_CHANGE_VALUE
+
+    def get_ttl_for_duplicates(self, device_name):
+        return DEFAULT_SEND_ON_CHANGE_INFINITE_TTL_VALUE
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/converter.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/ftp/__init__.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/ftp/__init__.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/ftp/file.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/ftp/file.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/ftp/ftp_connector.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/ftp/ftp_connector.py`

 * *Files 3% similar despite different names*

```diff
@@ -139,15 +139,15 @@
 
                 if '*' in path.path:
                     path.find_files(ftp)
 
                 for file in path.files:
                     current_hash = file.get_current_hash(ftp)
                     if ((file.has_hash() and current_hash != file.hash)
-                        or not file.has_hash()) and file.check_size_limit(ftp):
+                            or not file.has_hash()) and file.check_size_limit(ftp):
                         file.set_new_hash(current_hash)
 
                         handle_stream = io.BytesIO()
 
                         ftp.retrbinary('RETR ' + file.path_to_file, handle_stream.write)
 
                         handled_str = str(handle_stream.getvalue(), 'UTF-8')
@@ -156,42 +156,42 @@
                         convert_conf = {'file_ext': file.path_to_file.split('.')[-1]}
 
                         if convert_conf['file_ext'] == 'json':
                             json_data = simplejson.loads(handled_str)
                             if isinstance(json_data, list):
                                 for obj in json_data:
                                     converted_data = converter.convert(convert_conf, obj)
-                                    self.__gateway.send_to_storage(self.getName(), converted_data)
-                                    self.statistics['MessagesSent'] = self.statistics['MessagesSent'] + 1
-                                    log.debug("Data to ThingsBoard: %s", converted_data)
+                                    self.__send_data(converted_data)
                             else:
                                 converted_data = converter.convert(convert_conf, json_data)
-                                self.__gateway.send_to_storage(self.getName(), converted_data)
-                                self.statistics['MessagesSent'] = self.statistics['MessagesSent'] + 1
-                                log.debug("Data to ThingsBoard: %s", converted_data)
+                                self.__send_data(converted_data)
                         else:
                             cursor = file.cursor or 0
 
                             for (index, line) in enumerate(handled_array):
                                 if index == 0 and not path.txt_file_data_view == 'SLICED':
                                     convert_conf['headers'] = line.split(path.delimiter)
                                 else:
                                     if file.read_mode == File.ReadMode.PARTIAL and index >= cursor:
                                         converted_data = converter.convert(convert_conf, line)
                                         if index + 1 == len(handled_array):
                                             file.cursor = index
                                     else:
                                         converted_data = converter.convert(convert_conf, line)
 
-                                    self.__gateway.send_to_storage(self.getName(), converted_data)
-                                    self.statistics['MessagesSent'] = self.statistics['MessagesSent'] + 1
-                                    log.debug("Data to ThingsBoard: %s", converted_data)
+                                    self.__send_data(converted_data)
 
                         handle_stream.close()
 
+    def __send_data(self, converted_data):
+        if converted_data:
+            self.__gateway.send_to_storage(self.getName(), converted_data)
+            self.statistics['MessagesSent'] = self.statistics['MessagesSent'] + 1
+            log.debug("Data to ThingsBoard: %s", converted_data)
+
     def close(self):
         self.__stopped = True
 
     def get_name(self):
         return self.name
 
     def is_connected(self):
@@ -290,7 +290,10 @@
                             converted_data = str(handle_stream.getvalue(), 'UTF-8')
                             handle_stream.close()
 
                         self.__gateway.send_rpc_reply(device=content["device"], req_id=content["data"]["id"],
                                                       success_sent=success_sent, content=converted_data)
         except Exception as e:
             log.exception(e)
+
+    def get_config(self):
+        return self.__config
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/ftp/ftp_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/ftp/ftp_converter.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/ftp/ftp_uplink_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/ftp/ftp_uplink_converter.py`

 * *Files 0% similar despite different names*

```diff
@@ -192,16 +192,17 @@
             log.exception(e)
 
         return dict_result
 
     @StatisticsService.CollectStatistics(start_stat_type='receivedBytesFromDevices',
                                          end_stat_type='convertedBytesFromDevice')
     def convert(self, config, data):
-        if config['file_ext'] == 'csv' or (
-                config['file_ext'] == 'txt' and self.__config['txt_file_data_view'] == 'TABLE'):
-            return self._convert_table_view_data(config, data)
-        elif config['file_ext'] == 'txt' and self.__config['txt_file_data_view'] == 'SLICED':
-            return self._convert_slices_view_data(data)
-        elif config['file_ext'] == 'json':
-            return self._convert_json_file(data)
-        else:
-            raise Exception('Incorrect file extension or file data view mode')
+        if data:
+            if config['file_ext'] == 'csv' or (
+                    config['file_ext'] == 'txt' and self.__config['txt_file_data_view'] == 'TABLE'):
+                return self._convert_table_view_data(config, data)
+            elif config['file_ext'] == 'txt' and self.__config['txt_file_data_view'] == 'SLICED':
+                return self._convert_slices_view_data(data)
+            elif config['file_ext'] == 'json':
+                return self._convert_json_file(data)
+            else:
+                raise Exception('Incorrect file extension or file data view mode')
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/ftp/path.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/ftp/path.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/modbus/__init__.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/modbus/__init__.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/modbus/backward_compability_adapter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/modbus/backward_compability_adapter.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/modbus/bytes_modbus_downlink_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/modbus/bytes_modbus_downlink_converter.py`

 * *Files 1% similar despite different names*

```diff
@@ -98,15 +98,15 @@
 
         if function_code in builder_converting_functions:
             builder = builder_converting_functions[function_code]()
             log.debug(builder)
             if "Exception" in str(builder):
                 log.exception(builder)
                 builder = str(builder)
-            # if function_code is 5 , is useing first coils value 
+            # if function_code is 5 , is using first coils value
             if function_code == 5:
                 if isinstance(builder, list):
                     builder = builder[0]
             else:
                 if variable_size <= 16:
                     if isinstance(builder, list) and len(builder) not in (8, 16, 32, 64):
                         builder = builder[0]
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/modbus/bytes_modbus_uplink_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/modbus/bytes_modbus_uplink_converter.py`

 * *Files 0% similar despite different names*

```diff
@@ -52,15 +52,15 @@
                         word_order = config.get("wordOrder", "LITTLE")
                     else:
                         word_order = "LITTLE"
                     endian_order = Endian.Little if byte_order.upper() == "LITTLE" else Endian.Big
                     word_endian_order = Endian.Little if word_order.upper() == "LITTLE" else Endian.Big
                     decoded_data = None
                     if not isinstance(response, ModbusIOException) and not isinstance(response, ExceptionResponse):
-                        if configuration["functionCode"] in [1, 2] :
+                        if configuration["functionCode"] in [1, 2]:
                             decoder = None
                             coils = response.bits
                             try:
                                 decoder = BinaryPayloadDecoder.fromCoils(coils, byteorder=endian_order, wordorder=word_endian_order)
                             except TypeError:
                                 decoder = BinaryPayloadDecoder.fromCoils(coils, wordorder=word_endian_order)
                             assert decoder is not None
@@ -115,18 +115,18 @@
             '64int': decoder.decode_64bit_int,
             '64uint': decoder.decode_64bit_uint,
             '64float': decoder.decode_64bit_float,
             }
 
         decoded = None
 
-        if lower_type in ['bit','bits']:
-            decoded_lastbyte= decoder_functions[type_]()
-            decoded= decoder_functions[type_]()
-            decoded+=decoded_lastbyte
+        if lower_type in ['bit', 'bits']:
+            decoded_lastbyte = decoder_functions[type_]()
+            decoded = decoder_functions[type_]()
+            decoded += decoded_lastbyte
 
         elif lower_type == "string":
             decoded = decoder_functions[type_](objects_count * 2)
 
         elif lower_type == "bytes":
             decoded = decoder_functions[type_](size=objects_count * 2)
 
@@ -157,15 +157,18 @@
             result_data = decoded.decode('UTF-8')
         elif isinstance(decoded, bytes) and lower_type == "bytes":
             result_data = decoded.hex()
         elif isinstance(decoded, list):
             if configuration.get('bit') is not None:
                 result_data = int(decoded[configuration['bit']])
             else:
-                result_data = [int(bit) for bit in decoded]
+                if objects_count == 1 and configuration.get('bitTargetType', 'bool') == 'bool':
+                    result_data = bool(decoded[-1])
+                else:
+                    result_data = [int(bit) for bit in decoded]
         elif isinstance(decoded, float):
             result_data = decoded
         elif decoded is not None:
             result_data = int(decoded, 16)
         else:
             result_data = decoded
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/modbus/constants.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/modbus/constants.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/modbus/modbus_connector.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/modbus/modbus_connector.py`

 * *Files 2% similar despite different names*

```diff
@@ -44,24 +44,25 @@
 
 from twisted.internet import reactor
 from pymodbus.constants import Defaults
 from pymodbus.bit_write_message import WriteSingleCoilResponse, WriteMultipleCoilsResponse
 from pymodbus.register_write_message import WriteMultipleRegistersResponse, WriteSingleRegisterResponse
 from pymodbus.register_read_message import ReadRegistersResponseBase
 from pymodbus.bit_read_message import ReadBitsResponseBase
-from pymodbus.client import ModbusTcpClient, ModbusUdpClient, ModbusSerialClient
+from pymodbus.client import ModbusTcpClient, ModbusTlsClient, ModbusUdpClient, ModbusSerialClient
 from pymodbus.framer.rtu_framer import ModbusRtuFramer
 from pymodbus.framer.socket_framer import ModbusSocketFramer
 from pymodbus.framer.ascii_framer import ModbusAsciiFramer
-from pymodbus.exceptions import ConnectionException
-from pymodbus.server import StartTcpServer, StartUdpServer, StartSerialServer, ServerStop
+from pymodbus.exceptions import ConnectionException, ModbusIOException
+from pymodbus.server import StartTcpServer, StartTlsServer, StartUdpServer, StartSerialServer, ServerStop
 from pymodbus.device import ModbusDeviceIdentification
 from pymodbus.version import version
 from pymodbus.datastore import ModbusSlaveContext, ModbusServerContext
 from pymodbus.datastore import ModbusSparseDataBlock
+from pymodbus.pdu import ExceptionResponse
 
 from thingsboard_gateway.connectors.connector import Connector, log
 from thingsboard_gateway.connectors.modbus.constants import *
 from thingsboard_gateway.connectors.modbus.slave import Slave
 from thingsboard_gateway.connectors.modbus.backward_compability_adapter import BackwardCompatibilityAdapter
 from thingsboard_gateway.connectors.modbus.bytes_modbus_downlink_converter import BytesModbusDownlinkConverter
 
@@ -69,14 +70,15 @@
 FRAMER_TYPE = {
     'rtu': ModbusRtuFramer,
     'socket': ModbusSocketFramer,
     'ascii': ModbusAsciiFramer
 }
 SLAVE_TYPE = {
     'tcp': StartTcpServer,
+    'tls': StartTlsServer,
     'udp': StartUdpServer,
     'serial': StartSerialServer
 }
 FUNCTION_TYPE = {
     'coils_initializer': 'co',
     'holding_registers': 'hr',
     'input_registers': 'ir',
@@ -182,15 +184,15 @@
             blocks[FUNCTION_TYPE[key]] = ModbusSparseDataBlock(values)
 
         context = ModbusServerContext(slaves=ModbusSlaveContext(**blocks), single=True)
         SLAVE_TYPE[config['type']](context=context, identity=identity,
                                    address=(config.get('host'), config.get('port')) if (
                                            config['type'] == 'tcp' or 'udp') else None,
                                    port=config.get('port') if config['type'] == 'serial' else None,
-                                   framer=FRAMER_TYPE[config['method']])
+                                   framer=FRAMER_TYPE[config['method']], **config.get('security', {}))
 
     def __modify_main_config(self):
         config = self.__config['slave']
 
         values = config.pop('values')
         device = config
 
@@ -301,28 +303,38 @@
                 if device.config.get(TYPE_PARAMETER).lower() == 'serial':
                     self.lock.acquire()
 
                 device_responses = {'timeseries': {}, 'attributes': {}}
                 current_device_config = {}
                 try:
                     for config_section in device_responses:
-                        if device.config.get(config_section) is not None:
+                        if device.config.get(config_section) is not None and len(device.config.get(config_section)):
                             current_device_config = device.config
 
                             self.__connect_to_current_master(device)
 
                             if not device.config['master'].is_socket_open() or not len(
                                     current_device_config[config_section]):
+                                error = 'Socket is closed' if not device.config[
+                                    'master'].is_socket_open() else 'Config is invalid'
+                                log.error(error)
                                 continue
 
                             # Reading data from device
                             for interested_data in range(len(current_device_config[config_section])):
                                 current_data = current_device_config[config_section][interested_data]
                                 current_data[DEVICE_NAME_PARAMETER] = device
                                 input_data = self.__function_to_device(device, current_data)
+
+                                # due to issue #1056
+                                if isinstance(input_data, ModbusIOException) or isinstance(input_data, ExceptionResponse):
+                                    device.config.pop('master', None)
+                                    self.__connect_to_current_master(device)
+                                    break
+
                                 device_responses[config_section][current_data[TAG_PARAMETER]] = {
                                     "data_sent": current_data,
                                     "input_data": input_data}
 
                             log.debug("Checking %s for device %s", config_section, device)
                             log.debug('Device response: ', device_responses)
 
@@ -395,15 +407,24 @@
             device.config['last_connection_attempt_time'] = current_time
 
     @staticmethod
     def __configure_master(config):
         current_config = config
         current_config["rtu"] = FRAMER_TYPE[current_config['method']]
 
-        if current_config.get('type') == 'tcp':
+        if current_config.get('type') == 'tcp' and current_config.get('tls'):
+            master = ModbusTlsClient(current_config["host"],
+                                     current_config["port"],
+                                     current_config["rtu"],
+                                     timeout=current_config["timeout"],
+                                     retry_on_empty=current_config["retry_on_empty"],
+                                     retry_on_invalid=current_config["retry_on_invalid"],
+                                     retries=current_config["retries"],
+                                     **current_config['tls'])
+        elif current_config.get('type') == 'tcp':
             master = ModbusTcpClient(current_config["host"],
                                      current_config["port"],
                                      current_config["rtu"],
                                      timeout=current_config["timeout"],
                                      retry_on_empty=current_config["retry_on_empty"],
                                      retry_on_invalid=current_config["retry_on_invalid"],
                                      retries=current_config["retries"])
@@ -448,15 +469,15 @@
                 slave.config['master'].close()
 
     @staticmethod
     def __function_to_device(device, config):
         function_code = config.get('functionCode')
         result = None
         if function_code == 1:
-            #why count * 8 ? in my Modbus device one coils is 1bit, tow coils is 2bit,if * 8 can not read right coils
+            # why count * 8 ? in my Modbus device one coils is 1bit, tow coils is 2bit,if * 8 can not read right coils
             # result = device.config['available_functions'][function_code](address=config[ADDRESS_PARAMETER],
             #                                                              count=config.get(OBJECTS_COUNT_PARAMETER,
             #                                                                               config.get("registersCount",
             #                                                                                          config.get(
             #                                                                                              "registerCount",
             #                                                                                              1))) * 8,
             #                                                              slave=device.config['unitId'])
@@ -575,24 +596,25 @@
         if rpc_command_config is not None:
             device = tuple(filter(lambda slave: slave.name == content[DEVICE_SECTION_PARAMETER], self.__slaves))[0]
             rpc_command_config[UNIT_ID_PARAMETER] = device.config['unitId']
             rpc_command_config[BYTE_ORDER_PARAMETER] = device.config.get("byteOrder", "LITTLE")
             rpc_command_config[WORD_ORDER_PARAMETER] = device.config.get("wordOrder", "LITTLE")
             self.__connect_to_current_master(device)
 
-            if rpc_command_config.get(FUNCTION_CODE_PARAMETER) in (6, 16):
+            if rpc_command_config.get(FUNCTION_CODE_PARAMETER) in (5, 6):
                 converted_data = device.config[DOWNLINK_PREFIX + CONVERTER_PARAMETER].convert(rpc_command_config,
                                                                                               content)
                 try:
                     rpc_command_config[PAYLOAD_PARAMETER] = converted_data[0]
                 except IndexError and TypeError:
                     rpc_command_config[PAYLOAD_PARAMETER] = converted_data
-            elif rpc_command_config.get(FUNCTION_CODE_PARAMETER) in (5, 15):
+            elif rpc_command_config.get(FUNCTION_CODE_PARAMETER) in (15, 16):
                 converted_data = device.config[DOWNLINK_PREFIX + CONVERTER_PARAMETER].convert(rpc_command_config,
                                                                                               content)
+                converted_data.reverse()
                 rpc_command_config[PAYLOAD_PARAMETER] = converted_data
 
             try:
                 response = self.__function_to_device(device, rpc_command_config)
             except Exception as e:
                 log.exception(e)
                 response = e
@@ -627,14 +649,35 @@
                 else:
                     self.__gateway.send_rpc_reply(content[DEVICE_SECTION_PARAMETER],
                                                   content[DATA_PARAMETER][RPC_ID_PARAMETER],
                                                   response)
 
             log.debug("%r", response)
 
+    def get_config(self):
+        return self.__config
+
+    def update_converter_config(self, converter_name, config):
+        log.debug('Received remote converter configuration update for %s with configuration %s', converter_name,
+                  config)
+        for slave in self.__slaves:
+            try:
+                if slave.config[UPLINK_PREFIX + CONVERTER_PARAMETER].__class__.__name__ == converter_name:
+                    slave.config.update(config)
+                    log.info('Updated converter configuration for: %s with configuration %s',
+                             converter_name, config)
+
+                    for slave_config in self.__config['master']['slaves']:
+                        if slave_config['deviceName'] == slave.name:
+                            slave_config.update(config)
+
+                    self.__gateway.update_connector_config_file(self.name, self.__config)
+            except KeyError:
+                continue
+
     class ConverterWorker(Thread):
         def __init__(self, name, incoming_queue, send_result):
             super().__init__()
             self.stopped = False
             self.setName(name)
             self.setDaemon(True)
             self.__msg_queue = incoming_queue
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/modbus/modbus_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/modbus/modbus_converter.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/modbus/slave.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/modbus/slave.py`

 * *Files 1% similar despite different names*

```diff
@@ -37,14 +37,15 @@
             'unitId': kwargs['unitId'],
             'deviceType': kwargs.get('deviceType', 'default'),
             'type': kwargs['type'],
             'host': kwargs.get('host'),
             'port': kwargs['port'],
             'byteOrder': kwargs['byteOrder'],
             'wordOrder': kwargs['wordOrder'],
+            'tls': kwargs.get('tls'),
             'timeout': kwargs.get('timeout', 35),
             'stopbits': kwargs.get('stopbits', Defaults.Stopbits),
             'bytesize': kwargs.get('bytesize', Defaults.Bytesize),
             'parity': kwargs.get('parity', Defaults.Parity),
             'strict': kwargs.get('strict', True),
             'retries': kwargs.get('retries', 3),
             'connection_attempt': 0,
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/mqtt/__init__.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/mqtt/__init__.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/mqtt/bytes_mqtt_uplink_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/mqtt/bytes_mqtt_uplink_converter.py`

 * *Files 7% similar despite different names*

```diff
@@ -7,14 +7,22 @@
 from thingsboard_gateway.gateway.statistics_service import StatisticsService
 
 
 class BytesMqttUplinkConverter(MqttUplinkConverter):
     def __init__(self, config):
         self.__config = config.get('converter')
 
+    @property
+    def config(self):
+        return self.__config
+
+    @config.setter
+    def config(self, value):
+        self.__config = value
+
     @StatisticsService.CollectStatistics(start_stat_type='receivedBytesFromDevices',
                                          end_stat_type='convertedBytesFromDevice')
     def convert(self, topic, data):
         datatypes = {"attributes": "attributes",
                      "timeseries": "telemetry"}
         dict_result = {
             "deviceName": self.parse_data(self.__config['deviceNameExpression'], data),
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/mqtt/json_mqtt_uplink_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/mqtt/json_mqtt_uplink_converter.py`

 * *Files 14% similar despite different names*

```diff
@@ -9,26 +9,35 @@
 #     Unless required by applicable law or agreed to in writing, software
 #     distributed under the License is distributed on an "AS IS" BASIS,
 #     WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 #     See the License for the specific language governing permissions and
 #     limitations under the License.
 
 from re import search
-from time import time
 
 from simplejson import dumps
 
+from thingsboard_gateway.gateway.constants import SEND_ON_CHANGE_PARAMETER
 from thingsboard_gateway.connectors.mqtt.mqtt_uplink_converter import MqttUplinkConverter, log
 from thingsboard_gateway.tb_utility.tb_utility import TBUtility
 from thingsboard_gateway.gateway.statistics_service import StatisticsService
 
 
 class JsonMqttUplinkConverter(MqttUplinkConverter):
     def __init__(self, config):
         self.__config = config.get('converter')
+        self.__send_data_on_change = self.__config.get(SEND_ON_CHANGE_PARAMETER)
+
+    @property
+    def config(self):
+        return self.__config
+
+    @config.setter
+    def config(self, value):
+        self.__config = value
 
     @StatisticsService.CollectStatistics(start_stat_type='receivedBytesFromDevices',
                                          end_stat_type='convertedBytesFromDevice')
     def convert(self, topic, data):
         if isinstance(data, list):
             converted_data = []
             for item in data:
@@ -37,29 +46,32 @@
         else:
             return self._convert_single_item(topic, data)
 
     def _convert_single_item(self, topic, data):
         datatypes = {"attributes": "attributes",
                      "timeseries": "telemetry"}
         dict_result = {
-            "deviceName": JsonMqttUplinkConverter.parse_device_name(topic, data, self.__config),
-            "deviceType": JsonMqttUplinkConverter.parse_device_type(topic, data, self.__config),
+            "deviceName": self.parse_device_name(topic, data, self.__config),
+            "deviceType": self.parse_device_type(topic, data, self.__config),
             "attributes": [],
             "telemetry": []
         }
 
+        if isinstance(self.__send_data_on_change, bool):
+            dict_result[SEND_ON_CHANGE_PARAMETER] = self.__send_data_on_change
+
         try:
             for datatype in datatypes:
                 timestamp = data.get("ts", data.get("timestamp")) if datatype == 'timeseries' else None
                 dict_result[datatypes[datatype]] = []
                 for datatype_config in self.__config.get(datatype, []):
                     if isinstance(datatype_config, str) and datatype_config == "*":
                         for item in data:
                             dict_result[datatypes[datatype]].append(
-                                JsonMqttUplinkConverter.create_timeseries_record(item, data[item], timestamp))
+                                self.create_timeseries_record(item, data[item], timestamp))
                     else:
                         values = TBUtility.get_values(datatype_config["value"], data, datatype_config["type"],
                                                       expression_instead_none=False)
                         values_tags = TBUtility.get_values(datatype_config["value"], data, datatype_config["type"],
                                                            get_tag=True)
 
                         keys = TBUtility.get_values(datatype_config["key"], data, datatype_config["type"],
@@ -79,15 +91,15 @@
                                              datatype_config["value"]
 
                             full_value = full_value.replace('${' + str(value_tag) + '}',
                                                             str(value)) if is_valid_value else value
 
                         if full_key != 'None' and full_value != 'None':
                             dict_result[datatypes[datatype]].append(
-                                JsonMqttUplinkConverter.create_timeseries_record(full_key, full_value, timestamp))
+                                self.create_timeseries_record(full_key, full_value, timestamp))
         except Exception as e:
             log.error('Error in converter, for config: \n%s\n and message: \n%s\n', dumps(self.__config), str(data))
             log.exception(e)
         return dict_result
 
     @staticmethod
     def create_timeseries_record(key, value, timestamp):
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/mqtt/mqtt_connector.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/mqtt/mqtt_connector.py`

 * *Files 5% similar despite different names*

```diff
@@ -18,25 +18,28 @@
 from queue import Queue
 from re import fullmatch, match, search
 from threading import Thread
 from time import sleep, time
 
 import simplejson
 
+from thingsboard_gateway.gateway.constants import SEND_ON_CHANGE_PARAMETER, DEFAULT_SEND_ON_CHANGE_VALUE, \
+    ATTRIBUTES_PARAMETER, TELEMETRY_PARAMETER, SEND_ON_CHANGE_TTL_PARAMETER, DEFAULT_SEND_ON_CHANGE_INFINITE_TTL_VALUE
+from thingsboard_gateway.gateway.constant_enums import Status
 from thingsboard_gateway.connectors.connector import Connector, log
 from thingsboard_gateway.connectors.mqtt.mqtt_decorators import CustomCollectStatistics
 from thingsboard_gateway.tb_utility.tb_loader import TBModuleLoader
 from thingsboard_gateway.tb_utility.tb_utility import TBUtility
 from thingsboard_gateway.gateway.statistics_service import StatisticsService
 
 try:
     from paho.mqtt.client import Client
 except ImportError:
     print("paho-mqtt library not found")
-    TBUtility.install_package("paho-mqtt", version=">=1.6")
+    TBUtility.install_package("tb-paho-mqtt-client")
     from paho.mqtt.client import Client
 
 from paho.mqtt.client import MQTTv31, MQTTv311, MQTTv5
 
 
 MQTT_VERSIONS = {
     3: MQTTv31,
@@ -91,35 +94,45 @@
     160: "Maximum connect time",
     161: "Subscription Identifiers not supported",
     162: "Wildcard Subscription not supported"
 }
 
 
 class MqttConnector(Connector, Thread):
+    CONFIGURATION_KEY_SHARED_GLOBAL = "sharedGlobal"
+    CONFIGURATION_KEY_SHARED_ID = "sharedId"
+
     def __init__(self, gateway, config, connector_type):
         super().__init__()
 
         self.__gateway = gateway  # Reference to TB Gateway
         self._connector_type = connector_type  # Should be "mqtt"
         self.config = config  # mqtt.json contents
 
         self.__log = log
         self.statistics = {'MessagesReceived': 0, 'MessagesSent': 0}
         self.__subscribes_sent = {}
 
         # Extract main sections from configuration ---------------------------------------------------------------------
         self.__broker = config.get('broker')
+        self.__send_data_only_on_change = self.__broker.get(SEND_ON_CHANGE_PARAMETER, DEFAULT_SEND_ON_CHANGE_VALUE)
+        self.__send_data_only_on_change_ttl = self.__broker.get(SEND_ON_CHANGE_TTL_PARAMETER, DEFAULT_SEND_ON_CHANGE_INFINITE_TTL_VALUE)
+
+        # for sendDataOnlyOnChange param
+        self.__topic_content = {}
 
         self.__mapping = []
         self.__server_side_rpc = []
         self.__connect_requests = []
         self.__disconnect_requests = []
         self.__attribute_requests = []
         self.__attribute_updates = []
 
+        self.__shared_custom_converters = {}
+
         mandatory_keys = {
             "mapping": ['topicFilter', 'converter'],
             "serverSideRpc": ['deviceNameFilter', 'methodFilter', 'requestTopicExpression', 'valueExpression'],
             "connectRequests": ['topicFilter'],
             "disconnectRequests": ['topicFilter'],
             "attributeRequests": ['topicFilter', 'topicExpression', 'valueExpression'],
             "attributeUpdates": ['deviceNameFilter', 'attributeFilter', 'topicExpression', 'valueExpression']
@@ -156,17 +169,17 @@
         try:
             self._client = Client(client_id, protocol=MQTT_VERSIONS[self._mqtt_version])
         except KeyError:
             self.__log.error('Unknown MQTT version. Starting up on version 5...')
             self._client = Client(client_id, protocol=MQTTv5)
             self._mqtt_version = 5
 
-        self.setName(config.get("name", self.__broker.get(
+        self.name = config.get("name", self.__broker.get(
             "name",
-            'Mqtt Broker ' + ''.join(random.choice(string.ascii_lowercase) for _ in range(5)))))
+            'Mqtt Broker ' + ''.join(random.choice(string.ascii_lowercase) for _ in range(5))))
 
         if "username" in self.__broker["security"]:
             self._client.username_pw_set(self.__broker["security"]["username"],
                                          self.__broker["security"]["password"])
 
         if "caCert" in self.__broker["security"] \
                 or self.__broker["security"].get("type", "none").lower() == "tls":
@@ -211,14 +224,23 @@
         self.__max_msg_number_for_worker = config['broker'].get('maxMessageNumberPerWorker', 10)
         self.__max_number_of_workers = config['broker'].get('maxNumberOfWorkers', 100)
 
         self._on_message_queue = Queue()
         self._on_message_thread = Thread(name='On Message', target=self._process_on_message, daemon=True)
         self._on_message_thread.start()
 
+    def is_filtering_enable(self, device_name):
+        return self.__send_data_only_on_change
+
+    def get_config(self):
+        return self.config
+    
+    def get_ttl_for_duplicates(self, device_name):
+        return self.__send_data_only_on_change_ttl
+
     def load_handlers(self, handler_flavor, mandatory_keys, accepted_handlers_list):
         if handler_flavor not in self.config:
             self.__log.error("'%s' section missing from configuration", handler_flavor)
         else:
             for handler in self.config.get(handler_flavor):
                 discard = False
 
@@ -323,33 +345,62 @@
             # Setup data upload requests handling ----------------------------------------------------------------------
             for mapping in self.__mapping:
                 try:
                     # Load converter for this mapping entry ------------------------------------------------------------
                     # mappings are guaranteed to have topicFilter and converter fields. See __init__
                     default_converters = {
                         "json": "JsonMqttUplinkConverter",
-                        "bytes": "BytesMqttUplinkConverter",
-                        "custom": ""
+                        "bytes": "BytesMqttUplinkConverter"
                     }
 
                     # Get converter class from "extension" parameter or default converter
                     converter_class_name = mapping["converter"].get("extension",
-                                                                    default_converters[mapping['converter']['type']])
-                    # Find and load required class
-                    module = TBModuleLoader.import_module(self._connector_type, converter_class_name)
-                    if module:
-                        self.__log.debug('Converter %s for topic %s - found!', converter_class_name,
-                                         mapping["topicFilter"])
-                        converter = module(mapping)
-                    else:
-                        self.__log.error("Cannot find converter for %s topic", mapping["topicFilter"])
+                                                                    default_converters.get(
+                                                                        mapping['converter'].get('type')))
+                    if not converter_class_name:
+                        self.__log.error('Converter type or extension class should be configured!')
                         continue
 
+                    converter = None
+                    sharing_id = None
+                    if mapping["converter"].get("type") == "custom" or mapping["converter"].get("extension"):
+                        if mapping["converter"].get(self.CONFIGURATION_KEY_SHARED_GLOBAL, False):
+                            sharing_id = converter_class_name
+                        elif mapping["converter"].get(self.CONFIGURATION_KEY_SHARED_ID):
+                            sharing_id = mapping["converter"][self.CONFIGURATION_KEY_SHARED_ID]
+
+                        if sharing_id:
+                            converter = self.__shared_custom_converters.get(sharing_id)
+                            self.__log.debug('Converter %s for topic %s will use in sharing mode!', sharing_id,
+                                             mapping["topicFilter"])
+
+                    if not converter:
+                        # Find and load required class
+                        module = TBModuleLoader.import_module(self._connector_type, converter_class_name)
+                        if module:
+                            self.__log.debug('Converter %s for topic %s - found!', converter_class_name,
+                                             mapping["topicFilter"])
+                            converter = module(mapping)
+                            if sharing_id:
+                                self.__shared_custom_converters[sharing_id] = converter
+                        else:
+                            self.__log.error("Cannot find converter for %s topic", mapping["topicFilter"])
+                            continue
+                    else:
+                        self.__log.debug('Converter %s for topic %s - found in cache!', converter_class_name,
+                                         mapping["topicFilter"])
+
                     # Setup regexp topic acceptance list ---------------------------------------------------------------
-                    regex_topic = TBUtility.topic_to_regex(mapping["topicFilter"])
+                    # Check if topic is shared subscription type
+                    # (an exception is aws topics that do not support shared subscription)
+                    regex_topic = mapping["topicFilter"]
+                    if not regex_topic.startswith('$aws') and regex_topic.startswith('$'):
+                        regex_topic = '/'.join(regex_topic.split('/')[2:])
+                    else:
+                        regex_topic = TBUtility.topic_to_regex(regex_topic)
 
                     # There may be more than one converter per topic, so I'm using vectors
                     if not self.__mapping_sub_topics.get(regex_topic):
                         self.__mapping_sub_topics[regex_topic] = []
 
                     self.__mapping_sub_topics[regex_topic].append(converter)
 
@@ -381,20 +432,22 @@
             for request in [entry for entry in self.__attribute_requests if entry is not None]:
                 # requests are guaranteed to have topicFilter field. See __init__
                 self.__subscribe(request["topicFilter"], request.get("subscriptionQos", 1))
                 topic_filter = TBUtility.topic_to_regex(request.get("topicFilter"))
                 self.__attribute_requests_sub_topics[topic_filter] = request
         else:
             result_codes = RESULT_CODES_V5 if self._mqtt_version == 5 else RESULT_CODES_V3
-            if result_code in result_codes:
-                self.__log.error("%s connection FAIL with error %s %s!", self.get_name(), result_code,
-                                 result_codes[result_code])
+            rc = result_code.value if self._mqtt_version == 5 else result_code
+            if rc in result_codes:
+                self.__log.error("%s connection FAIL with error %s %s!", self.get_name(), rc, result_codes[rc])
             else:
                 self.__log.error("%s connection FAIL with unknown error!", self.get_name())
 
+        self._init_send_current_converter_config()
+
     def _on_disconnect(self, *args):
         self._connected = False
         self.__log.debug('"%s" was disconnected. %s', self.get_name(), str(args))
 
     def _on_log(self, *args):
         self.__log.debug(args)
 
@@ -419,17 +472,17 @@
     def put_data_to_convert(self, converter, message, content) -> bool:
         if not self.__msg_queue.full():
             self.__msg_queue.put((converter.convert, message.topic, content), True, 100)
             return True
         return False
 
     def _save_converted_msg(self, topic, data):
-        self.__gateway.send_to_storage(self.name, data)
-        self.statistics['MessagesSent'] += 1
-        self.__log.debug("Successfully converted message from topic %s", topic)
+        if self.__gateway.send_to_storage(self.name, data) == Status.SUCCESS:
+            self.statistics['MessagesSent'] += 1
+            self.__log.debug("Successfully converted message from topic %s", topic)
 
     def __threads_manager(self):
         if len(self.__workers_thread_pool) == 0:
             worker = MqttConnector.ConverterWorker("Main", self.__msg_queue, self._save_converted_msg)
             self.__workers_thread_pool.append(worker)
             worker.start()
 
@@ -469,14 +522,22 @@
                     # I will use a flag to understand whether at least one converter succeeded
                     request_handled = False
 
                     for topic in topic_handlers:
                         available_converters = self.__mapping_sub_topics[topic]
                         for converter in available_converters:
                             try:
+                                # check if data is equal
+                                if converter.config.get('sendDataOnlyOnChange', False) and self.__topic_content.get(
+                                        message.topic) == content:
+                                    request_handled = True
+                                    continue
+
+                                self.__topic_content[message.topic] = content
+
                                 request_handled = self.put_data_to_convert(converter, message, content)
                             except Exception as e:
                                 log.exception(e)
 
                     if not request_handled:
                         self.__log.error('Cannot find converter for the topic:"%s"! Client: %s, User data: %s',
                                          message.topic,
@@ -805,14 +866,54 @@
     def _publish(self, request_topic, data_to_send, retain):
         self._client.publish(request_topic, data_to_send, retain).wait_for_publish()
 
     def rpc_cancel_processing(self, topic):
         log.info("RPC canceled or terminated. Unsubscribing from %s", topic)
         self._client.unsubscribe(topic)
 
+    def get_converters(self):
+        return [item[0] for _, item in self.__mapping_sub_topics.items()]
+
+    def update_converter_config(self, converter_name, config):
+        self.__log.debug('Received remote converter configuration update for %s with configuration %s', converter_name,
+                         config)
+        converters = self.get_converters()
+        for converter_class_obj in converters:
+            converter_class_name = converter_class_obj.__class__.__name__
+            converter_obj = converter_class_obj
+            if converter_class_name == converter_name:
+                converter_obj.config = config
+                self._send_current_converter_config(self.name + ':' + converter_name, config)
+                log.info('Updated converter configuration for: %s with configuration %s',
+                         converter_name, converter_obj.config)
+
+                for device_config in self.config['mapping']:
+                    try:
+                        if device_config['converter']['deviceNameJsonExpression'] == config['deviceNameJsonExpression']:
+                            device_config['converter'].update(config)
+
+                        if device_config['converter']['deviceNameTopicExpression'] == config[
+                                'deviceNameTopicExpression']:
+                            device_config['converter'].update(config)
+                    except KeyError:
+                        continue
+
+                self.__gateway.update_connector_config_file(self.name, self.config)
+
+    def _init_send_current_converter_config(self):
+        for converter_obj in self.get_converters():
+            try:
+                self.__gateway.tb_client.client.send_attributes(
+                    {self.name + ':' + converter_obj.__class__.__name__: converter_obj.config})
+            except AttributeError:
+                continue
+
+    def _send_current_converter_config(self, name, config):
+        self.__gateway.tb_client.client.send_attributes({name: config})
+
     class ConverterWorker(Thread):
         def __init__(self, name, incoming_queue, send_result):
             super().__init__()
             self.stopped = False
             self.setName(name)
             self.setDaemon(True)
             self.__msg_queue = incoming_queue
@@ -822,12 +923,13 @@
         def run(self):
             while not self.stopped:
                 if not self.__msg_queue.empty():
                     self.in_progress = True
                     convert_function, config, incoming_data = self.__msg_queue.get(True, 100)
                     converted_data = convert_function(config, incoming_data)
                     log.debug(converted_data)
-                    if converted_data and (converted_data.get('attributes') or converted_data.get('telemetry')):
+                    if converted_data and (converted_data.get(ATTRIBUTES_PARAMETER) or
+                                           converted_data.get(TELEMETRY_PARAMETER)):
                         self.__send_result(config, converted_data)
                     self.in_progress = False
                 else:
                     sleep(.2)
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/mqtt/mqtt_uplink_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/mqtt/mqtt_uplink_converter.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/ocpp/__init__.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/ocpp/__init__.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/ocpp/charge_point.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/ocpp/charge_point.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/ocpp/ocpp_connector.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/ocpp/ocpp_connector.py`

 * *Files 0% similar despite different names*

```diff
@@ -23,15 +23,14 @@
 from time import sleep
 
 from simplejson import dumps
 
 from thingsboard_gateway.connectors.connector import Connector, log
 from thingsboard_gateway.gateway.statistics_service import StatisticsService
 from thingsboard_gateway.tb_utility.tb_utility import TBUtility
-from thingsboard_gateway.connectors.ocpp.charge_point import ChargePoint
 
 try:
     import ocpp
 except ImportError:
     print('OCPP library not found - installing...')
     TBUtility.install_package("ocpp")
     import ocpp
@@ -40,14 +39,15 @@
     import websockets
 except ImportError:
     print('websockets library not found - installing...')
     TBUtility.install_package("websockets")
     import websockets
 
 from ocpp.v16 import call
+from thingsboard_gateway.connectors.ocpp.charge_point import ChargePoint
 
 
 class NotAuthorized(Exception):
     """Charge Point not authorized"""
 
 
 class OcppConnector(Connector, Thread):
@@ -308,7 +308,10 @@
 
                     if rpc.get('withResponse', True):
                         self._gateway.send_rpc_reply(content["device"], content["data"]["id"], str(task.result()))
 
                         return
         except Exception as e:
             self._log.exception(e)
+
+    def get_config(self):
+        return {'CS': self._central_system_config, 'CP': self._charge_points_config}
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/ocpp/ocpp_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/ocpp/ocpp_converter.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/ocpp/ocpp_uplink_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/ocpp/ocpp_uplink_converter.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/odbc/__init__.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/odbc/__init__.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/odbc/odbc_connector.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/odbc/odbc_connector.py`

 * *Files 2% similar despite different names*

```diff
@@ -249,41 +249,55 @@
 
             device_name = eval(self.__config["mapping"]["device"]["name"], globals(), data)
 
             device_type = eval(self.__config["mapping"]["device"]["type"], globals(), data)
             if not device_type:
                 device_type = self.__config["mapping"]["device"].get("type", "default")
 
-            if device_name not in self.__devices:
-                self.__devices[device_name] = {"attributes": {}, "telemetry": {}}
-                self.__gateway.add_device(device_name, {"connector": self},
-                                          device_type=device_type)
+            if to_send["telemetry"] or to_send["attributes"]:
+                if device_name not in self.__devices:
+                    self.__devices[device_name] = {"attributes": {}, "telemetry": {}}
+                    self.__gateway.add_device(device_name, {"connector": self},
+                                              device_type=device_type)
 
-            self.__iterator["value"] = getattr(row, self.__iterator["name"])
-            self.__check_and_send(device_name, device_type, to_send)
+                self.__iterator["value"] = getattr(row, self.__iterator["name"])
+                self.__check_and_send(device_name, device_type, to_send)
         except Exception as e:
             log.warning("[%s] Failed to process database row: %s", self.get_name(), str(e))
 
     @staticmethod
     def row_to_dict(row):
         data = {}
         for column_description in row.cursor_description:
             data[column_description[0]] = getattr(row, column_description[0])
         return data
 
     def __check_and_send(self, device_name, device_type, new_data):
         self.statistics['MessagesReceived'] += 1
         to_send = {"attributes": [], "telemetry": []}
         send_on_change = self.__config["mapping"].get("sendDataOnlyOnChange", self.DEFAULT_SEND_IF_CHANGED)
+        send_on_change_attributes = self.__config["mapping"].get("sendDataOnlyOnChangeAttributes")
+        send_on_change_telemetry = self.__config["mapping"].get("sendDataOnlyOnChangeTelemetry")
 
-        for tb_key in to_send.keys():
-            for key, new_value in new_data[tb_key].items():
-                if not send_on_change or self.__devices[device_name][tb_key].get(key, None) != new_value:
-                    self.__devices[device_name][tb_key][key] = new_value
-                    to_send[tb_key].append({key: new_value})
+        if send_on_change_attributes is None and send_on_change_telemetry is None:
+            for tb_key in to_send.keys():
+                for key, new_value in new_data[tb_key].items():
+                    if not send_on_change or self.__devices[device_name][tb_key].get(key, None) != new_value:
+                        self.__devices[device_name][tb_key][key] = new_value
+                        to_send[tb_key].append({key: new_value})
+        else:
+            for key, new_value in new_data["attributes"].items():
+                if not send_on_change_attributes or self.__devices[device_name]["attributes"].get(key, None) != new_value:
+                    self.__devices[device_name]["attributes"][key] = new_value
+                    to_send["attributes"].append({key: new_value})
+
+            for key, new_value in new_data["telemetry"].items():
+                if not send_on_change_telemetry or self.__devices[device_name]["telemetry"].get(key, None) != new_value:
+                    self.__devices[device_name]["telemetry"][key] = new_value
+                    to_send["telemetry"].append({key: new_value})
 
         if to_send["attributes"] or to_send["telemetry"]:
             to_send["deviceName"] = device_name
             to_send["deviceType"] = device_type
 
             to_send['telemetry'] = {'ts': new_data.get('ts', int(time()) * 1000), 'values': new_data['telemetry']}
 
@@ -452,7 +466,10 @@
             elif isinstance(rpc_config, dict):
                 reformatted_config[rpc_config["name"]] = rpc_config
             else:
                 log.warning("[%s] Wrong RPC config format. Expected str or dict, get %s", self.get_name(),
                             type(rpc_config))
 
         self.__config["serverSideRpc"]["methods"] = reformatted_config
+
+    def get_config(self):
+        return self.__config
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/odbc/odbc_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/request/request_converter.py`

 * *Files 10% similar despite different names*

```diff
@@ -8,14 +8,14 @@
 #
 #     Unless required by applicable law or agreed to in writing, software
 #     distributed under the License is distributed on an "AS IS" BASIS,
 #     WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 #     See the License for the specific language governing permissions and
 #     limitations under the License.
 
-from thingsboard_gateway.connectors.converter import ABC, abstractmethod
+from thingsboard_gateway.connectors.converter import Converter, abstractmethod, log
 
 
-class OdbcConverter(ABC):
+class RequestConverter(Converter):
     @abstractmethod
     def convert(self, config, data):
         pass
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/odbc/odbc_uplink_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/odbc/odbc_uplink_converter.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/opcua/__init__.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/opcua/__init__.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/opcua/opcua_connector.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/opcua/opcua_connector.py`

 * *Files 1% similar despite different names*

```diff
@@ -654,14 +654,37 @@
         result = information_path[:]
         return result
 
     @property
     def subscribed(self):
         return self._subscribed
 
+    def get_config(self):
+        return self.__server_conf
+
+    def get_converters(self):
+        return [item['converter'] for _, item in self.subscribed.items()]
+
+    def update_converter_config(self, converter_name, config):
+        log.debug('Received remote converter configuration update for %s with configuration %s', converter_name,
+                         config)
+        converters = self.get_converters()
+        for converter_class_obj in converters:
+            converter_class_name = converter_class_obj.__class__.__name__
+            converter_obj = converter_class_obj
+            if converter_class_name == converter_name:
+                converter_obj.config = config
+                log.info('Updated converter configuration for: %s with configuration %s',
+                         converter_name, converter_obj.config)
+
+                for node_config in self.__server_conf['mapping']:
+                    if node_config['deviceNodePattern'] == config['deviceNodePattern']:
+                        node_config.update(config)
+
+                self.__gateway.update_connector_config_file(self.name, {'server': self.__server_conf})
 
 class SubHandler(object):
     def __init__(self, connector: OpcUaConnector):
         self.connector = connector
 
     def datachange_notification(self, node, val, data):
         try:
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/opcua/opcua_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/opcua/opcua_converter.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/opcua/opcua_uplink_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/opcua/opcua_uplink_converter.py`

 * *Files 7% similar despite different names*

```diff
@@ -21,14 +21,22 @@
 from thingsboard_gateway.gateway.statistics_service import StatisticsService
 
 
 class OpcUaUplinkConverter(OpcUaConverter):
     def __init__(self, config):
         self.__config = config
 
+    @property
+    def config(self):
+        return self.__config
+
+    @config.setter
+    def config(self, value):
+        self.__config = value
+
     @StatisticsService.CollectStatistics(start_stat_type='receivedBytesFromDevices',
                                          end_stat_type='convertedBytesFromDevice')
     def convert(self, config, val, data=None, key=None):
         device_name = self.__config["deviceName"]
         result = {"deviceName": device_name,
                   "deviceType": self.__config.get("deviceType", "OPC-UA Device"),
                   "attributes": [],
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/opcua_asyncio/device.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/opcua_asyncio/device.py`

 * *Files 1% similar despite different names*

```diff
@@ -24,20 +24,20 @@
         self.converter = converter
         self.converter_for_sub = converter_for_sub
         self.values = {
             'timeseries': [],
             'attributes': []
         }
 
-        self.__load_values()
+        self.load_values()
 
     def __repr__(self):
         return f'{self.path}'
 
-    def __load_values(self):
+    def load_values(self):
         for section in ('attributes', 'timeseries'):
             for node_config in self.config.get(section, []):
                 try:
                     if re.search(r"(ns=\d+;[isgb]=[^}]+)", node_config['path']):
                         child = re.search(r"(ns=\d+;[isgb]=[^}]+)", node_config['path'])
                         self.values[section].append({'path': child.groups()[0], 'key': node_config['key']})
                     elif re.search(r"\${([A-Za-z.:\\\d]+)}", node_config['path']):
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/opcua_asyncio/opcua_connector.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/opcua_asyncio/opcua_connector.py`

 * *Files 5% similar despite different names*

```diff
@@ -43,17 +43,14 @@
     "Basic128Rsa15": SecurityPolicyBasic128Rsa15,
     "Basic256": SecurityPolicyBasic256,
     "Basic256Sha256": SecurityPolicyBasic256Sha256,
 }
 
 
 class OpcUaConnectorAsyncIO(Connector, Thread):
-    DATA_TO_SEND = Queue(-1)
-    SUB_DATA_TO_CONVERT = Queue(-1)
-
     def __init__(self, gateway, config, connector_type):
         self.statistics = {'MessagesReceived': 0,
                            'MessagesSent': 0}
         self.__log = log
         super().__init__()
         self._connector_type = connector_type
         self.__gateway = gateway
@@ -63,14 +60,17 @@
             self.__server_conf.get("name", 'OPC-UA Connector ' + ''.join(choice(ascii_lowercase) for _ in range(5))))
 
         if "opc.tcp" not in self.__server_conf.get("url"):
             self.__opcua_url = "opc.tcp://" + self.__server_conf.get("url")
         else:
             self.__opcua_url = self.__server_conf.get("url")
 
+        self.__data_to_send = Queue(-1)
+        self.__sub_data_to_convert = Queue(-1)
+
         self.__loop = asyncio.new_event_loop()
 
         self.__client = None
         self.__subscription = None
 
         self.__connected = False
         self.__stopped = False
@@ -121,14 +121,17 @@
 
     def get_name(self):
         return self.name
 
     def is_connected(self):
         return self.__connected
 
+    def get_config(self):
+        return self.__server_conf
+
     def run(self):
         data_send_thread = Thread(name='Send Data Thread', target=self.__send_data, daemon=True)
         data_send_thread.start()
 
         if not self.__server_conf.get('disableSubscriptions', False):
             sub_data_convert_thread = Thread(name='Sub Data Convert Thread', target=self.__convert_sub_data,
                                              daemon=True)
@@ -297,27 +300,27 @@
             if device_name not in scanned_devices:
                 await self.__reset_nodes(device_name)
 
         self.__log.debug('Device nodes: %s', self.__device_nodes)
 
     def __convert_sub_data(self):
         while not self.__stopped:
-            if not OpcUaConnectorAsyncIO.SUB_DATA_TO_CONVERT.empty():
-                sub_node, data = OpcUaConnectorAsyncIO.SUB_DATA_TO_CONVERT.get()
+            if not self.__sub_data_to_convert.empty():
+                sub_node, data = self.__sub_data_to_convert.get()
 
                 for device in self.__device_nodes:
                     for section in ('attributes', 'timeseries'):
                         for node in device.values.get(section, []):
                             if node.get('id') == sub_node.__str__():
                                 device.converter_for_sub.convert(config={'section': section, 'key': node['key']},
                                                                  val=data.monitored_item.Value)
                                 converter_data = device.converter_for_sub.get_data()
 
                                 if converter_data:
-                                    OpcUaConnectorAsyncIO.DATA_TO_SEND.put(*converter_data)
+                                    self.__data_to_send.put(*converter_data)
                                     device.converter_for_sub.clear_data()
             else:
                 sleep(.2)
 
     async def __poll_nodes(self):
         for device in self.__device_nodes:
             for section in ('attributes', 'timeseries'):
@@ -341,71 +344,91 @@
 
                             var = await self.__client.nodes.root.get_child(path)
 
                         if not node.get('valid', False) or self.__server_conf.get('disableSubscriptions', False):
                             value = await var.read_data_value()
                             device.converter.convert(config={'section': section, 'key': node['key']}, val=value)
 
-                            if not self.__server_conf.get('disableSubscriptions', False) and not node.get('sub_on', False):
+                            if not self.__server_conf.get('disableSubscriptions', False) and not node.get('sub_on',
+                                                                                                          False):
                                 if self.__subscription is None:
-                                    self.__subscription = await self.__client.create_subscription(1, SubHandler())
+                                    self.__subscription = await self.__client.create_subscription(1, SubHandler(
+                                        self.__sub_data_to_convert))
                                 handle = await self.__subscription.subscribe_data_change(var)
                                 node['subscription'] = handle
                                 node['sub_on'] = True
                                 node['id'] = var.nodeid.to_string()
                                 self.__log.info("Subscribed on data change; device: %s, key: %s, path: %s", device.name, node['key'], node['id'])
 
                             node['valid'] = True
                     except ConnectionError:
                         raise
-                    except (BadNodeIdUnknown, BadConnectionClosed, BadInvalidState, BadAttributeIdInvalid, BadCommunicationError, BadOutOfService):
+                    except (BadNodeIdUnknown, BadConnectionClosed, BadInvalidState, BadAttributeIdInvalid,
+                            BadCommunicationError, BadOutOfService):
                         if node.get('valid', True):
                             self.__log.warning('Node not found (2); device: %s, key: %s, path: %s', device.name, node['key'], node['path'])
                             await self.__reset_node(node)
                     except UaStatusCodeError as uae:
                         if node.get('valid', True):
                             self.__log.exception('Node status code error: %s', uae)
                             await self.__reset_node(node)
                     except Exception as e:
                         if node.get('valid', True):
                             self.__log.exception(e)
                             await self.__reset_node(node)
 
             converter_data = device.converter.get_data()
             if converter_data:
-                OpcUaConnectorAsyncIO.DATA_TO_SEND.put(*converter_data)
+                self.__data_to_send.put(*converter_data)
 
                 device.converter.clear_data()
 
     def __send_data(self):
         while not self.__stopped:
-            if not OpcUaConnectorAsyncIO.DATA_TO_SEND.empty():
-                data = OpcUaConnectorAsyncIO.DATA_TO_SEND.get()
+            if not self.__data_to_send.empty():
+                data = self.__data_to_send.get()
                 self.statistics['MessagesReceived'] = self.statistics['MessagesReceived'] + 1
                 self.__log.debug(data)
                 self.__gateway.send_to_storage(self.get_name(), data)
                 self.statistics['MessagesSent'] = self.statistics['MessagesSent'] + 1
                 self.__log.debug('Data to ThingsBoard %s', data)
             else:
                 sleep(.2)
 
+    async def get_shared_attr_node_id(self, path, result={}):
+        try:
+            q_path = await self.find_node_name_space_index(path)
+            var = await self.__client.nodes.root.get_child(q_path[0])
+            result['result'] = var
+        except Exception as e:
+            result['error'] = e.__str__()
+
     def on_attributes_update(self, content):
         self.__log.debug(content)
         try:
             device = tuple(filter(lambda i: i.name == content['device'], self.__device_nodes))[0]
 
             for (key, value) in content['data'].items():
                 for attr_update in device.config['attributes_updates']:
                     if attr_update['attributeOnThingsBoard'] == key:
-                        for section in ('attributes', 'timeseries'):
-                            for node in device.values[section]:
-                                if re.fullmatch(attr_update['attributeOnDevice'],
-                                                '.'.join(device.path) + f'.{node["path"]}'):
-                                    self.__loop.create_task(self.__write_value(node['id'], value))
-
+                        result = {}
+                        task = self.__loop.create_task(
+                            self.get_shared_attr_node_id(
+                                device.path + attr_update['attributeOnDevice'].replace('\\', '').split('.'), result))
+
+                        while not task.done():
+                            sleep(.1)
+
+                        if result.get('error'):
+                            self.__log.error('Node not found! (%s)', result['error'])
+                            return
+
+                        node_id = result['result']
+                        self.__loop.create_task(self.__write_value(node_id, value))
+                        return
         except Exception as e:
             self.__log.exception(e)
 
     def server_side_rpc_handler(self, content):
         try:
             rpc_method = content["data"].get("method")
 
@@ -475,15 +498,18 @@
                                                        "code": 404})
 
         except Exception as e:
             self.__log.exception(e)
 
     async def __write_value(self, path, value, result={}):
         try:
-            var = self.__client.get_node(path.replace('\\.', '.'))
+            var = path
+            if isinstance(path, str):
+                var = self.__client.get_node(path.replace('\\.', '.'))
+
             await var.write_value(value)
         except Exception as e:
             result['error'] = e.__str__()
 
     async def __read_value(self, path, result={}):
         try:
             var = self.__client.get_node(path)
@@ -494,20 +520,37 @@
     async def __call_method(self, path, arguments, result={}):
         try:
             var = self.__client.get_node(path)
             result['result'] = await var.call_method(*arguments)
         except Exception as e:
             result['error'] = e.__str__()
 
+    def update_converter_config(self, converter_name, config):
+        log.debug('Received remote converter configuration update for %s with configuration %s', converter_name,
+                  config)
+        for device in self.__device_nodes:
+            if device.converter.__class__.__name__ == converter_name:
+                device.config.update(config)
+                device.load_values()
+                log.info('Updated converter configuration for: %s with configuration %s',
+                         converter_name, device.config)
+
+                for node_config in self.__server_conf['mapping']:
+                    if node_config['deviceNodePattern'] == device.config['deviceNodePattern']:
+                        node_config.update(config)
+
+                self.__gateway.update_connector_config_file(self.name, {'server': self.__server_conf})
 
 class SubHandler:
-    @staticmethod
-    def datachange_notification(node, _, data):
+    def __init__(self, queue):
+        self.__queue = queue
+
+    def datachange_notification(self, node, _, data):
         log.debug("New data change event %s %s", node, data)
-        OpcUaConnectorAsyncIO.SUB_DATA_TO_CONVERT.put((node, data))
+        self.__queue.put((node, data))
 
     @staticmethod
     def event_notification(event):
         try:
             log.info("New event %s", event)
         except Exception as e:
             log.exception(e)
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/opcua_asyncio/opcua_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/opcua_asyncio/opcua_converter.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/opcua_asyncio/opcua_uplink_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/opcua_asyncio/opcua_uplink_converter.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/request/__init__.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/request/__init__.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/request/json_request_downlink_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/rest/json_rest_downlink_converter.py`

 * *Files 5% similar despite different names*

```diff
@@ -10,50 +10,51 @@
 #     distributed under the License is distributed on an "AS IS" BASIS,
 #     WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 #     See the License for the specific language governing permissions and
 #     limitations under the License.
 
 from urllib.parse import quote
 
-from thingsboard_gateway.connectors.request.request_converter import RequestConverter, log
+from thingsboard_gateway.connectors.rest.rest_converter import RESTConverter, log
 from thingsboard_gateway.tb_utility.tb_utility import TBUtility
 from thingsboard_gateway.gateway.statistics_service import StatisticsService
 
 
-class JsonRequestDownlinkConverter(RequestConverter):
+class JsonRESTDownlinkConverter(RESTConverter):
     def __init__(self, config):
         self.__config = config
 
     @StatisticsService.CollectStatistics(start_stat_type='allReceivedBytesFromTB',
                                          end_stat_type='allBytesSentToDevices')
     def convert(self, config, data):
         try:
             if data["data"].get("id") is None:
                 attribute_key = list(data["data"].keys())[0]
                 attribute_value = list(data["data"].values())[0]
 
                 result = {
-                    "url": self.__config["requestUrlExpression"].replace("${attributeKey}", quote(attribute_key))
-                                                                .replace("${attributeValue}", quote(attribute_value))
-                                                                .replace("${deviceName}", quote(data["device"])),
-                    "data": self.__config["valueExpression"].replace("${attributeKey}", quote(attribute_key))
-                                                            .replace("${attributeValue}", quote(attribute_value))
-                                                            .replace("${deviceName}", quote(data["device"]))
-                }
+                    "url": self.__config["requestUrlExpression"]
+                        .replace("${attributeKey}", quote(attribute_key))
+                        .replace("${attributeValue}", quote(str(attribute_value)))
+                        .replace("${deviceName}", quote(data["device"])),
+                    "data": self.__config["valueExpression"]
+                        .replace("${attributeKey}", quote(attribute_key))
+                        .replace("${attributeValue}", quote(str(attribute_value)))
+                        .replace("${deviceName}", quote(data["device"]))}
             else:
-                request_id = str(data["data"]["id"])
+                rest_id = str(data["data"]["id"])
                 method_name = data["data"]["method"]
 
                 result = {
-                    "url": self.__config["requestUrlExpression"].replace("${requestId}", request_id)
-                                                                .replace("${methodName}", method_name)
-                                                                .replace("${deviceName}", quote(data["device"])),
-                    "data": self.__config["valueExpression"].replace("${requestId}", request_id)
-                                                            .replace("${methodName}", method_name)
-                                                            .replace("${deviceName}", quote(data["device"]))
+                    "url": self.__config["requestUrlExpression"].replace("${restId}", rest_id)
+                        .replace("${methodName}", method_name)
+                        .replace("${deviceName}", quote(data["device"])),
+                    "data": self.__config["valueExpression"].replace("${restId}", rest_id)
+                        .replace("${methodName}", method_name)
+                        .replace("${deviceName}", quote(data["device"]))
                 }
 
                 result['url'] = TBUtility.replace_params_tags(result['url'], data)
 
                 data_tags = TBUtility.get_values(config.get('valueExpression'), data['data'], 'params',
                                                  get_tag=True)
                 data_values = TBUtility.get_values(config.get('valueExpression'), data['data'], 'params',
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/request/json_request_uplink_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/request/json_request_uplink_converter.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/request/request_connector.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/request/request_connector.py`

 * *Files 3% similar despite different names*

```diff
@@ -16,14 +16,16 @@
 from queue import Queue
 from random import choice
 from re import fullmatch
 from string import ascii_lowercase
 from threading import Thread
 from time import sleep, time
 
+import simplejson
+
 from thingsboard_gateway.tb_utility.tb_loader import TBModuleLoader
 from thingsboard_gateway.tb_utility.tb_utility import TBUtility
 
 try:
     from requests import Timeout, request
 except ImportError:
     print("Requests library not found - installing...")
@@ -88,15 +90,16 @@
             for attribute_request in self.__attribute_updates:
                 if fullmatch(attribute_request["deviceNameFilter"], content["device"]) and fullmatch(
                         attribute_request["attributeFilter"], list(content["data"].keys())[0]):
                     converted_data = attribute_request["converter"].convert(attribute_request, content)
                     response_queue = Queue(1)
                     request_dict = {"config": {**attribute_request,
                                                **converted_data},
-                                    "request": request}
+                                    "request": request,
+                                    "withResponse": True}
                     attribute_update_request_thread = Thread(target=self.__send_request,
                                                              args=(request_dict, response_queue, log),
                                                              daemon=True,
                                                              name="Attribute request to %s" % (converted_data["url"]))
                     attribute_update_request_thread.start()
                     attribute_update_request_thread.join()
                     if not response_queue.empty():
@@ -111,27 +114,48 @@
             for rpc_request in self.__rpc_requests:
                 if fullmatch(rpc_request["deviceNameFilter"], content["device"]) and fullmatch(
                         rpc_request["methodFilter"], content["data"]["method"]):
                     converted_data = rpc_request["converter"].convert(rpc_request, content)
                     response_queue = Queue(1)
                     request_dict = {"config": {**rpc_request,
                                                **converted_data},
-                                    "request": request}
-                    request_dict["config"].get("uplink_converter")
+                                    "request": request,
+                                    "withResponse": True}
                     rpc_request_thread = Thread(target=self.__send_request,
                                                 args=(request_dict, response_queue, log),
                                                 daemon=True,
                                                 name="RPC request to %s" % (converted_data["url"]))
                     rpc_request_thread.start()
                     rpc_request_thread.join()
                     if not response_queue.empty():
                         response = response_queue.get_nowait()
-                        log.debug(response)
+
+                        if rpc_request.get('responseValueExpression'):
+                            response_value_expression = rpc_request['responseValueExpression']
+                            values = TBUtility.get_values(response_value_expression, response.json(),
+                                                          expression_instead_none=True)
+                            values_tags = TBUtility.get_values(response_value_expression, response.json(), get_tag=True)
+                            full_value = response_value_expression
+                            for (value, value_tag) in zip(values, values_tags):
+                                is_valid_value = "${" in response_value_expression and "}" in \
+                                                 response_value_expression
+
+                                full_value = full_value.replace('${' + str(value_tag) + '}',
+                                                                str(value)) if is_valid_value else str(value)
+
+                            self.__gateway.send_rpc_reply(device=content["device"], req_id=content["data"]["id"],
+                                                          content=full_value)
+                            del response_queue
+                            return
+
                         self.__gateway.send_rpc_reply(device=content["device"], req_id=content["data"]["id"],
-                                                      content=response[2])
+                                                      content=response.text)
+                        del response_queue
+                        return
+
                     self.__gateway.send_rpc_reply(device=content["device"], req_id=content["data"]["id"],
                                                   success_sent=True)
 
                     del response_queue
         except Exception as e:
             log.exception(e)
 
@@ -197,14 +221,19 @@
                 "data": request["config"].get("data", {})
                 }
             logger.debug(url)
             if request["config"].get("httpHeaders") is not None:
                 params["headers"] = request["config"]["httpHeaders"]
             logger.debug("Request to %s will be sent", url)
             response = request["request"](**params)
+
+            if request.get('withResponse'):
+                converter_queue.put(response)
+                return
+
             if response and response.ok:
                 if not converter_queue.full():
                     data_to_storage = [url, request["converter"]]
                     try:
                         data_to_storage.append(response.json())
                     except UnicodeDecodeError:
                         data_to_storage.append(response.content())
@@ -276,7 +305,10 @@
 
     def open(self):
         self.__stopped = False
         self.start()
 
     def close(self):
         self.__stopped = True
+
+    def get_config(self):
+        return self.__config
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/request/request_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/rest/rest_converter.py`

 * *Files 10% similar despite different names*

```diff
@@ -8,14 +8,14 @@
 #
 #     Unless required by applicable law or agreed to in writing, software
 #     distributed under the License is distributed on an "AS IS" BASIS,
 #     WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 #     See the License for the specific language governing permissions and
 #     limitations under the License.
 
-from thingsboard_gateway.connectors.converter import Converter, abstractmethod, log
+from thingsboard_gateway.connectors.converter import Converter, log
 
 
-class RequestConverter(Converter):
-    @abstractmethod
+class RESTConverter(Converter):
+
     def convert(self, config, data):
         pass
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/request/request_uplink_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/request/request_uplink_converter.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/rest/__init__.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/rest/__init__.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/rest/json_rest_downlink_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/request/json_request_downlink_converter.py`

 * *Files 6% similar despite different names*

```diff
@@ -10,58 +10,57 @@
 #     distributed under the License is distributed on an "AS IS" BASIS,
 #     WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 #     See the License for the specific language governing permissions and
 #     limitations under the License.
 
 from urllib.parse import quote
 
-from thingsboard_gateway.connectors.rest.rest_converter import RESTConverter, log
+from thingsboard_gateway.connectors.request.request_converter import RequestConverter, log
 from thingsboard_gateway.tb_utility.tb_utility import TBUtility
 from thingsboard_gateway.gateway.statistics_service import StatisticsService
 
 
-class JsonRESTDownlinkConverter(RESTConverter):
+class JsonRequestDownlinkConverter(RequestConverter):
     def __init__(self, config):
         self.__config = config
 
     @StatisticsService.CollectStatistics(start_stat_type='allReceivedBytesFromTB',
                                          end_stat_type='allBytesSentToDevices')
     def convert(self, config, data):
         try:
             if data["data"].get("id") is None:
                 attribute_key = list(data["data"].keys())[0]
                 attribute_value = list(data["data"].values())[0]
 
                 result = {
-                    "url": self.__config["requestUrlExpression"]
-                        .replace("${attributeKey}", quote(attribute_key))
-                        .replace("${attributeValue}", quote(str(attribute_value)))
-                        .replace("${deviceName}", quote(data["device"])),
-                    "data": self.__config["valueExpression"]
-                        .replace("${attributeKey}", quote(attribute_key))
-                        .replace("${attributeValue}", quote(str(attribute_value)))
-                        .replace("${deviceName}", quote(data["device"]))}
+                    "url": self.__config["requestUrlExpression"].replace("${attributeKey}", quote(attribute_key))
+                                                                .replace("${attributeValue}", quote(str(attribute_value)))
+                                                                .replace("${deviceName}", quote(data["device"])),
+                    "data": self.__config["requestValueExpression"].replace("${attributeKey}", quote(attribute_key))
+                                                                   .replace("${attributeValue}", quote(str(attribute_value)))
+                                                                   .replace("${deviceName}", quote(data["device"]))
+                }
             else:
-                rest_id = str(data["data"]["id"])
+                request_id = str(data["data"]["id"])
                 method_name = data["data"]["method"]
 
                 result = {
-                    "url": self.__config["requestUrlExpression"].replace("${restId}", rest_id)
-                        .replace("${methodName}", method_name)
-                        .replace("${deviceName}", quote(data["device"])),
-                    "data": self.__config["valueExpression"].replace("${restId}", rest_id)
-                        .replace("${methodName}", method_name)
-                        .replace("${deviceName}", quote(data["device"]))
+                    "url": self.__config["requestUrlExpression"].replace("${requestId}", request_id)
+                                                                .replace("${methodName}", method_name)
+                                                                .replace("${deviceName}", quote(data["device"])),
+                    "data": self.__config["requestValueExpression"].replace("${requestId}", request_id)
+                                                                   .replace("${methodName}", method_name)
+                                                                   .replace("${deviceName}", quote(data["device"]))
                 }
 
                 result['url'] = TBUtility.replace_params_tags(result['url'], data)
 
-                data_tags = TBUtility.get_values(config.get('valueExpression'), data['data'], 'params',
+                data_tags = TBUtility.get_values(config.get('requestValueExpression'), data['data'], 'params',
                                                  get_tag=True)
-                data_values = TBUtility.get_values(config.get('valueExpression'), data['data'], 'params',
+                data_values = TBUtility.get_values(config.get('requestValueExpression'), data['data'], 'params',
                                                    expression_instead_none=True)
 
                 for (tag, value) in zip(data_tags, data_values):
                     result['data'] = result["data"].replace('${' + tag + '}', str(value))
 
             return result
         except Exception as e:
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/rest/json_rest_uplink_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/rest/json_rest_uplink_converter.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/rest/rest_connector.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/rest/rest_connector.py`

 * *Files 0% similar despite different names*

```diff
@@ -177,14 +177,17 @@
 
     def get_name(self):
         return self.name
 
     def is_connected(self):
         return self._connected
 
+    def get_config(self):
+        return self.__config
+
     def on_attributes_update(self, content):
         try:
             for attribute_request in self.__attribute_updates:
                 if fullmatch(attribute_request["deviceNameFilter"], content["device"]) and \
                         fullmatch(attribute_request["attributeFilter"], list(content["data"].keys())[0]):
                     converted_data = attribute_request["downlink_converter"].convert(attribute_request, content)
                     response_queue = Queue(1)
@@ -495,15 +498,16 @@
                                 status=415)
 
         endpoint_config = self.endpoint['config']
         if request.method.upper() not in [method.upper() for method in endpoint_config['HTTPMethods']]:
             return web.Response(body=str(self.unsuccessful_response) if self.unsuccessful_response else None,
                                 status=405)
 
-        data = json_data if json_data else dict(request.query)
+        json_data.update(dict(request.query))
+        data = json_data
 
         # check if request is Attribute Request type
         result = self.process_attribute_request(data)
         if isinstance(result, web.Response):
             return result
 
         try:
@@ -543,15 +547,16 @@
 
             endpoint_config = self.endpoint['config']
 
             if request.method.upper() not in [method.upper() for method in endpoint_config['HTTPMethods']]:
                 return web.Response(body=str(self.unsuccessful_response) if self.unsuccessful_response else None,
                                     status=405)
 
-            data = json_data if json_data else dict(request.query)
+            json_data.update(dict(request.query))
+            data = json_data
 
             # check if request is Attribute Request type
             result = self.process_attribute_request(data)
             if isinstance(result, web.Response):
                 return result
 
             try:
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/rest/rest_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/snmp/snmp_downlink_converter.py`

 * *Files 18% similar despite different names*

```diff
@@ -8,14 +8,19 @@
 #
 #     Unless required by applicable law or agreed to in writing, software
 #     distributed under the License is distributed on an "AS IS" BASIS,
 #     WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 #     See the License for the specific language governing permissions and
 #     limitations under the License.
 
-from thingsboard_gateway.connectors.converter import Converter, log
+from thingsboard_gateway.connectors.converter import Converter
+from thingsboard_gateway.gateway.statistics_service import StatisticsService
 
 
-class RESTConverter(Converter):
+class SNMPDownlinkConverter(Converter):
+    def __init__(self, config):
+        self.__config = config
 
+    @StatisticsService.CollectStatistics(start_stat_type='allReceivedBytesFromTB',
+                                         end_stat_type='allBytesSentToDevices')
     def convert(self, config, data):
-        pass
+        return data["params"]
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/rest/ssl_generator.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/rest/ssl_generator.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/snmp/__init__.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/snmp/__init__.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/snmp/snmp_connector.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/snmp/snmp_connector.py`

 * *Files 7% similar despite different names*

```diff
@@ -8,31 +8,42 @@
 #
 #     Unless required by applicable law or agreed to in writing, software
 #     distributed under the License is distributed on an "AS IS" BASIS,
 #     WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 #     See the License for the specific language governing permissions and
 #     limitations under the License.
 
+import asyncio
 from random import choice
 from re import search
 from socket import gethostbyname
 from string import ascii_lowercase
 from threading import Thread
 from time import sleep, time
 
 from thingsboard_gateway.connectors.connector import Connector, log
 from thingsboard_gateway.tb_utility.tb_loader import TBModuleLoader
 from thingsboard_gateway.tb_utility.tb_utility import TBUtility
 
+# Try import Pymodbus library or install it and import
+installation_required = False
+
 try:
-    import puresnmp
+    from puresnmp import __version__ as pymodbus_version
+
+    if int(pymodbus_version.split('.')[0]) < 2:
+        installation_required = True
 except ImportError:
-    TBUtility.install_package("puresnmp")
-    import puresnmp
+    installation_required = True
+
+if installation_required:
+    print("Modbus library not found - installing...")
+    TBUtility.install_package("puresnmp", ">=2.0.0")
 
+from puresnmp import Client, credentials, PyWrapper
 from puresnmp.exc import Timeout as SNMPTimeoutException
 
 
 class SNMPConnector(Connector, Thread):
     def __init__(self, gateway, config, connector_type):
         super().__init__()
         self.daemon = True
@@ -44,205 +55,213 @@
         self.__devices = self.__config["devices"]
         self.setName(config.get("name", 'SNMP Connector ' + ''.join(choice(ascii_lowercase) for _ in range(5))))
         self.statistics = {'MessagesReceived': 0,
                            'MessagesSent': 0}
         self._default_converters = {
             "uplink": "SNMPUplinkConverter",
             "downlink": "SNMPDownlinkConverter"
-            }
-        self.__methods = ["get", "multiget", "getnext", "multigetnext", "walk", "multiwalk", "set", "multiset", "bulkget", "bulkwalk", "table", "bulktable"]
+        }
+        self.__methods = ["get", "multiget", "getnext", "walk", "multiwalk", "set", "multiset",
+                          "bulkget", "bulkwalk", "table", "bulktable"]
         self.__datatypes = ('attributes', 'telemetry')
 
+        self.__loop = asyncio.new_event_loop()
+
     def open(self):
         self.__stopped = False
         self.__fill_converters()
         self.start()
 
     def run(self):
         self._connected = True
         try:
-            while not self.__stopped:
-                current_time = time() * 1000
-                for device in self.__devices:
-                    try:
-                        if device.get("previous_poll_time", 0) + device.get("pollPeriod", 10000) < current_time:
-                            self.__process_data(device)
-                            device["previous_poll_time"] = current_time
-                    except Exception as e:
-                        log.exception(e)
-                if self.__stopped:
-                    break
-                else:
-                    sleep(.2)
+            self.__loop.run_until_complete(self._run())
         except Exception as e:
             log.exception(e)
 
+    async def _run(self):
+        while not self.__stopped:
+            current_time = time() * 1000
+            for device in self.__devices:
+                try:
+                    if device.get("previous_poll_time", 0) + device.get("pollPeriod", 10000) < current_time:
+                        await self.__process_data(device)
+                        device["previous_poll_time"] = current_time
+                except Exception as e:
+                    log.exception(e)
+            if self.__stopped:
+                break
+            else:
+                sleep(.2)
+
     def close(self):
         self.__stopped = True
         self._connected = False
 
     def get_name(self):
         return self.name
 
     def is_connected(self):
         return self._connected
 
-    def on_attributes_update(self, content):
-        try:
-            for device in self.__devices:
-                if content["device"] == device["deviceName"]:
-                    for attribute_request_config in device["attributeUpdateRequests"]:
-                        for attribute, value in content["data"]:
-                            if search(attribute, attribute_request_config["attributeFilter"]):
-                                common_parameters = self.__get_common_parameters(device)
-                                result = self.__process_methods(attribute_request_config["method"], common_parameters,
-                                                                {**attribute_request_config, "value": value})
-                                log.debug("Received attribute update request for device \"%s\" with attribute \"%s\" and value \"%s\"", content["device"],
-                                          attribute)
-                                log.debug(result)
-                                log.debug(content)
-        except Exception as e:
-            log.exception(e)
-
-    def server_side_rpc_handler(self, content):
-        try:
-            for device in self.__devices:
-                if content["device"] == device["deviceName"]:
-                    for rpc_request_config in device["serverSideRpcRequests"]:
-                        if search(content["data"]["method"], rpc_request_config["requestFilter"]):
-                            common_parameters = self.__get_common_parameters(device)
-                            result = self.__process_methods(rpc_request_config["method"], common_parameters,
-                                                            {**rpc_request_config, "value": content["data"]["params"]})
-                            log.debug("Received RPC request for device \"%s\" with command \"%s\" and value \"%s\"", content["device"],
-                                      content["data"]["method"])
-                            log.debug(result)
-                            log.debug(content)
-                            self.__gateway.send_rpc_reply(device=content["device"], req_id=content["data"]["id"], content=result)
-        except Exception as e:
-            log.exception(e)
-            self.__gateway.send_rpc_reply(device=content["device"], req_id=content["data"]["id"], success_sent=False)
+    def get_config(self):
+        return self.__config
 
     def collect_statistic_and_send(self, connector_name, data):
         self.statistics["MessagesReceived"] = self.statistics["MessagesReceived"] + 1
         self.__gateway.send_to_storage(connector_name, data)
         self.statistics["MessagesSent"] = self.statistics["MessagesSent"] + 1
 
-    def __process_data(self, device):
+    async def __process_data(self, device):
         common_parameters = self.__get_common_parameters(device)
         converted_data = {}
         for datatype in self.__datatypes:
             for datatype_config in device[datatype]:
                 try:
                     response = None
                     method = datatype_config.get("method")
                     if method is None:
                         log.error("Method not found in configuration: %r", datatype_config)
                         continue
                     else:
                         method = method.lower()
                     if method not in self.__methods:
                         log.error("Unknown method: %s, configuration is: %r", method, datatype_config)
-                    response = self.__process_methods(method, common_parameters, datatype_config)
+                    response = await self.__process_methods(method, common_parameters, datatype_config)
                     converted_data.update(**device["uplink_converter"].convert((datatype, datatype_config), response))
                 except SNMPTimeoutException:
-                    log.error("Timeout exception on connection to device \"%s\" with ip: \"%s\"", device["deviceName"], device["ip"])
+                    log.error("Timeout exception on connection to device \"%s\" with ip: \"%s\"", device["deviceName"],
+                              device["ip"])
                     return
                 except Exception as e:
                     log.exception(e)
 
         if isinstance(converted_data, dict) and (converted_data.get("attributes") or converted_data.get("telemetry")):
             self.collect_statistic_and_send(self.get_name(), converted_data)
 
     @staticmethod
-    def __process_methods(method, common_parameters, datatype_config):
+    async def __process_methods(method, common_parameters, datatype_config):
+        client = Client(ip=common_parameters['ip'],
+                        port=common_parameters['port'],
+                        credentials=credentials.V1(common_parameters['community']))
+        client.configure(timeout=common_parameters['timeout'])
+        client = PyWrapper(client)
+
         response = None
 
         if method == "get":
             oid = datatype_config["oid"]
-            response = puresnmp.get(**common_parameters,
-                                    oid=oid)
+            response = await client.get(oid=oid)
         elif method == "multiget":
             oids = datatype_config["oid"]
             oids = oids if isinstance(oids, list) else list(oids)
-            response = puresnmp.multiget(**common_parameters,
-                                         oids=oids)
+            response = await client.multiget(oids=oids)
         elif method == "getnext":
             oid = datatype_config["oid"]
-            master_response = puresnmp.getnext(**common_parameters,
-                                               oid=oid)
+            master_response = await client.getnext(oid=oid)
             response = {master_response.oid: master_response.value}
-        elif method == "multigetnext":
-            oids = datatype_config["oid"]
-            oids = oids if isinstance(oids, list) else list(oids)
-            master_response = puresnmp.multigetnext(**common_parameters,
-                                                    oids=oids)
-            response = {binded_var.oid: binded_var.value for binded_var in master_response}
         elif method == "walk":
             oid = datatype_config["oid"]
-            response = {binded_var.oid: binded_var.value for binded_var in list(puresnmp.walk(**common_parameters,
-                                                                                              oid=oid))}
+            response = {}
+            async for binded_var in client.walk(oid=oid):
+                response[binded_var.oid] = binded_var.value
         elif method == "multiwalk":
             oids = datatype_config["oid"]
             oids = oids if isinstance(oids, list) else list(oids)
-            response = {binded_var.oid: binded_var.value for binded_var in list(puresnmp.multiwalk(**common_parameters,
-                                                                                                   oids=oids))}
+            response = {}
+            async for binded_var in client.multiwalk(oids=oids):
+                response[binded_var.oid] = binded_var.value
         elif method == "set":
             oid = datatype_config["oid"]
             value = datatype_config["value"]
-            response = puresnmp.set(**common_parameters,
-                                    oid=oid,
-                                    value=value)
+            response = await client.set(oid=oid, value=value)
         elif method == "multiset":
             mappings = datatype_config["mappings"]
-            response = puresnmp.multiset(**common_parameters,
-                                         mappings=mappings)
+            response = await client.multiset(mappings=mappings)
         elif method == "bulkget":
             scalar_oids = datatype_config.get("scalarOid", [])
             scalar_oids = scalar_oids if isinstance(scalar_oids, list) else list(scalar_oids)
             repeating_oids = datatype_config.get("repeatingOid", [])
             repeating_oids = repeating_oids if isinstance(repeating_oids, list) else list(repeating_oids)
             max_list_size = datatype_config.get("maxListSize", 1)
-            response = puresnmp.bulkget(**common_parameters,
-                                        scalar_oids=scalar_oids,
-                                        repeating_oids=repeating_oids,
-                                        max_list_size=max_list_size)._asdict()
+            response = await client.bulkget(scalar_oids=scalar_oids, repeating_oids=repeating_oids,
+                                            max_list_size=max_list_size)
+            response = response.scalars
         elif method == "bulkwalk":
             oids = datatype_config["oid"]
             oids = oids if isinstance(oids, list) else list(oids)
             bulk_size = datatype_config.get("bulkSize", 10)
-            response = {binded_var.oid: binded_var.value for binded_var in list(puresnmp.bulkwalk(**common_parameters,
-                                                                                                  bulk_size=bulk_size,
-                                                                                                  oids=oids))}
+            response = {}
+            async for binded_var in client.bulkwalk(bulk_size=bulk_size, oids=oids):
+                response[binded_var.oid] = binded_var.value
         elif method == "table":
             oid = datatype_config["oid"]
-            del common_parameters["timeout"]
             num_base_nodes = datatype_config.get("numBaseNodes", 0)
-            response = puresnmp.table(**common_parameters,
-                                      oid=oid,
-                                      num_base_nodes=num_base_nodes)
+            response = await client.table(oid=oid)
         elif method == "bulktable":
             oid = datatype_config["oid"]
             num_base_nodes = datatype_config.get("numBaseNodes", 0)
             bulk_size = datatype_config.get("bulkSize", 10)
-            response = puresnmp.bulktable(**common_parameters,
-                                          oid=oid,
-                                          num_base_nodes=num_base_nodes,
-                                          bulk_size=bulk_size)
+            response = await client.bulktable(oid=oid, bulk_size=bulk_size)
         else:
             log.error("Method \"%s\" - Not found", str(method))
         return response
 
     def __fill_converters(self):
         try:
             for device in self.__devices:
-                device["uplink_converter"] = TBModuleLoader.import_module("snmp", device.get('converter', self._default_converters["uplink"]))(device)
-                device["downlink_converter"] = TBModuleLoader.import_module("snmp", device.get('converter', self._default_converters["downlink"]))(device)
+                device["uplink_converter"] = TBModuleLoader.import_module("snmp", device.get('converter',
+                                                                                             self._default_converters[
+                                                                                                 "uplink"]))(device)
+                device["downlink_converter"] = TBModuleLoader.import_module("snmp", device.get('converter',
+                                                                                               self._default_converters[
+                                                                                                   "downlink"]))(device)
         except Exception as e:
             log.exception(e)
 
     @staticmethod
     def __get_common_parameters(device):
         return {"ip": gethostbyname(device["ip"]),
                 "port": device.get("port", 161),
                 "timeout": device.get("timeout", 6),
                 "community": device["community"],
                 }
+
+    def on_attributes_update(self, content):
+        try:
+            for device in self.__devices:
+                if content["device"] == device["deviceName"]:
+                    for attribute_request_config in device["attributeUpdateRequests"]:
+                        for attribute, value in content["data"]:
+                            if search(attribute, attribute_request_config["attributeFilter"]):
+                                common_parameters = self.__get_common_parameters(device)
+                                result = self.__process_methods(attribute_request_config["method"], common_parameters,
+                                                                {**attribute_request_config, "value": value})
+                                log.debug(
+                                    "Received attribute update request for device \"%s\" "
+                                    "with attribute \"%s\" and value \"%s\"",
+                                    content["device"],
+                                    attribute)
+                                log.debug(result)
+                                log.debug(content)
+        except Exception as e:
+            log.exception(e)
+
+    def server_side_rpc_handler(self, content):
+        try:
+            for device in self.__devices:
+                if content["device"] == device["deviceName"]:
+                    for rpc_request_config in device["serverSideRpcRequests"]:
+                        if search(content["data"]["method"], rpc_request_config["requestFilter"]):
+                            common_parameters = self.__get_common_parameters(device)
+                            result = self.__process_methods(rpc_request_config["method"], common_parameters,
+                                                            {**rpc_request_config, "value": content["data"]["params"]})
+                            log.debug("Received RPC request for device \"%s\" with command \"%s\" and value \"%s\"",
+                                      content["device"],
+                                      content["data"]["method"])
+                            log.debug(result)
+                            log.debug(content)
+                            self.__gateway.send_rpc_reply(device=content["device"], req_id=content["data"]["id"],
+                                                          content=result)
+        except Exception as e:
+            log.exception(e)
+            self.__gateway.send_rpc_reply(device=content["device"], req_id=content["data"]["id"], success_sent=False)
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/snmp/snmp_downlink_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/storage/sqlite/storage_settings.py`

 * *Files 24% similar despite different names*

```diff
@@ -8,19 +8,12 @@
 #
 #     Unless required by applicable law or agreed to in writing, software
 #     distributed under the License is distributed on an "AS IS" BASIS,
 #     WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 #     See the License for the specific language governing permissions and
 #     limitations under the License.
 
-from thingsboard_gateway.connectors.converter import Converter
-from thingsboard_gateway.gateway.statistics_service import StatisticsService
-
-
-class SNMPDownlinkConverter(Converter):
+class StorageSettings:
     def __init__(self, config):
-        self.__config = config
-
-    @StatisticsService.CollectStatistics(start_stat_type='allReceivedBytesFromTB',
-                                         end_stat_type='allBytesSentToDevices')
-    def convert(self, config, data):
-        return data["params"]
+        self.data_folder_path = config.get("data_file_path", "./")
+        self.messages_ttl_check_in_hours = config.get('messages_ttl_check_in_hours', 1) * 3600
+        self.messages_ttl_in_days = config.get('messages_ttl_in_days', 7)
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/snmp/snmp_uplink_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/snmp/snmp_uplink_converter.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/socket/__init__.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/socket/__init__.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/socket/bytes_socket_uplink_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/socket/bytes_socket_uplink_converter.py`

 * *Files 10% similar despite different names*

```diff
@@ -15,28 +15,33 @@
 from thingsboard_gateway.connectors.socket.socket_uplink_converter import SocketUplinkConverter, log
 from thingsboard_gateway.gateway.statistics_service import StatisticsService
 
 
 class BytesSocketUplinkConverter(SocketUplinkConverter):
     def __init__(self, config):
         self.__config = config
-        self.dict_result = {
+        dict_result = {
             "deviceName": config['deviceName'],
             "deviceType": config['deviceType']
         }
 
     @StatisticsService.CollectStatistics(start_stat_type='receivedBytesFromDevices',
                                          end_stat_type='convertedBytesFromDevice')
     def convert(self, config, data):
         if data is None:
             return {}
 
+        dict_result = {
+            "deviceName": self.__config['deviceName'],
+            "deviceType": self.__config['deviceType']
+        }
+
         try:
-            self.dict_result["telemetry"] = []
-            self.dict_result["attributes"] = []
+            dict_result["telemetry"] = []
+            dict_result["attributes"] = []
 
             for section in ('telemetry', 'attributes'):
                 for item in config[section]:
                     try:
                         byte_from = item.get('byteFrom')
                         byte_to = item.get('byteTo')
 
@@ -45,18 +50,18 @@
 
                         try:
                             converted_data = converted_data.replace(b"\x00", b'').decode(config['encoding'])
                         except UnicodeDecodeError:
                             converted_data = str(converted_data)
 
                         if item.get('key') is not None:
-                            self.dict_result[section].append(
+                            dict_result[section].append(
                                 {item['key']: converted_data})
                         else:
                             log.error('Key for %s not found in config: %s', config['type'], config['section_config'])
                     except Exception as e:
                         log.exception(e)
         except Exception as e:
             log.exception(e)
 
-        log.debug(self.dict_result)
-        return self.dict_result
+        log.debug(dict_result)
+        return dict_result
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/socket/socket_connector.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/socket/socket_connector.py`

 * *Files 1% similar despite different names*

```diff
@@ -289,14 +289,17 @@
 
     def get_name(self):
         return self.name
 
     def is_connected(self):
         return self._connected
 
+    def get_config(self):
+        return self.__config
+
     @CustomCollectStatistics(start_stat_type='allBytesSentToDevices')
     def __write_value_via_tcp(self, address, port, value):
         try:
             self.__connections[(address, int(port))].sendall(value)
             return 'ok'
         except KeyError:
             try:
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/socket/socket_uplink_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/socket/socket_uplink_converter.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/xmpp/__init__.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/xmpp/__init__.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/xmpp/xmpp_connector.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/xmpp/xmpp_connector.py`

 * *Files 1% similar despite different names*

```diff
@@ -195,14 +195,17 @@
 
     def get_name(self):
         return self.name
 
     def is_connected(self):
         return self._connected
 
+    def get_config(self):
+        return self.__config
+
     @StatisticsService.CollectStatistics(start_stat_type='allBytesSentToDevices')
     def _send_message(self, jid, data):
         self._xmpp.send_message(mto=jid, mfrom=self._server_config['jid'], mbody=data,
                                 mtype='chat')
 
     @StatisticsService.CollectAllReceivedBytesStatistics(start_stat_type='allReceivedBytesFromTB')
     def on_attributes_update(self, content):
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/xmpp/xmpp_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/xmpp/xmpp_converter.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/connectors/xmpp/xmpp_uplink_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/connectors/xmpp/xmpp_uplink_converter.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/extensions/__init__.py` & `thingsboard-gateway-3.3/thingsboard_gateway/extensions/__init__.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/extensions/bacnet/__init__.py` & `thingsboard-gateway-3.3/thingsboard_gateway/extensions/bacnet/__init__.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/extensions/ble/__init__.py` & `thingsboard-gateway-3.3/thingsboard_gateway/extensions/ble/__init__.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/extensions/can/__init__.py` & `thingsboard-gateway-3.3/thingsboard_gateway/extensions/can/__init__.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/extensions/modbus/__init__.py` & `thingsboard-gateway-3.3/thingsboard_gateway/extensions/modbus/__init__.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/extensions/mqtt/__init__.py` & `thingsboard-gateway-3.3/thingsboard_gateway/extensions/mqtt/__init__.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/extensions/mqtt/custom_mqtt_uplink_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/extensions/request/custom_request_uplink_converter.py`

 * *Files 24% similar despite different names*

```diff
@@ -8,39 +8,59 @@
 #
 #     Unless required by applicable law or agreed to in writing, software
 #     distributed under the License is distributed on an "AS IS" BASIS,
 #     WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 #     See the License for the specific language governing permissions and
 #     limitations under the License.
 
+import struct
+
 from simplejson import dumps
 
-from thingsboard_gateway.connectors.mqtt.mqtt_uplink_converter import MqttUplinkConverter, log
+from thingsboard_gateway.connectors.request.request_converter import RequestConverter, log
+from thingsboard_gateway.tb_utility.tb_utility import TBUtility
 
 
-class CustomMqttUplinkConverter(MqttUplinkConverter):
+class CustomRequestUplinkConverter(RequestConverter):
     def __init__(self, config):
         self.__config = config.get('converter')
-        self.dict_result = {}
 
-    def convert(self, topic, body):
+    def convert(self, _, body):
         try:
-            self.dict_result["deviceName"] = topic.split("/")[
-                -1]  # getting all data after last '/' symbol in this case: if topic = 'devices/temperature/sensor1' device name will be 'sensor1'.
-            self.dict_result["deviceType"] = "Thermostat"  # just hardcode this
-            self.dict_result["telemetry"] = []  # template for telemetry array
-            bytes_to_read = body.replace("0x", "")  # Replacing the 0x (if '0x' in body), needs for converting to bytearray
-            converted_bytes = bytearray.fromhex(bytes_to_read)  # Converting incoming data to bytearray
+            data = body["data"]["value"]
+            dict_result = {}
+            dict_result["deviceName"] = TBUtility.get_value(self.__config.get("deviceNameJsonExpression"), body, expression_instead_none=True)
+            dict_result["deviceType"] = TBUtility.get_value(self.__config.get("deviceTypeJsonExpression"), body, expression_instead_none=True)
+            dict_result["attributes"] = []
+            dict_result["telemetry"] = []
+            converted_bytes = bytearray.fromhex(data)
             if self.__config.get("extension-config") is not None:
-                for telemetry_key in self.__config["extension-config"]:  # Processing every telemetry key in config for extension
-                    value = 0
-                    for _ in range(self.__config["extension-config"][telemetry_key]):  # reading every value with value length from config
-                        value = value * 256 + converted_bytes.pop(0)  # process and remove byte from processing
-                    telemetry_to_send = {telemetry_key.replace("Bytes", ""): value}  # creating telemetry data for sending into Thingsboard
-                    self.dict_result["telemetry"].append(telemetry_to_send)  # adding data to telemetry array
+                for telemetry_key in self.__config["extension-config"]:
+                    value = None
+                    byteorder = telemetry_key.get("byteorder", "big").lower()
+                    signed = telemetry_key.get("signed", True)
+                    if telemetry_key.get("byteAddress") is None:
+                        interest_bytes = converted_bytes[telemetry_key["fromByte"]: telemetry_key["toByte"]]
+                        if telemetry_key["type"] == "float":
+                            value = struct.unpack(">f" if byteorder == "big" else "<f", interest_bytes)
+                            value = value[0] if isinstance(value, list) else None
+                        if telemetry_key["type"] == "int":
+                            value = int.from_bytes(interest_bytes, byteorder=byteorder, signed=signed)
+                    else:
+                        interest_byte = converted_bytes[telemetry_key["byteAddress"]]
+                        bits = "{0:{fill}8b}".format(interest_byte, fill='0')
+                        bits = bits if byteorder == "big" else bits[::-1]
+                        value = int(bits[::-1][telemetry_key.get("fromBit"):telemetry_key.get("toBit")][::-1], 2)
+                    if value is not None:
+                        value = value * telemetry_key.get("multiplier", 1)
+                        telemetry_to_send = {
+                            telemetry_key["key"]: value}  # creating telemetry data for sending into Thingsboard
+                        # current_byte_position += self.__config["extension-config"][telemetry_key]
+                        dict_result["telemetry"].append(telemetry_to_send)  # adding data to telemetry array
             else:
-                self.dict_result["telemetry"] = {"data": int(body, 0)}  # if no specific configuration in config file - just send data which received
-            return self.dict_result
+                dict_result["telemetry"] = {
+                    "data": int(body, 0)}  # if no specific configuration in config file - just send data which received
+            return dict_result
 
         except Exception as e:
-            log.exception('Error in converter, for config: \n%s\n and message: \n%s\n', dumps(self.__config), body)
+            log.error('Error in converter, for config: \n%s\n and message: \n%s\n', dumps(self.__config), body)
             log.exception(e)
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/extensions/ocpp/__init__.py` & `thingsboard-gateway-3.3/thingsboard_gateway/extensions/ocpp/__init__.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/extensions/odbc/__init__.py` & `thingsboard-gateway-3.3/thingsboard_gateway/extensions/odbc/__init__.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/extensions/opcua/__init__.py` & `thingsboard-gateway-3.3/thingsboard_gateway/extensions/opcua/__init__.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/extensions/opcua_asyncio/__init__.py` & `thingsboard-gateway-3.3/thingsboard_gateway/extensions/opcua_asyncio/__init__.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/extensions/request/__init__.py` & `thingsboard-gateway-3.3/thingsboard_gateway/extensions/request/__init__.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/extensions/rest/__init__.py` & `thingsboard-gateway-3.3/thingsboard_gateway/extensions/rest/__init__.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/extensions/serial/__init__.py` & `thingsboard-gateway-3.3/thingsboard_gateway/extensions/serial/__init__.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/extensions/serial/custom_serial_connector.py` & `thingsboard-gateway-3.3/thingsboard_gateway/extensions/serial/custom_serial_connector.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/extensions/serial/custom_serial_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/extensions/serial/custom_serial_converter.py`

 * *Files 9% similar despite different names*

```diff
@@ -14,25 +14,25 @@
 
 from thingsboard_gateway.connectors.converter import Converter, log
 
 
 class CustomSerialUplinkConverter(Converter):
     def __init__(self, config):
         self.__config = config
-        self.result_dict = {
-            'deviceName': config.get('name', 'CustomSerialDevice'),
-            'deviceType': config.get('deviceType', 'default'),
-            'attributes': [],
-            'telemetry': []
-            }
 
     def convert(self, config, data: bytes):
+        dict_result = {
+            'deviceName': self.__config.get('name', 'CustomSerialDevice'),
+            'deviceType': self.__config.get('deviceType', 'default'),
+            'attributes': [],
+            'telemetry': []
+        }        
         keys = ['attributes', 'telemetry']
         for key in keys:
-            self.result_dict[key] = []
+            dict_result[key] = []
             if self.__config.get(key) is not None:
                 for config_object in self.__config.get(key):
                     data_to_convert = data
                     if config_object.get('untilDelimiter') is not None:
                         data_to_convert = data.split(config_object.get('untilDelimiter').encode('UTF-8'))[0]
                     if config_object.get('fromDelimiter') is not None:
                         data_to_convert = data.split(config_object.get('fromDelimiter').encode('UTF-8'))[1]
@@ -41,10 +41,10 @@
                         if to_byte == -1:
                             to_byte = len(data) - 1
                         data_to_convert = data_to_convert[:to_byte]
                     if config_object.get('fromByte') is not None:
                         from_byte = config_object.get('fromByte')
                         data_to_convert = data_to_convert[from_byte:]
                     converted_data = {config_object['key']: data_to_convert.decode('UTF-8')}
-                    self.result_dict[key].append(converted_data)
-        log.debug("Converted data: %s", self.result_dict)
-        return self.result_dict
+                    dict_result[key].append(converted_data)
+        log.debug("Converted data: %s", dict_result)
+        return dict_result
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/extensions/snmp/__init__.py` & `thingsboard-gateway-3.3/thingsboard_gateway/extensions/snmp/__init__.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/extensions/socket/__init__.py` & `thingsboard-gateway-3.3/thingsboard_gateway/extensions/socket/__init__.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/extensions/xmpp/__init__.py` & `thingsboard-gateway-3.3/thingsboard_gateway/extensions/xmpp/__init__.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/gateway/__init__.py` & `thingsboard-gateway-3.3/thingsboard_gateway/gateway/__init__.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/gateway/configuration_wizard.py` & `thingsboard-gateway-3.3/thingsboard_gateway/gateway/configuration_wizard.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/gateway/constant_enums.py` & `thingsboard-gateway-3.3/thingsboard_gateway/gateway/constant_enums.py`

 * *Files 7% similar despite different names*

```diff
@@ -30,8 +30,10 @@
     UnregisterConnectorMsg = 5,
     ConnectorGetConnectedDevicesResponseMsg = 6
 
 
 class Status(Enum):
     FAILURE = 1,
     NOT_FOUND = 2,
-    SUCCESS = 3
+    SUCCESS = 3,
+    NO_NEW_DATA = 4
+    FORBIDDEN_DEVICE = 5
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/gateway/constants.py` & `thingsboard-gateway-3.3/thingsboard_gateway/gateway/constants.py`

 * *Files 10% similar despite different names*

```diff
@@ -35,14 +35,24 @@
 DEVICE_SECTION_PARAMETER = "device"
 
 DEVICE_NAME_PARAMETER = "deviceName"
 DEVICE_TYPE_PARAMETER = "deviceType"
 
 ATTRIBUTES_PARAMETER = "attributes"
 TELEMETRY_PARAMETER = "telemetry"
+TELEMETRY_TIMESTAMP_PARAMETER = "ts"
+TELEMETRY_VALUES_PARAMETER = "values"
+
+SEND_ON_CHANGE_PARAMETER = "sendDataOnlyOnChange"
+# TTL value in milliseconds
+SEND_ON_CHANGE_TTL_PARAMETER = "sendDataOnlyOnChangeTtl"
+
+DEFAULT_SEND_ON_CHANGE_VALUE = False
+# TTL value in milliseconds
+DEFAULT_SEND_ON_CHANGE_INFINITE_TTL_VALUE = 0
 
 # RPC parameter constants
 
 RPC_ID_PARAMETER = "id"
 RPC_METHOD_PARAMETER = "method"
 RPC_PARAMS_PARAMETER = "params"
 DATA_PARAMETER = "data"
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/gateway/grpc_service/grpc_connector.py` & `thingsboard-gateway-3.3/thingsboard_gateway/gateway/grpc_service/grpc_connector.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/gateway/grpc_service/grpc_downlink_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/gateway/grpc_service/grpc_downlink_converter.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/gateway/grpc_service/grpc_uplink_converter.py` & `thingsboard-gateway-3.3/thingsboard_gateway/gateway/grpc_service/grpc_uplink_converter.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/gateway/grpc_service/tb_grpc_manager.py` & `thingsboard-gateway-3.3/thingsboard_gateway/gateway/grpc_service/tb_grpc_manager.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/gateway/grpc_service/tb_grpc_server.py` & `thingsboard-gateway-3.3/thingsboard_gateway/gateway/grpc_service/tb_grpc_server.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/gateway/hot_reloader.py` & `thingsboard-gateway-3.3/thingsboard_gateway/gateway/hot_reloader.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/gateway/proto/__init__.py` & `thingsboard-gateway-3.3/thingsboard_gateway/gateway/proto/__init__.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/gateway/proto/messages_pb2.py` & `thingsboard-gateway-3.3/thingsboard_gateway/gateway/proto/messages_pb2.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/gateway/proto/messages_pb2_grpc.py` & `thingsboard-gateway-3.3/thingsboard_gateway/gateway/proto/messages_pb2_grpc.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/gateway/statistics_service.py` & `thingsboard-gateway-3.3/thingsboard_gateway/gateway/statistics_service.py`

 * *Files 4% similar despite different names*

```diff
@@ -18,15 +18,15 @@
     def __init__(self, stats_send_period_in_seconds, gateway, log, config_path=None):
         super().__init__()
         self.name = 'Statistics Thread'
         self.daemon = True
         self._stopped = False
 
         self._config_path = config_path
-        self._stats_send_period_in_seconds = stats_send_period_in_seconds / 1000
+        self._stats_send_period_in_seconds = stats_send_period_in_seconds
         self._gateway = gateway
         self._log = log
         self._config = self._load_config()
         self._last_poll = 0
         self._last_streams_statistics_clear_time = datetime.datetime.now()
 
         self.start()
@@ -56,19 +56,20 @@
         }
 
     def run(self) -> None:
         while not self._stopped:
             if time() - self._last_poll >= self._stats_send_period_in_seconds:
                 data_to_send = {}
                 for attribute in self._config:
-                    process = subprocess.run(attribute['command'], stdout=subprocess.PIPE, stderr=subprocess.PIPE,
-                                             encoding='utf-8', timeout=attribute['timeout'])
-
-                    if process.returncode != 0:
-                        self._log.error("Statistic parameter raise the exception: %s", process.stderr)
+                    try:
+                        process = subprocess.run(attribute['command'], stdout=subprocess.PIPE, stderr=subprocess.PIPE,
+                                                 encoding='utf-8', timeout=attribute['timeout'])
+                    except Exception as e:
+                        self._log.warning("Statistic parameter %s raise the exception: %s",
+                                          attribute['attributeOnGateway'], e)
                         continue
 
                     value = process.stdout
 
                     data_to_send[attribute['attributeOnGateway']] = value
 
                 self._gateway.tb_client.client.send_attributes(data_to_send)
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/gateway/tb_gateway_service.py` & `thingsboard-gateway-3.3/thingsboard_gateway/gateway/tb_gateway_service.py`

 * *Files 2% similar despite different names*

```diff
@@ -11,32 +11,36 @@
 #     WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 #     See the License for the specific language governing permissions and
 #     limitations under the License.
 
 import logging
 import logging.config
 import logging.handlers
-from signal import signal, SIGINT
+import multiprocessing.managers
 import subprocess
-from copy import deepcopy
 from os import execv, listdir, path, pathsep, stat, system, environ
+from platform import system as platform_system
 from queue import SimpleQueue
 from random import choice
+from signal import signal, SIGINT
 from string import ascii_lowercase, hexdigits
 from sys import argv, executable, getsizeof
-from threading import RLock, Thread
+from threading import RLock, Thread, main_thread, current_thread
 from time import sleep, time
 
 import simplejson
 from simplejson import JSONDecodeError, dumps, load, loads
 from yaml import safe_load
 
 from thingsboard_gateway.gateway.constant_enums import DeviceActions, Status
 from thingsboard_gateway.gateway.constants import CONNECTED_DEVICES_FILENAME, CONNECTOR_PARAMETER, \
     PERSISTENT_GRPC_CONNECTORS_KEY_FILENAME
+from thingsboard_gateway.gateway.device_filter import DeviceFilter
+from thingsboard_gateway.gateway.duplicate_detector import DuplicateDetector
+from thingsboard_gateway.gateway.shell.proxy import AutoProxy
 from thingsboard_gateway.gateway.statistics_service import StatisticsService
 from thingsboard_gateway.gateway.tb_client import TBClient
 from thingsboard_gateway.storage.file.file_event_storage import FileEventStorage
 from thingsboard_gateway.storage.memory.memory_event_storage import MemoryEventStorage
 from thingsboard_gateway.storage.sqlite.sqlite_event_storage import SQLiteEventStorage
 from thingsboard_gateway.tb_utility.tb_gateway_remote_configurator import RemoteConfigurator
 from thingsboard_gateway.tb_utility.tb_loader import TBModuleLoader
@@ -76,14 +80,18 @@
 }
 
 DEFAULT_STATISTIC = {
     'enable': True,
     'statsSendPeriodInSeconds': 3600
 }
 
+DEFAULT_DEVICE_FILTER = {
+    'enable': False
+}
+
 SECURITY_VAR = ('accessToken', 'caCert', 'privateKey', 'cert')
 
 
 def load_file(path_to_file):
     content = None
     with open(path_to_file, 'r') as target_file:
         content = load(target_file)
@@ -111,17 +119,43 @@
                 converted_env_variables['security'][key] = value
             else:
                 converted_env_variables[key] = value
 
     return converted_env_variables
 
 
+class GatewayManager(multiprocessing.managers.BaseManager):
+    def __init__(self, address=None, authkey=b''):
+        super().__init__(address=address, authkey=authkey)
+        self.gateway = None
+
+    def has_gateway(self):
+        return self.gateway is not None
+
+    def add_gateway(self, gateway):
+        self.gateway = gateway
+
+    def shutdown(self) -> None:
+        pass
+
+
 class TBGatewayService:
+    EXPOSED_GETTERS = [
+        'ping',
+        'get_status',
+        'get_storage_name',
+        'get_storage_events_count',
+        'get_available_connectors',
+        'get_connector_status',
+        'get_connector_config'
+    ]
+
     def __init__(self, config_file=None):
-        signal(SIGINT, lambda _, __: self.__stop_gateway())
+        if current_thread() is main_thread():
+            signal(SIGINT, lambda _, __: self.__stop_gateway())
 
         self.stopped = False
         self.__lock = RLock()
         self.async_device_actions = {
             DeviceActions.CONNECT: self.add_device,
             DeviceActions.DISCONNECT: self.del_device
         }
@@ -168,15 +202,14 @@
         self.tb_client.connect()
         self.subscribe_to_required_topics()
         self.__subscribed_to_rpc_topics = True
         if logging_error is not None:
             self.tb_client.client.send_telemetry({"ts": time() * 1000, "values": {
                 "LOGS": "Logging loading exception, logs.conf is wrong: %s" % (str(logging_error),)}})
             TBLoggerHandler.set_default_handler()
-        self.counter = 0
         self.__rpc_reply_sent = False
         global main_handler
         self.main_handler = main_handler
         self.remote_handler = TBLoggerHandler(self)
         self.main_handler.setTarget(self.remote_handler)
         self._default_connectors = DEFAULT_CONNECTORS
         self.__converted_data_queue = SimpleQueue()
@@ -241,38 +274,76 @@
         if self.__statistics['enable']:
             self.__statistics_service = StatisticsService(self.__statistics['statsSendPeriodInSeconds'], self, log,
                                                           config_path=self._config_dir + self.__statistics[
                                                               'configuration'] if self.__statistics.get(
                                                               'configuration') else None)
 
         self._published_events = SimpleQueue()
+
+        self.__min_pack_send_delay_ms = self.__config['thingsboard'].get('minPackSendDelayMS', 200)
+        self.__min_pack_send_delay_ms = self.__min_pack_send_delay_ms / 1000.0
+        self.__min_pack_size_to_send = self.__config['thingsboard'].get('minPackSizeToSend', 50)
+
         self._send_thread = Thread(target=self.__read_data_from_storage, daemon=True,
                                    name="Send data to Thingsboard Thread")
         self._send_thread.start()
-        self.__min_pack_send_delay_ms = self.__config['thingsboard'].get('minPackSendDelayMS', 500) / 1000.0
+
+        self.__device_filter_config = self.__config['thingsboard'].get('deviceFiltering', DEFAULT_DEVICE_FILTER)
+        self.__device_filter = None
+        if self.__device_filter_config['enable']:
+            self.__device_filter = DeviceFilter(config_path=self._config_dir + self.__device_filter_config[
+                'filterFile'] if self.__device_filter_config.get('filterFile') else None)
+
+        self.__duplicate_detector = DuplicateDetector(self.available_connectors)
+
         log.info("Gateway started.")
 
         self._watchers_thread = Thread(target=self._watchers, name='Watchers', daemon=True)
         self._watchers_thread.start()
 
+        if path.exists('/tmp/gateway'):
+            try:
+                # deleting old manager if it was closed incorrectly
+                system('rm -rf /tmp/gateway')
+            except OSError as e:
+                log.exception(e)
+
+        manager_address = '/tmp/gateway'
+        if platform_system() == 'Windows':
+            manager_address = ('127.0.0.1', 9999)
+        self.manager = GatewayManager(address=manager_address, authkey=b'gateway')
+
+        if current_thread() is main_thread():
+            GatewayManager.register('get_gateway', self.get_gateway, proxytype=AutoProxy, exposed=self.EXPOSED_GETTERS,
+                                    create_method=False)
+            self.server = self.manager.get_server()
+            self.server.serve_forever()
+
+    def get_gateway(self):
+        if self.manager.has_gateway():
+            return self.manager.gateway
+        else:
+            self.manager.add_gateway(self)
+            self.manager.register('gateway', lambda: self, proxytype=AutoProxy)
+
     def _watchers(self):
         try:
             gateway_statistic_send = 0
             connectors_configuration_check_time = 0
 
             while not self.stopped:
                 cur_time = time() * 1000
 
                 if not self.tb_client.is_connected() and self.__subscribed_to_rpc_topics:
                     self.__subscribed_to_rpc_topics = False
 
                 if self.tb_client.is_connected() and not self.__subscribed_to_rpc_topics:
                     for device in self.__saved_devices:
                         self.add_device(device, {"connector": self.__saved_devices[device]["connector"]},
-                                        device_type=self.__saved_devices[device]["device_type"])
+                                        device_type=self.__saved_devices[device]["device_type"], reconnect=True)
                     self.subscribe_to_required_topics()
                     self.__subscribed_to_rpc_topics = True
 
                 if self.__scheduled_rpc_calls:
                     for rpc_call_index in range(len(self.__scheduled_rpc_calls)):
                         rpc_call = self.__scheduled_rpc_calls[rpc_call_index]
                         if cur_time > rpc_call[0]:
@@ -310,16 +381,15 @@
                         log.exception(e)
                         break
 
                 if not self.__request_config_after_connect and self.tb_client.is_connected() and not self.tb_client.client.get_subscriptions_in_progress():
                     self.__request_config_after_connect = True
                     self.__check_shared_attributes()
 
-                if cur_time - gateway_statistic_send > self.__statistics[
-                        'statsSendPeriodInSeconds'] * 1000 and self.tb_client.is_connected():
+                if cur_time - gateway_statistic_send > self.__statistics['statsSendPeriodInSeconds'] * 1000 and self.tb_client.is_connected():
                     summary_messages = self.__form_statistics()
                     # with self.__lock:
                     self.tb_client.client.send_telemetry(summary_messages)
                     gateway_statistic_send = time() * 1000
                     # self.__check_shared_attributes()
 
                 if cur_time - connectors_configuration_check_time > self.__config["thingsboard"].get(
@@ -360,14 +430,15 @@
         if self.__grpc_manager is not None:
             self.__grpc_manager.stop()
         self.__close_connectors()
         self._event_storage.stop()
         log.info("The gateway has been stopped.")
         self.tb_client.disconnect()
         self.tb_client.stop()
+        self.manager.shutdown()
 
     def __init_remote_configuration(self, force=False):
         if (self.__config["thingsboard"].get("remoteConfiguration") or force) and self.__remote_configurator is None:
             try:
                 self.__remote_configurator = RemoteConfigurator(self, self.__config)
                 if self.tb_client.is_connected() and not self.tb_client.client.get_subscriptions_in_progress():
                     self.__check_shared_attributes()
@@ -395,14 +466,15 @@
                               ", ".join([attr for attr in client_attributes.keys()]))
         except Exception as e:
             log.exception(e)
 
     def __process_attribute_update(self, content):
         self.__process_remote_logging_update(content.get("RemoteLoggingLevel"))
         self.__process_remote_configuration(content.get("configuration"))
+        self.__process_remote_converter_configuration_update(content)
 
     def __process_attributes_response(self, shared_attributes, client_attributes):
         self.__process_remote_logging_update(shared_attributes.get('RemoteLoggingLevel'))
         self.__process_remote_configuration(shared_attributes.get("configuration"))
 
     def __process_remote_logging_update(self, remote_logging_level):
         if remote_logging_level == 'NONE':
@@ -411,39 +483,65 @@
         elif remote_logging_level is not None:
             if self.remote_handler.current_log_level != remote_logging_level or not self.remote_handler.activated:
                 self.main_handler.setLevel(remote_logging_level)
                 self.remote_handler.activate(remote_logging_level)
                 log.info('Remote logging has being updated. Current logging level is: %s ',
                          remote_logging_level)
 
+    def __process_remote_converter_configuration_update(self, content: dict):
+        try:
+            key = list(content.keys())[0]
+            connector_name, converter_name = key.split(':')
+            log.info('Got remote converter configuration update')
+            if not self.available_connectors.get(connector_name):
+                raise ValueError
+
+            self.available_connectors[connector_name].update_converter_config(converter_name, content[key])
+        except (ValueError, AttributeError) as e:
+            log.error('Remote converter configuration update failed with exception:')
+            log.exception(e)
+        except IndexError:
+            log.debug('Received unknown request with content: %s', content)
+
+    def update_connector_config_file(self, connector_name, config):
+        for connector in self.__config['connectors']:
+            if connector['name'] == connector_name:
+                with open(self._config_dir + connector['configuration'], 'w', encoding='UTF-8') as file:
+                    file.writelines(dumps(config))
+
+                log.info('Updated %s configuration file', connector_name)
+                return
+
     def __process_deleted_gateway_devices(self, deleted_device_name: str):
         log.info("Received deleted gateway device notification: %s", deleted_device_name)
         if deleted_device_name in list(self.__renamed_devices.values()):
             first_device_name = TBUtility.get_dict_key_by_value(self.__renamed_devices, deleted_device_name)
             del self.__renamed_devices[first_device_name]
             deleted_device_name = first_device_name
             log.debug("Current renamed_devices dict: %s", self.__renamed_devices)
         if deleted_device_name in self.__connected_devices:
             del self.__connected_devices[deleted_device_name]
             log.debug("Device %s - was removed from __connected_devices", deleted_device_name)
         if deleted_device_name in self.__saved_devices:
             del self.__saved_devices[deleted_device_name]
             log.debug("Device %s - was removed from __saved_devices", deleted_device_name)
+        self.__duplicate_detector.delete_device(deleted_device_name)
         self.__save_persistent_devices()
         self.__load_persistent_devices()
 
     def __process_renamed_gateway_devices(self, renamed_device: dict):
         if self.__config.get('handleDeviceRenaming', True):
             log.info("Received renamed gateway device notification: %s", renamed_device)
             old_device_name, new_device_name = renamed_device.popitem()
             if old_device_name in list(self.__renamed_devices.values()):
                 device_name_key = TBUtility.get_dict_key_by_value(self.__renamed_devices, old_device_name)
             else:
                 device_name_key = new_device_name
             self.__renamed_devices[device_name_key] = new_device_name
+            self.__duplicate_detector.rename_device(old_device_name, new_device_name)
 
             self.__save_persistent_devices()
             self.__load_persistent_devices()
             log.debug("Current renamed_devices dict: %s", self.__renamed_devices)
         else:
             log.debug("Received renamed device notification %r, but device renaming handle is disabled", renamed_device)
 
@@ -471,32 +569,30 @@
         if shared_keys is not None:
             self.tb_client.client.gw_request_shared_attributes(device_name, shared_keys, callback)
 
     def __check_shared_attributes(self):
         self.tb_client.client.request_attributes(callback=self._attributes_parse)
 
     def __register_connector(self, session_id, connector_key):
-        if self.__grpc_connectors.get(connector_key) is not None and self.__grpc_connectors[connector_key][
-                'name'] not in self.available_connectors:
+        if self.__grpc_connectors.get(connector_key) is not None and self.__grpc_connectors[connector_key]['name'] not in self.available_connectors:
             target_connector = self.__grpc_connectors.get(connector_key)
             connector = GrpcConnector(self, target_connector['config'], self.__grpc_manager, session_id)
             connector.setName(target_connector['name'])
             self.available_connectors[connector.get_name()] = connector
             self.__grpc_manager.registration_finished(Status.SUCCESS, session_id, target_connector)
             log.info("GRPC connector with key %s registered with name %s", connector_key, connector.get_name())
         elif self.__grpc_connectors.get(connector_key) is not None:
             self.__grpc_manager.registration_finished(Status.FAILURE, session_id, None)
             log.error("GRPC connector with key: %s - already registered!", connector_key)
         else:
             self.__grpc_manager.registration_finished(Status.NOT_FOUND, session_id, None)
             log.error("GRPC configuration for connector with key: %s - not found", connector_key)
 
     def __unregister_connector(self, session_id, connector_key):
-        if self.__grpc_connectors.get(connector_key) is not None and self.__grpc_connectors[connector_key][
-                'name'] in self.available_connectors:
+        if self.__grpc_connectors.get(connector_key) is not None and self.__grpc_connectors[connector_key]['name'] in self.available_connectors:
             connector_name = self.__grpc_connectors[connector_key]['name']
             target_connector: GrpcConnector = self.available_connectors.pop(connector_name)
             self.__grpc_manager.unregister(Status.SUCCESS, session_id, target_connector)
             log.info("GRPC connector with key %s and name %s - unregistered", connector_key,
                      target_connector.get_name())
         elif self.__grpc_connectors.get(connector_key) is not None:
             self.__grpc_manager.unregister(Status.NOT_FOUND, session_id, None)
@@ -596,15 +692,15 @@
                             connector = None
                             try:
                                 if connector_config["config"][config] is not None:
                                     connector = self._implemented_connectors[connector_type](self,
                                                                                              connector_config["config"][
                                                                                                  config],
                                                                                              connector_type)
-                                    connector.setName(connector_config["name"])
+                                    connector.name = connector_config["name"]
                                     self.available_connectors[connector.get_name()] = connector
                                     connector.open()
                                 else:
                                     log.info("Config not found for %s", connector_type)
                             except Exception as e:
                                 log.exception(e)
                                 if connector is not None:
@@ -619,15 +715,16 @@
                                 **connector_config,
                                 'gateway': {
                                     'host': 'localhost',
                                     'port': self.__config['grpc']['serverPort']
                                 }
                             })
 
-                            thread = Thread(target=self._run_connector, args=(connector_abs_path, connector_config_json,),
+                            thread = Thread(target=self._run_connector,
+                                            args=(connector_abs_path, connector_config_json,),
                                             daemon=True, name='Separate DRPC Connector')
                             thread.start()
 
     def _run_connector(self, connector_abs_path, connector_config_json):
         subprocess.run(['python3', connector_abs_path, connector_config_json, self._config_dir],
                        check=True,
                        universal_newlines=True)
@@ -644,16 +741,28 @@
         if configuration_changed:
             self.__close_connectors()
             self._load_connectors()
             self._connect_with_connectors()
 
     def send_to_storage(self, connector_name, data):
         try:
-            self.__converted_data_queue.put((connector_name, data), True, 100)
-            return Status.SUCCESS
+            device_valid = True
+            if self.__device_filter:
+                device_valid = self.__device_filter.validate_device(connector_name, data)
+
+            if not device_valid:
+                log.warning('Device %s forbidden', data['deviceName'])
+                return Status.FORBIDDEN_DEVICE
+
+            filtered_data = self.__duplicate_detector.filter_data(connector_name, data)
+            if filtered_data:
+                self.__converted_data_queue.put((connector_name, filtered_data), True, 100)
+                return Status.SUCCESS
+            else:
+                return Status.NO_NEW_DATA
         except Exception as e:
             log.exception("Cannot put converted data!", e)
             return Status.FAILURE
 
     def __send_to_storage(self):
         while not self.stopped:
             try:
@@ -785,27 +894,26 @@
             for device in devices_data_in_event_pack:
                 devices_data_in_event_pack[device]["telemetry"] = []
                 devices_data_in_event_pack[device]["attributes"] = {}
 
     def __read_data_from_storage(self):
         devices_data_in_event_pack = {}
         log.debug("Send data Thread has been started successfully.")
+        log.debug("Maximal size of the client message queue is: %r", self.tb_client.client._client._max_queued_messages)
 
         while not self.stopped:
             try:
                 if self.tb_client.is_connected():
-                    size = self.__get_data_size(devices_data_in_event_pack) - 2
                     events = []
 
                     if self.__remote_configurator is None or not self.__remote_configurator.in_process:
                         events = self._event_storage.get_event_pack()
 
                     if events:
                         for event in events:
-                            self.counter += 1
                             try:
                                 current_event = loads(event)
                             except Exception as e:
                                 log.exception(e)
                                 continue
 
                             if not devices_data_in_event_pack.get(current_event["deviceName"]):
@@ -831,52 +939,53 @@
                                     self.check_size(devices_data_in_event_pack)
                                     devices_data_in_event_pack[current_event["deviceName"]]["attributes"].update(
                                         current_event["attributes"].items())
                         if devices_data_in_event_pack:
                             if not self.tb_client.is_connected():
                                 continue
                             while self.__rpc_reply_sent:
-                                sleep(.2)
+                                sleep(.01)
                             self.__send_data(devices_data_in_event_pack)
-                            sleep(self.__min_pack_send_delay_ms)
 
                         if self.tb_client.is_connected() and (
                                 self.__remote_configurator is None or not self.__remote_configurator.in_process):
                             success = True
                             while not self._published_events.empty():
                                 if (self.__remote_configurator is not None and self.__remote_configurator.in_process) or \
                                         not self.tb_client.is_connected() or \
                                         self._published_events.empty() or \
                                         self.__rpc_reply_sent:
                                     success = False
                                     break
-                                event = self._published_events.get(False, 10)
-                                try:
-                                    if self.tb_client.is_connected() and (
-                                            self.__remote_configurator is None or not self.__remote_configurator.in_process):
-                                        if self.tb_client.client.quality_of_service == 1:
-                                            success = event.get() == event.TB_ERR_SUCCESS
+
+                                events = [self._published_events.get(False, 10) for _ in
+                                          range(min(self.__min_pack_size_to_send, self._published_events.qsize()))]
+                                for event in events:
+                                    try:
+                                        if self.tb_client.is_connected() and (
+                                                self.__remote_configurator is None or not self.__remote_configurator.in_process):
+                                            if self.tb_client.client.quality_of_service == 1:
+                                                success = event.get() == event.TB_ERR_SUCCESS
+                                            else:
+                                                success = True
                                         else:
-                                            success = True
-                                    else:
-                                        break
-                                except Exception as e:
-                                    log.exception(e)
-                                    success = False
-                                sleep(0.2)
+                                            break
+                                    except Exception as e:
+                                        log.exception(e)
+                                        success = False
                             if success and self.tb_client.is_connected():
                                 self._event_storage.event_pack_processing_done()
                                 del devices_data_in_event_pack
                                 devices_data_in_event_pack = {}
                         else:
                             continue
                     else:
-                        sleep(0.2)
+                        sleep(self.__min_pack_send_delay_ms)
                 else:
-                    sleep(0.2)
+                    sleep(1)
             except Exception as e:
                 log.exception(e)
                 sleep(1)
 
     @StatisticsService.CollectAllSentTBBytesStatistics(start_stat_type='allBytesSentToTB')
     def __send_data(self, devices_data_in_event_pack):
         try:
@@ -1016,15 +1125,15 @@
 
     def rpc_with_reply_processing(self, topic, content):
         req_id = self.__rpc_requests_in_progress[topic][0]["data"]["id"]
         device = self.__rpc_requests_in_progress[topic][0]["device"]
         log.info("Outgoing RPC. Device: %s, ID: %d", device, req_id)
         self.send_rpc_reply(device, req_id, content)
 
-    @StatisticsService.CollectRPCReplyStatistics(start_stat_type='all_bytes_sent')
+    @StatisticsService.CollectRPCReplyStatistics(start_stat_type='allBytesSentToTB')
     def send_rpc_reply(self, device=None, req_id=None, content=None, success_sent=None, wait_for_publish=None,
                        quality_of_service=0):
         self.__rpc_processing_queue.put((device, req_id, content, success_sent, wait_for_publish, quality_of_service))
 
     def __send_rpc_reply_processing(self):
         while not self.stopped:
             if not self.__rpc_processing_queue.empty():
@@ -1073,39 +1182,38 @@
             except Exception as e:
                 log.exception(e)
         else:
             self._attributes_parse(content)
 
     def __form_statistics(self):
         summary_messages = {"eventsProduced": 0, "eventsSent": 0}
-        telemetry = {}
         for connector in self.available_connectors:
             connector_camel_case = connector.lower().replace(' ', '')
-            telemetry[(connector_camel_case + ' EventsProduced').replace(' ', '')] = \
-                self.available_connectors[connector].statistics['MessagesReceived']
-            self.available_connectors[connector].statistics['MessagesReceived'] = 0
-            telemetry[(connector_camel_case + ' EventsSent').replace(' ', '')] = \
-                self.available_connectors[connector].statistics['MessagesSent']
-            self.available_connectors[connector].statistics['MessagesSent'] = 0
+            telemetry = {
+                (connector_camel_case + ' EventsProduced').replace(' ', ''): self.available_connectors[
+                    connector].statistics.get('MessagesReceived', 0),
+                (connector_camel_case + ' EventsSent').replace(' ', ''): self.available_connectors[
+                    connector].statistics.get('MessagesSent', 0)
+            }
             summary_messages['eventsProduced'] += telemetry[
                 str(connector_camel_case + ' EventsProduced').replace(' ', '')]
             summary_messages['eventsSent'] += telemetry[
                 str(connector_camel_case + ' EventsSent').replace(' ', '')]
-            summary_messages.update(**telemetry)
+            summary_messages.update(telemetry)
         return summary_messages
 
     def add_device_async(self, data):
         if data['deviceName'] not in self.__saved_devices:
             self.__async_device_actions_queue.put((DeviceActions.CONNECT, data))
             return Status.SUCCESS
         else:
             return Status.FAILURE
 
-    def add_device(self, device_name, content, device_type=None):
-        if device_name not in self.__saved_devices:
+    def add_device(self, device_name, content, device_type=None, reconnect=False):
+        if device_name not in self.__saved_devices or reconnect:
             device_type = device_type if device_type is not None else 'default'
             self.__connected_devices[device_name] = {**content, "device_type": device_type}
             self.__saved_devices[device_name] = {**content, "device_type": device_type}
             self.__save_persistent_devices()
             self.tb_client.client.gw_connect_device(device_name, device_type)
 
     def update_device(self, device_name, event, content):
@@ -1126,15 +1234,15 @@
         self.__saved_devices.pop(device_name)
         self.__save_persistent_devices()
 
     def get_devices(self, connector_name: str = None):
         return self.__connected_devices if connector_name is None else {
             device_name: self.__connected_devices[device_name]["device_type"] for device_name in
             self.__connected_devices.keys() if self.__connected_devices[device_name].get("connector") is not None and
-            self.__connected_devices[device_name]["connector"].get_name() == connector_name}
+                                               self.__connected_devices[device_name]["connector"].get_name() == connector_name}
 
     def __process_async_device_actions(self):
         while not self.stopped:
             if not self.__async_device_actions_queue.empty():
                 action, data = self.__async_device_actions_queue.get()
                 if action == DeviceActions.CONNECT:
                     self.add_device(data['deviceName'], {CONNECTOR_PARAMETER: self.available_connectors[data['name']]},
@@ -1240,11 +1348,45 @@
 
                 log.debug('Delete device %s for the reason of idle time > %s.',
                           device_name,
                           disconnect_device_after_idle)
 
             sleep(check_devices_idle_every_sec)
 
+    # GETTERS --------------------
+    def ping(self):
+        return self.name
+
+    # ----------------------------
+    # Storage --------------------
+    def get_storage_name(self):
+        return self._event_storage.__class__.__name__
+
+    def get_storage_events_count(self):
+        return self._event_storage.len()
+
+    # Connectors -----------------
+    def get_available_connectors(self):
+        return {num + 1: name for (num, name) in enumerate(self.available_connectors)}
+
+    def get_connector_status(self, name):
+        try:
+            connector = self.available_connectors[name]
+            return {'connected': connector.is_connected()}
+        except KeyError:
+            return f'Connector {name} not found!'
+
+    def get_connector_config(self, name):
+        try:
+            connector = self.available_connectors[name]
+            return connector.get_config()
+        except KeyError:
+            return f'Connector {name} not found!'
+
+    # Gateway ----------------------
+    def get_status(self):
+        return {'connected': self.tb_client.is_connected()}
+
 
 if __name__ == '__main__':
     TBGatewayService(
         path.dirname(path.dirname(path.abspath(__file__))) + '/config/tb_gateway.yaml'.replace('/', path.sep))
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/storage/__init__.py` & `thingsboard-gateway-3.3/thingsboard_gateway/storage/__init__.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/storage/event_storage.py` & `thingsboard-gateway-3.3/thingsboard_gateway/storage/event_storage.py`

 * *Files 7% similar despite different names*

```diff
@@ -34,7 +34,11 @@
         # Indicates that events from previous "get_event_pack" may be cleared
         pass
 
     @abstractmethod
     def stop(self):
         # Stop the storage processing
         pass
+
+    @abstractmethod
+    def len(self):
+        pass
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/storage/file/event_storage_files.py` & `thingsboard-gateway-3.3/thingsboard_gateway/storage/file/event_storage_files.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/storage/file/event_storage_reader.py` & `thingsboard-gateway-3.3/thingsboard_gateway/storage/file/event_storage_reader.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/storage/file/event_storage_reader_pointer.py` & `thingsboard-gateway-3.3/thingsboard_gateway/storage/file/event_storage_reader_pointer.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/storage/file/event_storage_writer.py` & `thingsboard-gateway-3.3/thingsboard_gateway/storage/file/event_storage_writer.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/storage/file/file_event_storage.py` & `thingsboard-gateway-3.3/thingsboard_gateway/storage/file/file_event_storage.py`

 * *Files 2% similar despite different names*

```diff
@@ -97,7 +97,9 @@
             return prefix + filename + '.txt'
         except IOError as e:
             log.error("Failed to create a new file! Error: %s", e)
 
     def stop(self):
         self.__stopped = True
 
+    def len(self):
+        return len(self.__writer.files.data_files)
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/storage/file/file_event_storage_settings.py` & `thingsboard-gateway-3.3/thingsboard_gateway/storage/file/file_event_storage_settings.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/storage/memory/memory_event_storage.py` & `thingsboard-gateway-3.3/thingsboard_gateway/storage/memory/memory_event_storage.py`

 * *Files 6% similar despite different names*

```diff
@@ -49,7 +49,10 @@
         return self.__event_pack
 
     def event_pack_processing_done(self):
         self.__event_pack = []
 
     def stop(self):
         self.__stopped = True
+
+    def len(self):
+        return self.__events_queue.qsize()
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/storage/sqlite/database.py` & `thingsboard-gateway-3.3/thingsboard_gateway/storage/sqlite/database.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/storage/sqlite/database_action_type.py` & `thingsboard-gateway-3.3/thingsboard_gateway/storage/sqlite/database_action_type.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/storage/sqlite/database_connector.py` & `thingsboard-gateway-3.3/thingsboard_gateway/storage/sqlite/database_connector.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/storage/sqlite/database_request.py` & `thingsboard-gateway-3.3/thingsboard_gateway/storage/sqlite/database_request.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/storage/sqlite/sqlite_event_storage.py` & `thingsboard-gateway-3.3/thingsboard_gateway/storage/sqlite/sqlite_event_storage.py`

 * *Files 6% similar despite different names*

```diff
@@ -71,18 +71,20 @@
         try:
             if not self.stopped:
                 _type = DatabaseActionType.WRITE_DATA_STORAGE
                 request = DatabaseRequest(_type, message)
 
                 log.info("Sending data to storage")
                 self.processQueue.put(request)
-                self.db.process()
                 return True
             else:
                 return False
         except Exception as e:
             log.exception(e)
 
     def stop(self):
         self.stopped = True
         self.db.__stopped = True
         self.db.closeDB()
+
+    def len(self):
+        return self.processQueue.qsize()
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/tb_gateway.py` & `thingsboard-gateway-3.3/thingsboard_gateway/tb_gateway.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/tb_utility/__init__.py` & `thingsboard-gateway-3.3/thingsboard_gateway/tb_utility/__init__.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/tb_utility/tb_gateway_remote_configurator.py` & `thingsboard-gateway-3.3/thingsboard_gateway/tb_utility/tb_gateway_remote_configurator.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/tb_utility/tb_loader.py` & `thingsboard-gateway-3.3/thingsboard_gateway/tb_utility/tb_loader.py`

 * *Files 2% similar despite different names*

```diff
@@ -49,15 +49,15 @@
         if TBModuleLoader.LOADED_CONNECTORS.get(buffered_module_name) is not None:
             return TBModuleLoader.LOADED_CONNECTORS[buffered_module_name]
         try:
             for current_path in TBModuleLoader.PATHS:
                 current_extension_path = current_path + path.sep + extension_type
                 if path.exists(current_extension_path):
                     for file in listdir(current_extension_path):
-                        if not file.startswith('__') and file.endswith('.py'):
+                        if not file.startswith('__') and (file.endswith('.py') or file.endswith('.pyc')):
                             try:
                                 module_spec = spec_from_file_location(module_name, current_extension_path + path.sep + file)
                                 log.debug(module_spec)
 
                                 if module_spec is None:
                                     continue
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/tb_utility/tb_logger.py` & `thingsboard-gateway-3.3/thingsboard_gateway/tb_utility/tb_logger.py`

 * *Files 6% similar despite different names*

```diff
@@ -77,15 +77,14 @@
             handler = logging.StreamHandler(stdout)
             handler.setFormatter(logging.Formatter('[STREAM ONLY] %(asctime)s - %(levelname)s - [%(filename)s] - %(module)s - %(lineno)d - %(message)s'))
             logger.addHandler(handler)
 
 
 class TimedRotatingFileHandler(logging.handlers.TimedRotatingFileHandler):
     def __init__(self, filename, when='h', interval=1, backupCount=0,
-                 encoding=None, delay=False, utc=False, atTime=None,
-                 errors=None):
+                 encoding=None, delay=False, utc=False):
         config_path = environ.get('logs')
         if config_path:
             filename = config_path + '/' + filename.split('/')[-1]
 
         super().__init__(filename, when=when, interval=interval, backupCount=backupCount,
-                         encoding=encoding, delay=delay, utc=utc, atTime=atTime, errors=errors)
+                         encoding=encoding, delay=delay, utc=utc)
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/tb_utility/tb_remote_shell.py` & `thingsboard-gateway-3.3/thingsboard_gateway/tb_utility/tb_remote_shell.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/tb_utility/tb_updater.py` & `thingsboard-gateway-3.3/thingsboard_gateway/tb_utility/tb_updater.py`

 * *Files identical despite different names*

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway/tb_utility/tb_utility.py` & `thingsboard-gateway-3.3/thingsboard_gateway/tb_utility/tb_utility.py`

 * *Files 6% similar despite different names*

```diff
@@ -12,14 +12,15 @@
 #     See the License for the specific language governing permissions and
 #     limitations under the License.
 import datetime
 from logging import getLogger
 from re import search, findall
 
 from cryptography import x509
+from cryptography.x509.oid import NameOID
 from cryptography.hazmat.primitives import hashes
 from cryptography.hazmat.primitives.asymmetric import ec
 from cryptography.hazmat.primitives import serialization
 from jsonpath_rw import parse
 from simplejson import JSONDecodeError, dumps, loads
 
 log = getLogger("service")
@@ -172,20 +173,22 @@
         return text
 
     @staticmethod
     def get_dict_key_by_value(dictionary: dict, value):
         return list(dictionary.values())[list(dictionary.values()).index(value)]
 
     @staticmethod
-    def generate_certificate(old_certificate_path, old_key_path, old_certificate):
+    def generate_certificate(old_certificate_path, old_key_path, old_certificate=None):
         key = ec.generate_private_key(ec.SECP256R1())
         public_key = key.public_key()
         builder = x509.CertificateBuilder()
-        builder = builder.subject_name(old_certificate.subject)
-        builder = builder.issuer_name(old_certificate.issuer)
+        builder = builder.subject_name(old_certificate.subject if old_certificate else x509.Name(
+            [x509.NameAttribute(NameOID.COMMON_NAME, u'localhost'), ]))
+        builder = builder.issuer_name(old_certificate.issuer if old_certificate else x509.Name(
+            [x509.NameAttribute(NameOID.COMMON_NAME, u'localhost'), ]))
         builder = builder.not_valid_before(datetime.datetime.today() - datetime.timedelta(days=1))
         builder = builder.not_valid_after(datetime.datetime.today() + (datetime.timedelta(1, 0, 0) * 365))
         builder = builder.serial_number(x509.random_serial_number())
         builder = builder.public_key(public_key)
         certificate = builder.sign(private_key=key, algorithm=hashes.SHA256())
 
         cert = certificate.public_bytes(serialization.Encoding.PEM)
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway.egg-info/PKG-INFO` & `thingsboard-gateway-3.3/thingsboard_gateway.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,16 +1,16 @@
 Metadata-Version: 2.1
 Name: thingsboard-gateway
-Version: 3.2
+Version: 3.3
 Summary: Thingsboard Gateway for IoT devices.
 Home-page: https://github.com/thingsboard/thingsboard-gateway
 Author: ThingsBoard
 Author-email: info@thingsboard.io
 License: Apache Software License (Apache Software License 2.0)
-Download-URL: https://github.com/thingsboard/thingsboard-gateway/archive/3.2.tar.gz
+Download-URL: https://github.com/thingsboard/thingsboard-gateway/archive/3.3.tar.gz
 Platform: UNKNOWN
 Requires-Python: >=3.7
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 # ThingsBoard IoT Gateway
```

### Comparing `thingsboard-gateway-3.2/thingsboard_gateway.egg-info/SOURCES.txt` & `thingsboard-gateway-3.3/thingsboard_gateway.egg-info/SOURCES.txt`

 * *Files 2% similar despite different names*

```diff
@@ -1,39 +1,41 @@
 LICENSE
 MANIFEST.in
 README.md
 setup.py
-thingsboard_gateway/__init__.py
 thingsboard_gateway/tb_gateway.py
 thingsboard_gateway.egg-info/PKG-INFO
 thingsboard_gateway.egg-info/SOURCES.txt
 thingsboard_gateway.egg-info/dependency_links.txt
 thingsboard_gateway.egg-info/entry_points.txt
 thingsboard_gateway.egg-info/requires.txt
 thingsboard_gateway.egg-info/top_level.txt
 thingsboard_gateway/config/bacnet.json
 thingsboard_gateway/config/ble.json
 thingsboard_gateway/config/can.json
 thingsboard_gateway/config/custom_serial.json
 thingsboard_gateway/config/ftp.json
 thingsboard_gateway/config/grpc_connector_1.json
+thingsboard_gateway/config/list.json
 thingsboard_gateway/config/logs.conf
 thingsboard_gateway/config/modbus.json
 thingsboard_gateway/config/modbus_serial.json
 thingsboard_gateway/config/mqtt.json
 thingsboard_gateway/config/ocpp.json
 thingsboard_gateway/config/odbc.json
 thingsboard_gateway/config/opcua.json
 thingsboard_gateway/config/request.json
 thingsboard_gateway/config/rest.json
 thingsboard_gateway/config/snmp.json
 thingsboard_gateway/config/socket.json
-thingsboard_gateway/config/statistics.json
 thingsboard_gateway/config/tb_gateway.yaml
 thingsboard_gateway/config/xmpp.json
+thingsboard_gateway/config/statistics/statistics_linux.json
+thingsboard_gateway/config/statistics/statistics_macos.json
+thingsboard_gateway/config/statistics/statistics_windows.json
 thingsboard_gateway/connectors/__init__.py
 thingsboard_gateway/connectors/connector.py
 thingsboard_gateway/connectors/converter.py
 thingsboard_gateway/connectors/bacnet/__init__.py
 thingsboard_gateway/connectors/bacnet/bacnet_connector.py
 thingsboard_gateway/connectors/bacnet/bacnet_converter.py
 thingsboard_gateway/connectors/bacnet/bacnet_downlink_converter.py
@@ -43,14 +45,15 @@
 thingsboard_gateway/connectors/bacnet/bacnet_utilities/tb_gateway_bacnet_device.py
 thingsboard_gateway/connectors/ble/__init__.py
 thingsboard_gateway/connectors/ble/ble_connector.py
 thingsboard_gateway/connectors/ble/ble_uplink_converter.py
 thingsboard_gateway/connectors/ble/bytes_ble_uplink_converter.py
 thingsboard_gateway/connectors/ble/device.py
 thingsboard_gateway/connectors/ble/error_handler.py
+thingsboard_gateway/connectors/ble/hex_bytes_ble_uplink_converter.py
 thingsboard_gateway/connectors/can/__init__.py
 thingsboard_gateway/connectors/can/bytes_can_downlink_converter.py
 thingsboard_gateway/connectors/can/bytes_can_uplink_converter.py
 thingsboard_gateway/connectors/can/can_connector.py
 thingsboard_gateway/connectors/can/can_converter.py
 thingsboard_gateway/connectors/ftp/__init__.py
 thingsboard_gateway/connectors/ftp/file.py
@@ -136,27 +139,32 @@
 thingsboard_gateway/extensions/snmp/__init__.py
 thingsboard_gateway/extensions/socket/__init__.py
 thingsboard_gateway/extensions/xmpp/__init__.py
 thingsboard_gateway/gateway/__init__.py
 thingsboard_gateway/gateway/configuration_wizard.py
 thingsboard_gateway/gateway/constant_enums.py
 thingsboard_gateway/gateway/constants.py
+thingsboard_gateway/gateway/device_filter.py
+thingsboard_gateway/gateway/duplicate_detector.py
 thingsboard_gateway/gateway/hot_reloader.py
 thingsboard_gateway/gateway/statistics_service.py
 thingsboard_gateway/gateway/tb_client.py
 thingsboard_gateway/gateway/tb_gateway_service.py
 thingsboard_gateway/gateway/grpc_service/__init__.py
 thingsboard_gateway/gateway/grpc_service/grpc_connector.py
 thingsboard_gateway/gateway/grpc_service/grpc_downlink_converter.py
 thingsboard_gateway/gateway/grpc_service/grpc_uplink_converter.py
 thingsboard_gateway/gateway/grpc_service/tb_grpc_manager.py
 thingsboard_gateway/gateway/grpc_service/tb_grpc_server.py
 thingsboard_gateway/gateway/proto/__init__.py
 thingsboard_gateway/gateway/proto/messages_pb2.py
 thingsboard_gateway/gateway/proto/messages_pb2_grpc.py
+thingsboard_gateway/gateway/shell/__init__.py
+thingsboard_gateway/gateway/shell/proxy.py
+thingsboard_gateway/gateway/shell/shell.py
 thingsboard_gateway/storage/__init__.py
 thingsboard_gateway/storage/event_storage.py
 thingsboard_gateway/storage/file/__init__.py
 thingsboard_gateway/storage/file/event_storage_files.py
 thingsboard_gateway/storage/file/event_storage_reader.py
 thingsboard_gateway/storage/file/event_storage_reader_pointer.py
 thingsboard_gateway/storage/file/event_storage_writer.py
```

