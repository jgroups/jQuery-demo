第1章 认识jQuery 1
1.1 JavaScript和JavaScript库 1
1.1.1 JavaScript简介 1
1.1.2 JavaScript库作用及对比 1
1.2 加入jQuery 3
1.2.1 jQuery简介 3
1.2.2 jQuery的优势 4
1.3 jQuery代码的编写 5
1.3.1 配置jQuery环境 5
1.3.2 编写简单的jQuery代码 7
1.3.3 jQuery代码风格 8
1.4 jQuery对象和DOM对象 12
1.4.1 DOM对象和jQuery对象简介 12
1.4.2 jQurey对象和DOM对象的相互转换 14
1.4.3 实例研究 15
1.5 解决jQuery和其他库的冲突 17
1.6 jQuery开发工具和插件 20
1.7 小结 24

第2章 jQuery选择器 25
2.1 jQuery选择器是什么 25
2.2 jQuery选择器的优势 28
2.3 jQuery选择器 30
2.3.1 基本选择器 34
2.3.2 层次选择器 36
2.3.3 过滤选择器 38
2.3.4 表单选择器 49
2.4 应用jQuery改写示例 51
2.5 选择器中的一些注意事项 51
2.5.1 选择器中含有特殊符号的注意事项 51
2.5.2 选择器中含有空格的注意事项 52
2.6 案例研究——某网站品牌列表的效果 53
2.7 其他选择器 60
2.7.1 jQuery提供的选择器的扩展 60
2.7.2 其他使用CSS选择器的方法 60
2.8 小结 61

第3章 jQuery中的DOM操作 62
3.1 DOM操作的分类 62
3.2 jQuery中的DOM操作 63
3.2.1 查找节点 64
3.2.2 创建节点 65
3.2.3 插入节点 68
3.2.4 删除节点 70
3.2.5 复制节点 72
3.2.6 替换节点 73
3.2.7 包裹节点 73
3.2.8 属性操作 75
3.2.9 样式操作 76
3.2.10 设置和获取HTML.文本和值 80
3.2.11 遍历节点 86
3.2.12 CSS-DOM操作 89
3.3 案例研究——某网站的超链接和图片提示效果 91
3.4 小结 98

第4章 jQuery中的事件和动画 99
4.1 jQuery中的事件 99
4.1.1 加载DOM 99
4.1.2 事件绑定 102
4.1.3 合成事件 106
4.1.4 事件冒泡 109
4.1.5 事件对象的属性 113
4.1.6 移除事件 115
4.1.7 模拟操作 118
4.1.8 其他用法 119
4.2 jQuery中的动画 121
4.2.1 show()方法和hide()方法 121
4.2.2 fadeIn()方法和fadeOut()方法 124
4.2.3 slideUp()方法和slideDown()方法 124
4.2.4 自定义动画方法animate() 125
4.2.5 动画回调函数 128
4.2.6 停止动画和判断是否处于动画状态 128
4.2.7 其他动画方法 131
4.2.8 动画方法概括 132
4.3 视频展示效果实例 133
4.4 小结 140

第5章 jQuery对表单.表格的操作及更多应用 141
5.1 表单应用 141
5.1.1 单行文本框应用 141
5.1.2 多行文本框应用 143
5.1.3 复选框应用 146
5.1.4 下拉框应用 150
5.1.5 表单验证 152
5.2 表格应用 156
5.2.1 表格变色 157
5.2.2 表格展开关闭 161
5.2.3 表格内容筛选 163
5.3 其他应用 164
5.3.1 网页字体大小 164
5.3.2 网页选项卡 167
5.3.3 网页换肤 169
5.4 小结 173

第6章 jQuery与Ajax的应用 174
6.1 Ajax的优势和不足 174
6.1.1 Ajax的优势 174
6.1.2 Ajax的不足 175
6.2 Ajax的XMLHttpRequest对象 176
6.3 安装Web环境——AppServ 176
6.4 编写第1个Ajax例子 177
6.5 jQuery中的Ajax 179
6.5.1 load()方法 179
6.5.2 $.get()方法和$.post()方法.. 182
6.5.3 $.getScript()方法和$.getJson()方法 187
6.5.4 $.ajax()方法 191
6.6 序列化元素 194
6.7 jQuery中的Ajax全局事件 197
6.8 基于jQuery的Ajax聊天室程序 198
6.8.1 基本设想 198
6.8.2 设计数据库 199
6.8.3 服务器端处理 199
6.8.4 客户端处理 200
6.8.5 客户端代码 200
6.8.6 整合代码 204
6.9 小结 207

第7章 插件的使用和写法 208
7.1 jQuery表单验证插件——Validation 208
7.1.1 Validation简介 208
7.1.2 下载地址 209
7.1.3 快速上手 209
7.1.4 不同的验证写法 212
7.1.5 验证信息 215
7.1.6 自定义验证规则 218
7.1.7 API 219
7.2 jQuery表单插件——Form 219
7.2.1 Form插件简介 219
7.2.2 下载地址 219
7.2.3 快速上手 220
7.2.4 核心方法——ajaxForm()和ajaxSubmit() 221
7.2.5 ajaxForm()方法和ajaxSubmit()方法的参数 221
7.2.6 表单提交之前验证表单 224
7.2.7 API 226
7.3 动态绑定事件插件——livequery 226
7.3.1 livequery插件简介 226
7.3.2 下载地址 227
7.3.3 快速上手 227
7.3.4 与复杂选择器结合使用 228
7.3.5 触发回调函数 230
7.3.6 关于插件开发 230
7.3.7 API 231
7.4 jQueryUI插件 231
7.4.1 jQueryUI简介 231
7.4.2 下载地址 232
7.4.3 快速上手 233
7.4.4 与单击事件冲突 235
7.4.5 与后台结合 235
7.5 管理Cookie的插件——Cookie 237
7.5.1 Cookie插件简介 237
7.5.2 下载地址 238
7.5.3 快速上手 238
7.5.4 API 239
7.6 编写jQuery插件 240
7.6.1 插件的种类 240
7.6.2 插件的基本要点 241
7.6.3 插件中的闭包 241
7.6.4 jQuery插件的机制 243
7.6.5 编写jQuery插件 244
7.7 小结 255

第8章 用jQuery打造个性网站 256
8.1 案例背景介绍 256
8.2 网站材料 256
8.3 网站结构 256
8.3.1 文件结构 256
8.3.2 网页结构 257
8.3.3 界面设计 257
8.4 网站的(X)HTML 259
8.5 网站样式(CSS) 259
8.5.1 将CSS文件分门别类 259
8.5.2 编写CSS 260
8.6 网站脚本(jQuery) 274
8.6.1 准备工作 274
8.6.2 首页(index.html)上的功能 274
8.6.3 详细页(detail.html)上的功能 289
8.7 小结 298
附录A 关于$(document).ready()函数 299
A.1 $(document).ready()函数介绍 299
A.2 多个$(document).ready()函数 300
附录B Firebug 301
B.1 概述 301
B.2 主面板简介 302
B.2.1 控制台面板 304
B.2.2 HTML面板 308
B.2.3 CSS.脚本和网络面板 313
B.2.4 脚本面板 314
B.3 一些资源 318
B.4 总结 318
附录C Ajax的XMLHttpRequest对象的属性和方法 319
附录D jQuery$.ajax()方法的参数详解 322
附录E jQuery加载并解析XML 325
E.1 简述 325
E.2 Content-Type 325
E.3 XML结构 325
E.4 获取XML 326
E.5 解析XML 327
E.6 禁用缓存 328
附录F 插件API 329
F.1 Validation插件API 329
F.2 Form插件API 331
F.3 Livequery插件API 335
附录G jQuery速查表 337
G.1 基础 337
G.2 选择器 338
G.3 属性 340
G.4 筛选 340
G.5 文档处理 342
G.6 CSS 343
G.7 事件 343
G.8 效果 345
G.9 Ajax 346
G.10 实用项347
