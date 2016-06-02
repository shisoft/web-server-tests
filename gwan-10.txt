ab -n 1000000 -c 10 "http://10.0.1.111:8080/?hello.c"
This is ApacheBench, Version 2.3 <$Revision: 1706008 $>
Copyright 1996 Adam Twiss, Zeus Technology Ltd, http://www.zeustech.net/
Licensed to The Apache Software Foundation, http://www.apache.org/

Benchmarking 10.0.1.111 (be patient)
Completed 100000 requests
Completed 200000 requests
Completed 300000 requests
Completed 400000 requests
Completed 500000 requests
Completed 600000 requests
Completed 700000 requests
Completed 800000 requests
Completed 900000 requests
Completed 1000000 requests
Finished 1000000 requests


Server Software:        G-WAN
Server Hostname:        10.0.1.111
Server Port:            8080

Document Path:          /?hello.c
Document Length:        14 bytes

Concurrency Level:      10
Time taken for tests:   68.163 seconds
Complete requests:      1000000
Failed requests:        0
Total transferred:      239000000 bytes
HTML transferred:       14000000 bytes
Requests per second:    14670.78 [#/sec] (mean)
Time per request:       0.682 [ms] (mean)
Time per request:       0.068 [ms] (mean, across all concurrent requests)
Transfer rate:          3424.14 [Kbytes/sec] received

Connection Times (ms)
              min  mean[+/-sd] median   max
Connect:        0    0   0.7      0     141
Processing:     0    0   0.7      0     114
Waiting:        0    0   0.7      0     114
Total:          0    1   1.0      1     141

Percentage of the requests served within a certain time (ms)
  50%      1
  66%      1
  75%      1
  80%      1
  90%      1
  95%      1
  98%      1
  99%      1
 100%    141 (longest request)
