先写个readme，后面再补充内容。

目前的想法是通过开源的[logicflow](https://site.logic-flow.cn/docs/#/zh/)框架，做一个流程图插件。

想做的内容有，能够兼容基本的数据格式。可以导出数据和导入数据。

同时可以在图上直接画，也可以通过文本内容编辑。

而节点上的内容既可以是单纯的数据，也可以结合起条目来方便点击跳转。

数据储存的方式还是尽可能储存在条目的字段里，保存为json格式，这样比较好，实在不行，做成条目的专有格式，类似白板插件那样也可以。

最后再搞一搞ui什么的。看上来更现代化一点。

用reasonflow，是因为我们希望这个流程图是一个能够与任务管理结合起来的流程图。换言之，任务管理的可视化应该是以流程图这种形式，可以编辑的，而不是完全的图谱，无法编辑的形式。而任务管理的背后也需要意义的支撑。意义我们这里用了reason，相对理性一点的词语来代替。所以名称就出来了，reasonflow。

中文名就叫西瓜流。本来我是认真去找了各种材料，想了很多个名称，比如经流，但感觉有点怪。后面又去找各种典籍，去查流体力学，去看英文名的翻译。苦思冥想，忽然看到桌子上的西瓜，就决定叫西瓜流。反正中英文名不相关也没什么问题。

暂停开发。
