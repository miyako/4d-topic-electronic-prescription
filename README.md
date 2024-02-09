# 4d-topic-electronic-prescription
電子処方箋

#### step 0

* `JAHIS院外処方箋２次元シンボル記録条件規約`（JAHIS9）を電子処方箋管理サービス記録条件仕様（SJ1）に変換する
  * ヘッダーの違い
  * 文字コードの違い
  * 和暦`GYYMMDD`から西暦`YYYYMMDD`に日付を変換
  * その他

#### step 1

* CSVをXMLに変換する
* XMLを署名する

