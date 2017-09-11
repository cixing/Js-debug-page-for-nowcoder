﻿# 使用方法介绍

* Js文件放在code文件夹内
* 修改页面的entry.js文件的第4行，选择要调试的js代码
* 第一个的框写测试数据
* “执行”按钮：执行数据
* “重新测试”按钮：（不刷新页面的情况下）重新测试数据，点完后需再点一下“执行”
* “刷新”按钮：刷新页面
* 结果会在第二个的输出框打印出来
* 调试的功能当然还是由chrome的开发者工具来实现

![mark](http://onxem9xtk.bkt.clouddn.com/blog/170911/BlIEHhBFfi.gif)

## <span style="color:red">注意</spn>
**程序超级简陋，只是想实现基本的用牛客的方法调试Js的想法，大佬轻喷，当然你可以帮我完善一下。**

* 填测试数据的时候，**一开始不要打回车或者空格什么的，顶格写数据** 。因为没写过滤的函数，实在抱歉，后面有时间再完善吧。
* 如果想用es6的语法，建议将代码调试的时候讲代码用大括号括起来“{}”，不然“重新测试”的按钮用不了，因为其变量不能重复定义的关系。
* readline()和print()的使用和牛客提供的一样：

	![mark](http://onxem9xtk.bkt.clouddn.com/blog/170911/li2eDHfaAk.png)
