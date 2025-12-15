# Plotly.js サンプル集

Plotly.js を使用したデータ可視化のサンプルファイル集です。初心者から上級者まで、段階的に学習できるよう30個のサンプルを用意しています。

## 使い方

各HTMLファイルをブラウザで開くだけで動作します。すべてのサンプルは単一のHTMLファイルにHTML、CSS、JavaScriptがまとめられています。

## 目次

### 初心者レベル（01-10）

基本的なグラフの作成方法を学びます。

| No. | ファイル名 | 説明 |
|-----|-----------|------|
| 01 | [01-basic-line-chart.html](01-basic-line-chart.html) | 基本的な折れ線グラフ |
| 02 | [02-basic-bar-chart.html](02-basic-bar-chart.html) | 基本的な棒グラフ |
| 03 | [03-basic-pie-chart.html](03-basic-pie-chart.html) | 基本的な円グラフ |
| 04 | [04-scatter-plot.html](04-scatter-plot.html) | 散布図 |
| 05 | [05-multiple-line-chart.html](05-multiple-line-chart.html) | 複数データの折れ線グラフ |
| 06 | [06-horizontal-bar-chart.html](06-horizontal-bar-chart.html) | 横棒グラフ |
| 07 | [07-donut-chart.html](07-donut-chart.html) | ドーナツチャート |
| 08 | [08-area-chart.html](08-area-chart.html) | エリアチャート |
| 09 | [09-stacked-bar-chart.html](09-stacked-bar-chart.html) | 積み上げ棒グラフ |
| 10 | [10-bubble-chart.html](10-bubble-chart.html) | バブルチャート |

### 中級レベル（11-20）

より高度なグラフタイプと機能を学びます。

| No. | ファイル名 | 説明 |
|-----|-----------|------|
| 11 | [11-subplots.html](11-subplots.html) | サブプロット（複数グラフ配置） |
| 12 | [12-heatmap.html](12-heatmap.html) | ヒートマップ |
| 13 | [13-box-plot.html](13-box-plot.html) | 箱ひげ図 |
| 14 | [14-histogram.html](14-histogram.html) | ヒストグラム |
| 15 | [15-contour-plot.html](15-contour-plot.html) | 等高線図 |
| 16 | [16-3d-scatter.html](16-3d-scatter.html) | 3D散布図 |
| 17 | [17-3d-surface.html](17-3d-surface.html) | 3D曲面図 |
| 18 | [18-radar-chart.html](18-radar-chart.html) | レーダーチャート |
| 19 | [19-treemap.html](19-treemap.html) | ツリーマップ |
| 20 | [20-sankey-diagram.html](20-sankey-diagram.html) | サンキーダイアグラム |

### 上級レベル（21-30）

インタラクティブ機能と高度なカスタマイズを学びます。

| No. | ファイル名 | 説明 |
|-----|-----------|------|
| 21 | [21-animation.html](21-animation.html) | アニメーション付きグラフ |
| 22 | [22-custom-buttons.html](22-custom-buttons.html) | カスタムボタン付きグラフ |
| 23 | [23-slider.html](23-slider.html) | スライダー付きグラフ |
| 24 | [24-dropdown.html](24-dropdown.html) | ドロップダウン付きグラフ |
| 25 | [25-realtime-update.html](25-realtime-update.html) | リアルタイム更新グラフ |
| 26 | [26-combined-chart.html](26-combined-chart.html) | 複合グラフ（折れ線+棒、2軸） |
| 27 | [27-choropleth-map.html](27-choropleth-map.html) | 地理マップ（コロプレス） |
| 28 | [28-custom-hover.html](28-custom-hover.html) | カスタムホバー |
| 29 | [29-event-handling.html](29-event-handling.html) | イベントハンドリング |
| 30 | [30-dashboard.html](30-dashboard.html) | ダッシュボード風レイアウト |

## 学習のポイント

### 初心者レベル
- `Plotly.newPlot()` の基本的な使い方
- trace（データ）とlayout（レイアウト）の設定
- 基本的なグラフタイプ（scatter, bar, pie）の理解

### 中級レベル
- 複数グラフの配置（subplots）
- 統計グラフ（箱ひげ図、ヒストグラム）
- 3Dグラフの描画
- 特殊なグラフタイプ（サンキー、ツリーマップ）

### 上級レベル
- `Plotly.animate()` によるアニメーション
- `updatemenus` によるボタン・ドロップダウンの追加
- `Plotly.extendTraces()` によるリアルタイム更新
- イベントハンドリング（plotly_click, plotly_hover等）
- 複合グラフと2軸の使用
- ダッシュボードの構築

## 参考リンク

- [Plotly.js 公式ドキュメント](https://plotly.com/javascript/)
- [Plotly.js GitHub](https://github.com/plotly/plotly.js)

## 使用ライブラリ

- Plotly.js v2.27.0 (CDN)

## ライセンス

MIT License
