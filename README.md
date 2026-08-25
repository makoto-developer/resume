# 職務経歴書

フルスタックデベロッパー / テックリード。フロントエンド・バックエンド・インフラを横断し、要件定義から運用まで一貫して担当する。

- **開発歴** 15年目(2012年3月〜) / **個人事業歴** 7年目(2019年10月〜)
- **言語** Go, TypeScript, Elixir, Rust
- **設計** マイクロサービス / DDD / クリーンアーキテクチャ
- **インフラ** AWS, GCP, Terraform, Kubernetes

## 自己紹介

|項目|内容|
|:---|:---|
|所在|埼玉県所沢市|
|年齢|34歳(1992年生まれ)|
|GitHub|[@makoto-developer](https://github.com/makoto-developer)|
|X (Twitter)|[@makotodeveloper](https://x.com/makotodeveloper)|
|ブログ|[blog.makoto-developer.net](https://blog.makoto-developer.net)|

高校卒業後、データベース専門の会社でインフラエンジニアとしてサーバ構築の技術を身につける。プログラミングに興味を持ちSES企業へ転職し、複数のプロジェクトでWebアプリ開発の経験を積む。その後大手IT企業を経て、2019年10月にフリーランスとして独立。現在は都内のベンチャー企業を中心に開発している。

## 技術スキル

### 言語

<table>
<tr><th align="left" width="150">言語</th><th align="left">経験</th></tr>
<tr><td nowrap><b>Go</b><br>v1.14〜v1.26</td><td>Gin, gRPC, GORM, Cobra。goroutineによる並列・並行処理の設計、パフォーマンスチューニング</td></tr>
<tr><td nowrap><b>TypeScript</b><br>〜v5.9</td><td>Node.js(〜v24), Next.js(〜v16), Vue.js(v2), Redux, TanStack, React Native。型プログラミング、プロジェクト構成とデータストアの設計</td></tr>
<tr><td nowrap><b>Elixir / Erlang</b><br>v1.10〜v1.19</td><td>Phoenix, LiveView, Elixir Desktop。動画配信のルーティングサーバなどリアルタイム性が求められるネットワークプログラミング、TURN/STUNサーバ構築。高可用性が要るシステムで採用することが多い</td></tr>
<tr><td nowrap><b>Rust</b><br>v1.24〜v1.93</td><td>Actix Web, Tauri(v2)。GUIアプリ、Webアプリ。性能が要る部分をRustで書き、ルーティングはElixirに任せる構成で使うことが多い</td></tr>
</table>

### インフラ・ミドルウェア

<table>
<tr><th align="left" width="150">分類</th><th align="left">技術</th></tr>
<tr><td nowrap>AWS</td><td>Aurora, DynamoDB, Lambda, EKS/ECS, API Gateway, AppSync, Cognito, S3, SQS/SES, ElastiCache, WAF, VPC など</td></tr>
<tr><td nowrap>GCP</td><td>Spanner, Cloud SQL, BigQuery, GKE, Cloud Run/Functions, Pub/Sub, Firestore, Firebase, Dataflow, Cloud Armor など</td></tr>
<tr><td nowrap>IaC・コンテナ</td><td>Terraform, Kubernetes, Helm, Argo CD, Docker</td></tr>
<tr><td nowrap>データストア</td><td>PostgreSQL, MySQL, Oracle, Snowflake, Redis, MongoDB, Elasticsearch</td></tr>
<tr><td nowrap>SaaS・PaaS</td><td>Vercel, Netlify, Cloudflare, CircleCI, Auth0, Shopify, Salesforce, kintone, さくらVPS</td></tr>
<tr><td nowrap>その他</td><td>Kafka, RabbitMQ, Nginx, Zabbix</td></tr>
</table>

設計・導入からパフォーマンスチューニングまで担当。AWS / GCPともにTerraformで構築している。

### オンプレミス

サーバ構築(ラックサーバ、RAID、クラスタ)、ネットワーク敷設・設計(Yamaha RTX/SWXシリーズ)、DHCP/DNS/NFS/SSL、可用性設計、仮想化(VMware)。

### UI/UX

Figma, shadcn/ui, Material-UI, Bootstrap, BEM, レスポンシブ対応。見本があればその通りに実装し、なければ設計から提案する。

### AIツール

Claude Code, Codex, GitHub Copilot, JetBrains AI Assistant, Google Antigravity

## プロジェクト

> - 過去5年分のみ掲載(2012年より22の開発プロジェクトに参加)
> - 終了日の新しい順。期間が重複しているものは副業などで並行して稼働

### 1. 不動産データ分析アプリ開発 (2026-04 〜 現在)

商業施設やオフィスビルなどの公開されている市場データを蓄積、分析するアプリ。

**フルスタック** / 業務委託・フルリモート / 開発チーム5人(全体200人)

- 国土交通省が公開するオープンデータを使い、ビルや土地の市場価値を履歴として表示する機能を開発
- DWH(Snowflake / dbt / Embulk)によるデータ基盤の設計と構築
- 地理データを扱うAPIとDBの設計
- 複数プロダクトを横断してリファクタリング。重複ライブラリを共通化し、地理情報データマートを新規構築してデータ取得経路を統一
- 地図検索、PDF出力などのバグ修正とレスポンス改善
- AIがレビューまで担当する開発フローの構築と、複数プロダクトを同時に修正するための仕組み作り

<table>
<tr><th align="left" width="150">分類</th><th align="left">技術</th></tr>
<tr><td nowrap>フロントエンド</td><td>Next.js(v15), TypeScript(v5), TanStack, shadcn/ui, GraphQL</td></tr>
<tr><td nowrap>バックエンド</td><td>Rust, Ruby(Rails), Python, Go(v1.25), DDD, Snowflake, Google Maps API, PostgreSQL, MySQL, Highcharts, AWS(Aurora, EKS, ECS, Lambda など), GitHub</td></tr>
<tr><td nowrap>AI</td><td>Claude Code, Devin</td></tr>
</table>

### 2. Shopifyアプリ開発 (2025-04 〜 2026-03)

Shopifyアプリの機能開発・運用と、Shopifyに依存しないスピンオフアプリの新規開発。2024年3月に解散した開発チームに復帰。

**テックリード / フルスタック** / 業務委託・フルリモート / 開発チーム10人(全体15人)

- 既存Shopifyアプリの機能開発と運用。問い合わせ対応、トラブルシューティング、スクラムイベントの改善
- スピンオフアプリをゼロから設計・開発・リリース。多様なプラットフォームの注文データを扱うためDDD / クリーンアーキテクチャ / マイクロサービスを導入
- ProtobufでAPIを統一。他社のインターフェース変更にも追随できるよう、データ構造を抽象化して依存関係を分離
- AI(Claude Code / Copilot)を使った開発の仕組み作り。JetBrains MPSでDSLを読み込ませてClaudeのコンテキストを90%削減し、Claude自身用のKanbanで忘却を防ぐなど、AgentやGuidelineを設計

<table>
<tr><th align="left" width="150">分類</th><th align="left">技術</th></tr>
<tr><td nowrap>フロントエンド</td><td>Next.js(v15), TypeScript(v5), TanStack, shadcn/ui, grpc-transport</td></tr>
<tr><td nowrap>バックエンド</td><td>Go(v1.25), gRPC, マイクロサービスアーキテクチャ, クリーンアーキテクチャ, DDD, AWS(Aurora, EKS, ECS, Cognito, Lambda など), Terraform/Helm/Argo CD, GitLab</td></tr>
<tr><td nowrap>AI</td><td>Claude Code</td></tr>
<tr><td nowrap>その他</td><td>Python, Pandas, Jupyter Notebook, ペアプロ, スクラム(1週スプリント)</td></tr>
</table>

### 3. 決済システム開発 (2024-04 〜 2025-03)

> 2, 4と同じ会社、別開発チーム

クレジットカードや電子決済などの決済システムの機能開発、運用保守。

**フルスタック** / 業務委託・フルリモート / 開発チーム10人(全体200人)

- Cloud SQLからSpannerへの移行を設計・実装。IDをUUIDv6で生成して逆順で発行し、水平分散させるなどSpannerの特性を考慮して設計
- goroutineによる並行処理で応答速度を改善。MQサービスを使い、リクエストが急増しても処理を捌ける構成を設計
- 決済機能の開発を通じて、与信システムや3Dセキュアなどのドメイン知識を習得
- 1〜3年目の若手10名ほどのチームで、技術的なアドバイスとスクラムの進め方を指導。メンバーに合うやり方を提案し、生産性を高め、ドメイン知識を深めた

<table>
<tr><th align="left" width="150">分類</th><th align="left">技術</th></tr>
<tr><td nowrap>バックエンド</td><td>Go(v1.22), gRPC, GraphQL, マイクロサービスアーキテクチャ, クリーンアーキテクチャ, Kafka, GCP(Cloud SQL, Spanner, GKE, Cloud Functions, BigQuery など), Terraform/Helm/Argo CD, GitLab</td></tr>
<tr><td nowrap>その他</td><td>SAFe, スクラム(2週スプリント)</td></tr>
</table>

### 4. Shopifyアプリ開発 (2022-08 〜 2024-03)

> 2と同じクライアント・プロジェクト

Shopifyで公開しているアプリの開発、運用。

**フルスタック** / 業務委託・フルリモート / 開発チーム10人(全体15人)

- 初期リリースから担当し、利用者数を0人から数千人へ増やし、年間数億円の売上を達成
- フロントエンド、バックエンドを横断して開発
- Kubernetes / Terraform / Helm / Argo CDでインフラを管理
- Shopifyは頻繁にバージョンアップがあるため、E2Eでリグレッション試験を自動化して工数を削減
- 決済と国内/海外配送の実装を通じてドメイン知識を習得
- モブプロを導入し、既存メンバーしか知らないドメイン知識を新規メンバーへ共有して受け入れをしやすくした

<table>
<tr><th align="left" width="150">分類</th><th align="left">技術</th></tr>
<tr><td nowrap>フロントエンド</td><td>Next.js(v13), TypeScript(v4), アトミックデザイン, GraphQL, Playwright</td></tr>
<tr><td nowrap>バックエンド</td><td>Go(v1.17), GORM, gRPC, GraphQL, マイクロサービスアーキテクチャ, クリーンアーキテクチャ, AWS(Aurora, DynamoDB, SQS, SES, EKS, ECS など), Terraform/Helm/Argo CD, GitLab</td></tr>
<tr><td nowrap>その他</td><td>E2E, ペアプロ/モブプログラミング, スクラム(1週スプリント)</td></tr>
</table>

### 5. SNS配信システムのリプレイス (2020-05 〜 2023-11)

某SNSサービスのシステム移行。テックリードとして技術選定から導入・運用まで担当。

**テックリード / フルスタック** / 副業案件(アルバイト)・フルリモート / 開発チーム5人(全体200人)

- Node.jsからElixir(Phoenix)への移行を依頼され、技術選定、計画〜リリース、リリース後のメンテナンスまで対応
- 最大スループットを1,000 req/sから100,000 req/sに引き上げ
- サーバ数を100台から5台に減らし、インフラコストを削減
- 既存サービスの振る舞いをGherkinで記述して整理し、E2Eでデグレを検出できるようにした
- DevOps環境の導入
- Rust/Tauriを使ったモバイルアプリの開発
- 開発メンバーの面接・採用活動、Elixir/Erlangの勉強会の開催

<table>
<tr><th align="left" width="150">分類</th><th align="left">技術</th></tr>
<tr><td nowrap>フロントエンド</td><td>Next.js(v13), TypeScript(v3), Playwright/Gherkin</td></tr>
<tr><td nowrap>バックエンド</td><td>Node.js(v14), Elixir(v1.10〜v1.15), Phoenix(v1.4〜v1.6), PostgreSQL(v12), GCP(GKE, BigQuery, Firebase など), RabbitMQ, GitHub</td></tr>
<tr><td nowrap>モバイル</td><td>Rust(v1.43〜v1.73), Tauri(v1)</td></tr>
<tr><td nowrap>その他</td><td>E2E, ペアプロ</td></tr>
</table>

### 6. SNS配信システムの開発 (2022-03 〜 2022-07)

> 5とは異なる案件

フロントエンド開発チームのテックリードとしてReactアプリの設計を担当。

**テックリード / フルスタック** / 業務委託・フルリモート / 開発チーム5人(全体50人)

- 技術的負債が蓄積したVue.jsアプリをReactへ移行するにあたり、ディレクトリ構成、状態管理、モジュール管理方法を設計
- アトミックデザインで設計したコンポーネントを社内に配布し、どの部署でも使える開発環境を構築
- Cognitoを使った認証認可の設計

<table>
<tr><th align="left" width="150">分類</th><th align="left">技術</th></tr>
<tr><td nowrap>フロントエンド</td><td>Vue.js(v2), Next.js(v12), Redux, TypeScript(v4), アトミックデザイン</td></tr>
<tr><td nowrap>バックエンド</td><td>Node.js(v15), AWS(API Gateway, Lambda, Cognito, DynamoDB, AppSync など), レイヤードアーキテクチャ</td></tr>
</table>

### 7. インフルエンサー向けアプリ開発 (2021-07 〜 2022-02)

企業とインフルエンサーをつなぎ、商品PRを管理・運用するプラットフォーム。

**フルスタック** / 業務委託・基本リモート(週1出社) / 開発チーム7人(全体50人)

- 既存のVue.jsアプリへの機能追加
- アトミックデザインで新規Next.jsアプリを立ち上げ

<table>
<tr><th align="left" width="150">分類</th><th align="left">技術</th></tr>
<tr><td nowrap>フロントエンド</td><td>Vue.js(v2), Next.js(v11), TypeScript(v4), Redux, BEM(CSS), GraphQL</td></tr>
<tr><td nowrap>バックエンド</td><td>Go(v1.14), クリーンアーキテクチャ, GraphQL, gRPC, DDD, Auth0, GitHub</td></tr>
</table>

<!-- 原本(Notion): https://app.notion.com/p/40371b14ae284ff391016d0ad6f5fa04 -->
