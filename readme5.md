#第五次作业
 
##背景
- 继续完成第一章任意一道题
- 熟练使用画图工具和python

##正文
- 选择第6题(貌似也不难),关于人口增长的模型
- 可以由一阶微分方程描述$ dN/dt=aN-bN^2
- 当初始人口数比较小时,选择参数a=10,b=3.N(O)=10.t=3 分别用欧拉法和方程精确解算得
   ![这是图片](https://github.com/computationalphysics2013301020107/computationalphysics-N_2013301020107/blob/master/homework5.png)

-当初始人口数比较大时,选择参数a=10,b=0.01,N(0)=1000,t=300,分别用欧拉法和方程精确解算得 
   ![这是图片](https://github.com/computationalphysics2013301020107/computationalphysics-N_2013301020107/blob/master/homework5%27.png)

##结论
- 可以看出人口数比较小时,死亡率比较大,当时间增大时,人口数减小至一个定值.及a和b之比.即出生率与死亡率之比.
- 而当人口数较大时,死亡率较小,当时间增大时,人口数增大到一个定值.也是出生率与死亡率之比.
- 但是如果b=0,即没有死亡率,那么人口数会一直增长,明显不符合实际.因为地球上的资源有限,能容纳的总人口数必将是一个有限值.
- 可以的出结论,按照这个模型,人口数的稳定值就是出生率与死亡率之比.
- [代码1](https://github.com/computationalphysics2013301020107/computationalphysics-N_2013301020107/blob/master/homework5.py) [代码2](https://github.com/computationalphysics2013301020107/computationalphysics-N_2013301020107/blob/master/homework5.py!)

##致谢
- 感谢蔡老师的例子.
