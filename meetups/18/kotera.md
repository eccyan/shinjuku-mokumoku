## 会社や業務で普段やっていること
- 仕事
    - RoRアプリケーションのレビューしてます
    - 管理サーバをDockerに移行
    - 書類作成
    
## (option) 教えられるかもしれないこと
- RoR周りなら

## 今日やること

- 開発中のシステムをECRに置いて、k8sでデプロイする

## (option) もしかしたら相談するかもしれないこと
- kube-awsの使い方

## 成果

- 開発中のシステムをECRにおかずにk8sにコンテナを動かすことはできた
- ElastiCacheやSQSに繋がらない。SecurityGroupか? と思いkube-awsを編集。動かなくなったので戻した。動かない。冪等性ェェェ。
- システム構成図を作成中。
- k8sでどうやってデバッグするんだろう。minikube?
