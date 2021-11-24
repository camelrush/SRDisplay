# 空間ディスプレイ（Spatial Reality Display）

## SR Display Sample
公式サイトの[「クイックスタート」](https://www.sony.net/Products/Developer-Spatial-Reality-display/jp/develop/Unity/Quickstart.html)を参考に実践しました

![editor1](./doc/editor1.png)

これをビルドすると・・↓ のように表示されます。

![sample](./doc/sample.gif)

ボックスに球体（Sphere）を追加してみました。

![editor2](./doc/editor2.png)

↓ こうなりました。

![sample](./doc/sample2.gif)

置いてあるだけで動きませんね…  

どうも、この箇所でアニメーション制御しているっぽいね。

![editor2](./doc/editor3.png)

## ワンポイント
- SR Displayの実機がない場合は、以下の設定を行うこと。
  - Unityのメニューバーで、Edit > Project Settings を選択 
  - 「Spatial Reality Display」を選択
  - 「Run Without SR Display」をチェックする

- 以下のエラーが出る場合の対処法
  -「You should import Post Processing package from Package Manager if you want to use SRDPostProcessingSample」  
    - Unityのメニューバーで Window > Package Manager を選択
    - 左上「Packages:In Project▼」を「Unity Registry」に変更
    - 一覧の「▼ Post Processing」を選択して、右下「Install」をクリックする
