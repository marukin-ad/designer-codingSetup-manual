# デザイナー向け Git インストールマニュアル（Mac 版）

## はじめに

このマニュアルは、Mac で Git をインストールするための手順を、デザイナー向けに分かりやすく解説します。

Git とは、ソースコードを管理するためのツールです。誰がいつどのソースコードを管理しているかを知るのに役立ちます。

## 0. 必要なもの

- ターミナル
- Homebrew
- GitHub アカウント
  <br>
  <br>

## 1. Homebrew を使った Git のインストール

1. ターミナルを起動します。
2. 下記のコマンドを実行して `git` をインストールします。

```
brew install git
```

3. git インストール後、こちらも`Homebrew`と同じくどの階層にいても git コマンドを使用できるようにパスを設定します。

```
export PATH="/opt/homebrew/bin:$PATH"
```

4. インストールが完了したら、`git --v`コマンドを実行してバージョン情報が表示されれば、インストール成功です。
   <br>
   <br>

## 2. PC に Git アカウントを作成する

1. [GitHub](https://github.com/signup/) でアカウントを作成します。
   <br>

   ![GitHub アカウント作成](./image/github_signup.png)
   <br>
   <br>

## 3. 自分の PC に Git アカウントを設定する

1. ターミナルを起動します。
2. 下記のコマンドを実行して 先ほど作成した`GitHub`アカウントを設定します。

```
git config --global user.name "名前"
git config --global user.email "メールアドレス"
```

3. これで、Git のアカウント情報が設定され、Git を使うことができるようになりました！
   <br>
   <br>

## おまけ

### Git の構造図

![Gitの構造図](./image/git_flow.avif)
<br>
<br>

### 基本的な Git 用語

- Git： Git は、ソースコードを管理するためのツールです。
- GitHub： GitHub は、ソースコードを管理するためのサーバーです。
  <br>
  <br>

- リポジトリ: ファイルやディレクトリの状態を記録する場所。

  - ローカルリポジトリ：自分のパソコンの中に作られる保管場所（リポジトリ）です。
  - リモートリポジトリ：他の人が作成した保管場所（リポジトリ）です。
    <br>
    <br>

- コミット (commit) : データの変更
- プッシュ (push): データ
- プル (pull)：

    <br>
    <br>

### Git の始めたい方の参考資料

- [Git の始め方](https://prog-8.com/docs/git-env)

