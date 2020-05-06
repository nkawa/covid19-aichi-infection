# covid19-aichi-infection

感染がどのように起こっているか、COVID-19「愛知県内の感染者・遺伝子検査件数」の情報を用いて感染者間の関係をグラフにしてみました。

![SVG](https://github.com/nkawa/covid19-aichi-infection/blob/master/covid19_aichi20200505.svg)

https://github.com/nkawa/covid19-aichi-infection/blob/master/covid19_aichi20200505.pdf

なお、この図には371名の接触履歴が判明感染者が掲載されています。（残りの120名近くは不明）
図を見る限り、３～４つの大きな感染集団があることがわかります。

コードも公開予定ですが、整理できていないので、とりあえずできているデータだけでも公開します。
（泥臭いデータクレンジングなどがいろいろあります）

### TODO
- コード整理（公開に向けて）
- 外部からの感染情報（海外など）の追加
- 感染者重みの計算


## 利用データ
「愛知県内の感染者・遺伝子検査件数」
（なお、一部の接触者で「又は」という表現がありますが、両方からのリンクを生成しています）
また、変換中のバグ等により、誤ったリンクが張られている可能性もあります。適宜更新予定。

https://www.pref.aichi.jp/site/covid19-aichi/kansensya-kensa.html

なお、愛知県のPDFは、 Code for Nagoya の有志によって、csvデータ化されており、このデータを元にしています。

https://github.com/code4nagoya/covid19/blob/development/data/patients.csv




## 連絡先：
この件、興味ある方は河口の twitter @nkawa　( https://twitter.com/nkawa ) 
もしくは、Facebook ( https://fb.me/nobuo.kawaguchi )などにご連絡ください。

もっとカッコよくしてくれるのも大歓迎です。



