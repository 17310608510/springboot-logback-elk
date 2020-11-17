需求背景
Springboot集成Logback日志框架，同时把日志写入ELK实时日志系统中，便于统一查找和分析日志
destination中配置的ip:port，即为logstash服务器的ip和端口（Logstash > Elasticsearch > Kibana）


需搭建ELK