# ZiRoomAgent
每日搜集整理自如房源，北京、上海、深圳的小伙伴们有福利啦。

##一、文件说明
目前自如在如下城市有租房服务：

- 北京:[beijing.csv](https://github.com/yrjyrj123/ZiRoomAgent/releases)

- 上海:[shanghai.csv](https://github.com/yrjyrj123/ZiRoomAgent/releases)

- 深圳:[shenzhen.csv](https://github.com/yrjyrj123/ZiRoomAgent/releases)

##二、表格字段说明
目前搜集的信息包括如下字段:

- 编号:房间的编号，告知自如工作人员就可以看房租房

- 名称:房间的名称

- 类型:整租或合租

- 面积:房间的面积

- 结构:几室几厅

- 状态:房间当前的状态，待租的是最好的

- 价格:租金价位

- 单位:租金的单位，一般是月

- 出租时间:大多数房子要签约一年，部分房子支持月租

- 房间楼层:房间所在楼层

- 总楼层:楼总共层数

- 朝向:房间的朝向

- 独立卫生间:是否有独立卫生间

- 阳台:是否有阳台

- 采暖:采暖方式

- 区域:所在区域

- 交通:附近公共交通情况

- 特色:房间特色，比如装修风格等等

- 位置:具体的经纬度信息

- 地址:具体地址，看房有用

- 详细连接:具体链接，可以在这里下单预约看房

##三、数据来源
数据完全采集自[自如网](http://www.ziroom.com/)的公开数据

爬虫代码请参见我的另一个项目[传送门](https://github.com/yrjyrj123/ziRoom)

##四、更新频率
爬虫会发起大量连接，为了不给自如网服务器增加负担，每日凌晨更新数据。
