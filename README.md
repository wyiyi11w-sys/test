# ai电力电子应用
## gan网络
gan是xxx
### 损失函数

GAN 的训练基于极小极大（minimax）博弈，其目标函数如下：

$$
\mathcal{L}_{\text{GAN}} = \mathbb{E}_{x \sim p_{\text{data}}(x)}[\log D(x)] + \mathbb{E}_{z \sim p_z(z)}[\log(1 - D(G(z)))]
$$

其中：
- $x$ 是来自真实数据分布 $p_{\text{data}}(x)$ 的样本（如正常工况下的电流波形）；
- $z$ 是从先验噪声分布 $p_z(z)$（通常为高斯分布）中采样的输入；
- $G(z)$ 是生成器生成的“伪样本”；
- $D(x)$ 是判别器输出，表示样本为真实数据的概率。

最终目标是优化：
$$
\min_G \max_D \mathcal{L}_{\text{GAN}}
$$
即判别器 $D$ 尽可能区分真实与生成样本，而生成器 $G$ 力图使 $D$ 判别失败。
1. xxx
2. xxx
## xx网络
1. xxx
2. xxx
