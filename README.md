## 基本内容

爬取德国踢球者报（kicker）官网的德甲各赛季球员数据

## 基本思路
1.先从赛季总览页面获取各俱乐部url

![kicker赛季总览页面](https://github.com/AllesGutehang/python-spider-kicker-footballplayer-data/blob/master/%E8%B5%9B%E5%AD%A3%E6%80%BB%E8%A7%88%E9%A1%B5%E9%9D%A2.jpg)

2.进入各俱乐部页面，获取球员url

![球队球员总览页面](https://github.com/AllesGutehang/python-spider-kicker-footballplayer-data/blob/master/%E7%90%83%E9%98%9F%E7%90%83%E5%91%98%E6%80%BB%E8%A7%88%E9%A1%B5%E9%9D%A2.jpg)

3.获取各球员基本信息

![具体球员基本信息页面](https://github.com/AllesGutehang/python-spider-kicker-footballplayer-data/blob/master/%E5%85%B7%E4%BD%93%E7%90%83%E5%91%98%E4%BF%A1%E6%81%AF%E9%A1%B5%E9%9D%A2.jpg)
## 环境
python 3.7  windows10

## 所需要的库
request

beautifulsoup4

lxml

re

openpyxl

time

