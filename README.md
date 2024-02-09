# 4d-topic-electronic-prescription
電子処方箋

#### step 0 （未対応）

* `JAHIS院外処方箋２次元シンボル記録条件規約（JAHIS9）`を`電子処方箋管理サービス記録条件仕様（SJ1）`に変換する
  * ヘッダーの変換
  * 文字コードの変換
  * 和暦`GYYMMDD`から西暦`YYYYMMDD`に日付を変換
  * 公費単独の場合の特例
  * 分割指示
  * その他

#### step 1

* CSVをXMLに変換する
* XMLを署名する
* ICカードから証明書を取り出す

#### 関連プロジェクト

* [4d-plugin-xmlsec](https://github.com/miyako/4d-plugin-xmlsec) →XAdES
* [4d-plugin-timestamp-client](https://github.com/miyako/4d-plugin-timestamp-client) →RFC3161
