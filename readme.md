## python练习合集
* 考虑Windows 相关库的兼容性问题, 使用python 2.7

### replace
* 将指定文件夹下的指定文件中的'http://'替换为'https://'

### mongodb-import
* 需要模块: pymongo
* 批量将.json文件导入mongodb

### html-parse
* 需要模块: etree和requests
* 作用: 解析豆瓣电影一个周的口碑前十排行,并保存到rank.txt文件中
* 结果: rank.txt
```
3月31日 - 4月7日:
1.怒:https://movie.douban.com/subject/26279289/
2.看不见的客人:https://movie.douban.com/subject/26580232/
3.一念无明:https://movie.douban.com/subject/26704590/
4.无人之境:https://movie.douban.com/subject/26924748/
5.生日卡片:https://movie.douban.com/subject/26438851/
6.分裂:https://movie.douban.com/subject/26600660/
7.追捕聂鲁达:https://movie.douban.com/subject/26411217/
8.舞女:https://movie.douban.com/subject/26379657/
9.勃起之后:https://movie.douban.com/subject/27003570/
10.独家新闻:https://movie.douban.com/subject/26662168/
```