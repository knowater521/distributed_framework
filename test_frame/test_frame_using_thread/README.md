测试框架的使用，可以通过修改broker_kind来测试不同种类的中间件。

即使没有安装任何中间件，也可以使用此框架的基于sqlite persist queue方式的基于本机的分布式（需要设置broker_kind为6）（比基于python 内置 Queue对象比，兼容了不在同一解释器启动的脚本共享消息队列）。

正式使用墙裂推荐安装rabbitmq中间件。