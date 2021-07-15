# 教室管理系统SSM
SSM框架搭建的教室管理系统，可以在Eclipse上和IDEA上运行
在IDEA运行是修改后的Maven项目
主要表设计如下
表1管理员表
序号	字段名称	字段类型	大小	是否为空	是否主键
1	id	Int	4	否	是
2	une	varchar	150	否	否
3	pwd	varchar	150	否	否
4	qx	varchar	150	否	否
5	atime	DateTime	8	否	否
表2用户信息表
序号	字段名称	字段类型	大小	是否为空	是否主键
1	id	Int	4	否	是
2	yhmg	varchar	150	否	否
3	mm	varchar	150	否	否
4	xm	varchar	150	否	否
5	xb	varchar	150	否	否
6	cdnye	DateTime	8	否	否
7	QQ	varchar	150	是	否
8	youxiang	varchar	150	是	否
9	shouji	varchar	150	否	否
10	sfz	varchar	150	否	否
11	touxiang	varchar	150	是	否
12	dizhi	varchar	150	否	否
13	beizhu	varchar	1073741823	是	否
14	issh	varchar	30	是	否
15	atime	DateTime	8	否	否
表3教室信息表
序号	字段名称	字段类型	大小	是否为空	是否主键
1	id	Int	4	否	是
2	jiaoshi	varchar	150	否	否
3	louhao	varchar	150	否	否
4	zhuangtai	varchar	150	是	否
5	tupian	varchar	150	是	否
6	jiaoshigongnengjianjie	varchar	1073741823	是	否
7	atime	DateTime	8	否	否
其他表有表4系统公告表 表5楼层管理员表 表6楼层信息表 表7教室申请表 表8新闻通知表等等
