# docker-compose-cloudera-hue

"Sample" docker-compose file for Cloudera Hue Server.  
DO NOT WORK．  
You need to reflect your cluster settings.  

The startup procedure is as follows
```
$ docker-compose up --no-start
$ docker-compose start database
$ docker-compose up -d
```

See below for more details.

* [hue/tools/docker/hue at master · cloudera/hue](https://github.com/cloudera/hue/tree/master/tools/docker/hue)
* [Cloudera Hue On Dockerで使えないか検討してみる - Yassan's Memo](https://yassan.hatenablog.jp/entry/advent-calendar-2020-microad-1220)

