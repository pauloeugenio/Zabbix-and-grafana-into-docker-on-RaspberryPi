# Zabbix com Docker Compose no Raspberry Pi-2

O arquivo docker-compose.yml que disponibilizamos em nosso Github, foi configurado de forma que o Docker crie 4 containers: zabbix-server, zabbix-frontend, grafana e Postgress. Foram utilizadas as imagens oficiais do Zabbix, do Grafana e do Postgress. Os links para consulta estão no final deste artigo. 

Ao executar o comando docker-compose up, o Docker irá subir de forma automática os containers do Zabbix, do Grafana e do Postgress. Além disso, o Zabbix já estará conectado ao banco de dados Postgress e o Grafana já estará com o plugin do Zabbix instalado.

Executar o seguinte comando na pasta que esta localizado o arquivo docker-compose.yml para suber os containers:

docker-compose up -d
