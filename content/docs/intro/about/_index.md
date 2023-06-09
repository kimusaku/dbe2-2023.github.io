+++
title = "この科目について"
description = ""
weight = 10
alwaysopen = true
mathjax = true
+++

## moodle

講義管理システム．

* URL: https://moodle.is-trm.net/

## 副題

データベースを用いたウェブアプリケーションの構築

## 到達目標

* ウェブアプリケーションの構成を理解し，各要素の役割がわかるようになる．
* 簡単なウェブアプリケーションが構築できるようになる．

## 内容

今日実運用されている多くのアプリケーションは，以下の構造を持つものが多い．サーバで動作するデータベースをバックエンドに持ち，クライアントはウェブブラウザ上に構築して，サーバ・クライアント通信は HTTP(S) を用いるというものである．この科目では，このアーキテクチャを適用した簡単なアプリケーションを構築する技術を学ぶ．

## 他科目との関係

### データベース演習I (2年後期)

受講者は，「データベース演習I」の内容を理解していると期待されてい
る．履修を必須とするわけではなく，自習等によってSQLの基礎知識 (範
囲は「データベース演習I」のシラバスを参照) を習得していれば問題な
い．この知識がなければ，本科目の単位取得は極めて困難であると考えら
れる．

### データベース各論II (水曜2限) 

(主として田辺ゼミでの) 卒業研究実施に必要なスキルを，プログラミン
グを中心として習得．
この講義との関連性はあまり高くない．

### データベース各論I (昨年度後期)

プログラミング言語Pythonの習得
Pythonがわかっていると，この講義の内容がより深く理解できる．

## 参考書

Python について

* 大澤 文孝 「いちばんやさしい Python入門教室」 (ソーテック社)

リレーショナルデータベースについて

* 中山清喬，飯田 理恵子「スッキリわかる SQL入門」(インプレス)

その他，必要に応じて紹介する．

## 予備知識

本科目を受講するためには，以下の予備知識・技能が必要である．

* テキストエディタを用いて簡単なHTML文書が作成できること．
  * 情報基礎演習Iの内容が理解されていれば良い．
* 簡単なSQL文が書けること．
  DDL/DCLは不要だが，SELECT/INSERT/UPDATE/DELETE 文のうち，
  基本的なものが書ける必要がある．
  特に，JOIN句の理解が必要である．
  データベース演習Iの内容を習得していれば良い．
* プログラミング言語が使えること．
  たとえば，以下のいずれかの講義の内容を習得していれば良い
  * データベース各論I
  * プログラミング演習I または II
  * ネットワーク演習I または II．
* 実際には，プログラミング言語としては Python を用いる．
  Python 以外の言語しか使えない場合には，第3回授業頃を目安に，
  Python を自習しておくこと．
  たとえば，[Paizaラーニング Python3入門編](https://paiza.jp/works/python3/primer) の，1～5 と 7を学習すれば良い (ユーザ登録が必要)．
    

## 授業形態

* 原則としては，対面授業を行う．
* 一部の回の授業を遠隔 (同時双方向型またはオンデマンド型) で
  実施する可能性がある．その場合の受講方法は，前回の対面授業で指示する．

## 出席管理

* 授業で出席を取る．
* 課題の提出があれば，出席とみなす．
* 出席回数は，原則として，成績に影響しない．ただし:
  * 出席回数が授業回数の2/3未満の場合，成績がE判定となることがある．
  * 欠席回数が多いと，奨学金の受給などに影響する場合がある．

## 成績評価

* 期末試験または期末レポート，課題，小テストを総合的に判定する．
* 出席点はない．
* 試験・レポートの別は，学期末の状況をみて判断する．
* 課題については，期限までに提出することが重要．
  * ___期限後には提出できない___．
* S, A などの良い成績をとるためには，試験・レポートで良い点をとることが重要で，課題提出の影響度は小さい．
* 試験・レポートの得点が良くない場合，合格するためには，___課題を提出していることが重要___

成績評価の詳細は以下の通り

* 最終成績は，試験点 $a$ (1点満点) と，
  平常点 $b$ (1点満点) から，次の式で算出する．(小数点以下切捨)
  $$ 100\times (a + 0.6\times b(1 - a))$$
* 試験点 $a$ は，最終試験または最終レポートの得点 $c$ (1点満点) と，
  小テスト(1点満点)の平均点 $d$ から，次のように算出する．ただし，小
  テスト実施回数を $k$ として，$w = \frac{k}{k+5}$．
  ($k=0$ の可能性もある．)
  $$ a = \max(c,  (1-w)c + wd) $$
* 平常点は，各課題の評点 (1点満点) の平均である．
  通例では，期限までに提出すれば 0.7 点以上の評点が与えられる．
  期限までに提出しないと0点である．

## 質問対応

moodle の「授業に関する質問」フォーラムを利用する．

## moodle からのメール

* moodle からのメールが届く設定になっているか?
  * `*.is-trm.net` からのメールを拒否しないように注意．
* 設定のテストの仕方
  * テスト用フォーラムに入る．
  * 「新しいディスカッショントピックを追加する」ボタンを押す．
  * 適当に件名とメッセージを入力する．
    (他の人にも見えるので，個人情報などを書かないように．)
  * 「高度」ボタンを押す．
  * 「ディスカッション購読」のチェックをOnにする．
     (On になっているはず)
  * 「編集遅延時間無しにフォーラム投稿通知を送信する」のチェックをOnにする．
  * 「フォーラムに投稿する」ボタンを押す．
  * 入力したメッセージが自分宛にメールで届けばOK (数分かかる)




