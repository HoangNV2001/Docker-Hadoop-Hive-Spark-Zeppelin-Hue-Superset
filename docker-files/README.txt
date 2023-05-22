Set up:
  go to ./docker-files
  then run:
	docker-compose up

*NOTE: The Resource manager will restart a few times. Wait for a minute for setting up. 
---------------------------------------------------------------------------------

Service		URL (only list GUIs)			Notes
namenode		localhost:50070
datanode		localhost:50075
hive			localhost:10002
hue			localhost:8989				Input data (cả structured và unstructured) 
jupyter lab		localhost:8888				Notebooks
spark master	localhost:8080				Kill jobs here :)
superset		localhost:8089				Dashboards

---------------------------------------------------------------------------------

Upload data qua Hue: 

Chọn Dropdown ở "Query"

- Tạo bảng & insert data thủ công: Chọn "Hive"
- Import file lên thẳng HDFS: Chọn "Distcp"




