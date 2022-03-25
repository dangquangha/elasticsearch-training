<h1>Elasticsearch training</h1>

To install <b>Elasticsearh</b> and <b>Kibana</b>, you need follow these steps

```
git clone https://github.com/dangquangha/elasticsearch-training.git
```
```
cd elasticsearch-training
```
In <b>docker-compose.yml</b> you need change path to folder data (is path in your system to folder data in this repo)
```
volumes:
  esdata:
    driver_opts:
      device: [...]/data
      o: bind
      type: none
```
```
docker-compose up
```
Then you access <a href="http://localhost:5601/">Kibana</a> to start training
