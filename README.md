# Kerasのログから残り時間を算出するHTMLファイル

Kerasのログの末尾数行をコピペすると完了までの大体の時間を算出して表示してくれるだけのHTMLファイル。

探せばもっといいのがきっとあるはずと思いつつも作ってしまった。

## 制限事項など

- 現在実行中のEpochは計算に入れないのでちょっと多めに出るつもり。
- 1epochあたりの秒数が少ない場合、あまり正確に出ない。 (完了したepochの行の ` - 1s ` のような表示を元にしてるので。)
- 実装は古臭さ漂うBootstrap + jQuery。

## URL (GitHub Pages)

<https://ak110.github.io/keras_eta_estimator/keras_eta_estimator.html>
