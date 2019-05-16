# Social Network Analysis of Zhihu(知乎社交网络分析)
## Overview(简介)
### Motivation(动机)
Zhihu (www.zhihu.com) is the biggest Chinese knowledge ask-answer web site in China (example in English world: Quora). It has more than 220 million registered users (over 240 million among them are monthly active) by November 2018

知乎是中国最大的中文知识问答网站。截止2018年11月，该网站注册用户超过2.2亿(每月活跃用户流量超过2.4亿)

We wonder in such a platform, what kind of form of social network may existsa, and we want to know whether the knowledge areas (topics) have any contact with the interpersonal relationships (which is a special issue of Zhihu compared to social websites like Twitter or Facebook). 

我们想知道在这样一个平台上，可能存在什么样的社交网络形式，我们想知道知识领域(话题)是否与人际关系有任何联系(这是知乎与Twitter、Facebook等社交网站相比的一个特殊问题)。

### Manual(使用手册)
The project includes zhihu_analysis_LinuxWorkingStation_py3.py (extracting data from the database and analyzing, main function), zhi_database.py (importing data from csv file into the database), zhihu_schema.sql (SQLite database Schema)

该项目包含zhihu_analysis_LinuxWorkingStation_py3.py(从数据库中提取数据并进行分析、主函数)、zhi_database.py(导入csv文件中的数据至数据库中)、zhihu_schema.sql(SQLite数据库的schema)

zhihu.zip (database file download link)数据库文件下载地址

https://pan.baidu.com/s/1KJpBgaMj5MplIBg-QVOOiQ

password（提取码）：i3nm

<pre><code>
$ git clone https://github.com/MarsZhanCZ/social-network-exercise-project
unzip zhihu.zip
python zhihu_analysis_LinuxWorkStation_py3.7.py
</code></pre>

## Future Expectations(未来展望)
In the future, consider using existing data sets to do some analysis, such as user clustering and other issues.

未来考虑利用现有数据集再做一些分析，比如用户聚类等问题
