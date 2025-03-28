# openhands_sandbox

このプロジェクトはOpenHandsを使った開発を体験するためのサンドボックス環境です。

## プロジェクト概要
- 現在開発中のプロジェクトで、作るものや技術スタックはこれから決定します
- OpenHands AIアシスタントを使った開発フローを体験できます

## セットアップ手順
1. OpenHands resolverをインストール:
   ```bash
   pip install openhands-resolver
   ```
2. 環境変数を設定:
   ```bash
   export OPENHANDS_API_KEY=your_api_key_here
   ```

## OpenHandsへの依頼方法
- 修正や機能追加が必要な場合はIssueを作成
- Issueに`fix-me`ラベルを付けてください
- OpenHandsが自動的にIssueを検出して対応を開始します

## トラブルシューィング
- RateLimitErrorが発生した場合:
  ```python
  # modelを変更してみる
  model = "deepseek/deepseek-r1:free"  # google/gemini-2.5-pro-exp-03-25:freeから変更
  ```
