# AzurLane

自分用の値をまとめたり若干の計算をしたりするためのWebツール。

## コマンド

* `build`
  * すべてのTSをビルド
* `kansen`
  * KAN-SENのJSONを更新
    * 艦種などでソート
    * 画像から未追加の初期データを追加
  * KAN-SENの画像をテキスト化したJSONの更新
    * 画像からテキスト形式の画像をJSONで出力
  * 性質上2回実行が必要
    * KAN-SENの画像を追加
    * コマンドを実行してJSONの更新
    * JSONに手動で名前やレアリティなどの情報を追加
    * コマンドを実行してソート
  * 画像は各陣営のフォルダ内にアルファベットで追加
    * ウムラウトなどが入る場合はアルファベット対応表があるはずなのでそれに従う
    * `ö` は `oe` など
* `equip`
  * 装備周りのJSONを更新
