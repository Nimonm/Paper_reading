# Paper_reading
some of papers I read begin from 2020/05/04

[Circle Loss: A Unified Perspective of Pair Similarity Optimization](https://arxiv.org/pdf/2002.10857.pdf)<br>
>针对深度学习提供了相似度优化观点，最大化类内相似度sp，最小化类间相似度sn。但是直接用两者之差求最值作为loss function来优化不够灵活。所以作者通过对每个相似度重新加权，highlight未优化的相似度。因为决策边界是圆形的，所以就叫circle loss。
>原本的方法缺点：1.优化缺乏灵活性；2.收敛状态不明确。模棱两可的收敛方式损害了特征空间的可分离性。
