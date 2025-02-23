# 職務経歴

## 概要

機械学習の継続的な本番運用を支える MLOps 領域で経験を積んできました。また、データ活用を促進するための基盤構築にも一定の知見があります。さらに、エンジニアリングマネージャーとして、エンジニアリング組織全体の改善やチームマネジメントにも取り組んできました。

## 株式会社 CoeFont マネージャー/ 基盤全般のエンジニア (2023/06〜現在)

### エンジニアリングマネージャーとして開発組織の改善

約20名のエンジニア（副業含む）を、自分含む2人のEMとVPoEでマネジメントしながら、エンジニアリング組織全体の強化と組織課題の解決に取り組みました。

- **採用**
  - バックエンドエンジニア、MLOpsエンジニア、データエンジニア、機械学習エンジニアのポジションの採用要件・戦略を定め、採用プラットフォームやエージェント（5社）、直接のヘッドハンティング、リファラルなどを活用し、個人として5名の採用を実現しました。
- **目標管理**
  - 1on1ミーティングやOKRを活用し、各メンバーの目標設定と進捗管理を徹底。部門の目標・チームの目標と個人に期待する成果の認識をそろえることに努めました。
- **開発風土・制度設計**
  - AIコーディングエージェント (devin) や AIエディタ (cursor) 等の導入を推進し、開発生産性の向上に寄与しました。
  - リファラル制度を設計・導入し、褒賞金を設定しました。
  - フルリモートおよび英語公用語の組織における連携不足を補うため、定期的に対面での開発やブレインストーミングの場を設ける制度を導入しました。結果、プロダクトの開発品質とスピードが向上し、多くのエンジニアが継続を希望する組織風土を形成しました。
- **MLOpsチームのマネジメント**
  - チーム設立時から参画し、定例ミーティング、開発ルール、チームバックログの整備、メンバーアサインおよび進捗管理を主導しました。
  - 成果を評価され、参画3ヶ月でチームリーダー、1年でチームマネージャーに昇進。チーム規模を3名から6名に拡大しました。
- **CREチームのマネジメント**
  - CREチームの連続退職によるアウトプット低下を受け、新メンバーの受け入れとオペレーション再構築を実施しました。
  - CSチーム向けの管理画面開発および社内セキュリティオペレーションの整備プロジェクトを管理しました。
- **部門横断のバックエンドエンジニアのマネジメント**
  - 組織において Golang バックエンドの技術的負債が深刻化していたため、負債管理の仕組みを策定し、メンバー採用およびプロジェクト推進を実施して危機的状況を脱しました。

### DevOps・SRE関連の整備

WebAppチーム、Desktopチーム、MLOpsチームが利用する基盤の整備を担当しました。

- **監視体制の強化（Sentry / Datadog など）**
  - 全チームへの分散トレーシング導入を推進し、問題発生時の影響ユーザー数、エンドポイント、該当リリース、アプリケーション・ミドルウェア・インフラリソースの状態を可視化しました。これにより、インシデント発生から解決までの時間を短縮すると同時に、全社的に監視の重要性を浸透させました。
  - SLOの設計と継続的な監視・改善、外形監視の導入を実施し、サービス品質の維持・向上に貢献しました。
- **セキュリティの向上**
  - AWS WAFを導入し、ベストプラクティスに沿った設定を実施。必要なトラフィックを誤って遮断しないよう配慮しながら、DOS攻撃などの悪意あるトラフィックをブロックしました。
  - セキュリティ監査対応では、SOC2 typ1/type2に向けた不備のあるVPC整備、脆弱性修正、AWSインフラの整備と社内フローの見直しを実施し、全体の7割のタスクを完遂しました。
- **AWSインフラコスト管理**
  - 社内コスト削減ハッカソンを主導し、DynamoDBやAuroraDBのキャパシティプランニング、S3のリージョン修正、不要リソースの削除、Spotインスタンスへの移行などを実施。結果、全体の約20%のコスト削減に成功しました。
  - 意図しない課金が頻繁に発生していたため、Slack通知Botを整備し、迅速な対応体制を構築しました。

### ML基盤の開発

AI音声合成モデルの推論・学習システムに携わり、インフラ構築からMLエンジニアリング、アプリケーション開発まで幅広く担当しました。

- **基盤のインフラ開発**
  - 基準に満たないシステムをAWS EC2からAWS ECSへ移行し、オートヒーリングやスケーリング対応を実現してSLIを向上させました。また、セキュリティルールおよびサブネット構成の見直しにより、サーバー群をインターネットから隔離。これに伴うVPCや関連リソースの移行を推進しました。
  - AWS Step Functionsを活用した機械学習バッチ基盤のアーキテクチャを選定・構築し、Spotインスタンス利用によるコスト削減、自動リトライによるトイル削減、長期実行の防止、多段ジョブ実行を可能にしました。 [プレスリリース](https://prtimes.jp/main/html/rd/p/000000080.000078329.html)
- **アプリケーション開発**
  - Server-Sent Events（SSE）を利用したアプリケーションを開発し、リアルタイム性の高い機能を提供しました。また、SSEにおけるエラーハンドリングの対処も実施しました。
  - Poetry、Rye、UV、Black、Flake8などの開発ツールや、locustを利用した負荷試験ツールを活用してFastAPIを開発しました。
  - GitHubフローとGitHub Actionsを組み合わせたCI/CD環境を構築し、開発プロセスの効率化を実現しました。
- **MLエンジニアリング**
  - ノイズ除去モデルを導入し、読み上げ音声の品質向上に寄与しました。
  - 音素モデルのルールを改善し、読み上げ精度を向上させました。

### データ分析基盤の整備・社内データ分析文化の醸成

データ基盤をゼロから構築しました。

- **データ基盤の立ち上げ**
  - DynamoDBおよびAuroraからのデータ抽出バッチを開発（Extract処理）しました。
  - DataTransferServiceを活用したデータ転送プロセスを構築（Load処理）しました。
  - データ利用者向けにテーブル設計と最適化（Transform処理）を実施しました。
  - ポリシータグを使用し、センシティブデータへのアクセス制御を設定しました。
  - 不要なスキャンを抑制するための制御設定を実施しました。
  - Stripeやスプレッドシートなど、継続的に追加されるデータソースへの対応を実施しました。
  - Terraformを活用してインフラをコード管理（IaC）しました。
  - Cloud Run上でセルフホスティングされたGoogle Tag Managerを導入しました。
- **ウェアハウス層のモデリング**
  - ステージング層を導入し、一部でディメンショナルモデリングやワイドテーブルを準備しました。
- **社内データ分析文化の醸成**
  - 分析チュートリアルおよび分析事例をまとめたNotionを整備しました。
  - 全社KPIの見直しや開発組織への浸透を目的にワークショップを開催しました。
  - ダッシュボードツールMetabaseを選定し、部門内でアンバサダー活動を実施。結果、全社で定例にダッシュボードを確認する文化が形成されました。

## ピクシブ株式会社 機械学習エンジニア (2021/04〜2024/05)

### レコメンドの推論基盤の作成・社内用レコメンドAPIの作成など

GCP上で機械学習モデルをリアルタイムで推論するための基盤を構築しました。 [GCPの推論基盤を作成した話](https://inside.pixiv.blog/2023/03/02/140000)

- **インフラ**
  - Terraformを活用し、GKE、GCS、Artifact Registry、IAP、VPC Network、Managed SSL、BigQueryなどのリソースを構築しました。
  - Kubernetesのマニフェストをkustomizeで整備しました。
- **CI/CDの整備**
  - GitLab CIによるデプロイフローを整備し、GitOpsを導入しました。
- **アプリケーション変更**
  - PHPによるバックエンドAPIの変更、React、Next、Vueにおけるdebounce処理の実装、GTM用コンポーネントの変更、Google Tag Managerの整備などの付随タスクを実施しました。

- ピクシブ社が展開する複数サービスにレコメンドを提供するためのAPIを構築しました。 [レコメンドAPIを構築した話](https://inside.pixiv.blog/2022/08/04/120000)
  - PHPによるAPIを作成し、各種モックを利用したユニットテストを作成しました。
  - Swaggerを利用してAPIドキュメントを作成し、仕様と実装の一致を確認しました。相違がある場合はビルドを失敗させる仕組みを整備しました。
  - セキュリティ要件に沿ったパラメータ暗号化を実装しました。
  - 並列実施可能なABテスト機構を作成しました.
- **API作成後のプロジェクト推進**
  - 他サービスチームとの連携の下、コサイン類似度ベースのレコメンドを作成し、ABテスト後の効果検証を実施しました。

その他、次の開発業務も実施しました。

- 個人開発していた [文章でイラストを検索できるサービス](https://zenn.dev/sugasuga/articles/83a1ff1c62aa53) を会社POCとしてプロジェクト化しました。
- **バンディットアルゴリズムの設計と運用**
  - ε-greedy法を実装し、バッチで更新する仕組みを構築しました。
- **各種レコメンドアルゴリズム作成**
  - コサイン類似度やMatrix Factorizationベースのレコメンドアルゴリズムを実装しました。
- **GTMを利用した計測基盤の改修**
  - PHPバックエンドの修正、Vue/Reactフロントエンドの調整、GTM設定の見直しを実施しました。
- **悪質ユーザーの検知システム**
  - ルールベースのバッチ処理（PHP）を開発し、悪質ユーザーを検知しました。
- **データ基盤のメンテナンス**
  - JenkinsバッチをAirflowに移行し、Cloud LoggingデータのETL処理を実施しました。
- **インスタンス消し忘れ防止のバッチ**
  - GCEインスタンスの消し忘れをSlackに通知する仕組みを構築し、不要なコスト発生を防止しました。

### 採用・広報業務

採用・広報チームを兼任し、社内外で採用サポートを実施しました。

- **採用**
  - 応募要項の作成や構造化面接シートの策定を実施し、機械学習エンジニアのアルバイト、新卒、中途、業務委託採用のカジュアル面談、書類選考、一次面接の判断などを担当しました。
  - インターン・アルバイトのメンターを合計4回務め、そのうち1名が新卒入社しました。
  - 中途採用チームを兼任し、全職種の一次面接における社内エンジニアのアサイン調整、採用フロー改善、採用基準の統一化プロジェクトを推進しました。
- **広報**
  - 学生向け機械学習コンペティションのスポンサーとして、大学技術サークルと連携し、企画の立案・実施しました。 [コンペティションへのスポンサード事例](https://inside.pixiv.blog/2023/10/26/180000)
  - アプリエンジニア・デザイナー向けのイベントでは、他社との調整、会場設営、配信機材の整備などを担当しました。

## 技術スタック

- **言語**
  - Python (6年)
  - PHP (3年)
  - Golang (0.5年)
  - R (1年)
  - TypeScript (1年)
  - React / Vue (1年)
  - Ruby / C# /Java (学習経験あり)
- **Webフレームワーク**
  - FastAPI / Flask / Django / Echo
- **ミドルウェア**
  - MySQL (2年)
  - DynamoDB (0.5年)
  - Redis / Solr / ElasticSearch / Vertex Matching Engine (学習や個人開発で経験あり)
- **クラウド**
  - GCP全般の知識 (3年)
    - GKE / GCS / GCE / IAP / VPC / GAR / IAM / WAF / BigQuery / Cloud Logging
  - AWS全般の知識 (2年)
    - ECS / EC2 / Lambda / VPC / ECR / IAM / WAF / CloudWatch / CloudFormation
- **ツール**
  - コンテナ系  
    - docker / docker compose
  - Kubernetes系  
    - helm / kustomize / argoCD / k9s
  - バッチ関連ツール  
    - Airflow / Digdag / Jenkins / Step Functions
  - 監視系  
    - Datadog / Sentry

## アウトプット

- **社内ブログ**
  - [レコメンドAPIを構築した話](https://inside.pixiv.blog/2022/08/04/120000)
  - [GCPの推論基盤を作成した話](https://inside.pixiv.blog/2023/03/02/140000)
  - [コンペティションへのスポンサード事例](https://inside.pixiv.blog/2023/10/26/180000)
  - [DynamoDBとAuroraで作るミニマムなデータ基盤の事例紹介](https://zenn.dev/coefont/articles/25f0f649e0b42b)
  - [MLOpsチームの設立をチームトポロジーの視点から振り返る](https://zenn.dev/coefont/articles/21be3d84d1e375)
- **個人ブログ**
  - 技術ブログ [zennアカウント](https://zenn.dev/sugasuga)
  - 個人開発サービスについて: [文章でイラストを検索できるサービス作った](https://zenn.dev/sugasuga/articles/83a1ff1c62aa53)
- **GitHub**
  - GitHubアカウント: [機械学習アルゴリズムのスクラッチ実装など](https://github.com/sugakoji)
- **大学・大学院時代の論文**
  - 学会論文: NBL 送りバント研究 ~無死一塁における最適行動~ (日本統計学会)
  - 卒業論文: 球審の判定の歪みと戦略としての転用可能性 (日本統計学会)
  - 修士論文: 数理最適化によるupliftモデリングの応用と拡張
- **受賞歴**
  - Kaggle Expert (銀1・銅2)
  - 日本統計学会 第8回スポーツデータ解析コンペティション 学生奨励賞
  - 日本統計学会 第7回スポーツデータ解析コンペティション SEM賞
  - 第7回慶応データ解析コンテスト 入賞
  - SAJ2017 スポーツアナリティクス甲子園 入賞
- **学生時代のインターン経験**
  - Datum Studio (2年) ・ ヤフー研究所 (1年) ・ Gunosy.inc (1年) ・ pixiv株式会社 (0.5年) ・ リクルート株式会社 (3ヶ月)
- **資格**
  - GCP PDE資格
  - AWS SAA資格
  - TOEIC 940点
  - TOEFL 80点
  - 基本情報技術者

## 学歴

- 2019年 立教大学 経営学部 国際経営学科 卒業  
- 2021年 慶應義塾大学大学院 経済学研究科 卒業
