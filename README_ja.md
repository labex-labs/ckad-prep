# CKAD 対策コース

**言語:** [English](README.md) · [简体中文](README_zh.md) · [Español](README_es.md) · [Français](README_fr.md) · [Deutsch](README_de.md) · [日本語](README_ja.md) · [Русский](README_ru.md) · [한국어](README_ko.md) · [Português](README_pt.md)

<p align="center">
  <a href="https://labex.io/ja/courses/ckad-prep">
    <img src="https://course-cover.labex.io/ckad-prep.png?lang=ja" alt="CKAD 対策コース">
  </a>
</p>

初心者向けの CKAD 対策コースです。kubectl の基本操作やオブジェクトの基礎から、ワークロード、設定、デプロイ、可観測性、ネットワークに至るまで、42 のガイド付き Kubernetes アプリケーション開発実験を通じて体系的に学習できます。

[LabEx でコースを開始](https://labex.io/ja/courses/ckad-prep)

## 演習

|   インデックス | 名前                               | 難易度   | 練習                                                                                                                                   |
|----------|----------------------------------|-------|--------------------------------------------------------------------------------------------------------------------------------------|
|       01 | kubectl、コンテキスト、およびネームスペースの探索     | 初級    | <a target='_blank' href='https://labex.io/ja/labs/explore-kubectl-contexts-and-namespaces-663587?course=ckad-prep'>ラボを開始</a>         |
|       02 | Kubernetes API リソースの調査           | 初級    | <a target='_blank' href='https://labex.io/ja/labs/inspect-kubernetes-api-resources-663608?course=ckad-prep'>ラボを開始</a>                |
|       03 | Pod の作成と調査                       | 初級    | <a target='_blank' href='https://labex.io/ja/labs/create-and-inspect-a-pod-663597?course=ckad-prep'>ラボを開始</a>                        |
|       04 | Pod マニフェストの作成                    | 初級    | <a target='_blank' href='https://labex.io/ja/labs/write-a-pod-manifest-663628?course=ckad-prep'>ラボを開始</a>                            |
|       05 | ラベルとセレクターの使用                     | 初級    | <a target='_blank' href='https://labex.io/ja/labs/use-labels-and-selectors-663626?course=ckad-prep'>ラボを開始</a>                        |
|       06 | kubectl を使用したマニフェストの生成と編集        | 初級    | <a target='_blank' href='https://labex.io/ja/labs/generate-and-edit-manifests-with-kubectl-663604?course=ckad-prep'>ラボを開始</a>        |
|       07 | Deployment の作成                   | 初級    | <a target='_blank' href='https://labex.io/ja/labs/create-a-deployment-663596?course=ckad-prep'>ラボを開始</a>                             |
|       08 | Deployment のスケーリング               | 初級    | <a target='_blank' href='https://labex.io/ja/labs/scale-a-deployment-663618?course=ckad-prep'>ラボを開始</a>                              |
|       09 | ワンタイムジョブの実行                      | 初級    | <a target='_blank' href='https://labex.io/ja/labs/run-one-time-jobs-663616?course=ckad-prep'>ラボを開始</a>                               |
|       10 | CronJob のスケジュール設定                | 初級    | <a target='_blank' href='https://labex.io/ja/labs/schedule-cronjobs-663619?course=ckad-prep'>ラボを開始</a>                               |
|       11 | 適切なワークロードリソースの選択                 | 初級    | <a target='_blank' href='https://labex.io/ja/labs/choose-the-right-workload-resource-663592?course=ckad-prep'>ラボを開始</a>              |
|       12 | Init コンテナの追加                     | 初級    | <a target='_blank' href='https://labex.io/ja/labs/add-init-containers-663589?course=ckad-prep'>ラボを開始</a>                             |
|       13 | サイドカーコンテナの追加                     | 初級    | <a target='_blank' href='https://labex.io/ja/labs/add-a-sidecar-container-663588?course=ckad-prep'>ラボを開始</a>                         |
|       14 | Pod でエフェメラルボリュームと永続ボリュームを使用する    | 初級    | <a target='_blank' href='https://labex.io/ja/labs/use-ephemeral-and-persistent-volumes-in-pods-663624?course=ckad-prep'>ラボを開始</a>    |
|       15 | ConfigMap を使用したアプリケーションの設定       | 初級    | <a target='_blank' href='https://labex.io/ja/labs/configure-applications-with-configmaps-663593?course=ckad-prep'>ラボを開始</a>          |
|       16 | Secret を使用したアプリケーションの設定          | 初級    | <a target='_blank' href='https://labex.io/ja/labs/configure-applications-with-secrets-663594?course=ckad-prep'>ラボを開始</a>             |
|       17 | 環境変数の注入                          | 初級    | <a target='_blank' href='https://labex.io/ja/labs/inject-environment-variables-663607?course=ckad-prep'>ラボを開始</a>                    |
|       18 | 設定ファイルのマウント                      | 初級    | <a target='_blank' href='https://labex.io/ja/labs/mount-configuration-files-663609?course=ckad-prep'>ラボを開始</a>                       |
|       19 | Projected Volume（投影ボリューム）の使用     | 初級    | <a target='_blank' href='https://labex.io/ja/labs/use-projected-volumes-663627?course=ckad-prep'>ラボを開始</a>                           |
|       20 | リソースの要求（Requests）と制限（Limits）の設定  | 初級    | <a target='_blank' href='https://labex.io/ja/labs/set-resource-requests-and-limits-663620?course=ckad-prep'>ラボを開始</a>                |
|       21 | Namespace リソースクォータの適用            | 初級    | <a target='_blank' href='https://labex.io/ja/labs/apply-namespace-resource-quotas-663590?course=ckad-prep'>ラボを開始</a>                 |
|       22 | 専用の ServiceAccount で実行する         | 初級    | <a target='_blank' href='https://labex.io/ja/labs/run-with-a-dedicated-serviceaccount-663617?course=ckad-prep'>ラボを開始</a>             |
|       23 | Pod セキュリティコンテキストの強化              | 初級    | <a target='_blank' href='https://labex.io/ja/labs/harden-a-pod-security-context-663605?course=ckad-prep'>ラボを開始</a>                   |
|       24 | カスタムリソースの発見と利用                   | 初級    | <a target='_blank' href='https://labex.io/ja/labs/discover-and-use-custom-resources-663602?course=ckad-prep'>ラボを開始</a>               |
|       25 | ローリングアップデートの実行                   | 初級    | <a target='_blank' href='https://labex.io/ja/labs/perform-a-rolling-update-663610?course=ckad-prep'>ラボを開始</a>                        |
|       26 | 障害が発生したデプロイメントのロールバック            | 初級    | <a target='_blank' href='https://labex.io/ja/labs/roll-back-a-faulty-deployment-663614?course=ckad-prep'>ラボを開始</a>                   |
|       27 | Deployment の更新戦略を調整する            | 初級    | <a target='_blank' href='https://labex.io/ja/labs/tune-deployment-update-strategy-663622?course=ckad-prep'>ラボを開始</a>                 |
|       28 | カナリアリリースの実装                      | 初級    | <a target='_blank' href='https://labex.io/ja/labs/implement-a-canary-release-663606?course=ckad-prep'>ラボを開始</a>                      |
|       29 | Blue-Green デプロイメントによるトラフィックの切り替え | 初級    | <a target='_blank' href='https://labex.io/ja/labs/switch-blue-green-traffic-663621?course=ckad-prep'>ラボを開始</a>                       |
|       30 | ローカル Helm チャートのデプロイ              | 初級    | <a target='_blank' href='https://labex.io/ja/labs/deploy-a-local-helm-chart-663600?course=ckad-prep'>ラボを開始</a>                       |
|       31 | Kustomize を使用したアプリケーションのカスタマイズ   | 初級    | <a target='_blank' href='https://labex.io/ja/labs/customize-an-application-with-kustomize-663598?course=ckad-prep'>ラボを開始</a>         |
|       32 | ローカルアプリケーションイメージのビルドと実行          | 初級    | <a target='_blank' href='https://labex.io/ja/labs/build-and-run-a-local-application-image-663591?course=ckad-prep'>ラボを開始</a>         |
|       33 | ログとイベントの読み取り                     | 初級    | <a target='_blank' href='https://labex.io/ja/labs/read-logs-and-events-663611?course=ckad-prep'>ラボを開始</a>                            |
|       34 | exec とポートフォワードを使用したデバッグ          | 初級    | <a target='_blank' href='https://labex.io/ja/labs/use-exec-and-port-forwarding-for-debugging-663625?course=ckad-prep'>ラボを開始</a>      |
|       35 | Liveness プローブと Readiness プローブの設定 | 初級    | <a target='_blank' href='https://labex.io/ja/labs/configure-liveness-and-readiness-probes-663595?course=ckad-prep'>ラボを開始</a>         |
|       36 | CrashLooping アプリケーションのデバッグ       | 初級    | <a target='_blank' href='https://labex.io/ja/labs/debug-a-crashlooping-application-663599?course=ckad-prep'>ラボを開始</a>                |
|       37 | 非推奨 API マニフェストの更新                | 初級    | <a target='_blank' href='https://labex.io/ja/labs/update-deprecated-api-manifests-663623?course=ckad-prep'>ラボを開始</a>                 |
|       38 | Service を使用した Deployment の公開     | 初級    | <a target='_blank' href='https://labex.io/ja/labs/expose-a-deployment-with-a-service-663603?course=ckad-prep'>ラボを開始</a>              |
|       39 | Service DNS アクセスの診断              | 初級    | <a target='_blank' href='https://labex.io/ja/labs/diagnose-service-dns-access-663601?course=ckad-prep'>ラボを開始</a>                     |
|       40 | Ingress を使用した HTTP トラフィックのルーティング | 初級    | <a target='_blank' href='https://labex.io/ja/labs/route-http-traffic-with-ingress-663615?course=ckad-prep'>ラボを開始</a>                 |
|       41 | NetworkPolicy を使用したアプリケーション通信の制限 | 初級    | <a target='_blank' href='https://labex.io/ja/labs/restrict-application-traffic-with-networkpolicy-663613?course=ckad-prep'>ラボを開始</a> |
|       42 | 名前付きサービスポートルーティングの修復             | 初級    | <a target='_blank' href='https://labex.io/ja/labs/repair-named-service-port-routing-663612?course=ckad-prep'>ラボを開始</a>               |

## About LabEx

<div align="left"><p><a href="https://labex.io"><strong>LabEx</strong></a> is a <strong>hands-on learning platform for beginners</strong>.</p><p>Explore <a href="https://labex.io/learn/linux"><strong>Linux</strong></a>, <a href="https://labex.io/learn/devops"><strong>DevOps</strong></a>, <a href="https://labex.io/learn/cybersecurity"><strong>Cybersecurity</strong></a>, and <strong>more</strong> — all directly in your browser.</p><p>Learn step by step through <strong>interactive labs</strong>, <strong>guided exercises</strong>, and <strong>real-world projects</strong>. 🌱<br />No setup, no stress — just practice and grow your skills by doing.</p><br /><p><a href="https://apps.apple.com/app/id6765840991"><img src="https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg" alt="Download on the App Store" height="54" /></a>&nbsp;<a href="https://apps.apple.com/app/id6765840991"><img src="https://developer.apple.com/app-store/marketing/guidelines/images/badge-download-on-the-mac-app-store.svg" alt="Download on the Mac App Store" height="52" /></a></p><br /><p>📖 Need help? Visit our <a href="https://support.labex.io/">Help Center</a> or email info@labex.io</p></div>

