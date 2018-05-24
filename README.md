# mv-plugin-workbench
## これは何？
今どきのESを使ってツクールMVのプラグインを書きたい人のためのキットです。
一応Macでも使えるけど、おすすめしません。
## インストール方法
### 必要環境
- [Node.js](https://nodejs.org/ja/)
- [Yarn](https://yarnpkg.com/lang/ja/)
- [Git](https://git-scm.com/)
#### おすすめの構築方法
##### Windows
Windowsなら、[Chocolatey](https://chocolatey.org/)をインストールして、管理者権限のコマンドプロンプトで以下のコマンドを打つと一発で全部インストールできます。
```batchfile
cinst -y nodejs yarn git
```
### インストール
#### Windows
コマンドプロンプトで以下を入力すると、Cドライブ直下に「MV_Plugin_WorkBench」というフォルダが作られ、その中にインストールされます。
```batchfile
cd C:\ && mkdir MV_Plugin_WorkBench && cd MV_Plugin_WorkBench && git clone https://github.com/katai5plate/mv-plugin-workbench && cd mv-plugin-workbench && yarn install && explorer .
```
### 使い方
#### Windows
1. inputフォルダにプラグインを入れる
2. build.batを実行する
3. 特に問題なければ、outputフォルダに古い環境でも動くように変換されたプラグインが生成される。