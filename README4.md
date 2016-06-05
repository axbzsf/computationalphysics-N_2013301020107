# 第四次作页
##背景
- *本次作业选择了1.3题。*

##正文
- *这道题是关于摩擦力对速度的影响的。*
- *当摩擦力为定值时，速度与时间的关系可以用公式dv/dt=a-bv表示，其中参数a=10,b=1,初值v(t=0)=100*
- *当速度降低至v=a/b时加速度为0,此后速度恒定,可见,速度曲线应该是一个逐渐下降并不断逼近临界值的曲线.*
- *数值解法为欧拉法，用公式表示即为 v(t+dt)=v(t)+(a-b*v(t))*dt*
- *[代码](https://github.com/axbzsf/computationalphysics_N2013301020106/blob/master/homework5.py)
- *![图片](https://github.com/axbzsf/computationalphysics_N2013301020106/blob/master/homework5.png)

##总结
- **可以看到用欧拉法计算的曲线速度极限为10m/s，曲线趋势与之前分析相一致。**

##致谢
 **感谢刘祥干同学的帮助**
 **感谢python**
