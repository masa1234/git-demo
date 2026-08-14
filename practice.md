# 今日の学び

## 8月11日の学習

- gitの練習

- git init
- git add .
- git commit -m "Initial commit"

- M → 強制的に名前を変更する
- git branch -M main
- git remote add origin git@github.com:masa1234/git-demo.git
- git push -u origin main

## 8月12日の学習

- Spring Bootの学習
  - Spring Bootに関する概念理解
  - Spring Bootを活用するための環境構築
  - MVCモデルの基本に関する実践学習
  - Spring Bootの基本機能に関する実践学習
  - Spring Bootアプリの品質を高めるための学習

## 8月13日の学習

- Spring Boot MVCモデルの学習
  - MODEL　データベースとの接続に関するやり取りを行う。
    データベースとのデータ作成、読み取り、更新、削除を行う。
    データのチェック、金額計算なども実施する。
  - View　画面表示の役割を行う。
    Spring BootではThymeleafを活用したりする。
  - Controller　アプリの制御を担当する。モデルやビューへの支持を出すのが主な役割となる。

- EclipseにEmmetを導入する
  - 「ヘルプ」➡「新規ソフトウェアのインストール」
    画面が開くので「作業対象」に　「http://emmet.io/eclipse/updates/」　を「追加」

## 8月14日の学習

- Spring Boot MVCモデルの学習
  - Repositoryの作成方法を学習した。
    インタフェースで定義してCRUDは自動で生成することが可能なことを確認した。
  - Serviceの作成方法を学習した。
    - リポジトリのメソッドを組み合わせて、複数のデータベース操作を行う
      （例：データ登録後にデータを一括取得する）
    - データベース操作の前後にデータの加工やチェックを行う
      （例：データ登録前にデータが不正でないかチェックする）
    - @Transactionalアノテーションをつけて、複数データを更新するときにトランザクションを実現する
