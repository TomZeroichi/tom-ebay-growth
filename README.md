# TOM eBay Growth v1.0.1

eBayの12ヶ月成長ロードマップを管理するPWAツールです。
STEP3は7〜9ヶ月、STEP4は10〜12ヶ月です。

## GitHub Pagesの公開手順

1. GitHubリポジトリ `TomZeroichi/tom-ebay-growth` を開く。
2. **Settings → Pages → Build and deployment** に進み、Source を **Deploy from a branch**、Branch を **main**、Folder を **/(root)** にして Save する。
3. 公開URL: https://tomzeroichi.github.io/tom-ebay-growth/
4. Android Chromeの「ホーム画面に追加」「アプリをインストール」から使用できます。

## 収録機能

- 12ヶ月の目標・実績・進捗チェック
- 4ステップのロードマップ
- 利益・出品・評価の集計とグラフ
- 利益シミュレーター
- JSONバックアップ・復元
- PWA表示・オフライン利用

## データの扱い

入力した実績やメモはブラウザ内のlocalStorageに保存されます。GitHubには送信されません。
ブラウザデータを削除したり、端末を変えると消えるためJSONバックアップを使用してください。
このリポジトリのHTMLコードと初期目標のデータは公開されます。
他のTOMアプリのキャッシュを削除しないようService Workerの削除対象はこのアプリのものだけに制限しています。
