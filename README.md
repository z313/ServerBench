https://serverbench.info/
 
Benchmark Script 2
This is the classic FreeVPS.us Benchmark Script. By issuing this you can fetch quick information about your server including CPU Model, number of cores, CPU frequency, total amount of RAM, SWAP, system uptime and perform test of download speed and I/O speed.

 wget --no-check-certificate https://serverbench.info/bench-sh-2.sh -O - -o /dev/null|bash

 nench.sh ("new bench.sh")
Based on FreeVPS.us Benchmark Script but modified to include CPU and ioping measurements and to reduce the number of speedtests while retaining useful European and North American POPs. Made by n-st on GitHub.

 wget --no-check-certificate https://serverbench.info/nench.sh -O - -o /dev/null|bash

 ServerBench
Gives you the basic system information, disk speed and speedtest from 70 locations worldwide. Also includes IPv6 speedtest. Depending on your server, this might take a while. Made by K4Y5 from LowEndTalk, based on the script by Teddysun.

 wget --no-check-certificate https://serverbench.info/serverbench.sh -O - -o /dev/null|bash
