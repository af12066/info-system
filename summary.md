# 概要 (Introduction)

- EOGを使った新しいアプリケーションの紹介

    > In this study, a new application of EOG was introduced.

- 眼球移動によるDance Dance Revolution

    > For this purpose, a DDR (dance dance revolution) game device was introduced where EOG control signals produced from eye movement [11].)

- リアルタイムに16方向を判別できるアルゴリズムは提案されている

    > There has been a study where the classification of 16 different EOG signals was made in real time use [12].

- 日常利用ではEOGは複雑な波形となるため，各々を明確に判別するのは困難

    > However, reliable and non-ambiguous signal identification for a particular eye movement can be rather difficult to be achieved in real situation since EOG signals are complex in nature.

- 少ないクラスではっきりと区別できる方法をとる

    > In this study, only several eye movements that can be clearly distinguished were selected in order to implement them in a game algorithm using EOG.

# 方法

- Fig.1: 眼球変位角度と信号の関係
    - 差動増幅
    - 中央を見る: 信号の変動なし
    - 右を見る: 正方向の信号
    - 左を見る: 負方向の信号

    > Output signal of comparator; no signal when eyeball are centered (top), positive pulse with movement to the right (middle) and negative pulse with movement to the left (bottom)

- 眼球の角膜側に+，網膜側に-の電位差

    >The cornea side is designated as positive whereas the retina side is negative. This illustrates potential difference.

- Fig.2: EOGを計測するまでのブロック線図
- 使い捨て電極で
- IN+, IN-, Ref -> インスツルメンテーションアンプで増幅

    > Disposable Ag/AgCl electrodes were used for EOG measurement and one set consisted of three electrodes. One was connected to the positive input, another to the negative input and the last one as reference of the instrumentation amplifier (IA) as shown in Fig. 1.
