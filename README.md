# Bigdata stack on Docker
## Requirements: 
docker-compose

## Set up:
### For Windows:


	git clone https://github.com/HoangNV2001/Docker-Hadoop-Hive-Spark-JupyterLab-Hue-Superset --config core.autocrlf=input
 
 	cd ./Docker-Hadoop-Hive-Spark-JupyterLab-Hue-Superset/docker-files
  
  	docker-compose up



## List of services 
**Only list services with GUI, see docker-compose.yml file for details about all services and their versions.**

Service|URL (only list GUIs)|Notes|
| :---:   | :---: | :---: |
namenode|localhost:50070||
datanode|localhost:50075||
hive|localhost:10002||
hue|localhost:8989||
jupyter lab|localhost:8888||
spark master|localhost:8080|default: 2 workers, 512MB ram each.|
superset|localhost:8089|username:admin - password:admin|




