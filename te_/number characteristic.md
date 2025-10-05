# 一维
>$E(x)$ $D(x)$
- 离散型
    - ..rv ' 
        - 直求EX、DX 与变式
            - EX
                - 由F(x)写间断点
                - $\Sigma_{x=1}^\infty x_i p_i$
            - E(2X+5)
                - 2EX+5
            - E(X^2)
                - $\Sigma_{x=1}^\infty x^2_i p_i$
                - ↑E(g(x))
            - 多项式相乘则拆
                - E[(X-1)(X-2)]=E[X^2-3X+2]
                    - E[X^2]-E(3X)+2
                    - ↑由D(X^2)求E[X^2]
            - --
            - D(g(x))
                - E(g(x)^2) - E(g(x))^2
            - $D(aX+b)=a^2DX$
            - $D(X \pm Y)=DX+DY \pm 2Cov(X,Y)$
                - ↑usually also用ρ反求cov
                    - $\frac{Cov(X,Y)}{\sqrt{DX}\sqrt{DY}}$
                - Cov(X,Y)=$E[XY] - E[X]E[Y]$
                    -  ↑=$E[(X - E[X])(Y - E[Y])]$
                        - ？怎么约出来的
            - --
        - combine with常见分布conclude
            - 二项分布： np np(1-p)
            - 泊松：λ λ
    - ..rv函数..
- 连续型

# 二维
- 离散
    - 给cov 反求 分布
- 连续

# 

# judge：独立性&相关性
- 用分布
- 用ρ DX
# 切比雪夫
>估算取值; 证明收敛
- 构造表达式 match P{|ξ-Eξ|≥ε}≤$\frac{Dξ}{ε^2}$
   - >or..≤..＞1-..
