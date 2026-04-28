# 天野のポートフォリオ
YamaMatch

## アプリ概要
Next.js / React / TypeScript / Tailwind CSS / Supabaseを用いた、登山山決め診断アプリです。

## サイトイメージ
![アプリ画面](https://github.com/amanoyuma/portfolio/blob/41093b85196e94805a492514a57428092ef72a27/docs/%E3%83%A1%E3%82%A4%E3%83%B3%E7%94%BB%E9%9D%A2.png?raw=true)


## サイトURL
[アプリのURL](https://yamamatch-gules.vercel.app/)

[GitHubのURL](https://github.com/amanoyuma/yamamatch)

## 使用技術
  - フロントエンド：Next.js 15（App Router） / React / TypeScript  
  - UI：Tailwind CSS / shadcn/ui  
  - 認証・データベース：Supabase（Auth / PostgreSQL / RLS）  
  - API：Open-Meteo（天気情報取得）  
  - 状態管理：React Hooks / Context API（AuthContext）  
  - デプロイ：Vercel  
  - バージョン管理：Git / GitHub  
  - 開発ツール：VSCode / Chrome DevTools  
  - CI/CD：GitHub Actions（ESLint）  
## 設計ドキュメント
[要件定義・基本設計・詳細設計の一覧_Googleスプレッドシート](https://docs.google.com/spreadsheets/d/1X1eVxMKIFJwROTdSe-xkavsRJsfvgtBGdfmgZeLqHu8/edit?gid=983827669#gid=983827669)

詳細設計時のワイヤーフレーム、ER図、ワークフロー図の画像はdocsディレクトリに格納しています。（[こちらからアクセス](./docs)）

## 機能一覧
  - ユーザー登録、ログイン機能
  - 診断機能
  - 山情報表示
  - エラーハンドリング
  - お気に入り機能
  - 山詳細表示機能

## テスト・修正の設計及び実施書
[テスト・修正の設計及び実施書_Googleスプレッドシート](https://docs.google.com/spreadsheets/d/1v_ouh23tU7vjRqk-FJKwtiz9oGkCDDIQ47TfhTElrkY/edit)

## アプリの改善案
[アプリの改善案_Googleスプレッドシート](https://docs.google.com/spreadsheets/d/1DKzuctACtrj6PBpESm4s66xzeMozOg41rx2Ei_z9Yk4/edit)
  - 診断結果保存機能の実装
  - 提案する山のレパートリーを増やす

## 備考
  - 活用した生成AIとその用途
    - ChatGPT：要件定義、設計、各種リサーチ
    - v0：アプリのモック作成
    
    -GitHub Copilot Chat：ローカル環境でのコードの修正相談

  -リファクタリングの規則
  
