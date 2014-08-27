strcrzy/sink
============
a debian:jessie based docker image that includes:
 
 - elasticsearch, logstash, kibana
 - iwatch, watchers for bro and suricata logs from sensor containers
 - kibana dashboards for bro and suricata


soon:
 - more logstash grok patterns for bro

 designed for use with strcrzy/sensor

usage:
-----
`docker run -v /sink -p 80 -d strcrzy/sink`

now you are ready to add some [`sensor`](https://github.com/fortheswarm/sensor)s
 
