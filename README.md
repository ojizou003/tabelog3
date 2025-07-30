# Tabelog Scraper

このプロジェクトは、食べログ（Tabelog）から店舗情報をスクレイピングしてCSVファイルに出力するためのプログラムです。

## 概要

このプロジェクトには、以下のJupyter Notebookファイルが含まれています：

1. `dev.ipynb`: 水戸市の店舗情報を取得します。
2. `dev_2.ipynb`: 前橋市の店舗情報を取得します。
3. `dev_3.ipynb`: 宇都宮市の店舗情報を取得します。
4. `dev_4.ipynb`: つくば市の店舗情報を取得します。
5. `dev_5.ipynb`: 高崎市の店舗情報を取得します。
6. `dev_6.ipynb`: 小山市の店舗情報を取得します。
7. `dev_7.ipynb`: 福島市の店舗情報を取得します。
8. `dev_8.ipynb`: 郡山市の店舗情報を取得します。

各ノートブックは、指定された地域の食べログページから店舗の詳細情報を収集し、CSVファイルに保存します。

## 必要条件

- Python 3.11以上
- Jupyter Notebook
- 以下のPythonライブラリ:
  - requests
  - beautifulsoup4
  - tqdm
  - pandas

## インストール

1. リポジトリをクローンします。
2. 必要なライブラリをインストールします:

```bash
pip install requests beautifulsoup4 tqdm pandas
```
または、
```bash
uv sync
```

## 使用方法

1. 各Jupyter Notebookファイルを開きます。
2. ノートブック内のセルを順番に実行します。
3. スクレイピングされたデータは、各ノートブックに対応するCSVファイルに保存されます:
   - `dev.ipynb` -> `mito.csv`
   - `dev_2.ipynb` -> `maebashi.csv`
   - `dev_3.ipynb` -> `utsunomiya.csv`
   - `dev_4.ipynb` -> `tsukuba.csv`
   - `dev_5.ipynb` -> `takasaki.csv`
   - `dev_6.ipynb` -> `oyama.csv`
   - `dev_7.ipynb` -> `fukushima.csv`
   - `dev_8.ipynb` -> `kooriyama.csv`

## 出力ファイル

各CSVファイルには以下の情報が含まれます：

- 店名
- 住所
- 電話番号
- 予約・お問い合わせ

## 注意事項

- 過度なアクセスを避けるため、スクレイピングの際には適切な間隔をあけています。
- 食べログの利用規則を確認し、適切に利用してください。
## ライセンス
MIT copyright © 2025 ojizou003