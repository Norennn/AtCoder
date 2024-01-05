# AtCoder

AtCoderをJSで解く用テンプレート

## 実行環境

node 18.16.1

```bash
npm i
```
パッケージインストール

## 環境構築

- 基本的にこれ<br>
  https://zenn.dev/deen/articles/137bf151b139ef
- macOSでのPATHの通し方<br>
  https://zenn.dev/oreilly_ota/articles/b8482ba9a4ca24
- atcoder-cliを導入に関する記事<br>
  http://tatamo.81.la/blog/2018/12/07/atcoder-cli-tutorial/<br>
  https://twoooooda.net/post/introduce-atcoder-cli/
- エイリアスの設定<br>
  https://zenn.dev/collabostyle/articles/4ad7e7169da15b

## コマンド

```bash
acc new abs
```

問題のテスト用ファイルを取得
名前の部分は、AtCoderのサイトのURL末尾を見るとわかりやすい。<br>
absのコンテストトップページ：https://atcoder.jp/contests/abs

```bash
oj-t-js
```

テストを行う

```bash
acc-s-js
```

提出する
