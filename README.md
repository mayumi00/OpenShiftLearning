# OpenShiftハンズオンへようこそ

## 目的

- Container（Docker）の操作を体験します
- OpenShiftの超初級的内容を体験します

## ハンズオンに必要な環境

- ブラウザ（Firefox, Chrome）

## コース数と難易度

- Container編：2コース　★☆☆☆☆ 
- OpenShift編：9コース　★☆☆☆☆ 

|  難易度  |    |
| ---- | ---- |
|  とても易しい  |  ★☆☆☆☆  |
|  易しい |  ★★☆☆☆  |
|  普通  |  ★★★☆☆  |
|  少し難しい  |  ★★★★☆  |
|  難しい  |  ★★★★★  |

---

## Container編

Container 101,102の順に進めてください。
**ハンズオンのLaunchボタンを押して環境が整うまでに数分かかります。**

:green_book: [container101-jp](https://play.instruqt.com/embed/openshift/tracks/container101-jp?token=em_cwrtT0g1S8AGiCbI&show_challenges=true)（所要時間目安：15分〜30分）

難易度：★☆☆☆☆

概要: コンテナの起動と操作

- コンテナの起動
- コンテナの操作とコンテナ内の操作
- コンテナへのアプリケーションの導入
- コンテナイメージの作成

:green_book: [container102-jp](https://play.instruqt.com/embed/openshift/tracks/container102-jp?token=em_YTfHS1Bmrj3dKD5R&show_challenges=true)

難易度：★☆☆☆☆

概要: Dockerfileの利用

- Dockerfileを利用してのコンテナイメージのビルド
- Dockerfileの変更に基づくコンテナイメージの変更
- ビルドされたイメージの利用例

## OpenShift編

コースに順番はありません。好きなコースを体験してください。コース内容には一部重複するものがございます。
**ハンズオンのLaunchボタンを押して環境が整うまでに20分程度かかります。**

:green_book: [Login to an OpenShift cluster (Japanese)](https://play.instruqt.com/embed/openshift/tracks/logging-into-an-openshift-cluster-jp?token=em_5J6Y6rWmtHqwXuA9&show_challenges=true)（所要時間目安：10分〜15分）

難易度：★☆☆☆☆

概要: OpenShiftクラスターにログインしてユーザーの操作を行う

- OpenShiftクラスタのWebコンソールURLを調べてアクセスする
- OpenShift Command Line Toolの利用
- OpenShiftの新規ユーザー作成と権限付与
- ユーザーの切替

:green_book: [Getting Started with OpenShift for Developers (Japanese)](https://play.instruqt.com/embed/openshift/tracks/developing-on-openshift-getting-started-jp?token=em_ejUY5shIu9GHyZJD&show_challenges=true)（所要時間目安：15分〜30分）

難易度：★☆☆☆☆

概要: OpenShift環境でアプリケーションをビルドしてデプロイする

- ocコマンドでOpenShiftクラスタにアクセス
- WebコンソールでOpenShiftクラスタにアクセスしイメージからアプリケーションをデプロイ
- デプロイしたアプリケーションをスケールする
- OpenShift Routeを利用して外部に公開されたURLにアクセス

:green_book: [Deploying Applications From Source (Japanese)](https://play.instruqt.com/embed/openshift/tracks/deploying-applications-from-source-jp?token=em_vPba4iC-zQwOtP7S&show_challenges=true)（所要時間目安：15分〜30分）

難易度：★☆☆☆☆

概要: ソースからアプリケーションをビルドしてデプロイする

- ocコマンドを利用してプロジェクトを作成、Webコンソールで確認
- Webコンソールを利用してソースからアプリをビルド&デプロイ
- Webコンソールでアプリのログを確認
- 外部に公開されたURLにアクセスしアプリの確認
- アプリの削除
- ocコマンドでアプリを再度デプロイ
- ビルドトリガーの設定

### GitOps

:green_book: [Getting Started with ArgoCD and OpenShift GitOps Operator (Japanese)](https://play.instruqt.com/embed/openshift/tracks/gitops-getting-started-jp?token=em_eXQHuhFdwqfyZYka&show_challenges=true)（所要時間目安：15分〜30分）

難易度：★☆☆☆☆

概要: OpenShiftのGitOpsを体験する

- OpenShiftのGitOpsについてとOperatorのインストール
- Argo CDにインスタンスにCLIとGUIを用いて接続する
- サンプルアプリケーションをデプロイし、Gitで変更を行った内容がアプリに反映されることを確認する

:green_book: [Working with Kustomize (Japanese)](https://play.instruqt.com/embed/openshift/tracks/gitops-kustomize-jp?token=em_xwRSqwHEZLz-4S1u&show_challenges=true)（所要時間目安：15分〜30分）

難易度：★☆☆☆☆

概要: Kustomizeを利用してアプリケーションをデプロイする

- Kustomizeの仕組みとCLIについて
- Kustomizedアプリケーションをデプロイする

:new:
:green_book: [Working with Helm (Japanese)](https://play.instruqt.com/embed/openshift/tracks/gitops-helm-jp?token=em_0IilZzl5oFN6aht3&show_challenges=true
)（所要時間目安：15分〜30分）

難易度：★☆☆☆☆

概要: Argo CDを利用してHelmチャートをデプロイする

- Helmについて
- Argo CDを利用してHelmチャートをデプロイする

### Pipeline

[Getting Started with OpenShift Pipelines (Japanese)](https://play.instruqt.com/embed/openshift/tracks/gitops-pipelines-jp?token=em_Iuuq9GMWhtmKCsnX&show_challenges=true)（所要時間目安：15分〜30分）

難易度：★☆☆☆☆

概要: OpenShift Pipelines を使用してアプリケーションのデプロイを自動化する方法を学習する

- OpenShift Pipelines Operatorをインストール
- サンプル　Hello World Taskを作成
- Taskリソース定義
- Tekton Pipelineを作成
- 作成したPipelineをトリガーして、アプリケーションのデプロイを完了

### Serverless

:green_book: [Getting Started with OpenShift Serverless (Japanese)](https://play.instruqt.com/embed/openshift/tracks/serverless-getting-started-jp?token=em_l5TuSKB7oPQwryBT&show_challenges=true)（所要時間目安：15分〜30分）

難易度：★☆☆☆☆

概要: クラウドネィティブな開発モデルを提供する OpenShift Serverless の使用方法の基本を学習する

- OpenShift Serverlessのserviceをデプロイ
- 複数のrevisionsをデプロイ
- Serverless serviceの基本コンポーネント
- Serverlessがscale-to-zeroを可能にする方法
- canary および blue-green デプロイメント
- knative client の利用

### Playgrounds OpenShift

:green_book: [Playgrounds OpenShift 4.9 (Japanese)](https://play.instruqt.com/embed/openshift/tracks/playgrounds-openshift49-jp?token=em_45GQzjHJQWBluzkt&show_challenges=true)（1時間利用可能）

難易度：★☆☆☆☆

概要: 演習項目は特に無し

- admin権限ありで自由にえるOpenShift4.9環境。ただしworkerの数を増やすようなOps的な操作はできません。

:green_book: [Playgrounds OpenShift 4.11 (Japanese)](https://play.instruqt.com/embed/openshift/tracks/playgrounds-openshift411-jp?token=em_lgmeM3oAOksQvgHJ&show_challenges=true)（1時間利用可能）

難易度：★☆☆☆☆

概要: 演習項目は特に無し

- admin権限ありで自由に使えるOpenShift 4.11環境。ただしworkerの数を増やすようなOps的な操作はできません。


## :pencil: FAQ

- 演習環境が動きません
   - 環境のリソースの状態等により環境のロードに失敗する場合があります。リロードしてください。それでも駄目な場合は時間をおいて試してください。

- OpenShiftクラスターにログインを試みるとエラーメッセージが表示されます。／　OpenShiftコンソールのpodがRunning状態にもかかわらずconsoleへのrouteを探すコマンドを実行するとメッセージが表示されます。
   - `Error from server (InternalError): Internal error occurred: unexpected response: 503`
   - `Unable to connect to the server: EOF`
   - `The connection to the server oauth-openshift.crc-dzk9v-master-0.crc.XXXXXXX.instruqt.io was refused - did you specify the right host or port?`
   
      - まだ環境が整っていない可能性があるので、しばらく時間をおいてから、再度、ログインまたはconsoleへのrouteを探すコマンドを実行してください。
      
 
- OpenShiftのWebコンソールにアクセスするとエラーで接続できません
   - `アクセスしようとするサイトを見つけられません`
   
      - まだ環境が整っていない可能性があるので、しばらく時間をおいてから、再度、WebコンソールのURLにアクセスしてください。
   
- OpenShiftのWebコンソールにアクセスすると「警告：将来の潜在的なセキュリティリスク（Firefoxの場合）」が表示されます。
   - 自己証明利用に起因するものなので、そのまま続行してください。

- コピーしたコマンドを貼り付ける方法について

   - Cmd + V （macOS上のChrome）
   - Ctrl + Shift + V （Windows10上のChromeとFirefox）
   - ターミナルウィンドウで 右クリック + 貼り付け （Windows10 Edge）

##  :heavy_exclamation_mark: 免責事項

- 本教材は作成者およびコントリビューターが個人で知りうる範囲で作成しており、その正確性と完全性を保証するものではありません。
- 本教材から得られた情報により、何らかの損害を負った場合であっても、作成者並びにコントリビューターは一切の責任を負いません。予めご了承ください。
