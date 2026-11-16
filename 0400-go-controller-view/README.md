# Go Controller/View

## 学ぶこと

- Controller：リクエスト受付、入力検証、レスポンス返却
- View とデータアクセスの責務の分離
- `text/html`：HTML レスポンスの Content-Type
- `text/template`：テキスト生成
- `html/template`：HTML 生成と自動エスケープ

## 課題

[Go + Ent](../0300-go-postgres/README.md) の投稿アプリに画面を追加する。

1. 投稿一覧・詳細・新規作成・編集画面を作成する。
2. Controller で入力を検証し、保存処理と画面表示を呼び出す。
3. `html/template` で HTML を生成し、Content-Type に `text/html; charset=utf-8` を指定する。
4. 共通レイアウトと画面ごとのテンプレートを分離する。
5. `text/template` で投稿のテキスト出力を作成する。
6. 入力不正と投稿が存在しない場合の表示を実装する。

## 完了条件

- ブラウザーから投稿の一覧・詳細・作成・編集を操作できる。
- 入力された HTML がスクリプトとして実行されない。
- Controller と View の責務、2種類のテンプレートの用途を説明できる。

[課題一覧へ戻る](../README.md)
