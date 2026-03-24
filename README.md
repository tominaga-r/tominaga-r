# Hi, I'm Tominaga-r

Webアプリケーション開発に興味があり、個人開発を通して設計と実装の両方を学んでいます。  
Next.js / TypeScript / Supabase を使って、認証・権限制御・状態遷移・テストまで含めたアプリ開発に取り組んでいます。

## Main Projects

### Approval Workflow App
社内申請・承認フローを想定したワークフロー管理アプリです。  
申請者 / 承認者 / 管理者のロールを持ち、RBAC、RLS、RPC、トリガー、E2Eテストを用いて、業務アプリとして成立する最小構成を目指しました。

**主なポイント**
- Next.js App Router
- Supabase Auth / PostgreSQL
- Row Level Security
- RPCによる状態遷移制御
- RBAC
- Vitest / Playwright

### Log App
思考整理や個人用の記録のためのログアプリです。  
タグやテーマでログを整理できる、自分用の静かな記録空間を目指して作成しました。匿名利用から始められ、本登録時にはデータ移行できる構成です。

**主なポイント**
- 匿名ログイン導線
- ログ投稿 / 編集 / 削除
- テーマ・タグ管理
- 非表示フィルタ
- 本登録時のデータ移行
- 設定画面
- RLS / バリデーション / セキュリティ考慮

## What I’m Learning

最初に作ったToDoアプリでは、機能追加を優先しすぎて設計整理が追いつかず、状態管理・認証・API連携の一貫性維持が難しくなりました。  
この経験から、MVP思考、スコープ管理、責務分離の重要性を学びました。

その反省を活かして、最近の開発では次を意識しています。

- 目的と機能範囲を先に決める
- 権限と状態遷移を明確にする
- テストを用意する
- DBレベルでも制約を持たせる

## Tech Stack
- Next.js
- React
- TypeScript
- Supabase
- PostgreSQL
- Tailwind CSS
- Vitest
- Playwright
