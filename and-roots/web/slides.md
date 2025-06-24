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

### インターネットの誕生

---

<img src="./before-internet.png" className="w-[1000px] h-auto rounded-lg border-4 border-black"/>
<div v-click className="absolute backdrop-blur-xl top-0 left-0 w-full h-full flex items-center justify-center transition-all duration-300">
    <h2>
      元々、コンピューターは孤立していた
    </h2>
</div>

---

<div class="text-right">
<b>インターネットの原型となる ARPANET が誕生</b>
<br/>
(1969年)
</div>

---

<img src="./after-internet.png" className="w-[1000px] h-auto rounded-lg border-4 border-black"/>
<div v-click className="absolute backdrop-blur-xl top-0 left-0 w-full h-full flex items-center justify-center transition-all duration-300">
    <h2>
      コンピューター同士がつながった
    </h2>
</div>

---

**どんどんコンピューターが増えて、インターネットが大きくなった**

---

<img src="./submarine-cable.jpg" className="w-[1200px] h-auto rounded-lg "/>
<div v-click className="absolute backdrop-blur-xl top-0 left-0 w-full h-full flex items-center justify-center transition-all duration-300">
  <h3>
    海底ケーブルで大陸を繋ぐ
  </h3>
</div>

---

<img src="./world-internet.png" className="w-[1000px] h-auto rounded-lg border-4 border-black"/>
<div v-click className="absolute backdrop-blur-xl top-0 left-0 w-full h-full flex items-center justify-center transition-all duration-300">
  <h3>
    世界中の人と繋がれるようになった
  </h3>
</div>

---

### Web の誕生

---

#### 🚨 Web以前の問題点

---

**情報はあるが、見つからない**

---

#### 利用可能なサービス

📧 E-mail: メッセージ交換
<br/>
📁 FTP: ファイル転送
<br/>
💻 Telnet: 遠隔ログイン
<br/>
📰 Usenet: 電子掲示板

---

#### 深刻な課題

🔍 どこに何があるか分からない
<br/>
🔧 サービスごとに異なるコマンド
<br/>
⏰ 情報収集に数週間
<br/>
🤝 口コミと紹介が中心

---

🎯 例: 「人工知能の最新研究について調べたい」

---

1. 📚 大学図書館でコンピューター雑誌を調べる
   <br/>
   → 「○○大学の△△教授が有名」という情報発見

---

2. ☎️ ○○大学に電話
   <br/>
   → 「学会出張中です、来週お戻りです」

---

3. ☎️ △△教授と連絡成功
   <br/>
   → 「××研究所の◇◇さんに聞いてください」

---

4. ☎️ ××研究所に電話
   <br/>
   → 「論文リストを郵送します」

---

5. 📮 資料到着・確認
   <br/>
   → さらに詳しい情報が必要なら、また人探し...

---

<div class="text-center mt-4 p-3 bg-yellow-100 rounded">
<strong>結果: 一つの情報を得るのに1-2ヶ月</strong>
</div>

---

### 🌐 World Wide Web の誕生

---

<div class="mb-10">
<img
  src="https://cdn.britannica.com/22/221822-050-3B0A657F/British-scientist-Tim-Berners-Lee.jpg"
  className="w-[320px] h-[320px] mx-auto object-cover mb-4 rounded-full"
/>
<div class="italic text-center text-xl">— Tim Berners-Lee</div>
</div>

> **クリック一つで関連情報に飛べるシステムを作ろう！**

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
