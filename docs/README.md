# 職務経歴

## ピクシブ株式会社 機械学習・MLOps 基盤エンジニア (2021/04〜現在)

### 社内用レコメンド API の作成 (メンバー 2 人）

- 役割
  - 立ち上げ・技術選定・実装・運用
- 担当範囲
  - php による MVC アプリケーションの作成
    - MVC アプリケーションの作成
    - 各種モックを利用したユニットテストの作成
    - Swagger を利用した API ドキュメント作成
    - Swagger を利用した仕様と実装を一致させる仕組みの作成
  - 並列実施可能な AB テスト機構の作成
  - API 作成後の他サービスチームとのレコメンド導入のプロジェクト推進
    - コサイン類似度ベースでのレコメンドを作成
    - AB テスト後の効果検証

### MLOps 基盤の整備 (メンバー 3 人）

- 役割
  - 立ち上げ・技術選定・プロジェクト管理・実装・運用
- 担当範囲
  - 技術選定
    - 使用サービス・ツールの検証と選定
  - GCP におけるインフラ構築
    - terraform を使った GCP リソースの作成
    - GKE/GCS/Artifact Registory/IAP/VPC network/Managed SSL/BQ など
  - kubernetes の整備
    - マニフェストファイルの作成
    - kustomize による環境整備
  - CI/CD の整備
    - GitlabCI によるデプロイの整備

### おすすめタグ機能のリプレース (メンバー 2 人）

- 役割
  - 実装・運用
- 担当内容
  - python によるマイクロサービス API の構築
    - 技術選定
    - アプリケーションのレビューと設計方針のアドバイス（コア部分のコーディングはアルバイトの方に行なっていただいたため）
    - ロギング周りの整備
    - テスト/lint/docker image build のための CI の設定整備
  - php のバックエンド API 変更
    - GCP クライアントライブラリ作成
  - react, next, vue のフロントエンド変更
    - debounce 処理の実装
    - UI の変更
    - GTM 用のコンポーネント変更
  - Google Tag Manager の整備
    - 設定変更

### その他の業務 (メンバー 1~3 人）

- bandit アルゴリズムの作成と運用
  - epsilon greedy 法の実装
  - バッチ更新の仕組みの作成
- レコメンドアルゴリズム軽量化
  - BQ でのレコメンドの作成と軽量化
  - 年間 300 万相当の削減
- 各種レコメンドアルゴリズム作成
  - コサイン類似度ベース
  - Matrix Factrization ベース
- GTM を利用した計測基盤の改修
  - php のバックエンド修正
  - vue・react のフロント修正
  - Google Tag Manager の設定作成
- 悪質なユーザーの検知
  - ルールベースで検知するバッチを php で書く
- Jenkins バッチの Airflow 移行
  - 各種 ETL 処理の移行
- cloud logging データの ETL 処理
  - 各種 ETL 処理の実装
- 停止インスタンス防止のバッチ
  - GCE インスタンスの消し忘れを slack に通知する仕組みの作成

### 兼任の採用業務

- 採用
  - 機械学習エンジニアの採用業務  
    機械学習エンジニアのメンバーが数人いる内、VPoE から採用のリーダーにアサインされた。  
    機械学習エンジニアにおける、アルバイト・新卒・中途・業務委託の採用業務を担当。また、応募要項の作成・面接シートの制定・書類選考・1 次面接における判断業務を担当
  - インターン・アルバイトのメンター  
    インターンやアルバイトのメンターを担当  
    合計で 4 人受け入れ、そのうち 1 人は新卒入社予定
  - カジュアル面談担当者  
    カジュアル面談の担当
  - エンジニアの全職種の採用活動  
    エンジニア(数人)・マネージャー・人事・役員から構成される中途採用チームを兼任  
    定常業務で、中途採用における 1 次面接の社内エンジニアのアサインを担当  
    採用フローの改善や、採用基準の統一化プロジェクトを推進

# 技術スタック

- 言語
  - Python(5 年)
  - PHP(2 年)
  - R(1 年)
  - TypeScript(1 年)
  - React/Vue(1 年)
  - Golang(学習経験あり)
  - Ruby, C#, Java(学習経験あり)
- フレームワーク
  - FastAPI/Flask/Django/Next.js
- ミドルウェア
  - MySQL(1 年)
  - Redis/Solr/ElasticSearch/Vertex Matching Engine(学習や個人開発で経験あり)
- クラウド
  - GCP 全般の知識(2 年)
    - GKE/GCS/GCE/IAP/VPC/GAR/IAM/BQ/Cloud Logging
  - AWS
    - SAA 保持程度には学習と経験あり
- ツール
  - コンテナ系  
    docker/docker-compose
  - kubernetes 系  
    helm/kustomize/argoCD/k9s
  - バッチ関連のツール  
    Airflow/Digdag/Jenkins
  - 監視系  
    datadog/sentry

# アウトプット

- 社内ブログ
  - レコメンド API を構築した話：[https://inside.pixiv.blog/2022/08/04/120000](https://inside.pixiv.blog/2022/08/04/120000)
  - GCP の推論基盤を作成した話：[https://inside.pixiv.blog/2023/03/02/140000](https://inside.pixiv.blog/2023/03/02/140000)
- 個人ブログ
  - 技術ブログ zenn: [https://zenn.dev/sugasuga](https://zenn.dev/sugasuga)
  - 個人開発サービスの話: [https://zenn.dev/sugasuga/articles/83a1ff1c62aa53](https://zenn.dev/sugasuga/articles/83a1ff1c62aa53)
- 大学・大学院時代の論文
  - 学会論文: NBL 送りバント研究 ~無死一塁における最適行動~(日本統計学会)
  - 卒業論文: 球審の判定の歪みと戦略としての転用可能性(日本統計学会)
  - 修士論文: 数理最適化による uplift モデリングの応用と拡張
- github  
  機械学習アルゴリズムのスクラッチ実装など  
  [https://github.com/sugakoji](https://github.com/sugakoji)
- 受賞歴
  - kaggle expert(銀 1・銅 2)
  - 日本統計学会 第８回スポーツデータ解析コンペティション 学生奨励賞
  - 日本統計学会 第７回スポーツデータ解析コンペティション SEM 賞
  - 第７回慶応データ解析コンテスト　入賞
  - SAJ2017 スポーツアナリティクス甲子園　入賞
- 学生時代のインターン経験
  - Datum Studio(2 年)
  - ヤフー研究所(1 年)
  - Gunosy.inc(1 年)
  - pixiv 株式会社(0.5 年)
  - リクルート株式会社(3 ヶ月)
- 資格
  - GCP の PDE 資格
  - AWS の SAA 資格
  - TOEIC 940 点
  - TOFFEL 80 点

# 学歴

2019 立教大学 経営学部 国際経営学科 卒業  
2021 慶應大学 大学院 経済大学院 卒業
