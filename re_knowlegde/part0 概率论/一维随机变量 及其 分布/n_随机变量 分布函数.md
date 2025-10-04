<div style="float: left; width: 64%; padding: 1%;">

# <span style="color: gray;"><span style="color:blue;">一维</span>随机变量 及其 分布

<ul>

## <span style="color: gray;">随机变量

<ul>

1.  definition
    *   ![](https://api2.mubu.com/v3/document_image/abea0b15-b85c-44e9-af84-69a5290ff9ea-15201174.jpg)
    *   每一个$\omega \in \Omega$ ,都有唯一实数$X(\omega)$与之对应
    *   且 对于 任意实数<span style="color:blue;">x</span> $\{ \omega | X(\omega) \le x, \omega \in \Omega \}$ **是**<u>随机事件</u>
    *   则 称定义在Ω上的**实值单值函数**<span style="color:blue;">$X(\omega)$</span> 为 随机变量，简记为 随机变量**X**
        *   ![](https://api2.mubu.com/v3/document_image/e257c586-c58d-48ac-80c7-f7b3261df8ad-15201174.jpg)
2.  **阐述**
    *   随机事件是静态观点，而 随机变量是动态观点
    *   实值单值函数 的<u>定义域</u> 不一定是实数集

</ul>

## <span style="color: gray;"><span style="color:darkorange;">分布</span><span style="color:blue;">函数</span>

<ul>

1.  definition
    *   ![](https://api2.mubu.com/v3/document_image/312954f6-c8d7-4f9d-b5b7-ace614bac88e-15201174.jpg)
    *   <span style="color:blue;">$F(x)=P\{X \le x\}$</span> 为随机变量X的<span style="color:darkorange;">分布函数</span>
        *   $(x \in R)$
        *   //此形式是 离散型
    *   或称X服从<u>F(x)分布</u>，记为$X$ ~ $F(x)$
        *   //F(x)体现实值单值函数X(ω)的分布，X(ω)是 事件-数值 函数，体现 概率
2.  **<span style="color:darkorange;">性质</span>**(充要条件)
    *   ① $F(x)$ 是 x 的**单调不减**函数
        *   ![](https://api2.mubu.com/v3/document_image/85c9a4f8-564a-4060-b0fa-43ab2fe3ef21-15201174.jpg)
    *   ② $F(x)$ 是x的**右连续**函数
    *   ③ $F(-\infty)=0$ ；$F(+\infty)=0$
        *   ![](https://api2.mubu.com/v3/document_image/5c8462c3-4471-4621-be95-1866d764d292-15201174.jpg)
    *   add. $0 \le F(x) \le 1$ ，是有界函数
3.  **<span style="color:green;">应用</span>——求概率**
    *   $P\{X \le a\}$ = $F(a)$
    *   $P\{X < a\}$ =$F(a-0)$
    *   $P\{X = a\}$ = $F(a)-F(a-0)$
        *   ?F(0)=?
</div>
<div style="float: right; width: 26%; padding: 1%;">

</div>
<div style="clear: both;"></div>
