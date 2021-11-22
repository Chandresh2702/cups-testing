# ADDING COMMENTS AND PRINTING THEM
I added some notes to the cupsFilePrintf() function, which was located in the scheduler's log.c file. I marked the function with a note. Following the modification of the file. Enter the make and make install commands once again.

## Here is modified accesslog



```
localhost - - [22/Nov/2021:13:09:01 +0530] "POST /admin/ HTTP/1.1" 401 154 CUPS-Delete-Printer successful-ok
localhost - chandresh [22/Nov/2021:13:09:01 +0530] "POST /admin/ HTTP/1.1" 200 154 CUPS-Delete-Printer successful-ok
localhost - - [22/Nov/2021:13:09:54 +0530] "POST /admin/ HTTP/1.1" 401 241 CUPS-Add-Modify-Printer successful-ok
localhost - chandresh [22/Nov/2021:13:09:54 +0530] "POST /admin/ HTTP/1.1" 200 241 CUPS-Add-Modify-Printer successful-ok
localhost - - [22/Nov/2021:13:10:02 +0530] "POST /printers/test HTTP/1.1" 200 380 Create-Job successful-ok
localhost - - [22/Nov/2021:13:10:02 +0530] "POST /printers/test HTTP/1.1" 200 2160714 Send-Document successful-ok
localhost - - [22/Nov/2021:13:12:12 +0530] "POST /admin/ HTTP/1.1" 401 154 CUPS-Delete-Printer successful-ok
localhost - chandresh [22/Nov/2021:13:12:12 +0530] "POST /admin/ HTTP/1.1" 200 154 CUPS-Delete-Printer successful-ok
localhost - - [22/Nov/2021:13:14:40 +0530] "POST /admin/ HTTP/1.1" 401 241 CUPS-Add-Modify-Printer successful-ok
localhost - chandresh [22/Nov/2021:13:14:40 +0530] "POST /admin/ HTTP/1.1" 200 241 CUPS-Add-Modify-Printer successful-ok
localhost - - [22/Nov/2021:13:14:45 +0530] "POST /printers/test HTTP/1.1" 200 380 Create-Job successful-ok
localhost - - [22/Nov/2021:13:14:45 +0530] "POST /printers/test HTTP/1.1" 200 2160714 Send-Document successful-ok
chandresh contributed this remark  
 localhost - - [22/Nov/2021:13:16:51 +0530] "POST /admin/ HTTP/1.1" 401 154 CUPS-Delete-Printer successful-ok
chandresh contributed this remark  
 localhost - chandresh [22/Nov/2021:13:16:51 +0530] "POST /admin/ HTTP/1.1" 200 154 CUPS-Delete-Printer successful-ok
chandresh contributed this remark  
 localhost - - [22/Nov/2021:13:20:00 +0530] "POST /admin/ HTTP/1.1" 401 241 CUPS-Add-Modify-Printer successful-ok
chandresh contributed this remark  
 localhost - chandresh [22/Nov/2021:13:20:00 +0530] "POST /admin/ HTTP/1.1" 200 241 CUPS-Add-Modify-Printer successful-ok
chandresh contributed this remark  
 localhost - - [22/Nov/2021:13:20:05 +0530] "POST /printers/test HTTP/1.1" 200 380 Create-Job successful-ok
chandresh contributed this remark  
 localhost - - [22/Nov/2021:13:20:05 +0530] "POST /printers/test HTTP/1.1" 200 2160714 Send-Document successful-ok
chandresh contributed this remark  
 localhost - - [22/Nov/2021:13:20:33 +0530] "POST /admin/ HTTP/1.1" 401 154 CUPS-Delete-Printer successful-ok
chandresh contributed this remark  
```
