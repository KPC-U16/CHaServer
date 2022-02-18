# リポジトリ管理

## 1. issueについて
### MUST
1. バグ修正、機能追加を行う際は必ず先にissueを立てる 
2. 関連するissue,pullReqが存在する場合は必ずコメントにIDを記載する
3. 適切なTemplateを利用する
4. 作業担当者を必ずアサインする(新規で割り振られた場合も同様)
### SHOUD
1. 解決策を記載するときは分かりやすく書く
2. 外部から引用する際はURLと引用したい部分を書く
<br>
<br>

## 2. pullReqestについて
### MUST
1. 作業途中でcommitする場合はdraftで作成する
2. 関連するissue,pullReqが存在する場合は必ずコメントにIDを記載する
3. Reviewersを設定する(Self-Reviewしたい場合は設定しない)
<br>
<br>

## 3. branchについて
### MUST
1. git-flowをベースに運用する
2. 以下の命名規則に従う  
` {feature,hotfix,release}-任意のブランチ名_{issue又はpullReqのID} `    
例えば [issue] README.mdの整備#1 を作業するときは  
` future-README_#1 `  
となります。
3. featureはdevelopへmargeするまでにdevelopのすべての変更を取り込む
<br>
<br>

