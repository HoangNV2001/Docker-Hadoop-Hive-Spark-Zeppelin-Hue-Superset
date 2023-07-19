# Bigdata stack on Docker
## Requirements
docker-compose

## Set up
### For Windows


	$git clone https://github.com/HoangNV2001/Docker-Hadoop-Hive-Spark-JupyterLab-Hue-Superset --config core.autocrlf=input
 
 	$cd ./Docker-Hadoop-Hive-Spark-JupyterLab-Hue-Superset/docker-files
  
  	$docker-compose up --no-start

	$docker-compose start database

	$docker-compose up -d

**Note:** 
* **Use** `--config core.autocrlf=input` **on cloning to handle Unix line endings**
* **Start database before running** `docker-compose up`

## List of services 
**Only list services with GUI, see docker-compose.yml file for details about all services and their versions.**

Service|URL (only list GUIs)|Notes|
| :---:   | :---: | :---: |
namenode|localhost:9870||
datanode|localhost:9864||
hive|localhost:10002||
hue|localhost:8888||
zeppelin|localhost:8090||
spark master|localhost:8080|2 workers - 2 cores & 2GB ram each.|
superset|localhost:8008|username:admin - password:admin|




