# 第３回講義課題
## 2023年2月受講
#### 1. サンプルアプリケーションのデプロイ

<img width="397" alt="webアプリケーションの起動" src="https://github.com/NakanoYm/Raisetech/assets/157878670/930af723-0102-40c3-ad63-b0299a725434">

#### 2. APサーバーについて
- puma  ver. 5.6.8
- APサーバーの終了と再起動

<img width="558" alt="アプリケーション非表示" src="https://github.com/NakanoYm/Raisetech/assets/157878670/5fa12128-4d6d-410c-9652-06af1103afc1">
<img width="523" alt="APサーバーの再起動" src="https://github.com/NakanoYm/Raisetech/assets/157878670/6a5d8ac5-f907-495c-8140-b0c0e752763e">

#### 3. DBサーバーについて
- MySQL  ver. 8.0.36
- DBサーバーの終了と再アクセス

<img width="528" alt="DBサーバーの終了と再アクセス" src="https://github.com/NakanoYm/Raisetech/assets/157878670/0ef229ee-b4a0-475e-ab07-a9f168fa4acc">

- Railsの構成管理ツールはBundler


#### 今回の課題の所感
デプロイの過程でMySQLのPWを間違えてymlファイルに記入しており、解決に１週間ほどを要した。
その過程でコマンドやエラーの解釈や、バージョンのセットアップ作業の反芻など、得られるものは多かったが、
現場に出た時は、無用に時間を浪費してしまう凡ミスには気をつけたい。
