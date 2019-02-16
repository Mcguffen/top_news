# top_news
+ Juptier
+ generate model
+ server
+ newsdeduper  

## 网站展示页面
![top_news_base](https://img2018.cnblogs.com/blog/1248976/201809/1248976-20180918165300319-1355579553.png)
![top_news_index](https://github.com/WeiChienHsu/NEWS_push_project/raw/master/image/Auth.png)
![top_news_login](https://img2018.cnblogs.com/blog/1248976/201809/1248976-20180923164342951-1823072310.png)

## generate model
python news_class_trainer.py

## Notes
mongodb
```
mongoexport --db <database-name> --collection <collection-name> --out output.json

mongoimport --db <database-name> --collection <collection-name> --file input.json

mongoexport --db tap-news --collection news-test --out output.json

mongoimport --db tap-news --collection news-test --file output.json


db["news-test"].find().count()

tap-news news-test
```

sudo pip install tensorflow
sudo pip install watchdog
server/$ python server.js

Run backfill_class.py only add topic in MongoDB without topic
python backfill_class.py

+ Must reading Stanford Deep learning class
+ Must reading Doc of TensorFlow

### QA

Design Doc

Very important in industrial company

Almost all feature is in Design Doc

Since, Team work in different group, like all sorts of API

Responsibility of Design Doc, which is reviewed by other group members

SOA  web server backend recommendation system

each components commuincation by API
