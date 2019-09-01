<!--
 * @Author: Luoxd
 * @Description: 
 * @Date: 2019-09-01 21:41:20
 * @LastEditTime: 2019-09-01 21:45:29
 * @LastEditors: Luoxd
 -->
## 《重学前端》学习笔记

#### 如何正确的判断浮点数？
使用JavaScript提供的最小精度值：
console.log(Math.abs(0.1 + 0.2 - 0.3) <= Number.EPSILON)
检查等式左右两边差的绝对值是否小于最小精度，才是正确的比较浮点数的方法。这段代码结果就是 true了。

#### 持续更新笔记...