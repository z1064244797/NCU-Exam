# 运维考核及说明

## 1、文件处理题


使用git clone或者直接复制代码，在本地用python3运行此代码

当前目录下生成Exam文件夹
在Exam文件夹下生成随机个数的txt文件，和一个随机名字的文件夹
随机名字的文件夹中，也有随机个数的txt文件

要求：
- 去除所有文件名[]中的内容（包括[]）
- 使用正则表达式

提示：
- 使用os、re模块
- 不需要考虑重名情况

注意：
- 所有文件的名字，长度不确定

## 2. Mysql操作题

连接远程数据库，使用exam数据库，用自己名字建表，包含两列id，name即可，随便插入两三条信息，并进行更改信息，将所有命令记录，并截图

连接命令：
mysql -uexam -h182.254.242.102 -pexam@lu

## 3. 爬虫

爬取豆瓣话题广场

数目：
- 大于等于5条

链接：
- https://www.douban.com/gallery/

要求：
- 标题
- 时间
- 作者
- 概要
- 点赞数

## 4. Linux命令题

如何在Linux下运行定时任务，如在每天8点执行一个命令。使用搜索工具进行自学。面试时提问


## 提交形式

使用github进行pull request请求或保存压缩包私发给运维组长
