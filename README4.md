# 第四次作页
##背景
- *第四次作业是课后练习题,我选择了第三道,比较简单,正好适合我这种纯新手,呵呵...^_^*

##正文
- *这道题是有关摩擦力的,众所周知,在摩擦力的作用下加速度会和速度成正比,导致速度逐渐降低至一个极限值；*
- *用公式表达就是 $dv/dt=a-bv  ,当速度降低至a/b时加速度为0,此后速度恒定,可见,速度曲线应该是一个逐渐下降逼近一个临界值.*
- *用欧拉法解决该题就是将微分方程化为差分方程,即
 $$ v(t+detat)=v(t)+(a-b*v(t))*detat*
- *选择参数a=10,b=1,和初值为v(t=0)=100*
- *[代码在此](https://github.com/axbzsf/computationalphysics_N2013301020106/blob/master/homework5.py)
- *![这是图片](https://github.com/axbzsf/computationalphysics_N2013301020106/blob/master/homework5.png)

- *进一步地,我找到了精确解:v=90+10/e^t,可以检验之前的欧拉法的正确度.[对比代码](https://github.com/computationalphysics2013301020107/computationalphysics-N_2013301020107/blob/master/homework4.py)
-  *![这是对比图](https://github.com/computationalphysics2013301020107/computationalphysics-N_2013301020107/blob/master/homework4.png)
 
##总结
- **明显可见用欧拉法计算的曲线和之前分析的情况一样.速度极限为10m/s.在大概6s的时候就已经很逼近极限值了.**
- **对比精确解和欧拉法可以发现二者在前段和后段都比较贴近,在曲线中间部分略有错开,证明在这里欧拉法出现了一点误差.仔细分析可以发现,这一段的曲线正是变化率较大的一段,说明欧拉法这种属于迭代的数值解法在变化率较大时会累计一定的误差,而在其他比较平缓的段则可以较好模拟.

##致谢
 **感谢百度!!感谢蔡老师的示例代码!!**
