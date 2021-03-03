# ポートフォリオ概要
石油暖房機メーカーの販売データーを「年代別の年齢」を切り口で可視化するデモダッシュボードを作成しました。
デモダッシュボードで使用させて頂いたメーカーはファーストキャリアでお世話になった企業です。分析をイメージする参考の為使用させて頂きました。
ダミーデーターはエクセルで、RANDARRAY関数を用いて作成しています。
データーは全てランダム値になります。

# 使用環境
Salesforce の無料で使える開発環境「Developer Edition」


# Login
アプリケーションを作成し、TableauCRMで作成したダッシュボードを埋め込んでいます

ログイン頂くと当該ページをご確認いただけます。
初回ログイン時の確認メールが飛ばないよう設定しています。

|  項目  |  詳細  |
| ---- | ---- |
|  ユーザ名  |  aaa001@aaa.aaa  |
|  PASS  |  a1234567  |
|  URL  |  https://login.salesforce.com/  |



# データフロー

データフローを用いてデータを一部加工しています。
テーブルの結合と項目の生成をしています。

![](https://gyazo.com/a86482d94a1e556f19422682be997132.png)
