# Go RealWorld

## 学ぶこと

- API：HTTP メソッド、JSON、入力検証、認証・認可
- Test Code：単体テストと API の結合テスト
- SPA：画面遷移、状態管理、API 連携
- Docker：開発・実行環境のコンテナ化
- Terraform：インフラ構成のコード管理
- Agentic Coding：AI エージェントを活用した開発
  - SKILL：繰り返し使う開発手順の整理
  - MCP：エージェントと開発ツールの接続
  - AgentReview：エージェントによるレビューと指摘の検証

## 課題

Next.js などの SPA と Go の API を組み合わせ、Todo アプリを作成する。

1. ユーザー登録・ログインと、ユーザーごとの Todo の CRUD を実装する。
2. API のリクエスト・レスポンス・エラー形式を定義し、SPA から利用する。
3. 正常系、入力不正、未認証、他ユーザーのデータへのアクセスをテストする。
4. SPA に一覧・追加・編集・削除と、通信中・エラー時の表示を実装する。
5. Docker Compose で SPA・API・PostgreSQL を起動する。
6. Terraform でインフラを定義し、plan で作成予定のリソースを確認する。適用する場合は費用と削除方法を事前に確認する。
7. プロジェクト固有の開発手順を SKILL にまとめる。
8. MCP で開発ツールに接続し、接続先と権限を記録する。
9. AgentReview を実施し、指摘の検証結果と対応を記録する。

## 完了条件

- README の手順で起動し、SPA から Todo を操作できる。
- 他ユーザーの Todo にアクセスできず、主要な正常系・異常系のテストが通る。
- Terraform の plan 結果とインフラの作成・削除手順を説明できる。
- SKILL、MCP、AgentReview の活用方法を説明できる。

[課題一覧へ戻る](../README.md)
