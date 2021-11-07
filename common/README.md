You'll find here all the common libraries and files used by the Tasmota projects of this repository.

  * **xdrv_50_filesystem_cfg_csv.ino** : Extension of LittleFS manager to es usefull function to handle **INI** configuration files and **CSV** data files
  * **xdrv_94_ip_address.ino** : Add fixed IP address management with GUI
  * **xdrv_95_timezone.ino** : Add timezone management with GUI
  * **xdrv_96_ftp_server.ino** : Simple embedded FTP server to easily access LittleFS filesystem in read/write. Needs **FTPClientServer** installed in **lib/default**
  * **xdrv_97_tcp_server.ino** : A very simple TCP server to be used to serve a realtime stream

  * **esp32_partition_app1441k_spiffs1245.csv** : partition mapping to maximize ESP32 LittleFS partition size