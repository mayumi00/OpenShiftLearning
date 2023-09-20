# OpenShiftハンズオンへようこそ

## 目的

- Container（Docker）の操作を体験します
- OpenShiftの超初級的内容を体験します

## ハンズオンに必要な環境

- ブラウザ（Firefox, Chrome）

## コース数と難易度

- Container編：2コース　★☆☆☆☆ 
- OpenShift編：14コース　★☆☆☆☆ 〜 ★★☆☆☆ 

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

- ハンズオンに順番はありません。好きなハンズオンを体験してください
- OpenShift基礎編はその順が望ましいです
- ハンズオンはそれぞれ独立しているため、Webコンソールやocコマンドでのログインなど重複する部分が多々あります。

**ハンズオンのLaunchボタンを押して環境が整うまでに20分程度かかります。**

### OpenShift基礎編

:green_book: [Getting Started with OpenShift for Developers (Japanese)](https://play.instruqt.com/embed/openshift/tracks/developing-on-openshift-getting-started-jp?token=em_ejUY5shIu9GHyZJD&show_challenges=true)（はじめてみようOpenShift）（所要時間目安：15分〜30分）

難易度：★☆☆☆☆

概要: OpenShift環境でアプリケーションをビルドしてデプロイする

- コマンドラインインターフェースを使用してログインする
- Webコンソールでログインして、新しいプロジェクトを作成し、Parkmapsアプリをイメージからデプロイする
- Webコンソールでアプリケーションをスケーリングする
- OpenShift Routeを利用して外部に公開されたURLにアクセス

:green_book: [Login to an OpenShift cluster (Japanese)](https://play.instruqt.com/embed/openshift/tracks/logging-into-an-openshift-cluster-jp?token=em_5J6Y6rWmtHqwXuA9&show_challenges=true)（OpenShiftクラスター上でのユーザー切り替え）（所要時間目安：10分〜15分）

難易度：★☆☆☆☆

概要: OpenShiftクラスターにログインしてユーザーの操作を行う

- WebコンソールのURLを調べてログインし、新しいプロジェクトを作成する
- コマンドラインインターフェースを使用してログインする
- ocコマンドで新しいユーザーを作成する、Webコンソールを利用してユーザー権限を付与する
- ocコマンドで、ユーザーの切り替えを行う

:green_book: [Deploying Applications From Images (Japanese)](https://play.instruqt.com/embed/openshift/tracks/deploying-applications-from-images-jp?token=em_4er-ge2Y68HjE2Oc&show_challenges=true)（イメージを利用したアプリのデプロイ）（所要時間目安：10分〜15分）

難易度：★☆☆☆☆

概要: イメージを利用してアプリケーションをデプロイする

*NOTE: [Getting Started with OpenShift for Developers (Japanese)](https://play.instruqt.com/embed/openshift/tracks/developing-on-openshift-getting-started-jp?token=em_ejUY5shIu9GHyZJD&show_challenges=true)とほぼ同じ内容で、ocコマンドでイメージからデプロイする項目が追加されています。*

- コマンドラインインターフェースを使用してログインし、ocコマンドで新しプロジェクトを作成する
- Webコンソールでログインして、Parkmapsアプリをイメージからデプロイする
- Webコンソールでアプリケーションをスケーリングする
- ocコマンドでParkmapsに関する詳細を表示した後に、Parkmapsに関連するオブジェクトを削除する
- ocコマンドでParkmapsアプリをイメージからデプロイする


:green_book: [Deploying Applications From Source (Japanese)](https://play.instruqt.com/embed/openshift/tracks/deploying-applications-from-source-jp?token=em_vPba4iC-zQwOtP7S&show_challenges=true)（ソースからのアプリのデプロイ）（所要時間目安：15分〜30分）

難易度：★☆☆☆☆

概要: ソースからアプリケーションをビルドしてデプロイする

- コマンドラインインターフェースを使用してログインし、ocコマンドで新しプロジェクトを作成する
- Webコンソールでログインして、ソースコードをビルドし、アプリをデプロイする
- Webコンソールで、アプリのデプロイのログを表示する
- デプロイされたアプリのURLにアクセスする
- ocコマンドで、デプロイしたアプリに関連するオブジェクトを削除する
- ocコマンドで同じアプリをデプロイする
- 既に実行されているアプリをocコマンドでリビルドする

:new:
:green_book: [OpenShift Persistent Volume (Japanese)](https://play.instruqt.com/embed/openshift/tracks/openshift-persistent-volume-jp?token=em_ZLVCcR0uwZ5MRuvt_challenges=true)（OpenShiftの永続ストレージ）（所要時間目安：15分〜30分）

難易度：★☆☆☆☆

概要: OpenShiftの永続ストレージについて学習する

- ocコマンドで新規プロジェクトを作成し、アプリケーションをデプロイする
- Persistent Volume Clame と Persistent Volumeについて
- 永続ストレージの動作を確認する


:green_book: [Manage Resource Objects (Japanese)](https://play.instruqt.com/embed/openshift/tracks/openshift-manage-resource-objects-jp?token=em_2P_-985m1wllVPOZ&show_challenges=true)（OpenShiftのリソースオブジェクト）（所要時間目安：15分〜30分）

難易度：★☆☆☆☆

概要: OpenShiftの様々なリソースオブジェクトについて理解する

- コマンドラインインターフェースを使用してログインし、ocコマンドで新しプロジェクトを作成し、アプリケーションをデプロイする
- 様々なリソースオブジェクトを表示する
- リソースオブジェクトについて詳細な説明を表示する
- oc editコマンドでリソースオブジェクトを編集する
- oc createでリソースオブジェクトを作成する
- oc replaceとoc patchコマンドの利用
- oc labelコマンドでラベルを設定する
- リソースオブジェクトを削除する

:green_book: （メンテ中）Using Port Forwarding （ポートフォワーディングによるデータベースへのリモートアクセス）（所要時間目安：15分〜30分）

難易度：★★☆☆☆

概要: OpenShift上のデータベースにポートフォワーディングを使用してリモートアクセスする

- コマンドラインインターフェースを使用してログインし、ocコマンドで新しプロジェクトを作成する
- oc new-appコマンドでpostgresql-ephemeralというDBアプリをデプロイする
- oc rshコマンドを利用してコンテナのインタラクティブシェルにアクセスし、shコマンドを実行する
- oc port-forwardコマンドでDBにリモートアクセスする

:green_book: [Transferring Files in and out of Containers (Japanese)](https://play.instruqt.com/embed/openshift/tracks/openshift-transferring-files-jp?token=em_uw1_ii0Sbu-uvwG-&show_challenges=true)（コンテナとローカルマシン間のファイルのコピー）（所要時間目安：15分〜30分）

難易度：★★☆☆☆

概要: 実行中のコンテナとローカルマシンの間でファイルをコピーする

- コマンドラインインターフェースを使用してログインし、ocコマンドで新しプロジェクトを作成する
- oc new-appコマンドでsimplemessageという文字列を表示するアプリをデプロイする
- oc rsyncコマンドでローカルにあるファイルをPodに転送し、ファイルにある文字列が表示されることを確認する
- ローカルのファイルの変更に応じてPodのファイルも変更されることを確認する
- persistent volumeを利用する

### GitOps

:green_book: [Getting Started with ArgoCD and OpenShift GitOps Operator (Japanese)](https://play.instruqt.com/embed/openshift/tracks/gitops-getting-started-jp?token=em_eXQHuhFdwqfyZYka&show_challenges=true)（ArgoCDを使ってみよう）（所要時間目安：15分〜30分）

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

:green_book: [Working with Helm (Japanese)](https://play.instruqt.com/embed/openshift/tracks/gitops-helm-jp?token=em_0IilZzl5oFN6aht3&show_challenges=true
)（所要時間目安：15分〜30分）

難易度：★☆☆☆☆

概要: Argo CDを利用してHelmチャートをデプロイする

- Helmについて
- Argo CDを利用してHelmチャートをデプロイする

### Pipeline

[Getting Started with OpenShift Pipelines (Japanese)](https://play.instruqt.com/embed/openshift/tracks/gitops-pipelines-jp?token=em_Iuuq9GMWhtmKCsnX&show_challenges=true)（tektonを使ってみよう）（所要時間目安：15分〜30分）

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

:green_book: [Playgrounds OpenShift 4.12 (Japanese)](https://play.instruqt.com/embed/openshift/tracks/red-hat-openshift-playground-412-jp?token=em_76RNgIPdTf3tHjE1=true)（自由に使えるOpenShift環境）（1時間利用可能）

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
