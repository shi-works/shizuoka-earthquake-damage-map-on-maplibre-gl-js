# MapLibre GL JSで静岡県地震被害想定マップ（震度分布図及び液状化可能性分布図）を表示するデモサイト
## Public Website
https://shi-works.github.io/shizuoka-earthquake-damage-map-on-maplibre-gl-js/

![image](https://github.com/shi-works/shizuoka-earthquake-damage-map-on-maplibre-gl-js/assets/71203808/8d46d1e7-784d-451a-ba24-cb1cd3769dd8)

## Data Source
### 静岡県
- 静岡県第４次地震被害想定地震動・液状化（南海トラフ巨大地震（基本ケース））
    - 出典：https://opendata.pref.shizuoka.jp/dataset/fuji-100.html
    - 概要：静岡県第４次地震被害想定の地震動・液状化（南海トラフ巨大地震（基本ケース））データです。
    - ライセンス：CC BY

- 静岡県第４次地震被害想定地震動・液状化（南海トラフ巨大地震（東側ケース））
    - 出典：https://opendata.pref.shizuoka.jp/dataset/fuji-101.html
    - 概要：静岡県第４次地震被害想定の地震動・液状化（南海トラフ巨大地震（東側ケース））データです。
    - ライセンス：CC BY
 
- 静岡県第４次地震被害想定地震動・液状化（南海トラフ巨大地震（陸側ケース））
    - 出典：https://opendata.pref.shizuoka.jp/dataset/fuji-102.html
    - 概要：静岡県第４次地震被害想定の地震動・液状化（南海トラフ巨大地震（陸側ケース））データです。
    - ライセンス：CC BY

### 人口分布データ
- 令和2年簡易100mメッシュ人口データ（静岡県）（PMTiles形式）
    - 出典：https://github.com/shi-works/noto-hanto-earthquake-2024-100m-mesh-pop-data
        - 原初データ出典：[地域分析に有用なデータの提供, 地域・交通データ研究所代表（東京大学空間情報科学研究センター客員研究員）西澤明](https://gtfs-gis.jp/teikyo/index.html)
    - 概要：地域・交通データ研究所にて公開されている令和2年簡易100mメッシュ人口データをPMTiles形式に変換したデータです。
    - ライセンス：[西澤明](https://gtfs-gis.jp/teikyo/index.html)、[@shi-works](https://twitter.com/shi__works)、[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.ja)

### 背景地図及び地形データ
- 国土地理院 最適化ベクトルタイル
    - 出典：https://github.com/gsi-cyberjapan/optimal_bvmap
    - ライセンス：[国土地理院コンテンツ利用規約](https://www.gsi.go.jp/kikakuchousei/kikakuchousei40182.html)に従い、出典明示により、転載も含め使用可
- 国土地理院 地理院タイル（陰影起伏図）
    - 出典：https://maps.gsi.go.jp/development/ichiran.html#hillshademap
    - ライセンス：[国土地理院コンテンツ利用規約](https://www.gsi.go.jp/kikakuchousei/kikakuchousei40182.html)に従い、出典明示により、転載も含め使用可
- 産業技術総合研究所 シームレス標高タイル（統合DEM）
    - 出典：https://tiles.gsj.jp/tiles/elev/tiles.html
    - ライセンス：「[産総研地質調査総合センターウェブサイト利用規約](https://www.gsj.jp/license/license.html)」に従い、商用を含む自由な二次利用が可能です。この規約はCC BY 4.0と互換です。
