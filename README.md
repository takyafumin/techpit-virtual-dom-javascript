Techpit, 自作仮想 DOM フレームワークでフォローボタンを実装して React や Vue の内部を理解しよう！
====================


<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->

<!-- code_chunk_output -->

- [環境](#-環境)
- [構成](#-構成)
- [使い方](#-使い方)
  - [jQueryプロジェクト](#-jqueryプロジェクト)
  - [myprojectプロジェクト](#-myprojectプロジェクト)
  - [reactプロジェクト](#-reactプロジェクト)

<!-- /code_chunk_output -->

## 環境

| プログラム | バージョン |
| ---------- | ---------- |
| node       | v19.1.0    |


## 構成

| フォルダ  |             内容             |
| --------- | ---------------------------- |
| jquery    | jQueryで実装したプロジェクト |
| myproject | 自作したプロジェクト         |
| react-app | reactで実装したプロジェクト  |


## 使い方

リポジトリを`clone`して各プロジェクトごとにサーバを起動してください

### jQueryプロジェクト

`jquery/src/index.html`をブラウザで開いてください。

### myprojectプロジェクト

```bash
cd myproject

# npm modulesをインストール
npm ci

# 開発用サーバを起動
# 停止させる場合はCntl-C
npm start
```

### reactプロジェクト

```bash
cd react-app

# npm modulesをインストール
npm ci

# 開発用サーバを起動
# 停止させる場合はCntl-C
npm start
```
