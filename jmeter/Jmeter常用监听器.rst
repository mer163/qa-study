Jmeter常用监听器
======================================

查看结果树
---------------------------------------
查看结果树(View Results Tree)
我们可以在查看结果树里面查看接口响应，会显示每一次请求，但运行的时候每运行一次都会多一个节点，使用会大量消耗运行机器资源，因此在运行性能测试计划的时候不建议开启，通常会在接口调试中使用，

参数说明：
名称：原件别名，可以为空
注释：原件注释，可以为空
文件：性能测试完成后会生成jtl文件，可以对jtl文件进行导入，查看对应结果树。
取样器结果：显示取样器的运行结果
请求：请求的表单内容
响应结果：请求的响应结果，带有Search搜索功能


