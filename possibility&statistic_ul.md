# <span style="color: gray;">随机事件 与 概率

<ul>


## <span style="color: gray;">0 基本<span style="color:darkorange;">概念</span>

<ul>

#### <span style="color: gray;">a. 随机试验

<ul>

*   3 个条件
    *   <span style="color:blue;">同条件</span>下 <span style="color:green;">重复</span>进行
    *   <span style="color:blue;">结果 </span><span style="color:green;"> 明确</span>可知 <span style="color:green;">不止一</span>个
    *   <span style="color:darkorange;">不确定</span>

</ul>

#### <span style="color: gray;">b. 随机事件

<ul>

*   1) 随机事件
    *   <span style="color:blue;">结果 </span><span style="color:green;">可能</span>出现 也<span style="color:green;">可能不</span>
*   2) 必然事件
    *   <span style="color:green;">必定</span>

</ul>

#### <span style="color: gray;">c. 样本空间

<ul>

*   1) 样本点
    *   <span style="color:darkorange;">every</span> <span style="color:green;">可能的</span> <span style="color:blue;">结果</span>
*   2) 样本空间 /基本事件空间 **Ω**
    *   <span style="color:green;">全体</span> 样本点的 <span style="color:blue;">集合</span>
*   3) 基本事件 **A**
    *   <span style="color:purple;">一个样本点 </span>构成的 事件 // $A \subset \Omega$

</ul>



## <span style="color: gray;">1 事件的<span style="color:blue;">关系</span>与<span style="color:green;">运算</span>

<ul>

#### <span style="color: gray;">(1) 关系与运算

<ul>

*   A. 关系
    *   含 = ; 斥 逆
    *   ![](https://api2.mubu.com/v3/document_image/00388a35-9e79-4e17-acd4-1a9dbf66581e-15201174.jpg)
        *   包含
    *   ![](https://api2.mubu.com/v3/document_image/62dbc1e0-b76f-4bda-9ed9-b2ce372e16a2-15201174.jpg)
        *   相等
    *   <span style="color:blue;">相容</span>|<span style="color:green;">互斥</span>
        *   ![](https://api2.mubu.com/v3/document_image/92ca75de-ae03-4325-92a4-8a7c4d74da05-15201174.jpg)
            *   相容
        *   ![](https://api2.mubu.com/v3/document_image/527faa55-40c6-401e-baef-1046b54910b1-15201174.jpg)
            *   互斥(互不相容)
    *   对立(逆事件)
        *   ![](https://api2.mubu.com/v3/document_image/185a9488-3c06-4083-8cb6-e4099f8717f1-15201174.jpg)
*   B. 运算
    *   和（并）
    *   差
    *   积（交）
##### <span style="color: gray;">运算法则

<ul>

*   吸收律
    *   ![](https://api2.mubu.com/v3/document_image/114c2302-b88e-49ba-8a87-e32015ed3c4f-15201174.jpg)
*   交换律 结合律 **分配律**
    *   ![](https://api2.mubu.com/v3/document_image/d036ab9a-68f0-471c-a907-07fc88ab2f9d-15201174.jpg)
    *   ![](https://api2.mubu.com/v3/document_image/ad1d9430-32a8-4e7a-9685-b2010b83f0ce-15201174.jpg)
*   **对偶律（德·摩根律）**//并交互换，拆横线定律
    *   ![](https://api2.mubu.com/v3/document_image/442787ec-34d0-427b-bb82-c169d176c91a-15201174.jpg)

</ul>

</ul>

#### <span style="color: gray;">(2) 概率与概型

<ul>

*   a. 概率的定义
    *   ① 描述性定义
        *   事件A发生的 **可能性**大小的<span style="color:blue;">度量</span>(非负)
    *   ② 统计性定义
        *   频率 → 概率
            *   当实验次数<span style="color:blue;">n</span><u>充分</u>**大**，频率稳定于一常数p
            *   频率：
                *   <u>相同条件下重复试验</u>
                    *   A出现的次数k
                    *   总次数n
                    *   k/n=A的频率
    *   ③ **公理化**定义
        *   随机试验的样本空间为Ω
            *   对于每一个事件A都有一个确定的实数**P(A)**
            *   事件函数**P(·)** **满足**
                *   1)
                    *   ![](https://api2.mubu.com/v3/document_image/6eee0aeb-4655-4c24-af16-49bb70f9058e-15201174.jpg)
                    *   ![](https://api2.mubu.com/v3/document_image/5ce1c917-1b5d-4277-9852-fc73bc5aaf29-15201174.jpg)
                *   2)
                    *   ![](https://api2.mubu.com/v3/document_image/edfcebdb-35d1-463e-8063-1131fb339e4f-15201174.jpg)
                        *   常用来判断 P(·) whther是概率
        *   则称 P(·) **概率** ; P(A)事件**A的概率**
*   b. 古典概型和几何概型
    *   ① **古典**概型
        *   0). 定义
            *   <span style="color:green;">有限</span>个样本点(基本事件)
            *   每个样本点(基本事件)发生的<span style="color:blue;">可能性</span><span style="color:green;">一样</span>
            *   ![](https://api2.mubu.com/v3/document_image/99b3e318-a958-4969-ada1-12d3572a16f4-15201174.jpg)
        *   数数法
        *   随机分配
        *   简单随机抽样
    *   ② **几何**概型
        *   0) 定义
            *   样本空间<span style="color:blue;">Ω</span>是一个<u>可度量</u>的<span style="color:green;">有界</span>区域
            *   每个样本点(基本事件)发生的<span style="color:blue;">可能性</span><span style="color:green;">一样</span>
                *   即<span style="color:blue;">可能性</span>与几何度量有关，**与**<u>形状位置</u>等**无关**
            *   ![](https://api2.mubu.com/v3/document_image/8be8001f-ea6d-452c-b788-209abb8ed5d8-15201174.jpg)

</ul>

</ul>

</ul>

## <span style="color: gray;">性质：

<ul>

### <span style="color: gray;">1 概率的基本<span style="color:darkorange;">性质</span>与<span style="color:blue;">公式</span>

<ul>

#### <span style="color: gray;">(1) 性质

<ul>

*   **有界**性
    *   ![](https://api2.mubu.com/v3/document_image/c3d940d7-c851-40b3-bbaa-9187c0acc699-15201174.jpg)
    *   ![](https://api2.mubu.com/v3/document_image/643acf9c-7bb6-4b96-9036-b54e668c58b0-15201174.jpg)
*   **单调**性
    *   ![](https://api2.mubu.com/v3/document_image/18da15e7-6693-4889-96b7-0d48aadcf616-15201174.jpg)
    *   ![](https://api2.mubu.com/v3/document_image/97a1b1e3-e68a-4206-9b20-729b9f05836f-15201174.jpg)

</ul>

#### <span style="color: gray;">(2) 公式

<ul>

*   1 ![](https://api2.mubu.com/v3/document_image/85c31956-a87f-471f-9434-8dd28864f24e-15201174.jpg)
    *   逆事件概率公式
*   2
    *   ![](https://api2.mubu.com/v3/document_image/777c2633-0780-4f54-a7a0-048ec9f88885-15201174.jpg)
        *   加法公式
    *   ![](https://api2.mubu.com/v3/document_image/f967bde4-2f7e-47e2-a25a-7e221d4ecbf9-15201174.jpg)
        *   减法公式
    *   **乘法**公式
        *   ![](https://api2.mubu.com/v3/document_image/10533fc0-fbc6-44c1-ad2c-9117c260bdf2-15201174.jpg)
        *   ![](https://api2.mubu.com/v3/document_image/c4489851-6083-4e1d-aff0-2b149c145500-15201174.jpg)
*   <span style="color:darkorange;">3</span>
    *   **条件**概率公式 ![](https://api2.mubu.com/v3/document_image/bbebf5bc-65bd-4f2d-af13-61b3f07301a3-15201174.jpg)
        *   //带着条件B 筛选A中的目标
    *   **<span style="color:darkorange;">全概率</span>**公式
        *   条件
            *   ![](https://api2.mubu.com/v3/document_image/38567a04-2694-4124-8712-db7e8b7ea9ce-15201174.jpg)
            *   ![](https://api2.mubu.com/v3/document_image/46c07830-19d0-45eb-9a10-9e871e8db948-15201174.jpg)
        *   则有
            *   ![](https://api2.mubu.com/v3/document_image/782f282a-5d98-440c-bd2a-840bf79df906-15201174.jpg)
    *   **<span style="color:darkorange;">贝叶斯</span>**公式（逆概率公式）
        *   条件
            *   ![](https://api2.mubu.com/v3/document_image/38567a04-2694-4124-8712-db7e8b7ea9ce-15201174.jpg)
            *   ![](https://api2.mubu.com/v3/document_image/46c07830-19d0-45eb-9a10-9e871e8db948-15201174.jpg)
        *   则有
            *   ![](https://api2.mubu.com/v3/document_image/ed978a39-c6c9-4f96-88b7-e8dbf4327d6e-15201174.jpg)

</ul>

</ul>

### <span style="color: gray;">2 <span style="color:purple;">独立</span>性

<ul>

*   (1) **事件**的独立性
    *   a. <u>描述性</u>定义
        *   其中一个/任何几个事件 发生的概率<span style="color:green;">不受</span>其他事情的<span style="color:blue;">影响</span>
            *   相互独立 与 两两独立
    *   b. **数学**定义
        *   ![](https://api2.mubu.com/v3/document_image/417e5a55-499a-47f9-935d-8ecebb6f78bf-15201174.jpg)
    *   c. 实验定义
        *   实验结果相互独立
*   (2) n重伯努利概型
    *   a. 独立检验 序列 模型
        *   **独立重复**相同实验
        *   结果及其**概率**不变
        *   每次事件相互独立
    *   b. n重伯努利模型
        *   结果
            *   仅$A$ 和$\overline{A}$
        *   每次A发生的概率相等
        *   独立重复n次

</ul>

</ul>

</ul>

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

</ul>

</ul>

2.  **~** <span style="color:green;">分类</span>

<ul>

## <span style="color: gray;">A. 一维<span style="color:green;">离散</span>型随机变量

<ul>

### <span style="color: gray;"> **(1) 离散型随机变量 | 概率分布**
*   a. 离散型
    *   $X$ 只能取有限个
        *   ![](https://api2.mubu.com/v3/document_image/dd8216b1-8d7f-4277-b77c-e6e3223c3e67-15201174.jpg)
*   b. 分布列(分布律、**概率分布**)
    *   1) 表示形式
        *   记为<span style="color:blue;">$P\{X=x_i\}=p_i$</span>
            *   $i=1,2,\dots$
        *   <span style="color:green;">常用</span> <span style="color:blue;">表格</span>/矩阵 表示
            *   ![](https://api2.mubu.com/v3/document_image/94acb166-0859-4b4f-be14-eb7b6b0bb7d7-15201174.jpg)
            *   ![](https://api2.mubu.com/v3/document_image/f78cd6ff-265f-4c4c-aeac-9023d4026faa-15201174.jpg)
    *   2) **数列** 是 离散型随机变量 的<u>概率分布 </u>的充要条件:
        *   ![](https://api2.mubu.com/v3/document_image/5e0ca1b5-d521-43ed-b22a-33fd3cdeaad3-15201174.jpg)
### <span style="color: gray;"> **(2) <span style="color:darkorange;"><u>五大分布</u></span>**
*   按 概率分布type 分
    *   **0—1分布**B(1.p)
        *   设定
            *   ![](https://api2.mubu.com/v3/document_image/31a27d44-f710-4be0-9cab-232a967215c8-15201174.jpg)
                *   即 ![](https://api2.mubu.com/v3/document_image/db932eb7-83f7-4cad-9ed9-5edd362fbd18-15201174.jpg)
        *   称X服从参数为p的 **0-1分布**
            *   记为
                *   ![](https://api2.mubu.com/v3/document_image/a659efad-9510-4374-b3c4-820616803e09-15201174.jpg)
    *   **二项分布**B(n.p)
        *   设定
            *   X的 概率分布
                *   ![](https://api2.mubu.com/v3/document_image/7aa3b056-0c65-4526-9e30-ab0553457575-15201174.jpg)
                    *   ![](https://api2.mubu.com/v3/document_image/6a5d76d0-69da-4878-bc19-4d47eadcdf3c-15201174.jpg)
        *   称X服从参数为(n,p)的二项分布
            *   //常与 n重伯努利实验一起运用
            *   记为
                *   ![](https://api2.mubu.com/v3/document_image/11e9d0e8-042d-4fee-a73c-2118fb6cd4a4-15201174.jpg)
    *   **泊松分布**P(λ)
        *   设定
            *   X的 **概率分布**
                *   ![](https://api2.mubu.com/v3/document_image/c845bca0-7d3d-45d1-8bc5-fd7e9c585e3d-15201174.jpg)
                    *   ![](https://api2.mubu.com/v3/document_image/352aeb00-3d4b-4bb0-b631-1572a78cd7fc-15201174.jpg)
        *   称X服从参数为λ的泊松分布
            *   记为$X$~$p(\lambda)$
    *   <u>**几何**</u>分布G(p)
        *   设定
            *   X的 **概率分布**
                *   ![](https://api2.mubu.com/v3/document_image/650657e6-0d95-4c67-ac77-494907ce10f4-15201174.jpg)
                    *   ![](https://api2.mubu.com/v3/document_image/a8da1614-f4a9-4a04-af4a-0e6a4f588317-15201174.jpg)
        *   称X服从参数为p的几何分布
            *   记为$X$~$G(p)$
    *   <u>**超几何**</u>分布H(n，N，M)
        *   设定
            *   ![](https://api2.mubu.com/v3/document_image/899d5710-7ca2-486f-aeed-a05431ddbee2-15201174.jpg)
                *   ![](https://api2.mubu.com/v3/document_image/52df4124-fd39-4330-9f00-28dfff42e8bc-15201174.jpg)
        *   称X服从参数为(n，N，M) 的 超几何分布
            *   记为$X$~H(n,N,M)

</ul>

## <span style="color: gray;">B. 一维<span style="color:blue;">连续</span>型随机变量

<ul>

### <span style="color: gray;">(1) 连续型随机变量 | 概率密度
*   a. 基本定义
    *   由 <u>分布函数</u> <span style="color:blue;">type</span> <span style="color:green;">确定</span> X类型
        *   $F(x)=\int_{-\infty}^x {f(t)} \,{\rm d}t$
            *   $f(x)$ 是非负可积函数
        *   称
            *   <span style="color:blue;">X </span>为 <span style="color:green;"><u>连续</u></span><u>型 随机变量</u>
            *   <span style="color:blue;">$f(x)$</span> 为X的 **概率密度函数**，简称 <span style="color:blue;">概率密度</span>
                *   记为 $X$ ~ $f(x)$
*   b. 性质
    *   1) f(x)为 <span style="color:blue;">概率密度</span> 的<span style="color:green;">充要</span>条件
        *   $f(x) \ge 0$ 且 $\int_{-\infty}^{+\infty}{f(x)}\,{\rm d}x = 1$
            *   函数在 实数域积分=1
    *   2) $X$ ~ $f(x)$
        *   ① 对任意实数c，有$P{X=c}=0$
        *   ② 对实数轴上任一集合B，有$P{x \in B }=\int_B f(x)\,{\rm d}x$
            *   特别地
                *   不管分布函数区间开闭， ![](https://api2.mubu.com/v3/document_image/64d435f3-e72e-48e8-aa48-dd832a4460e7-15201174.jpg)
                *   均可 用 概率密度 在区间上的积分表示 ![](https://api2.mubu.com/v3/document_image/34ef9683-b1f9-46d2-973a-f77232596538-15201174.jpg)
### <span style="color: gray;">(2) <span style="color:darkorange;">三大分布</span>
*   由 概率密度<span style="color:green;">f(x)</span> 和 分布函数<span style="color:blue;">F(x) </span>共同确定 //仅正态分布 仅由f(x)确定
    *   均匀分布 U(a,b)
        *   ![](https://api2.mubu.com/v3/document_image/01762cd4-e32e-4ec2-9725-a5f13e974e1d-15201174.jpg)
            *   ![](https://api2.mubu.com/v3/document_image/e6ba235d-de58-426b-a14a-b29e6b54ebc3-15201174.jpg)
    *   指数分布 E(λ)
        *   ![](https://api2.mubu.com/v3/document_image/0bf8b153-8b79-4841-b9cf-0ecea6bdfa85-15201174.jpg)
            *   ![](https://api2.mubu.com/v3/document_image/13c9002d-1dc2-4c76-9775-65c07e11caf1-15201174.jpg)
    *   <span style="color:blue;">正态</span>分布 $N(\mu,\sigma^2)$
        *   a. 定义
            *   概率密度
                *   ![](https://api2.mubu.com/v3/document_image/5594b8b7-5baf-4202-a872-44bd88a7c0b5-15201174.jpg)
                    *   其中
                        *   ![](https://api2.mubu.com/v3/document_image/a0efb0f0-1699-45b7-b8c4-3da63077b992-15201174.jpg)
                        *   ![](https://api2.mubu.com/v3/document_image/79a8c0d7-494f-42d9-b2c8-5a11a717a805-15201174.jpg)
            *   称
                *   ① X 服从参数为$(\mu,\sigma^2)$ 的正态分布
                    *   X 为 正态变量
                *   ② μ=0 σ=1时的 正态分布N（0,1）为 **标准正态分布**
        *   f(x)**图像**
            *   正态分布image
                *   ![](https://api2.mubu.com/v3/document_image/53e58d10-a026-4578-8730-12bc6b063e2f-15201174.jpg)
            *   标准正态分布image
                *   ![](https://api2.mubu.com/v3/document_image/e738eafe-bae4-4b14-b554-2aed32f17275-15201174.jpg)
                    *   概率密度 φ(x)
                        *   ![](https://api2.mubu.com/v3/document_image/1bc0ab36-9050-4d64-abec-2cfe7385289c-15201174.jpg)
                    *   分布函数 Φ(x)
                        *   ![](https://api2.mubu.com/v3/document_image/72539321-9fe5-4e23-aada-33ec21d82c38-15201174.jpg)
                    *   特点
                        *   ① 分布函数Φ(x)
                            *   ![](https://api2.mubu.com/v3/document_image/3e48b3e1-dbee-423a-b15c-7292d0b8289b-15201174.jpg)
                                *   ![](https://api2.mubu.com/v3/document_image/b978caf4-c600-4353-9b93-712246e167df-15201174.jpg)
                        *   ② 上侧α分位数(上α分位点)

</ul>

</ul>

## <span style="color: gray;"> ~<span style="color:darkorange;">函数</span>的分布

<ul>

### <span style="color: gray;">A. 随机变量函数 //
*   X、Y都是 随机变量,函数$y=g(x)$
*   称 $Y=g(x)$ 是 随机变量X的函数
    *   eg.
        *   ![](https://api2.mubu.com/v3/document_image/d372b870-6e64-4a97-b492-057717f8db9c-15201174.jpg)
### <span style="color: gray;">B. 随机变量函数的分布
*   1) 离散型→离散型
    *   X是离散型 随机变量，Y也是离散型
        *   X概率分布
            *   ![](https://api2.mubu.com/v3/document_image/5091ad0b-d407-495c-a61c-a8e54058f59d-15201174.jpg)
        *   Y概率分布
            *   ![](https://api2.mubu.com/v3/document_image/443a381d-ca2a-4cbb-9bff-19020c2006e3-15201174.jpg)
            *   即
                *   ![](https://api2.mubu.com/v3/document_image/92272db1-7c2a-43ba-87b6-64a8e7606a5e-15201174.jpg)
*   2) 连续型→连续型（混合型）
    *   X、Y都是 连续型
        *   X的f(x)与F(x)
            *   ![](https://api2.mubu.com/v3/document_image/06a17111-80eb-412d-bda8-b6350bfb3b0d-15201174.jpg)
        *   y的f(x)与F(x) //?用分布函数法求得
            *   ![](https://api2.mubu.com/v3/document_image/9900fafa-64e0-4ea6-bc54-371d6213e2b6-15201174.jpg)

</ul>

</ul>

</ul>

# <span style="color: gray;"><span style="color:green;">多维</span>.. 

<ul>

## <span style="color: gray;"><span style="color:darkorange;">basic</span>

<ul>

### <span style="color: gray;">(1) 二维（n维）随机变量

<ul>

#### <span style="color: gray;">A. 概念
*   1) n维随机变量
    *   <span style="color:blue;">n</span>个<span style="color:blue;">随机变量</span>$X_1,X_2,\dots,X_n$定义在 同一个 样本空间Ω 上
    *   称 其 为 <u>n维</u>**随机变量** or <u>n维 </u>随机<span style="color:darkorange;">向量</span>
        *   $X_i$ 称为 第i个分量
*   2) 二维随机变量
    *   当n=2时，记为 $(X,Y)$
#### <span style="color: gray;">B. 联合<span style="color:darkorange;">分布函数</span>
*   1) 概念
    *   ① n元函数:
        *   ![](https://api2.mubu.com/v3/document_image/cc0cc246-2e31-406a-8a7f-d06b842fbc48-15201174.jpg)
            *   n维随机变量的 联合<span style="color:darkorange;">分布函数</span>
    *   ② 当n=2时，二元函数
        *   ![](https://api2.mubu.com/v3/document_image/74687f79-2716-4ad8-9ef3-ae93d2424bb7-15201174.jpg)
        *   记为 $(X,Y)$~$F(x,y)$
        *   F(x,y)是 事件A={X≤x}与B={Y≤y} 同时发生的概率
*   2) 性质
    *   ① 单调，F(X,Y)是 单调不减 函数
        *   即 单增or取等 ![](https://api2.mubu.com/v3/document_image/c26b1f77-bdac-4acb-8e4f-5c71373c1e6d-15201174.jpg)
    *   ② 右连续
    *   ③ 有界性
    *   ④ 非负性
        *   对任意$x_1 < x_2$ $y_1 < y_2$ 有 ![](https://api2.mubu.com/v3/document_image/0deb4cf1-cab7-4286-923f-9ea52ff86c67-15201174.jpg)
#### <span style="color: gray;">C. <span style="color:blue;">边缘</span><span style="color:darkorange;">分布函数</span>
*   1) 基本定义
    *   设定: 联合分布函数$F(X,Y)$
    *   随机变量 $X$ 、$Y$ 的分布函数<span style="color:blue;">$F_X(x)$</span> 、<span style="color:blue;">$F_Y(x)$</span>
        *   称为$(X,Y)$ 关于X 和 关于Y 的 <span style="color:blue;">边缘</span><span style="color:darkorange;">分布函数</span>
*   2) 性质
    *   a. 推导
        *   i
            *   ![](https://api2.mubu.com/v3/document_image/e28ace47-8b58-40db-bb4d-d4cf7c99683e-15201174.jpg)
        *   ii
            *   ![](https://api2.mubu.com/v3/document_image/d87f0213-5c9c-48d1-8d34-2c5510759a9e-15201174.jpg)
            *   ![](https://api2.mubu.com/v3/document_image/b4a29c99-56d6-487e-a079-a126ffaab532-15201174.jpg)
    *   b. 结论
        *   $F_X(x)=F(x,+\infty)$ //Y同理

</ul>

### <span style="color: gray;">(2) <span style="color:green;">离散</span>型~ 与 <span style="color:blue;">连续</span>型~

<ul>

#### <span style="color: gray;">A. 二维 <span style="color:green;">离散</span>型 随机变量

<ul>

*   **0) 二维 离散型~ 的定义**
    *   $(X,Y)$ 只能取有限对值 或 可列对值
*   **1) 分布列(分布律|<span style="color:darkorange;">概率分布</span>)**
    *   a. 定义
        *   称 ![](https://api2.mubu.com/v3/document_image/743a030b-d2e1-45bc-b57d-3beb17ee379c-15201174.jpg)
        *   为 (X,Y)的分布律 或 随机变量X、Y 的联合分布律
            *   记为$(X,Y)$ ~ $p_{ij}$
    *   b. 表示
        *   常用表格形式表示
            *   ![](https://api2.mubu.com/v3/document_image/f1c4f343-ef30-4118-8db4-9937208da614-15201174.jpg)
    *   c. 性质
        *   数列{$p_{ij}$} 是 某一/二维 离散型随机变量的概率分布的 充要条件
            *   $p_{ij}$ ≥0
            *   ![](https://api2.mubu.com/v3/document_image/f137f58b-ae1b-42dc-b243-e41ecf95e35f-15201174.jpg)
*   **2) 联合<span style="color:darkorange;">分布函数 |</span> <span style="color:blue;">边缘分布 | 条件分布</span>**
    *   a. 联合分布
        *   ① 总体：
            *   ![](https://api2.mubu.com/v3/document_image/e11cc46f-f964-4e54-8120-144dba6d8e2d-15201174.jpg)
        *   ② 某一区域G
            *   ![](https://api2.mubu.com/v3/document_image/c3e42504-dd20-40b7-9383-822a7dcdd6ea-15201174.jpg)
    *   b. 边缘分布
        *   对X
            *   ![](https://api2.mubu.com/v3/document_image/abf29994-553d-473f-ae23-a7294cf54b2c-15201174.jpg)
            *   ![](https://api2.mubu.com/v3/document_image/73a1cd4a-1c74-4ba7-80e8-f08bdda8de66-15201174.jpg)
        *   对Y
            *   ![](https://api2.mubu.com/v3/document_image/32e78c84-7dc0-477f-82a1-816cbc130538-15201174.jpg)
            *   ![](https://api2.mubu.com/v3/document_image/ce603a6c-952c-44aa-859f-5d0cdc839326-15201174.jpg)
    *   c. 条件分布
        *   <span style="color:green;">满足</span><span style="color:darkorange;">固定</span>$i$ or $j$ 条件
            *   ① 固定i,且$p_{(i·)}>0$
                *   可定义在$X=x_i$ 条件下的
                *   条件分布
                    *   ![](https://api2.mubu.com/v3/document_image/9cb2469c-c903-40d1-bdab-26e9834ead4c-15201174.jpg)
            *   ② 固定j,且$p_{(·j)}>0$
                *   可定义在$Y=y_j$ 条件下的
                *   条件分布
                    *   ![](https://api2.mubu.com/v3/document_image/6f161c0f-3319-4b79-8486-c55df1b6988a-15201174.jpg)

</ul>

#### <span style="color: gray;">B. 二维 <span style="color:blue;">连续</span>型 随机变量

<ul>

##### <span style="color: gray;">1) 概率密度 **$f(x,y)$**
*   a. 定义
    *   联合分布函数F(X,Y)可表示为
        *   ![](https://api2.mubu.com/v3/document_image/e87cc0ec-968f-4e93-9654-9b2f3eb41436-15201174.jpg)
    *   称
        *   $(X,Y)$为 二维连续型随机变量
        *   $f(x,y)$ 为$(X,Y)$的概率密度
            *   记为$(X,Y)$~$f(x,y)$
*   b. f(x,y)是概率密度的 充要条件
    *   ![](https://api2.mubu.com/v3/document_image/b74af039-db8f-47e9-bd19-31259e3e0517-15201174.jpg)
##### <span style="color: gray;"> 2) 联合<span style="color:darkorange;">分布函数</span> 与 概率密度 | <span style="color:green;">边缘概率密度 | <span style="color:blue;">条件概率密度</span></span>
*   a. 联合<span style="color:darkorange;">分布函数 </span>$F(X,Y)$<span style="color:darkorange;"> </span>与 概率密度 $f(x,y)$
    *   i. $G$ 为平面上的某区域
        *   则 ![](https://api2.mubu.com/v3/document_image/ae4e9e4c-c892-4f91-a46b-0de809a9c8a7-15201174.jpg)
    *   ii. $f(x,y)$ 在点(x,y)处连续
        *   则 ![](https://api2.mubu.com/v3/document_image/63a5adb8-e4b4-4d23-bf6a-3c898c583b0a-15201174.jpg)
    *   iii. $F(x,y)$ 连续且可导
        *   则
            *   (X,Y)是连续型随机变量
            *   概率密度为
                *   ![](https://api2.mubu.com/v3/document_image/afaffc1a-a76c-4984-b335-00a6c2d5e3bc-15201174.jpg)
*   b. <span style="color:green;">边缘</span>概率密度
    *   边缘分布函数 可表示为
        *   ![](https://api2.mubu.com/v3/document_image/0c42bee8-c4f7-453d-832b-565235d8ffcb-15201174.jpg)
    *   称
        *   ① 对X
            *   $X$是连续型随机变量
            *   其概率密度为
                *   $f_X(x)$
                    *   ![](https://api2.mubu.com/v3/document_image/df974527-d985-49d0-8fcb-3639b5da7b85-15201174.jpg)
        *   ② 对y
            *   $Y$是连续型随机变量
            *   其概率密度为
                *   $f_Y(y)$
                    *   ![](https://api2.mubu.com/v3/document_image/a919d367-310d-4dd9-9e2b-93161246ba1c-15201174.jpg)
*   c. <span style="color:blue;">条件</span>概率密度
    *   a. 定义
        *   设定：$(X,Y)$ ~ $f(X,Y)$ ,边缘概率密度$f_X(x)$ or$f_Y(y)$ >0
            *   称
                *   ① X=x条件
                    *   ![](https://api2.mubu.com/v3/document_image/234fb472-e52d-479b-8080-8c22c67ee4ad-15201174.jpg)
                    *   为Y在"X=x"条件下的 条件概率密度
                *   ② Y条件
                    *   ![](https://api2.mubu.com/v3/document_image/363cad14-63b4-4953-878e-bc30ebd040a3-15201174.jpg)
                    *   为X在"Y=y"条件下的 条件概率密度
    *   b. 概率密度 乘法公式
        *   ![](https://api2.mubu.com/v3/document_image/1a2a6f37-c70e-48fa-940f-4c281a806b91-15201174.jpg)
    *   c. 条件分布函数
        *   ① X=x条件(x为常量
            *   ![](https://api2.mubu.com/v3/document_image/1352b8af-746b-469b-8d4e-b73053ff30ba-15201174.jpg)
        *   ② Y=y条件(y为常量
            *   ![](https://api2.mubu.com/v3/document_image/cab164bd-c364-4236-8f92-c0e3a3fcc5ce-15201174.jpg)
##### <span style="color: gray;"> 3) 常见的二维分布
*   按 概率密度f(x,y) 判断
    *   a. 二维均匀分布
        *   概率密度为
            *   ![](https://api2.mubu.com/v3/document_image/a25732b4-e743-420d-a18b-77080fc213fe-15201174.jpg)
                *   其中$S_D$为区域D的面积
    *   b. 二维正态分布
        *   i. 定义
            *   f(x,y)为
                *   ![](https://api2.mubu.com/v3/document_image/980962a7-c665-4a89-bc27-c48a71e1f98d-15201174.jpg)
            *   称(X,Y)服从参数为$\mu_1,\mu_2,\sigma_1^2,\sigma_1^2,\rho$ 的二维正态分布
                *   记为 ![](https://api2.mubu.com/v3/document_image/06273557-f8be-49f2-9738-a513156d2d0a-15201174.jpg)
        *   ii. 阐述
            *   $X$ ~ $N(\mu_1,\sigma_1^2)$ ,$Y$ ~ $N(\mu_2,\sigma_2^2)$ ,ρ为X 与 Y 的相关系数
                *   即 ![](https://api2.mubu.com/v3/document_image/6c2424a4-c889-43e4-b520-15e4d7922f46-15201174.jpg)
            *   ② $X,Y$的条件分布都是正态分布
            *   ③ $aX+bY$ (a≠0或b≠0) 服从正态分布
            *   ④ $X$与$Y$相互独立的充要条件
                *   $X$与$Y$ 不相关 即 ρ=0

</ul>

</ul>

</ul>

## <span style="color: gray;">性质-<span style="color:darkorange;">独立性</span>

<ul>

### <span style="color: gray;">(1) <span style="color:darkorange;">概念</span>

<ul>

#### <span style="color: gray;">a. <span style="color:green;">二维</span>随机变量$(X,Y)$

<ul>

*   对 联合分布函数$F(X,Y)$ 和 边缘分布函数$F_X(x)$ $F_Y(y)$
*   都有$F(X,Y)$ = $F_X(x)$·$F_Y(y)$
*   称X与Y相互独立

</ul>

#### <span style="color: gray;">b. <span style="color:blue;">n维</span>随机变量($X_1,X_2,\dots,X_n$)

<ul>

*   联合分布函数 = 边缘分布函数的乘积
    *   ![](https://api2.mubu.com/v3/document_image/5d165555-0ed8-4ccd-888e-0602ee8a00d2-15201174.jpg)
        *   称$X_1,X_2,\dots,X_n$ 相互独立
*   若$X_1,X_2,\dots,X_n$ 相互独立，任意k(k≥2)，$X_1,X_2,\dots,X_k$ 相互独立

</ul>

#### <span style="color: gray;">c. 两组多维随机变量($X_1,X_2,\dots,X_n$)与($Y_1,Y_2,\dots,Y_n$)

<ul>

*   联合分布函数 等于 各自的联合分布函数 的乘积
    *   ![](https://api2.mubu.com/v3/document_image/98cf4cb5-1951-459d-89a5-2f735f8e226a-15201174.jpg)
        *   即 ![](https://api2.mubu.com/v3/document_image/5c8dfdce-c0a4-481c-badf-a31a06f72773-15201174.jpg)

</ul>

</ul>

### <span style="color: gray;">(2) 相互独立的<span style="color:darkorange;">充要</span><span style="color:blue;">条件</span>

<ul>

*   a. n个随机变量
    *   n个<span style="color:blue;">实数</span>$x_i$ ,n个<u>事件</u>{$X_1 \le x_1$} ,…, {$X_n \le x_n$} 相互独立
*   b. <span style="color:green;">离散</span>型 随机变量
    *   联合分布函数F：
        *   联合分布=<span style="color:darkorange;">边缘</span>分布相乘
            *   二维~
                *   ![](https://api2.mubu.com/v3/document_image/aa842223-2f26-4c81-9637-f062203ced23-15201174.jpg)
            *   n维~
                *   即 ![](https://api2.mubu.com/v3/document_image/f4b9a1b2-2b91-4784-b7ad-8f3fd88472f6-15201174.jpg)
*   c. <span style="color:blue;">连续</span>型 随机变量
    *   概率<span style="color:green;">密度</span>f：
        *   概率密度=<span style="color:darkorange;">边缘</span>概率密度相乘
            *   二维
                *   ![](https://api2.mubu.com/v3/document_image/c84e0d09-4f27-4d1f-9fb6-f974098dc0aa-15201174.jpg)
            *   n维
                *   ![](https://api2.mubu.com/v3/document_image/211c3af6-cfff-4e6d-bdf8-8cd82bdd04a6-15201174.jpg)

</ul>

### <span style="color: gray;">(3) <span style="color:green;">相互</span><span style="color:blue;">独立</span>的<span style="color:darkorange;">性质</span>

<ul>

*   A. n维：
    *   $X_1,X_2,\dots,X_n$ 相互独立
        *   则 其中任意<span style="color:blue;">$k$</span> $(2 \le k \le m)$ 个随机变量也~
*   B. <span style="color:blue;">二</span>维：
    *   X与Y独立
        *   离散型
            *   <span style="color:blue;">条件</span>分布=<span style="color:green;">边缘</span>分布
        *   连续型
            *   <span style="color:blue;">条件</span>概率=<span style="color:green;">边缘</span>概率
*   C. n维 与 $g()$
    *   $X_1,X_2,\dots,X_n$ 相互独立
        *   $g_1(x),g_2(x),\dots,g_n(x)$ 为一元连续函数
            *   则$g_1(X_1),g_2(X_2),\dots,g_n(X_n)$ ~
    *   $X_{11},\dots,X_{1t_1},X_{21},\dots,X_{2t_2},\dots,X_{n1},\dots,X_{nt_n}$ 相互独立
        *   $g_i$ 是$t_i$元连续函数
            *   $g_1X_{11},\dots,X_{1t_1}),g_2(X_{21},\dots,X_{2t_2}),\dots,g_n(X_{n1},\dots,X_{nt_n})$ ~

</ul>

</ul>

## <span style="color: gray;"><u>多维</u>随机变量函数的<span style="color:darkorange;">分布</span>

<ul>

### <span style="color: gray;">(1) 概念

<ul>

*   $X,Y$为随机变量，$g(x,y)$是二元函数
*   以$X,Y$作为变量的函数<span style="color:blue;">$U=g(X,Y)$</span>也是 随机变量
*   称<span style="color:blue;">$U$</span>为随机变量$X,Y$ 的函数
    *   eg. U
        *   ![](https://api2.mubu.com/v3/document_image/85717383-09bc-4317-b98a-9d9a338ce91c-15201174.jpg)
        *   ![](https://api2.mubu.com/v3/document_image/fa26d9bf-96c2-4ae2-b481-f36a2b2354f7-15201174.jpg)
    *   eg. 题
        *   ![](https://api2.mubu.com/v3/document_image/e5cec2ee-63d2-4294-8e50-6f5a833ecd67-15201174.jpg)
        *   ![](https://api2.mubu.com/v3/document_image/cf3e4a3b-8a12-4324-b92d-1277d4f0e223-15201174.jpg)

</ul>

### <span style="color: gray;">(2) 求法

<ul>

*   已知(X,Y)的联合分布，求函数Z=g(X,Y)的分布
    *   step1 确定X,Y类型
        *   A. 均为 <span style="color:green;">离散</span>型
            *   1) 则Z也是离散型
            *   2) 求出Z的值，求其相应的$p$
            *   3) 用 一般阶梯模式(<span style="color:blue;">矩阵法</span>) 即可求得Z的分布
            *   add. eg
                *   问
                    *   背景： ![](https://api2.mubu.com/v3/document_image/e9c6f07f-e922-422f-9cea-1a88d7b2bf85-15201174.jpg)
                    *   求：
                        *   1 ![](https://api2.mubu.com/v3/document_image/d648f7ac-828c-4dff-b300-7059cc0955f7-15201174.jpg)
                        *   2 ![](https://api2.mubu.com/v3/document_image/ffaba3f6-4cb7-4b66-b256-337fca14c9db-15201174.jpg)
                        *   3 ![](https://api2.mubu.com/v3/document_image/e2de9c00-5c7d-4d3e-baab-236ca0629437-15201174.jpg)
        *   B. 其中一个<span style="color:green;">离散</span>，另一个<span style="color:purple;">非</span><span style="color:green;">离散</span>
            *   1) 对离散型 的 一切可能值 进行全集分解
            *   2) <span style="color:darkorange;">全概率</span>公式 求得Z的分布
            *   add. eg
                *   问： ![](https://api2.mubu.com/v3/document_image/eb2c4f6b-5d25-4343-9f00-95dd0569c404-15201174.jpg)
        *   C. 均为 <span style="color:blue;">连续</span>型
            *   1) Z的分布函数为
                *   ![](https://api2.mubu.com/v3/document_image/067874e7-8ebb-47d6-a300-528a27179e48-15201174.jpg)
            *   2) 求概率密度 直用
                *   (3)中公式
    *   step2 采用相应公式计算

</ul>

### <span style="color: gray;">(3) <span style="color:green;">相互</span><span style="color:blue;">独立</span> 随机变量函数 的<span style="color:darkorange;">分布</span> | <span style="color:blue;">卷积</span>公式

<ul>

*   A. 求 (X,Y)~f(x,y)的 不同形式 的 概率密度
    *   1) 和分布Z=X+Y
    *   2) 差分布Z=X-Y
    *   3) 积分布Z=XY
    *   4) 商分布Z=X/Y
    *   5) max{X,Y}分布
    *   6) min{X,Y}分布
    *   add. 常见分布的可加性

</ul>

</ul>

</ul>

# <span style="color: gray;">03 <span style="color:blue;">数字</span><span style="color:darkorange;">特征</span>

<ul>

## <span style="color: gray;">一维随机变量的<span style="color:blue;">数字</span><span style="color:darkorange;">特征</span>

<ul>

### <span style="color: gray;">(1) 数学期望$E(X)$

<ul>

*   又称 <u>概率平均值</u>，简称<u> 期望</u>or<u>均值</u>
*   A. <u>概念</u>
    *   1) X为 <span style="color:green;">离散</span>型
        *   a. $E(X)$
            *   X是离散型随机变量，分布列为$p_i$
            *   级数$\sum_{i=1}^∞ {x_ip_i}$ 绝对收敛
            *   称
                *   随机变量X的 数学期望存在
                    *   <span style="color:blue;">$\sum_{i=1}^∞ {x_ip_i}$</span> ~
                        *   记为E(X)或EX
                *   即$EX=\sum_{i=1}^∞ {x_ip_i}$
            *   %否则称 X 数学期望 不存在
        *   b. $E[g(X)]$
            *   级数$\sum_{i=1}^∞ {g(x_i)p_i}$ 绝对收敛
                *   称$Y=g(x)$ 的数学期望存在
                    *   即 $E[g(X)]$ =$\sum_{i=1}^∞ {g(x_i)p_i}$
                *   %否则称 g(X) 数学期望 不存在
    *   2) X为 <span style="color:blue;">连续</span>型
        *   a. $E(X)$
            *   X是连续型随机变量，概率密度为f(x)
            *   积分<span style="color:blue;">$\int_{-\infty}^{+\infty} {xf(x)} \,{\rm d}x$</span> 绝对收敛
            *   称
                *   随机变量X的 数学期望存在
                *   $EX=\int_{-\infty}^{+\infty} {xf(x)} \,{\rm d}x$
            *   %否则称 X 数学期望 不存在
        *   b. $E[g(X)]$
            *   积分$\int_{-\infty}^{+\infty} {xf(x)} \,{\rm d}x$ 绝对收敛
                *   称$Y=g(x)$ 的数学期望存在
                    *   即 $E[g(X)]$ =$\int_{-\infty}^{+\infty} {g(x)f(x)} \,{\rm d}x$
                *   %否则称 g(X) 数学期望 不存在
*   B. <span style="color:darkorange;">性质</span>
    *   拆分
        *   1) 数乘or相加
            *   base: ![](https://api2.mubu.com/v3/document_image/c605b77e-d515-4975-acdd-ca8c87004923-15201174.jpg)
                *   $a_i$ 为任意常数
            *   特殊：
                *   a. 常数 的E 是常数本身
                    *   ![](https://api2.mubu.com/v3/document_image/490d03bf-c556-4358-b47d-a967d5537225-15201174.jpg)
                    *   ![](https://api2.mubu.com/v3/document_image/dc62abcf-8493-4bec-9131-7c90c8b6fffe-15201174.jpg)
                *   b. $X,Y$ 也可拆
                    *   ![](https://api2.mubu.com/v3/document_image/a1761388-5c05-4cf3-89c0-9c450c367edb-15201174.jpg)
        *   2) $X,Y$相乘
            *   求 相互独立 随机变量 乘积 的E=随机变量 各自的E 相乘
                *   a. 一般性
                    *   ![](https://api2.mubu.com/v3/document_image/5da59a86-5acb-4bd9-9351-0129a5f061f4-15201174.jpg)
                    *   ![](https://api2.mubu.com/v3/document_image/95eceaba-08ea-498a-831e-5106e6656bb6-15201174.jpg)
                *   b. 二维
                    *   1 ![](https://api2.mubu.com/v3/document_image/22ba9755-67f4-4e6e-9bc6-377982c3477b-15201174.jpg)
                    *   2 ![](https://api2.mubu.com/v3/document_image/b3c409be-27d6-4808-a3c7-7787142b0558-15201174.jpg)

</ul>

### <span style="color: gray;">(2) 方差$DX$ | 标准差$\sigma(X)$

<ul>

*   A. 概念
    *   1) $DX$
        *   $DX=$ $E[(X-EX)^2]$ =<span style="color:blue;">$E(X^2)-(EX)^2$</span>
    *   2) $\sigma(X)$
        *   $\sigma(X)$=<span style="color:blue;">$\sqrt{DX}$</span>
    *   3) $X*$
        *   标准化随机变量
            *   ![](https://api2.mubu.com/v3/document_image/57752eb2-fade-4eac-ad80-a6681df3c84e-15201174.jpg)
                *   此时
                    *   EX*=0
                    *   DX*=1
*   B. 性质
    *   1) D(X)≥0，$E(X^2)$=$DX$+$(EX)^2$
        *   ≥$(EX)^2$
    *   2) $Dc=0$
        *   常数的 方差为0
    *   3) $D(aX+b)=a^2DX$
    *   4) $D(X \pm Y)=DX+DY \pm 2Cov(X,Y)$
        *   $Cov(X,Y)$
            *   <span style="color:green;">协</span><span style="color:blue;">方差</span>
            *   $Cov(X, Y)$
            *   $= E\left[\left(X - E[X]\right)\left(Y - E[Y]\right)\right]$
            *   =<span style="color:blue;"> $E[XY] - E[X]E[Y]$</span>
    *   5) $D(aX+bY)=a^2DX+b^2DY$ //X ,Y相互独立
        *   ![](https://api2.mubu.com/v3/document_image/f47819d2-e8c9-4c98-ae60-e82311ff37bc-15201174.jpg)
        *   ![](https://api2.mubu.com/v3/document_image/ccaa78ce-7ba0-4ee7-a074-c2a0a9b87735-15201174.jpg)

</ul>

### <span style="color: gray;">(3) <span style="color:blue;">切比雪夫</span><u>不等式</u>

<ul>

*   X、E(X)、D(X)存在
    *   对任意 ε>0，有
    *   P{|X-EX|≥ε $ \le$ \frac{DX}{ε^2}$
    *   P{|X-EX|<ε} ≥<span style="color:darkorange;">1</span>- <span style="color:blue;">$\frac{DX}{ε^2}$</span>
*   add. 常用分布的 期望和方差
    *   ![](https://api2.mubu.com/v3/document_image/28dd0f30-ba7a-47d3-8a9d-f8823f4957d7-15201174.jpg)

</ul>

</ul>

## <span style="color: gray;"><span style="color:blue;">二维</span>随机变量的数字特征

<ul>

### <span style="color: gray;">(1) 二维<u>随机变量函数</u>的$E[g(X,Y)]$
*   A. 离散型
    *   ![](https://api2.mubu.com/v3/document_image/69037ab3-e13f-4d06-86d0-c70d4da1ed5c-15201174.jpg)
*   B. 连续型
    *   ![](https://api2.mubu.com/v3/document_image/e839dec6-c2db-4d97-931f-09ffceac8d5f-15201174.jpg)
### <span style="color: gray;">(2) 随机变量的<span style="color:green;">协</span><span style="color:blue;">方差</span>与相关系数
*   A. 概念
    *   1) <span style="color:green;"> 协</span><span style="color:blue;">方差</span>
        *   $Cov(X,Y)$
            *   描述 随机变量$X,Y$ 间偏差的 <span style="color:blue;">关联</span><span style="color:darkorange;">程度</span>
            *   $Cov(X, Y)$
            *   $= E\left[\left(X - E[X]\right)\left(Y - E[Y]\right)\right]$
            *   =<span style="color:blue;"> $E[XY] - E[X]E[Y]$</span>
    *   2) 相关系数$\rho_{xy}$
        *   X,Y之间 <span style="color:darkorange;">线性</span>相关程度 的度量
        *   $\rho_{xy}$ =$\frac{Cov(X,Y)}{\sqrt{DX}\sqrt{DY}}$
            *   若$\rho_{xy}$ =0，X与Y 不相关
            *   若$\rho_{xy}$ ≠0，X与Y 相关
*   B. 性质
    *   1) 对称性
        *   ![](https://api2.mubu.com/v3/document_image/5633e6d2-ee27-4378-9aa3-f7e3e7638f76-15201174.jpg)
        *   ![](https://api2.mubu.com/v3/document_image/4c4aeda6-2c84-4b1c-974c-3d7c6f65a187-15201174.jpg)
    *   2) 线性性
        *   a. 常数
            *   ![](https://api2.mubu.com/v3/document_image/04b7da4a-9870-409f-9c17-7a6f9d4617c3-15201174.jpg)
            *   ![](https://api2.mubu.com/v3/document_image/4f37c042-3bae-4694-9cd1-e3930b1feaac-15201174.jpg)
        *   b. X,Y
            *   ![](https://api2.mubu.com/v3/document_image/cfa8e6b3-ff82-4cd9-86ce-d566ccc72bac-15201174.jpg)
    *   3) 单相关系数$\rho_{xy}$
        *   a. $\rho_{xy}$ 的有界性
            *   $|\rho_{xy}|$≤1
        *   b. 线性关系下的$\rho_{xy}$
            *   若$Y=aX+b$
            *   则 ![](https://api2.mubu.com/v3/document_image/ba3202e4-a355-4329-b220-0745a938f5ce-15201174.jpg)

</ul>

## <span style="color: gray;"><span style="color:darkorange;">独立性</span>与相关性的判定

<ul>

*   (1) 用分布判定独立性
*   (2) 用数字特征判定相关性

</ul>

</ul>

# <span style="color: gray;">
# <span style="color: gray;">04 大数定律 与 <u>中心极限</u>定理

<ul>

## <span style="color: gray;">0 <u>依概率</u><span style="color:darkorange;">收敛</span>

<ul>

*   随机变量X与随机变量序列{$X_n$ }(n=1,2,3,…)，对任意ε有
    *   ![](https://api2.mubu.com/v3/document_image/098d2c00-d83e-4e60-bf5f-9097a4bce644-15201174.jpg)
    *   或 ![](https://api2.mubu.com/v3/document_image/958e55f6-dc94-454b-9ce2-b45b4436e787-15201174.jpg)
*   称 随机变量序列{${X_n}$} **依概率**<u>收敛于</u>随机变量X，记为
    *   ![](https://api2.mubu.com/v3/document_image/c41932c3-db45-4ce6-b60e-d3eca2e2ee48-15201174.jpg)
    *   或 ![](https://api2.mubu.com/v3/document_image/f7d6a3b2-7255-4185-952f-2f6e95ea9ac4-15201174.jpg)

</ul>

## <span style="color: gray;">大数定律

<ul>

*   (1) 切比雪夫大数定律
*   (2) 伯努利大数定律
*   (3) 辛钦大数定律

</ul>

## <span style="color: gray;"><span style="color:darkorange;">中心极限</span>定理

<ul>

### <span style="color: gray;">(1) 列维-林德伯格定理 （<span style="color:blue;">独立 同分布</span>~）

<ul>

*   {${X_n}$}是<u> 独立同分布</u>的 随机变量序列，$EX_i=\mu$,$DX_i=\sigma^2$>0 存在
    *   对任意实数x，有 ![](https://api2.mubu.com/v3/document_image/e07c80e0-d87f-4818-aad9-5dfa0da68652-15201174.jpg)
        *   当n很大时， 独立同分布随机变量的和$\sum_{i=0}^nX_i$ 近似服从正态分布$N(n\mu,n\sigma^2)$
        *   <u>当n很大时</u> ![](https://api2.mubu.com/v3/document_image/f6a8060b-9b58-45e9-81b0-f4c8aa3ec4f4-15201174.jpg)

</ul>

### <span style="color: gray;">(2) 棣莫弗-拉普拉斯定理 （<span style="color:green;">二项</span>分布~）

<ul>

*   随机变量 $Y_n$~$B(n,p)$ $(0 \le p \le 1,,n \ge 1)$
    *   对任意实数x
    *   ![](https://api2.mubu.com/v3/document_image/4c475faa-8a35-4e8a-9f44-c1203be085b1-15201174.jpg)
    *   ![](https://api2.mubu.com/v3/document_image/0c14f8dc-741d-4b6f-8c38-ef837e8fde12-15201174.jpg)

</ul>

</ul>

</ul>

# <span style="color: gray;">05 数理统计

<ul>

## <span style="color: gray;"><span style="color:darkorange;">总体</span>与<span style="color:blue;">样本</span>

<ul>

### <span style="color: gray;">(1) <span style="color:darkorange;">总体</span> = 随机变量 <span style="color:darkorange;">X</span>

<ul>

*   研究对象的 <u>全体</u> 称为 <span style="color:darkorange;">总体</span>
    *   <span style="color:darkorange;">总体</span> 中的 每个 元素 称为 个体

</ul>

### <span style="color: gray;">(2) <span style="color:blue;">样本</span> (抽样)

<ul>

*   A. <span style="color:blue;">样本</span>
    *   n 个相互独立 且 与总体 同 概率分布 的 随机变量$X_1\dots,X_n$
    *   所组成的 整体($X_1\dots,X_n$ )
    *   称 其为
        *   来自总体$X$，容量为n的一个<u> 简单</u>**随机**样本
        *   简称<span style="color:blue;">样本</span>
        *   //样本 是 总体X 抽出的 一部分
*   B. 观测值(<span style="color:blue;">样本</span><span style="color:darkorange;">值</span>)
    *   **一次** 抽样结果 的 n个 <u>具体</u>数值(<span style="color:blue;">$x_1,\dots,x_n$</span>)
    *   称为 样本 $X_1\dots,X_n$  的 **一个** <span style="color:blue;">样本</span><span style="color:darkorange;">值</span>

</ul>

### <span style="color: gray;">(3) <span style="color:blue;">样本</span><u>分布</u>

<ul>

*   <span style="color:darkorange;">总体</span>X 的分布函数F(x) (概率密度为f(x) or 概率分布为$p_i$ =$P$ {$X=x_i$ })
*   则 样本 $X_1\dots,X_n$
    *   分布函数为
        *   各个F相乘 ![](https://api2.mubu.com/v3/document_image/312c8270-bb14-4f45-9505-cf6cf95c09f2-15201174.jpg)
    *   联合分布为
        *   离散型 ![](https://api2.mubu.com/v3/document_image/f9319e77-0531-4cd0-a8d3-28aa2e8eb86b-15201174.jpg)
        *   连续型 ![](https://api2.mubu.com/v3/document_image/826d658f-963c-4aef-ad4e-764bb63e7b47-15201174.jpg)

</ul>

</ul>

## <span style="color: gray;"><span style="color:green;">统计量</span>及其<span style="color:darkorange;">分布</span>(三大分布)

<ul>

### <span style="color: gray;">(1) <span style="color:green;">统计量</span>

<ul>

#### <span style="color: gray;">A. 定义

<ul>

*   $X_1\dots,X_n$  为 来自<span style="color:darkorange;">总体X</span>的一个 <span style="color:blue;">样本</span> ，g($x_1,\dots,x_n$)为n元函数 %n中<u>不含任何未知参数</u>
*   称$g(X_1\dots,X_n)$  为样本$X_1\dots,X_n$ 和 一个<span style="color:green;"> 统计量</span>
    *   若(<span style="color:blue;">$x_1,\dots,x_n$</span>)为样本值
    *   称 **g($x_1,\dots,x_n$)** 为 $g(X_1\dots,X_n)$ 的**观测值**
*   <span style="color:green;">统计量 </span>也是 <span style="color:darkorange;">随机变量</span>

</ul>

#### <span style="color: gray;">B. <span style="color:darkorange;">常用</span><span style="color:green;">统计量</span>

<ul>

*   1) 样本<u>数字特征</u>
    *   a. 样本均值$\overline{X}$
        *   ![](https://api2.mubu.com/v3/document_image/11a5c095-3074-4471-8cbb-98ac268008dc-15201174.jpg)
    *   b. 样本方差 $S^2$
        *   ![](https://api2.mubu.com/v3/document_image/6e581dd7-b45f-4aa2-8acd-6665ede2617c-15201174.jpg)
        *   样本标准差$S$ ![](https://api2.mubu.com/v3/document_image/a36ad78d-e81f-4782-b5c6-a10fce7eb25b-15201174.jpg)
    *   c. 样本k阶<u>（原点）</u><span style="color:green;">矩</span> ![](https://api2.mubu.com/v3/document_image/a7254575-333f-4c34-b7c9-3eb54493418f-15201174.jpg)
        *   样本k阶<u>中心</u><span style="color:green;">矩</span> ![](https://api2.mubu.com/v3/document_image/f2d74e8f-6bad-4be2-8ec9-d68c7981aab8-15201174.jpg)
*   2) <u>顺序</u><span style="color:green;">统计量</span>
    *   将样本$X_1\dots,X_n$  的n个观测量按其从大到小的顺序排列
        *   得
            *   ![](https://api2.mubu.com/v3/document_image/c953f2e1-2ca0-4e8c-a94d-cbf739605803-15201174.jpg)
                *   $X_{(k)}$ 称作 第k顺统计量
                *   $X_{(1)}$ 称作 最小顺序统计量
                    *   ![](https://api2.mubu.com/v3/document_image/4c955fc7-8636-4de7-8801-5382eceeb0f6-15201174.jpg)
                *   $X_{(n)}$称作 最大顺序统计量
                    *   1 ![](https://api2.mubu.com/v3/document_image/57036b0c-17be-4a62-8981-200a887f2d88-15201174.jpg)
                        *   ![](https://api2.mubu.com/v3/document_image/1ed9aaf6-7930-43d4-ab6f-06abccb7ea1b-15201174.jpg)
                    *   ![](https://api2.mubu.com/v3/document_image/f8f03d76-59ec-46e4-b8d7-81b852b86e1c-15201174.jpg)
                        *   ![](https://api2.mubu.com/v3/document_image/1593e2cf-02ac-494d-b778-91ea81dec403-15201174.jpg)

</ul>

#### <span style="color: gray;">3) 性质

<ul>

*   设定：
*   设<span style="color:darkorange;">总体</span>X的期望$EX=\mu$ ,方差$DX=\sigma²$, $X_1,X_2,\dots,X_n$是取自总体X,容量为n的一个样本
*   $\overline{X},S^2$ 分别为<span style="color:blue;">样本</span>的均值和方差
*   则 对<span style="color:blue;">样本</span>
    *   $E(\overline{X})=E(X)=\mu$
    *   $D(\overline{X})=\frac{1}{n}D(X)=\frac{1}{n}\sigma^2$
    *   $E(S^2)=DX=\sigma^2$

</ul>

</ul>

### <span style="color: gray;">(2) <span style="color:darkorange;">三大</span> 抽样分布

<ul>

#### <span style="color: gray;">1) <span style="color:blue;">$χ^2$</span>分布

<ul>

*   0. 定义：
    *   随机变量 $X_1,X_2,\dots,X_n$ 相互独立
    *   都服从 标准正态分布 即N(0,1)
    *   则
        *   随机变量$X=\sum_{i=1}^ {n}X_i^2$ 服从**自由度**为<u>n</u>的 $χ^2$分布
            *   自由度即 指和式中的 独立变量的个数
        *   记为 $X$~$χ^2(n)$
*   a. f(x)图像：
    *   ![](https://api2.mubu.com/v3/document_image/e5f69a27-a217-4e3d-854e-23d6db712f02-15201174.jpg)
*   **b. <span style="color:green;">上</span><span style="color:darkorange;">α</span><span style="color:blue;">分位点</span>**
    *   1) 定义：
        *   对给定的α(0<α<1)
        *   称 满足
            *   ![](https://api2.mubu.com/v3/document_image/0ee2d9ac-9e6d-4376-bd94-f93b353df48b-15201174.jpg)
        *   的$χ_α^2(n)$为$χ^2(n)$ 的分布上α分位点
            *   对于不同的α,n  的**<span style="color:green;">上</span><span style="color:darkorange;">α</span><span style="color:blue;">分位点</span>** 可查表求得
    *   2）上α分位点(亦称上侧α分位数)为μ ![](https://api2.mubu.com/v3/document_image/7d87087e-e8aa-41d9-a419-02adabdfce7a-15201174.jpg)
    *   意指：点μ上侧(即右侧),该概率密度曲线下方(阴影部分),x轴上方图形面积为α
*   c. <span style="color:darkorange;">性质</span>
    *   ① $X_1$~$χ^2(n_1)$ $X_2$~$χ^2(n_2)$  $X_1,X_2$相互独立
        *   $X_1+X_2$ ~ $χ^2(n_1+n_2)$
    *   ② $X$~$χ^2(n)$
        *   则
            *   $EX=n$
            *   $DX=2n$

</ul>

#### <span style="color: gray;">2) <span style="color:green;">$t$</span>分布

<ul>

*   0. <span style="color:darkorange;">定义</span>：
    *   $X$~ $N(0,1)$ ,$Y$ ~$χ^2(n)$ ，$X,Y$相互独立
    *   随机变量 $t=\frac{X}{\sqrt{Y/n}}$
    *   称 其 服从 自由度为n 的t分布
        *   记为 $t$~$t(n)$
*   a. f(x)<span style="color:blue;">图像</span>
    *   ![](https://api2.mubu.com/v3/document_image/9ec49b87-9145-424f-a9d5-3a6ab0b37f7f-15201174.jpg)
        *   关于x=0对称
        *   $Et=0$(n≥2)
*   b. <span style="color:darkorange;">性质</span>
    *   ( $t_α$与$t_{1-α}$ <span style="color:green;">相反数</span>)
    *   由f(x)对称性可知
        *   ![](https://api2.mubu.com/v3/document_image/d960526a-5ef8-46b3-bae6-1eb41d307c37-15201174.jpg)
    *   故 ![](https://api2.mubu.com/v3/document_image/3262a894-e8f3-488c-a542-4d9e72da0fe6-15201174.jpg)

</ul>

#### <span style="color: gray;">3) <span style="color:darkorange;">$F$</span>分布

<ul>

*   0. 定义
    *   $X$~$χ^2(n_1)$ $Y$~$χ^2(n_2)$ $X,Y$相互独立
    *   随机变量 $F=\frac{X/n_1}{Y/n_2}$
    *   称 其 服从 自由度为$(n_1,n_2)$ 的F分布
        *   记为$F$~$F(n_1,n_2)$
        *   $n_1$为第一自由度，$n_2$ 为第二自由度
*   b. f(x)<span style="color:blue;">图像</span>
    *   ![](https://api2.mubu.com/v3/document_image/2f822ed1-7d9b-4850-a6ee-fcaf882b7a40-15201174.jpg)
*   c. <span style="color:darkorange;">性质</span>
    *   <span style="color:green;">倒数 </span>关系 ($F$ 与 <span style="color:blue;">$\frac{1}{F}$</span> ; $F_{1-α}(n_1,n_2)$ 与$\frac{1}{F_α(n_1,n_2)}$ )
    *   ① $F$ 服从$F(n_1,n_2)$ 分布，则
        *   <span style="color:blue;">$\frac{1}{F}$</span> 也服从$F(n_1,n_2)$ 分布
            *   即 $\frac{1}{F}$~$F(n_1,n_2)$
    *   ② $F_{1-α}(n_1,n_2)$ =$\frac{1}{F_α(n_1,n_2)}$

</ul>

</ul>

### <span style="color: gray;">(3) 正态总体下的<u>常用结论</u>

<ul>

*   设定:
    *   $X_1,X_2,\dots,X_n$是取自 正态总体$X$~$N(\mu,\sigma²)$ 的一个样本
    *   $\overline{X},S^2$ 分别为<span style="color:blue;">样本</span>的均值和方差
*   则 样本
    *   1 ![](https://api2.mubu.com/v3/document_image/148db947-8dcf-4e00-96de-c008611ed624-15201174.jpg)
    *   2 ![](https://api2.mubu.com/v3/document_image/288365f0-be20-459b-8387-230e5eb1c571-15201174.jpg)
    *   3 ![](https://api2.mubu.com/v3/document_image/43823fbb-4218-4fe6-8777-d4e2581c177b-15201174.jpg)
        *   ![](https://api2.mubu.com/v3/document_image/f54e9f4e-49b5-40f8-a3ae-cb99281d83d1-15201174.jpg)
    *   4 ![](https://api2.mubu.com/v3/document_image/dccc523f-10ae-4d07-839c-303e48e868d7-15201174.jpg)
        *   ![](https://api2.mubu.com/v3/document_image/830a6d03-068e-46b3-bf09-1938deea0ef9-15201174.jpg)
        *   进一步 有 ![](https://api2.mubu.com/v3/document_image/4939eea3-7584-47e1-a517-546e8090451a-15201174.jpg)

</ul>

</ul>

## <span style="color: gray;">参数<span style="color:darkorange;">估计</span>

<ul>

### <span style="color: gray;">(1) 参数的<span style="color:blue;">点</span><span style="color:darkorange;">估计</span>

<ul>

#### <span style="color: gray;">A. 概念

<ul>

*   1) **估计量**
    *   设定
        *   总体$X$ 的分布函数$F(x;θ)$
            *   可以多维
            *   θ是一个未知参数
        *   $X_1,X_2,\dots,X_n$ 是取自总体$X$ 的一个样本
        *   由样本构造一个 适当的统计量$\hat\theta$ ($X_1,X_2,\dots,X_n$ )作为参数$\theta$ 的估计
    *   称
        *   **统计量**$\hat\theta$ ($X_1,X_2,\dots,X_n$ ) 为$\theta$ 的<span style="color:blue;">估计量</span>
            *   记为$\hat\theta$=$\hat\theta$ ($X_1,X_2,\dots,X_n$ )
*   2) **估计值**
    *   $x_1,\dots,x_n$ 是样本的<u>观察值</u>
    *   代入估计量$\hat\theta$ 中得到值$\hat\theta$ ($x_1,\dots,x_n$ )
    *   并以此值作为未知参数$\hat\theta$ 的<span style="color:green;">**估计值**</span>
*   3) **点估计问题**
    *   <u>建立</u>一个适当的统计量作为未知参数θ的<span style="color:blue;">估计量</span>
    *   以相应的观察值作为未知参数<span style="color:green;">估计值</span>的问题

</ul>

#### <span style="color: gray;">B. 方法

<ul>

*   1) 矩估计法
    *   E(X)存在
        *   ![](https://api2.mubu.com/v3/document_image/22bc8d55-dc28-4637-b64e-67ec9e6e6c5a-15201174.jpg)
    *   样本 原点矩 = 总体矩
        *   ![](https://api2.mubu.com/v3/document_image/c75b2210-37e1-4184-ad5c-97e42637ca49-15201174.jpg)
            *   包含k个未知参数的k个联立方程(矩法方程)
    *   解得
        *   ![](https://api2.mubu.com/v3/document_image/ac54a88f-bef7-4869-bd4c-8ea72c0f43a3-15201174.jpg)
        *   称
            *   $\hat\theta$ ($X_1,X_2,\dots,X_n$ ) 矩估计量
            *   $\hat\theta$ ($x_1,\dots,x_n$ )矩估计值
*   2) <span style="color:blue;">最大</span><span style="color:green;">似然</span><span style="color:darkorange;">估计</span>法
    *   a. 最大似然原理
        *   对未知参数θ进行估计时，在该参数可能的取值范围$I$内选取
        *   用使“样本获此观测值$x_1,\dots,x_n$的概率最大的参数值θ作为θ的估计
        *   这样选定的$\hat\theta$最有利于$x_1,\dots,x_n$的出现
    *   b. 建立似然函数$L(\theta)$
        *   i. 离散型
            *   设定：
                *   $X_1,X_2,\dots,X_n$  取值为$x_1,\dots,x_n$ 的<u>概率</u>
            *   每一个值 连乘
                *   ![](https://api2.mubu.com/v3/document_image/27729d2d-6ec2-463a-b2ae-d83a589ab364-15201174.jpg)
            *   这个<u>概率</u>**值** (累乘的值) 是$\theta$ 的函数，将其记为
                *   ![](https://api2.mubu.com/v3/document_image/9d759d97-705d-4341-bd40-27b12891780e-15201174.jpg)
            *   称$L(\theta)$为 样本的似然函数
                *   若存在$\hat\theta\in{I}$ ，使得$L(\theta)$ 取最大值
                *   $\hat\theta$= $\hat\theta$ ($x_1,\dots,x_n$ )称为参数$\theta$的 <span style="color:blue;">最大</span><span style="color:green;">似然</span><span style="color:darkorange;">估计</span>**值**
                *   $\hat\theta$ ($X_1,X_2,\dots,X_n$ ) 为 <span style="color:blue;">最大</span><span style="color:green;">似然</span><span style="color:darkorange;">估计</span>**量**
        *   ii. 连续型
            *   $L(\theta)$
                *   ![](https://api2.mubu.com/v3/document_image/38fa9652-e4d1-4cec-a5e2-e958c37016fc-15201174.jpg)
            *   $\hat\theta$
                *   ![](https://api2.mubu.com/v3/document_image/b6b0c2fa-8ace-47eb-9043-cb0a5c967454-15201174.jpg)

</ul>

#### <span style="color: gray;">C. <span style="color:blue;">估计量</span>的<u>评价标准</u>

<ul>

*   1) **<span style="color:green;">无偏</span>性**
    *   设定
        *   $\hat\theta$=$\hat\theta$ ($X_1,X_2,\dots,X_n$ )
        *   对一切$n$ 及$\theta\in {I}$
        *   有 $E\hat\theta$ =$\theta$
    *   称
        *   $\hat\theta$ 为$\theta$ 的 无偏估计量
*   2) 有效性（最小方差性）
*   3) 一致性（相合性）

</ul>

</ul>

### <span style="color: gray;">(2) 参数的<span style="color:green;">区间</span><span style="color:darkorange;">估计</span>与<span style="color:blue;">假设</span><u>检验</u>

<ul>

#### <span style="color: gray;">A. <span style="color:green;">区间</span>估计

<ul>

*   **1) 概念**
    *   设θ是总体X的一个未知参数，对于给定的a(0<a<1)
    *   由样本X₁,X₂,…,X,确定的两个统计量
        *   $\hat\theta_1$=$\hat\theta_1$ ($X_1,X_2,\dots,X_n$ )
        *   $\hat\theta_2$=$\hat\theta_2$ ($X_1,X_2,\dots,X_n$ )
        *   $\hat\theta_1$<$\hat\theta_2$
    *   使得
        *   $P$ {$\hat\theta_1$ ($X_1,X_2,\dots,X_n$ ) <$\hat\theta$<$\hat\theta_2$ ($X_1,X_2,\dots,X_n$ ) }
        *   =
        *   $1-\alpha$
    *   称 随机区间($\hat\theta_1$,$\hat\theta_2$) 是 $1-\alpha$ 的**置信<span style="color:green;">区间</span>**
        *   $\hat\theta_1$,$\hat\theta_2$ 分别称为 双侧置信区间的 置信下限和置信上限
        *   $1-\alpha$ 称为 **置信度** or **置信水平**
            *   $\alpha$ 称为显著性水平
*   2) 正态总体均值的置信区间（置信度为1-a)
    *   ![](https://api2.mubu.com/v3/document_image/5bb497f7-d092-4d4b-a2ef-90dff458201f-15201174.jpg)

</ul>

#### <span style="color: gray;">B. 假设检验

<ul>

*   1) 定义
*   a. 思想方法
    *   i. 统计假设
        *   关于总体(分布中的未知参数，分布的类型、特征、相关性、独立性…)的每一种论断(“看法”)称为统计假设
    *   ii. 假设检验
        *   根据样本观察数据或试验结果所提供的信息
        *   去<u>推断</u>(检验)这个“看法”(即假设)<u>是否成立</u>
        *   这类统计推断问题称为统计假设检验问题
    *   iii. ~的基本思想
        *   采用带有概率性质的反证法
*   b. 拒绝域 | 接受域
    *   在假设检验中
        *   i. 拒绝域
            *   由拒绝原假设$H_0$的全体样本点所组成的集合C
*   2) 正态总体下的六大检验及拒绝域
*   3) 两类错误

</ul>

</ul>

</ul>

</ul>
