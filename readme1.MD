Roboshop ecommerce project
==========================================

Databse
Backend(App tier/application tier)
Frontend(web tier)

===========================================
RDBMS
=======
Mysql is data tables in the form of rows and columns follows strict rules

product name --> name,description,faq,reviews,feedback,size,ratings,price,discounts,checkout,emi options...


key-->value

{
   "name": colorpens
   "price": rs40
   "description": colorpens are useful to color paints
   "expiry": 2026-09-21
}

{
   "name": colorpens
   "price": rs40
   "description": colorpens are useful to color paints
   "expiry": 2026-09-21
}



/etc/yum.repos.d

mongodb == 27017

bibindip

netstat -lntp

127.0.0.0:27017
0.0.0.0:27017


/etc/systemd/system/catalogue.service

nslookup mongodb.rohith86s.fun

telnet ip portnumber

telent mongodb.rohith86s.fun 27017

ctrl + ]
quit

systemctl daemon-reload catalogue

systemctl start catalogue

systemctl enable catalogue

curl http://loacalhost:8080/health

curl --help

curl -v http://loacalhost:8080/health
