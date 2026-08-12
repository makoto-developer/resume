# 職務経歴書

フルスタックデベロッパー / テックリード。フロントエンド・バックエンド・インフラを横断し、要件定義から運用まで一貫して担当しています。

- **開発歴** 15年目(2012年3月〜) / **個人事業歴** 7年目(2019年10月〜)
- **得意領域** Go, TypeScript, Elixir, Rust / マイクロサービス・DDD・クリーンアーキテクチャ / AWS・GCP + Terraform

### 主な実績

- SNS配信システムを Node.js から Elixir(Phoenix) へ移行し、最大スループットを **1,000 req/s → 100,000 req/s** に改善。あわせてサーバ台数を **100台 → 5台** に削減
- Shopifyアプリを初期リリースから担当し、利用者数 **0人 → 数千人**、**年間数億円**の売上を達成
- 決済システムを Cloud SQL から Spanner へ移行。UUIDv6を逆順で発行して水平分散させるなど、Spannerの特性を踏まえて設計・実装

### 目次

- [自己紹介](#自己紹介)
- [技術スキル](#技術スキル)
- [プロジェクト](#プロジェクト)
- [自己PR](#自己pr)

## 自己紹介

|項目|内容|
|:---|:---|
|所在|埼玉県所沢市|
|年齢|34歳(1992年生まれ)|
|開発歴|15年目(2012年3月〜)|
|個人事業歴|7年目(2019年10月〜)|

高校卒業後、データベース専門の会社でインフラエンジニアとしてサーバ構築の技術を身につける。
プログラミングに興味を持ち、SES企業へ転職し複数のプロジェクトでWebアプリ開発の経験を積む。その後大手IT企業へ転職する。
現在はフリーランスとして独立(2019年10月〜)し、都内のベンチャー企業を中心に開発をしている。

### 連絡先・リンク

|項目|リンク|
|:---|:---|
|GitHub|[@makoto-developer](https://github.com/makoto-developer)|
|X (Twitter)|[@makotodeveloper](https://x.com/makotodeveloper)|
|ブログ|[blog.makoto-developer.net](https://blog.makoto-developer.net)|

## 技術スキル

フルスタックデベロッパーとして、フロントエンド、バックエンド、インフラ構築を含む、要件定義〜運用まで一貫して開発をしている。

### プログラミング言語・フレームワーク

**JavaScript・TypeScript(〜v5.9)**

- TypeScript, Node.js(〜v24), Next.js(〜v16), Vue.js(v2), Redux, TanStack, React Nativeなど
- 型プログラミングの経験
- Reactアプリのプロジェクト構成、データストアの設計の経験

**Golang(v1.18〜v1.26)**

- Gin, gRPC, GORM, Cobraなど
- goroutineによる並列・並行処理の設計経験
- パフォーマンスチューニングの経験

**Erlang/Elixir(v1.10〜v1.19)**

- 動画配信サービスのルーティングサーバなど、リアルタイム性が求められるネットワークプログラミングの経験
- TURN/STUNサーバ構築、Phoenixアプリ、LiveViewでチャットアプリなどの開発経験
- Elixir Desktopによるモバイルアプリ、デスクトップアプリの開発経験
- 高性能なサーバを用意せずともリソース効率がとても良い。高可用性が求められるシステムではErlang/Elixirの実績(ダウンタイムがほぼゼロ)を活かして採用することが多い

**Rust(v1.24〜v1.93)**

- Actix Web, Tauri(v2)など
- GUIアプリ、Webアプリなどの開発の経験
- パフォーマンスが求められる部分をRustで作成して、ルーティングはElixirに任せるといった設計の目的で利用することが多い

### UI/UX

Bootstrap, Material-UI, BEM, レスポンシブ対応, Figma, shadcn/uiなど

- 見本があればデザインの実装が可能です。なければ適切に提案して設計・作成します。
- UI/UXの改善・設計の経験

### ミドルウェア

PostgreSQL, MySQL, Oracle, RabbitMQ, MongoDB, Redis, Nginx, Elasticsearch, Zabbixなど

- 設計、導入、パフォーマンスチューニングの経験

### XaaS

Vercel, Netlify, Cloudflare, CircleCI, Salesforce, kintone, さくらVPS, Auth0, Shopifyなど

### AWS

Lambda, AppSync, API Gateway, ElastiCache, Aurora, DynamoDB, CloudWatch, EC2, S3, Cognito, EKS, ECS, WAF, VPC など

- Terraformによるインフラ構築経験

### GCP

Compute Engine, Cloud Functions, Cloud Run, API Gateway, Batch, BigQuery, Bigtable, Dataform, Dataflow, Cloud Tasks, Cloud Scheduler, Cloud SQL, Firebase(Authentication/Data Connect/App Hosting), Spanner, Firestore, Pub/Sub, Vision API, GKE, Cloud Console, Cloud Armor など

- Terraformによるインフラ構築経験

### インフラスキル

オンプレミス環境の構築経験

- サーバ構築
    - 富士通 PRIMERGY ラックサーバ
- ネットワーク敷設作業・設計・構築
    - Yamaha RTXシリーズ、Yamaha L2-PoE(SWX2)、L3-PoE(SWX3)
- 可用性システムの設計、DHCPサーバ、ドメインネームサーバ、SSL設定、NFSサーバ、セキュリティ設計、仮想化(VMware)、コンテナ(Docker) など

### バージョン管理・プロジェクト管理ツール

- GitHub, GitLab, JIRA/Confluence, Backlog, Asana など
- Slack, Discord, oVice, Gather など

### 開発環境

- OS: macOS, Ubuntu
- エディタ: Vim(Neovim), JetBrains製品

### AIツール

Claude Code, Codex, Google Antigravity, GitHub Copilot, JetBrains AI Assistant

## プロジェクト

> - 過去5年分のプロジェクトのみ掲載(2012年より22の開発プロジェクトに参加)
> - 終了日の新しい順に掲載。期間が重複しているものは副業などで並行して稼働
> - 代表的なツールやライブラリのみ記載しているので記載していない技術があります。経験があるかは直接聞いてもらえれば幸いです

### 1. 不動産データ分析アプリ開発 (2026-04 〜 現在)

商業施設やオフィスビルなどの公開されている市場データを蓄積、分析するアプリを開発。

- **ポジション**: フルスタック
- **働き方**: 業務委託 / フルリモート / 開発チーム5人(全体200人)

**担当**

1. オープンデータを担当。国土交通省で公開されているオープンデータを使ってビルや土地の市場価値を履歴として表示する機能を作成。
2. 複数のプロダクトを横断でリファクタリング。重複しているライブラリを共通化、地理データ情報マートを新規構築してデータ取得経路を統一。
3. 検索機能の改善。地図検索機能、PDF出力機能など、バグ修正やレスポンス改善を行う。

**アピールポイント**

- DWH(Snowflake / dbt / Embulk)を使ったデータ基盤の設計と構築
- 地理データを扱うAPIとDB設計
- AIのみでレビューを含めた開発、複数のプロダクトを同時に修正するための仕組み作り

**技術スタック**

- **フロントエンド**: Next.js(v15), TypeScript(v5), TanStack, shadcn/ui, GraphQL
- **バックエンド**: Rust, Ruby(Rails), Python, Golang(v1.25), DDD, Snowflake, Google Maps API, PostgreSQL, MySQL, Highcharts, AWS(Aurora, EKS, ECS, Lambda など), GitHub
- **AI**: Claude Code, Devin

### 2. Shopifyアプリ開発 (2025-04 〜 2026-03)

2024年3月に解散した開発チームに戻る。

- **ポジション**: テックリード / フルスタック
- **働き方**: 業務委託 / フルリモート / 開発チーム10人(全体15人)

**担当**

1. Shopifyアプリの機能開発、運用を担当。問い合わせ対応、トラブルシューティング、スクラムイベントの改善、新規機能追加/機能改善リリースなどを対応。
2. 現在公開しているアプリからShopifyに依存しない新規のスピンオフアプリの開発を担当。
    - ゼロから設計・開発〜リリースまで対応した。
    - Shopify以外のさまざまなプラットフォームの注文データを扱うため、DDD / クリーンアーキテクチャ / マイクロサービスのフルセットを導入した。
    - ProtobufでAPIを統一。DBのテーブルやProtobufのデータ構造は複雑になることが予想されるため抽象化して依存関係を分離して整理。他社のインターフェース変更があった際にも柔軟に変更できるようにデータ構造を設計した。
    - AIを使った開発では、JetBrains MPSを使ってDSLを読み込ませてClaudeのコンテキストを90%減らし、Claude自身用のKanbanを作成して忘却を防ぐなど、ClaudeのAgentやGuidelineを設計して開発した。

**アピールポイント**

- AI(Claude Code / Copilot)を使った開発経験

**技術スタック**

- **フロントエンド**: Next.js(v15), TypeScript(v5), TanStack, shadcn/ui, grpc-transport
- **バックエンド**: Golang(v1.25), gRPC, マイクロサービスアーキテクチャ, クリーンアーキテクチャ, DDD, AWS(Aurora, EKS, ECS, Cognito, Lambda など), Terraform/Helm/Argo, GitLab
- **AI**: Claude Code
- **その他**: Python, Pandas, Jupyter Notebook, ペアプロ, スクラム(1週スプリント)

### 3. 決済システム開発 (2024-04 〜 2025-03)

> 2, 4と同じ会社、別開発チーム

クレジットカードや電子決済などの決済システムの機能開発、運用保守を担当。

- **ポジション**: フルスタック
- **働き方**: 業務委託 / フルリモート / 開発チーム10人(全体200人)

**担当**

- 1〜3年目の若手10名ほどで構成された開発チームで、技術的なアドバイスや開発の進め方などを指導。
- スクラムの進め方などを指導。今いるメンバーに合うやり方を提案して生産性と固有ドメイン知識を徐々に深めて成長する経験を得た。
- Cloud SQLからより高速で可用性の高いSpannerへ移行設計と実装をした。IDをUUIDv6で生成し、逆順で発行しSpannerに登録させることで水平分散させるなど、Spannerの特性を考慮した設計をした。
- Goroutineで並行処理するようにして応答速度を上げたり、MQサービスを使ってビッグバンリクエストがあっても問題ないような可用性を高めるための設計や実装をした。

**アピールポイント**

- 決済の知識(与信システムや3Dセキュアなど)
- GCP Spannerの経験
- Goのパフォーマンスチューニング

**技術スタック**

- **バックエンド**: Golang(v1.22), gRPC, GraphQL, マイクロサービスアーキテクチャ, クリーンアーキテクチャ, Kafka, GCP(Cloud SQL, Spanner, GKE, Cloud Functions, BigQuery など), Terraform/Helm/Argo, GitLab
- **その他**: SAFe, スクラム(2週スプリント)

### 4. Shopifyアプリ開発 (2022-08 〜 2024-03)

> 2と同じクライアント・プロジェクト

Shopifyで公開しているアプリの開発、運用を担当。

- **ポジション**: フルスタック
- **働き方**: 業務委託 / フルリモート / 開発チーム10人(全体15人)

**担当**

- フロントエンド、バックエンドなど含め横断して開発した。
- Kubernetes / Terraform / Helm / Argo セットでインフラを管理する。
- Shopifyは頻繁にバージョンアップがあるためE2Eを実行することでリグレッション試験の時間を短くして工数を削減するなどの取り組みを行った。
- 初期リリースから担当し、利用者数が0人から数千人へ増やし、年間数億円の売り上げを達成することができた。

**アピールポイント**

- Shopifyアプリの開発経験
- 決済システムの開発経験
- 国内/海外配送の知識
- E2Eの導入経験
- モブプロを経験(既存メンバーしか知らない固有ドメイン知識を新規メンバーに共有して受け入れしやすくした)

**技術スタック**

- **フロントエンド**: Next.js(v13), TypeScript(v4), アトミックデザイン, GraphQL, Playwright
- **バックエンド**: Golang(v1.17), GORM, gRPC, GraphQL, マイクロサービスアーキテクチャ, クリーンアーキテクチャ, AWS(Aurora, DynamoDB, SQS, SES, EKS, ECS など), Terraform/Helm/Argo, GitLab
- **その他**: E2E, ペアプロ/モブプログラミング, スクラム(1週スプリント)

### 5. SNS配信システムのリプレイス (2020-05 〜 2023-11)

某SNSサービスのシステム移行。テックリードとして設計から導入〜運用を担当。

- **ポジション**: テックリード / フルスタック
- **働き方**: 副業案件(アルバイト) / フルリモート / 開発チーム5人(全体200人)

**担当**

- Node.jsからElixir(Phoenix)に入れ替えたいと依頼を受けて支援した。
- 技術選定、計画〜リリース、リリース後のメンテナンスなど対応。
- Elixirを導入して、最大スループット1,000req/sから最大100,000req/sに引き上げた。
- サーバ数を100台から5台に減らしてインフラコストを削減できた。

**アピールポイント**

- テックリードの経験
- 開発メンバーの面接、採用活動
- Elixir/Erlangの技術仕様の質疑や勉強会を開催
- Rust/Tauriを使ったモバイルアプリの開発経験
- DevOps環境の導入経験
- 既存サービスの振る舞いをGherkinで記述して整理(E2E試験でデグレ確認)

**技術スタック**

- **フロントエンド**: Next.js(v13), TypeScript(v3), Playwright/Gherkin
- **バックエンド**: Node.js(v14), Elixir(v1.10〜v1.15), Phoenix(v1.4〜v1.6), PostgreSQL(v12), GCP(GKE, BigQuery, Firebase など), RabbitMQ, GitHub
- **モバイル**: Rust(v1.43〜v1.73), Tauri(v1)
- **その他**: E2E, ペアプロ

### 6. SNS配信システムの開発 (2022-03 〜 2022-07)

> 5とは異なる案件

フロントエンド開発チームのテックリードとしてReactの設計を担当。

- **ポジション**: テックリード / フルスタック
- **働き方**: 業務委託 / フルリモート / 開発チーム5人(全体50人)

**担当**

- Vue.jsで作られたアプリが技術的負債が多くなっていたため、新しいアプリでReactに移行したいと依頼を受けて、Reactプロジェクトの設計や実装をした。
- Reactプロジェクトのディレクトリ構成や状態管理設計、モジュール管理方法などを設計した。
- アトミックデザインで設計し、作成したコンポーネントを社内で配布し、誰でも利用できる開発環境を構築した。

**アピールポイント**

- Reactプロジェクトの設計
- Cognitoを使った認証認可の設計

**技術スタック**

- **フロントエンド**: Vue.js(v2), Next.js(v12), Redux, TypeScript(v4), アトミックデザイン
- **バックエンド**: Node.js(v15), AWS(API Gateway, Lambda, Cognito, DynamoDB, AppSync など), レイヤードアーキテクチャ

### 7. インフルエンサー向けアプリ開発 (2021-07 〜 2022-02)

企業とインフルエンサーをつなぎ、商品PRを効率的に管理・運用するためのプラットフォーム開発を担当。

- **ポジション**: フルスタック
- **働き方**: 業務委託 / 基本リモート(週1出社) / 開発チーム7人(全体50人)

**担当**

1. 既存システムの機能開発。Vue.jsアプリに機能追加をした。
2. 新規アプリの立ち上げ。Next.jsアプリの開発。

**アピールポイント**

- アトミックデザインの開発経験
- モダンなフロントエンドの開発経験

**技術スタック**

- **フロントエンド**: Vue.js(v2), Next.js(v11), TypeScript(v4), Redux, BEM(CSS), GraphQL
- **バックエンド**: Golang(v1.14), クリーンアーキテクチャ, GraphQL, gRPC, DDD, Auth0, GitHub

## 自己PR

**分からないことを曖昧にしない**

- 仕様の不明点や疑問点、分からないことがあったら質問するようにしている。
- 率先して仕様や技術など把握するため、どのプロジェクトでも早い段階でプロジェクトの中心メンバーとして動けている。

**テックリードの経験**

- オンプレ・クラウドでサーバ構築、ネットワークの設計、フロントエンド、バックエンド、デザイン、Webアプリ開発に関するほとんどを取り扱える。
- ゼロから設計〜導入、運用を含めて一貫して対応可能。
- また、社員時代にプロジェクトリーダーを経験しており、リリース計画の立案から進行管理・会議のファシリテーションまで対応。

<!-- 原本(Notion): https://app.notion.com/p/40371b14ae284ff391016d0ad6f5fa04 -->
