# 事件属性表

### 窗口事件属性（Window Event Attributes）

由窗口触发该事件 (适用于 \<body> 标签):

| 属性                                                                 | 值        | 描述                                     |
| ------------------------------------------------------------------ | -------- | -------------------------------------- |
| [onafterprint](https://www.runoob.com/tags/ev-onafterprint.html)   | _script_ | 在打印文档之后运行脚本                            |
| [onbeforeprint](https://www.runoob.com/tags/ev-onbeforeprint.html) | _script_ | 在文档打印之前运行脚本                            |
| onbeforeonload                                                     | _script_ | 在文档加载之前运行脚本                            |
| onblur                                                             | _script_ | 当窗口失去焦点时运行脚本                           |
| onerror                                                            | _script_ | 当错误发生时运行脚本                             |
| onfocus                                                            | _script_ | 当窗口获得焦点时运行脚本                           |
| onhashchange                                                       | _script_ | 当文档改变时运行脚本                             |
| [onload](https://www.runoob.com/tags/ev-onload.html)               | _script_ | 当文档加载时运行脚本                             |
| onmessage                                                          | _script_ | 当触发消息时运行脚本                             |
| onoffline                                                          | _script_ | 当文档离线时运行脚本                             |
| ononline                                                           | _script_ | 当文档上线时运行脚本                             |
| onpagehide                                                         | _script_ | 当窗口隐藏时运行脚本                             |
| onpageshow                                                         | _script_ | 当窗口可见时运行脚本                             |
| onpopstate                                                         | _script_ | 当窗口历史记录改变时运行脚本                         |
| onredo                                                             | _script_ | 当文档执行再执行操作（redo）时运行脚本                  |
| [onresize](https://www.runoob.com/tags/ev-onresize.html)           | _script_ | 当调整窗口大小时运行脚本                           |
| onstorage                                                          | _script_ | 当 Web Storage 区域更新时（存储空间中的数据发生变化时）运行脚本 |
| onundo                                                             | _script_ | 当文档执行撤销时运行脚本                           |
| [onunload](https://www.runoob.com/tags/ev-onunload.html)           | _script_ | 当用户离开文档时运行脚本                           |

\


***

### 表单事件(Form Events)

表单事件在HTML表单中触发 (适用于所有 HTML 元素, 但该HTML元素需在form表单内):

| 属性                                                       | 值        | 描述                     |
| -------------------------------------------------------- | -------- | ---------------------- |
| [onblur](https://www.runoob.com/tags/ev-onblur.html)     | _script_ | 当元素失去焦点时运行脚本           |
| [onchange](https://www.runoob.com/tags/ev-onchange.html) | _script_ | 当元素改变时运行脚本             |
| oncontextmenu                                            | _script_ | 当触发上下文菜单时运行脚本          |
| [onfocus](https://www.runoob.com/tags/ev-onfocus.html)   | _script_ | 当元素获得焦点时运行脚本           |
| onformchange                                             | _script_ | 当表单改变时运行脚本             |
| onforminput                                              | _script_ | 当表单获得用户输入时运行脚本         |
| oninput                                                  | _script_ | 当元素获得用户输入时运行脚本         |
| oninvalid                                                | _script_ | 当元素无效时运行脚本             |
| onreset                                                  | _script_ | 当表单重置时运行脚本。HTML 5 不支持。 |
| [onselect](https://www.runoob.com/tags/ev-onselect.html) | _script_ | 当选取元素时运行脚本             |
| [onsubmit](https://www.runoob.com/tags/ev-onsubmit.html) | _script_ | 当提交表单时运行脚本             |

\


***

### 键盘事件（Keyboard Events）

| 属性                                                           | 值        | 描述            |
| ------------------------------------------------------------ | -------- | ------------- |
| [onkeydown](https://www.runoob.com/tags/ev-onkeydown.html)   | _script_ | 当按下按键时运行脚本    |
| [onkeypress](https://www.runoob.com/tags/ev-onkeypress.html) | _script_ | 当按下并松开按键时运行脚本 |
| [onkeyup](https://www.runoob.com/tags/ev-onkeyup.html)       | _script_ | 当松开按键时运行脚本    |

\


***

### 鼠标事件（Mouse Events）

通过鼠标触发事件, 类似用户的行为:

| 属性                                                             | 值        | 描述                   |
| -------------------------------------------------------------- | -------- | -------------------- |
| [onclick](https://www.runoob.com/tags/ev-onclick.html)         | _script_ | 当单击鼠标时运行脚本           |
| [ondblclick](https://www.runoob.com/tags/ev-ondblclick.html)   | _script_ | 当双击鼠标时运行脚本           |
| ondragNew                                                      | _script_ | 当拖动元素时运行脚本           |
| ondragendNew                                                   | _script_ | 当拖动操作结束时运行脚本         |
| ondragenterNew                                                 | _script_ | 当元素被拖动至有效的拖放目标时运行脚本  |
| ondragleaveNew                                                 | _script_ | 当元素离开有效拖放目标时运行脚本     |
| ondragoverNew                                                  | _script_ | 当元素被拖动至有效拖放目标上方时运行脚本 |
| ondragstartNew                                                 | _script_ | 当拖动操作开始时运行脚本         |
| ondropNew                                                      | _script_ | 当被拖动元素正在被拖放时运行脚本     |
| [onmousedown](https://www.runoob.com/tags/ev-onmousedown.html) | _script_ | 当按下鼠标按钮时运行脚本         |
| [onmousemove](https://www.runoob.com/tags/ev-onmousemove.html) | _script_ | 当鼠标指针移动时运行脚本         |
| [onmouseout](https://www.runoob.com/tags/ev-onmouseout.html)   | _script_ | 当鼠标指针移出元素时运行脚本       |
| [onmouseover](https://www.runoob.com/tags/ev-onmouseover.html) | _script_ | 当鼠标指针移至元素之上时运行脚本     |
| [onmouseup](https://www.runoob.com/tags/ev-onmouseup.html)     | _script_ | 当松开鼠标按钮时运行脚本         |
| onmousewheelNew                                                | _script_ | 当转动鼠标滚轮时运行脚本         |
| onscrollNew                                                    | _script_ | 当滚动元素的滚动条时运行脚本       |

\


***

### 多媒体事件(Media Events)

通过视频（videos），图像（images）或者音频（audio） 触发该事件，多应用于 HTML 媒体元素比如 \<audio>, \<embed>, \<img>, \<object>, 和\<video>:

| 属性                    | 值        | 描述                              |
| --------------------- | -------- | ------------------------------- |
| onabort               | _script_ | 当发生中止事件时运行脚本                    |
| oncanplayNew          | _script_ | 当媒介能够开始播放但可能因缓冲而需要停止时运行脚本       |
| oncanplaythroughNew   | _script_ | 当媒介能够无需因缓冲而停止即可播放至结尾时运行脚本       |
| ondurationchangeNew   | _script_ | 当媒介长度改变时运行脚本                    |
| onemptiedNew          | _script_ | 当媒介资源元素突然为空时（网络错误、加载错误等）运行脚本    |
| onendedNew            | _script_ | 当媒介已抵达结尾时运行脚本                   |
| onerrorNew            | _script_ | 当在元素加载期间发生错误时运行脚本               |
| onloadeddataNew       | _script_ | 当加载媒介数据时运行脚本                    |
| onloadedmetadataNew   | _script_ | 当媒介元素的持续时间以及其他媒介数据已加载时运行脚本      |
| onloadstartNew        | _script_ | 当浏览器开始加载媒介数据时运行脚本               |
| onpauseNew            | _script_ | 当媒介数据暂停时运行脚本                    |
| onplayNew             | _script_ | 当媒介数据将要开始播放时运行脚本                |
| onplayingNew          | _script_ | 当媒介数据已开始播放时运行脚本                 |
| onprogressNew         | _script_ | 当浏览器正在取媒介数据时运行脚本                |
| onratechangeNew       | _script_ | 当媒介数据的播放速率改变时运行脚本               |
| onreadystatechangeNew | _script_ | 当就绪状态（ready-state）改变时运行脚本       |
| onseekedNew           | _script_ | 当媒介元素的定位属性 \[1] 不再为真且定位已结束时运行脚本 |
| onseekingNew          | _script_ | 当媒介元素的定位属性为真且定位已开始时运行脚本         |
| onstalledNew          | _script_ | 当取回媒介数据过程中（延迟）存在错误时运行脚本         |
| onsuspendNew          | _script_ | 当浏览器已在取媒介数据但在取回整个媒介文件之前停止时运行脚本  |
| ontimeupdateNew       | _script_ | 当媒介改变其播放位置时运行脚本                 |
| onvolumechangeNew     | _script_ | 当媒介改变音量亦或当音量被设置为静音时运行脚本         |
| onwaitingNew          | _script_ | 当媒介已停止播放但打算继续播放时运行脚本            |

### 其他事件

| 属性                                                          | 值        | 描述                        |
| ----------------------------------------------------------- | -------- | ------------------------- |
| [onshow](https://www.runoob.com/tags/ev-onshow.html)New     | _script_ | 当 \<menu> 元素在上下文显示时触发     |
| [ontoggle](https://www.runoob.com/tags/ev-ontoggle.html)New | _script_ | 当用户打开或关闭 \<details> 元素时触发 |
