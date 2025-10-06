# 依概率收敛

# 大数(3

- 切比雪夫
    - judge 序列X是否满足
        - >独立
        - 方差一致&有界
            - ↑推广式: 运用DX性质
                - $D(\frac{1}{n}X_n)$
                    - $\frac{1}{n^2}D(X_n)$
                - $D(nX_n)$
                    - $n^2D(X_n)$
                - $D(n^2X_n)$
                    - $n^4D(X_n)$
            - 指数分布: $\frac{1}{\lambda}$ $\frac{1}{\lambda^2}$ ←服从参数为λ的..
- 伯努利
- 辛钦
    - judge...
        - >独立同分布
            - EX存在
        - ↑泊松分布 皆包含? 
            - ↑8大分布是不是都满足独立同分布←数学期望一致

# 中心极限(2
>独立同分布，EX DX存在
- 列-林
    - 建模
        - 总约束P{$\Sigma_i^n X_n$≤k}≈ $\Phi(\frac{k-\mu n}{{\sqrt n}\sigma})$ `＞` $\Phi(m)$←utilize已知k
            - $\frac{k-\mu n}{{\sqrt n}\sigma}$ ＞ m
            - 3元素:
                - $\Sigma_i^n X_n$
                - $n\mu$、${\sqrt n} \sigma$
       
---
- 莫-拉
    - >Y_n视为$\Sigma_{i=1}^n X_i$
    - $\frac{Y_n-\mu n}{{\sqrt n}\sigma}$
---
# add 正态related
- 标准化
    - $Z = \frac{X - \mu}{\sigma}$
- Z分数
    - 标准化后结果
- Z分布: 
    - 标准正态分布$Z \sim N(0,1)$
- --
- 中心极限的另一种写法(正态分布写法不同$N(\mu, \frac{\sigma^2}{n})$
    - $ Z = \frac{\bar{X} - \mu}{\sigma / \sqrt{n}} $
