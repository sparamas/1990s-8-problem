# 1990s-8-problem and Cidr block

![Screen Shot 2022-09-21 at 9 37 14 AM](https://user-images.githubusercontent.com/13231217/191534053-812beb1e-eb5b-4af4-9eb4-22a5272d5628.png)


![Screen Shot 2022-09-21 at 9 40 36 AM](https://user-images.githubusercontent.com/13231217/191534681-b9764dad-1af1-4ecc-a786-067fdd6658fe.png)


![Screen Shot 2022-09-21 at 9 44 02 AM](https://user-images.githubusercontent.com/13231217/191535524-298e84ac-21ed-44a8-94bf-5d8495a26ceb.png)


```
32 bit
CIDR block
10.0.0.0/20
------------
32 - bits constant
-20 -host IP
----
12
---
2 power 12 = 4,096
Total Ip address for 4096
----------------------
20 is 32 bit, it is in octet like this
11111111. 11111111. 11110000.00000000
 trun them 1 ->0 and 0->1
Finding ending range
00000000.00000000.00001111.11111111
00000000 = 0
00000000 = 0
00001111->2 power 4 = 16 -1 = 15
11111111->2 power 8 =256-1 = 255
now end range is
0.0.15.255

```
```
how to get only 16 ip addresss?
using this cidr block 10.0.0.0/20
32-28 =4
2 power 4 =16
so cidr range should be 10.0.0.0/28





```


