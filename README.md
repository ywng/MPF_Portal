MPF_Portal
==========

A serverlet program
-for extracting online data from webpages
-for storing extracted data into db 
-and make a API url for data retriving 

For some of the online data, they can be accessed by in most case not programatically eaasy, say, not have any API to retrive data.

For some of the sites, like Bloomberg, contain many unseful information that we are interested. If we don't want to pay for their API, or they actually don't have API
for data retrival. Then, we need to make our own. This repo provide a quick, simple picture that allow you to grisp how to make your own API.

A quick description:
I scrapped it from Bloomberg webpage, by a servelet (see further the code on my github:https://github.com/ywng/MPF_Portal )I made, which is then trigger by an online scheduler server (cron scheduler: https://mywebcron-com.loopiasecure.com/members.php?Jobs). So, the price is extracted daily and updated into my database (free host: http://www.db4free.net/). After extracting the data, I also made an API url for external requesting of data.