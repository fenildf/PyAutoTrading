# PyAutoTrading
股票交易软件辅助工具
# 简介
只能用于华泰证券独立交易软件(同花顺通用版暂时不支持），先启动交易软件，切换到双向委托界面下。在系统->快速交易 选型卡下，把 “委托前是否需要确认”和“委托成功后是否弹出对话框”全选为否，另外把买卖价格锁定为涨停价和跌停价，尽量以市价成交，目前软件还无法知道是否真的成交，只能知道委托是否成功。
开发环境是win8.1 64bit, python3 、pywin32、tushare。
### 版本：
* v 0.01 修正了股票价格实时显示问题。
* v 0.02 重构了交易软件接口，目前在最小化状态下也可以下单，下单速度加快，增加委托日志。
* v 0.03 重新布局了控件，修改委托日志控件。修复了少许Bug。
* v 0.04 重新布局了控件，重构了monitor函数。现在一次可以下4个条件单。
* v 0.05 加入时间条件单。
* v 0.06 交易软件接口函数单独放winguiauto文件。