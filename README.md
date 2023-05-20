# Bigdata stack on Docker
## Requirements: 
docker-compose

## Set up:
  go to **./docker-files**

  then run:
  
  ```bash
	docker-compose up
  ```

## List of services 
**Only list services with GUI, see docker-compose.yml file for details about all services and their versions.**

Service|URL (only list GUIs)|Notes|
| :---:   | :---: | :---: |
namenode|localhost:50070||
datanode|localhost:50075||
hive|localhost:10002||
hue|localhost:8989|Used as GUI for HIVE|
jupyter lab|localhost:8888|Notebooks|
spark master|localhost:8080|Kill jobs here :)|
superset|localhost:8089|Dashboards|





