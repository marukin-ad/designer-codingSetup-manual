# デザイナー向け Node インストールマニュアル（Mac 版）

## はじめに

このマニュアルは、Mac で Node.js をインストールするための手順を、デザイナー向けに分かりやすく解説します。
<br>Node.js は JavaScript をサーバー側で実行できるプラットフォームで、Web サイトやアプリの開発、ツール作成など様々な用途で利用されています。

今回は、Mac で Node.js とそれに付随する npm をインストールする方法について説明します。
<br>
<br>
※ こちらは、homebrew がインストール済んでいることを前提で説明しますので、<br>　 まだインストールしていない方は、[こちら](./1_homebrew_install.md)を参照してください。

<br>
<br>

## 0. 必要なもの

- ターミナル
- [Homebrew] (https://brew.sh/ja/)

<br>
<br>

## 1. Volta を使った Node.js のインストール

Volta は、Mac で Node.js をインストールするためのツールであり、Node.js のバージョンを管理するためのツールです。<br>そのため、まず Volta をインストールする必要があります。
<br>

1. ターミナルを起動します。

2. Volta をインストールします。

```
curl https://get.volta.sh | bash
```

3. これで、インストールが完了です。

<br>
<br>

## 2. Node.js のインストール

1. ターミナルを起動します。

2. Node.js をインストールします。

```
# 安定版
volta install node@latest
```

```
# バージョン指定
volta install node@18
volta install node@14.16.1
```

3. npm をインストールします。

```
volta install npm
```

4. これで、インストールが完了です。
   <br>
   <br>

## 3. インストール済みの Node.js の確認

1. ターミナルを起動します。

2. Node.js のバージョンを確認します。

```
node -v
```

```
npm -v
```

3. これで、インストール済みの Node.js と npm のバージョンを確認できます。
   <br>
   <br>

## 参考 URL

- [Node.js バージョン管理ツール『Volta』を使ってみる](https://qiita.com/nakashun1129/items/47c09ccbbba73c4ef8c4)
  <br>
  <br>

## 各種ツールの URL

- [Volta](https://volta.sh/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/)

