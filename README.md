# groovy-web-gradle-spring-jsp-filebeat-elk-multi-node-simple

## Description
A jsp springboot groovy gradle build,
that connects to elasticsearch database multi node cluster.

Loads data from filebeat through logstash.

Uses spring test + spock to unit test.

## Tech stack
- springboot
  - jsp
- gradle
  - elasticsearch drivers
  - lombok
  - spock
  - spring test
- bootstrap
- jquery
- dataTable
- logstash
- kibana
- filebeat

## Docker stack
- elasticsearch:8.2
- logstash:7.12
- kibana:7.12
- filebeat:7.12
- gradle:jdk11

## To run
`sudo ./install.sh -u`
- Endpoints
  - Get all curl -i localhost/dogs
  - Get by id curl -i localhost/dog/<id>
- [Available](http://localhost)
- [Node 1 elasticsearch webui](http://localhost:9200)
- [Node 2 elasticsearch webui](http://localhost:9201)
- [Node 3 elasticsearch webui](http://localhost:9202)

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credits
- [Baeldung code](https://www.baeldung.com/spring-data-elasticsearch-tutorial)
- [Springboot Application Config](https://bettergroovycode.com/programming/elasticsearch-spring-boot)
- [Gradle logging plugin](https://github.com/radarsh/gradle-test-logger-plugin)
