20190219

主体基本完成。


1.表单使用了jsgrid插件

2.页面没有全部做，只有总包合同。原因是 更改表格需要对接口进行修改，这一步需要先确定后台接口。

3.点击 添加合同 后会展开直接填信息添加，同时可以在表格上添加修改。

20190220

待解决问题：

    1.不同iframe之间通信问题，要求一个iframe改变别的都要改变

20190222

tabs标签过多问题：
    当页签过多时，一方面可以减小宽度，适度隐藏半条以增加容量，另一方面也可以增加一个省略号表示过多，但是目前先做判断，以限制个数。日后有机会参考参考浏览器页签特效后再更新效果。   

tabsFunctions.js 绑定问题

    标签的绑定事件会被重复绑定，但是不影响效果。页面请求在第一次点击的时候就执行了，不会产生重复请求的事件。但是以后可以考虑改下这个bug。

15.22

    点击 更多 可以滑出新页面了，同时新页面为选中状态。 此时点击页签时可以正常切换，同时再次点击 相同按钮（更多）
    时，可以切回新页面。关闭新页面后再点击 更多 按钮，如此往复。
