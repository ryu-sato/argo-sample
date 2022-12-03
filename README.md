# argo-sample
argocd の self manage 設定サンプル

# argocd の Application を追加する方法

- argocd の Application マニフェストを argo/argocd/application-XXX.yaml として追加する (XXX はアプリケーション名と一致させる)
- argo/argocd/kustomization.yaml 内の resources 配列に追加した Application マニフェストファイルへのパスを追加する
- 変更点を git コミットする

# argocd 管理画面例

![image](https://user-images.githubusercontent.com/32702772/205438373-f04c3612-706a-4440-bb91-e0dc91690828.png)
