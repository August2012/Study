Sphinx相关：
=================================
在大数据量环境下，使用sphinx进行搜素
基于SQL的全文搜索引擎

show create table `news`;
alert table `news` add index(title) title; // mysql的索引功能

单表超百万，做模糊查询时，LIKE等