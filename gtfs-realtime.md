# 動的データ(GTFS Realtime)の解説

# GTFS Realtimeについて

## フォーマットの概要

図解など

## ベースとするフォーマット

* 2019年3月時点の「標準的なバス情報フォーマット」の動的データのベースのフォーマットは、GTFS Realtime v2.0とします。
* 日本語文書は[Google Developersのサイト](https://developers.google.com/transit/gtfs-realtime/reference/)を参照してください。

# 推奨する設定方法

## バスロケーション情報として出力すべき項目

* 旅程の更新情報（Trip Update）と、車両の現在位置（Vehicle Position）の両方を出力

## 遅延時間(delay)の設定方法

* 丸め加工をしない

## 不確実性(uncertainty)の設定方法

* 通過実績の不確実度は0にする

# 推奨する配信方法

## データの更新間隔

- 30秒以下

# 補足事項

## 車両とダイヤの紐付けについて

* 災害時
* 臨時便
* 簡易なバスロケ

## リードタイム短縮のための工夫

## 到着予測