---
title: INFINITAS 楽曲一覧ページの作成作業中4
#tag: 
tags: INFINTIAS
#category:
categories: INFINTIAS Update
comments: true
---
結局Google APIは無効化している！！  
というわけで、今回の更新内容。  
というか前回の記事から変わりすぎなので箇条書きっぽいです。  

## [できること / 検索条件]
- 譜面Lv・ノート数・特殊ノート
- バージョン
- 配信条件
- 配信開始月
- BIT配信開始月
- 入手可否
- 曲名・ジャンル・アーティスト名の部分一致
- 楽曲BPM
  
## [できること / データ保存機能を使用した場合の検索条件]
- 譜面の解禁状況
- 譜面毎のDJレベル
- 譜面毎のEXスコア
- 譜面毎のミスカウント
- 譜面毎のクリアランプ
  
## [できること / その他]
- 検索結果のBIT解禁状況(BIT解禁対象・残り・解禁済の譜面数およびBIT)の表示
- 検索結果のソート指定
- DJレベルの表示方法指定
  
できることはこんな感じでしょうか？  
それぞれの使い方とかを個別記事にしないとよくわからないですね。  
そのうち気が向いたら記事にしていきたいです。  

あとは、今後やっていきたいこと。  
いっぱいある気がするけど、いつになったら作るんですかね？  
  
## [やりたいこと / 検索条件]
- 検索条件をORで指定
- 配信条件に「購入済みパックのみ選択 / 解除」のリンク追加
- アーティスト名検索で別名義でも検索可能にしたい
- 段位認定曲かどうかの検索条件追加

## [やりたいこと / 楽曲データ]
- アーティスト名の別名義をメモするプロパティの作成とデータ登録
- BPM可変曲のメインBPMプロパティの作成とデータ登録
- 段位認定譜面のプロパティの作成

## [やりたいこと / その他]
- jQuery依存の実装を脱する(★ 今やってる)
- JavaScriptのリファクタリング(★ 今やってる)
- 使い方を説明したページの作成
- 楽曲の追加・訂正情報を投稿できるページの追加
- 特殊ノートの数を表示
- 楽曲の解禁状況を一括チェックできるボタンを追加