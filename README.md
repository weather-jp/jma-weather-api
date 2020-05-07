# jma-weather-api
Scrape the weather forecast of the Japan Meteorological Agency

## 天気予報 | weather forecast in japan

[気象庁の天気予報](https://www.jma.go.jp/jp/yoho/) を json化して実験配信しています。  
毎日5時・11時・17時の定時発表をうけて、1分後からスクレイピングを開始します。  
またメンテナンス時にはその時点の予報がスクレイピングされます。  
配信データの形式は今後予告なく整理・変更を行う予定です。

### 地域一覧 | region list

`https://weather-jp.github.io/jma-weather-api/data/forecast/index.json`

### 各地域の予報 | forecast of each region

エリアリストからidを選択し、ファイルパスに設定してください。  
Choose ID from region list, and set into the file path.

`https://weather-jp.github.io/jma-weather-api/data/forecast/{ID}.json`
