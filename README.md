# Made A Pie
MadeAPie的建议与反馈

一直想要实现代码创造价值

遂开发了 [MadeAPie](http://pie.antcode.net)，数据是MakeAPie的，感谢好心人提供数据

目前已实现过滤，搜索。

代码编辑页实现了在线编辑与预览，可切换echarts版本，尽量还原MakeAPie的所有功能。

由于数据仅包含图表代码与预览图，所以很多使用外部数据以及外部静态资源的案例图无法渲染，

尽可能的保证未使用外部资源的案例能够正常显示与调试，目前已修复了一些3D图与词云图的显示，

一些使用了jquery语法的案例也已经做了处理。

大家可以提issue，完善优化以及升级它。

域名madeapie.com正在备案中，备案完成后，将使用该域名。

# 后续计划
代码编辑添加外部资源引用，格式化代码功能

实现登录注册，

开发个人中心，

实现图表创建

# 开发进度
2022/2/14  修复大量echarts案例无法正常显示的问题，例如地图，3D图，水球图等使用插件类图表。还有一些未修复，是由于引入的cdnjs文件404，这些暂不处理。

2022/2/15  将echarts挂载元素id改为chart-panel，将数据库中所有使用echarts4.2.0版本的全部替换为4.2.1，又修复了一大波不显示预览的案例

2022/2/17  添加外部脚本显示与整理代码功能

2022/2/24  修复大部分词云图不显示的案例，原因是由于echarts版本不匹配以及词云图在线js为http资源的问题
