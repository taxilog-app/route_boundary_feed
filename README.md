# route_boundary_feed

タクシー運行アプリ（route_timer_app）の**丁目境界レイヤ**用データ配信ハブ。
営業圏ごとにフォルダを分け、GitHub Pages で静的配信する。

- `fukuoka/` … 福岡交通圏
- `tokyo23/` … 東京特別区・武三交通圏（東京23区＋武蔵野市＋三鷹市）

各フォルダに `choume_fill.geojson`（丁目・塗り）と `machi_frame.geojson`（町枠）。
出典：国勢調査2020 小地域（町丁・字等別）境界データ（総務省統計局／e-Stat）を加工。
