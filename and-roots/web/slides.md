---
theme: ./theme
title: あなたの知らない Web の世界
favicon: /ando_icon.webp
mdc: true
transition: slide-left
colorSchema: light
fonts:
  # basically the text
  sans: Robot
  serif: Robot Slab
  mono: Fira Code
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides (markdown enabled)
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)

# open graph
# seoMeta:
#  ogImage: https://cover.sli.dev
---

## あなたの知らない Web の世界

---

## 今日のアジェンダ

1. **Webって何？**
2. **Web の歴史**
3. **Webを支える技術**
4. **Webの構成要素**

---

## 1. Webって何？

---

### ブラウザで見ているもの全て

---

- ニュースサイト
- ショッピングサイト
- SNS
- 動画サイト
- 検索エンジン

---

Web は
<br/>
**世界中の情報をつなぐ仕組み**

---

正式名称は
<br/>
**World Wide Web**

---

直訳すると
<br/>
**世界中に張り巡らされた蜘蛛の巣**

---

### インターネットとは

---

**コンピューター同士をつなぐ巨大なネットワーク**

---

**情報が行き交うための道路や線路のようなもの**

---

**Web は、インターネットの上で動く一つのサービス**

---

**インターネット上には他にも：**
メール、チャット、ファイル共有、オンラインゲームなど

---

## 道路と車の関係

**道路** = インターネット
<br/>
**車** = Web、メール、ゲームなど

---

**つまり：**
Web はインターネットの上で動く一つのサービス

---

## 3. Web の歴史

---

### 1960年代〜

- インターネットの原型「ARPANET」誕生
- 軍事目的で開発、最初のメッセージは「LO」だけ送信されてクラッシュ

---

### 1980年代〜

- インターネットの基礎技術「TCP/IP」標準化（1983年）
- 世界中の大学や研究機関がつながり始める
- 日本では「JUNET」誕生（1984年）

---

### 1990年代〜

- ティム・バーナーズ＝リーが「World Wide Web」発明（1991年）
- 世界初のWebサイトは「情報のための情報」
- 「Yahoo!」「Google」など検索エンジン登場

---

### 2000年代〜

- SNSの登場（mixi, Facebook, Twitter）で人と人がつながる
- YouTubeで動画共有が一般化
- 「Web 2.0」＝みんなが参加するWebへ

---

### 2010年代〜

- スマートフォン普及で「いつでもどこでもWeb」
- InstagramやTikTokなど新しいSNSが流行
- クラウドサービスが生活の一部に

---

### 2020年代〜

- AIやIoTでWebがさらに進化
- メタバースやWeb3など新しいWebの形が登場
- インターネット利用者は世界人口の約65%に！

---

## 4. Webを支える技術

---

- URL
- HTML
- HTTP

---

### URL

---

**Web 上の住所のようなもの**
<br/>

**例：https://www.google.com**

---

### HTML

---

**Web ページを作成するためのマークアップ言語**

---

### HTTP

---

**Web 上の情報をやり取りするためのルール**

---

### 3つの技術の連携

---

1. **URL**で「どこの情報が欲しいか」を指定

   - 例：`https://news.example.com`

2. **HTTP**で「その情報をください」とお願い

   - ブラウザがサーバーにリクエスト

3. **HTML**で情報が返ってくる

   - サーバーがページの内容を送信

4. **ブラウザ**がHTMLを読んで画面に表示
   - 私たちが見慣れたWebページに

---

## 5. Webの構成要素

---

### Webサーバー

- 情報を保管・提供する場所
- 24時間365日動き続ける

---

### ブラウザ

- 情報を見るためのソフト
- Chrome、Safari、Edgeなど
- HTMLを読んで画面に表示

---

### Webページ

- 実際に見ている画面
- 文字、画像、動画、リンク
- サーバーからブラウザに送られる

---

**この 3 つが連携して、Web ページを表示している**

---

### 流れ

1. **ブラウザ**がURLにアクセス
2. **Webサーバー**にページを要求
3. **サーバー**がHTMLファイルを送信
4. **ブラウザ**がページを表示

---

# 私たちの生活への影響

<div class="grid grid-cols-2 gap-8">

<div v-click="1">

## 変わったこと

- **情報収集**：図書館→検索エンジン
- **買い物**：店舗→オンラインショッピング
- **コミュニケーション**：電話→SNS・メッセージ
- **エンターテイメント**：テレビ→動画配信
- **学習**：教室→オンライン授業

</div>

<div v-click="2">

## 未来の可能性

- **AI**との自然な対話
- **VR/AR**での没入体験
- **IoT**との連携
- **リアルタイム**翻訳・通訳
- **パーソナライズ**された情報

</div>

</div>

<div v-click="3" class="mt-8 text-center">

**Webは私たちの生活を根本から変え、これからも進化し続けます**

</div>

---

layout: center
class: text-center

---

### まとめ

- **Web**はインターネット上で世界中の情報を繋ぐ仕組みの
- **URL, HTML, HTTP** の 3 つの技術で動いている
- **ブラウザが Web サーバーが連携して、Web ページを表示している**

---

## 次回

---

**あなたの知らないダークウェブの世界**

---

# ご清聴ありがとうございました

質問はありますか？
