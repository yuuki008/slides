---
transition: slide-up
---

## ドメインとは

---
transition: slide-up
---

### インターネット上の住所

---
transition: slide-up
---

<div className="font-semibold text-[45px] italic">
https://<span v-mark.underline.red=1>androots.co.jp</span>
<br/>
https://<span v-mark.underline.red=1>google.com</span>/search?q=androots
<br/>
https://<span v-mark.underline.red=1>youtube.com</span>/watch?v=androots
</div>

---
transition: slide-left
---

## ドメインの歴史

<!-- スライド「ドメインの歴史」では、初期の一元管理からDNS誕生までの流れを簡潔に説明します。 -->

---
transition: slide-left
---

### 初期のインターネットと一元管理

- ARPANET時代は全ホスト情報を「HOSTS.TXT」で一括管理
- IPアドレスという数字の羅列で管理され、覚えづらかった

<!-- 画像例: 昔のコンピュータやHOSTS.TXTのイメージ図。古い文書や一覧表のスクリーンショットなど -->

---
transition: slide-left
---

### 管理の限界とDNSの誕生

- インターネットの急速な拡大で一元管理が限界に
- 1980年代にDNS（ドメインネームシステム）が開発され、名前とIPアドレスを分散管理へ
- 各組織にドメイン管理を委譲できる仕組みに変革

<!-- 画像例: DNSの階層構造（ルート、TLD、セカンドレベル）の図。ツリー形式の図解が分かりやすい -->

---
transition: slide-left
---

## ドメインの仕組み

<!-- このセクションでは、ドメインの階層構造と委譲関係、名前解決の流れを説明します。 -->

---
transition: slide-left
---

### 階層構造の基本

- **ルート**
  インターネット全体の基盤
- **トップレベルドメイン（TLD）**
  例: .com, .jp など
- **セカンドレベルドメイン**
  例: example.com
- **サブドメイン**
  例: www.example.com

<!-- 画像例: 階層構造を示すツリー状の図。各階層（ルート → TLD → セカンドレベル → サブドメイン）が明示されている図 -->

---
transition: slide-left
---

### 委譲関係と分散管理

- 上位ドメインが下位ドメインの管理権限を委譲
  - 例: 「.com」が企業に example.com の管理権を委ねる
- 分散管理により、全世界の膨大なホストを効率的に管理

<!-- 画像例: 郵便局の仕組み（中央局から各支店へ委譲するイメージ）や、家系図のようなイラストで委譲関係を視覚化 -->

---
transition: slide-left
---

### DNSによる名前解決の流れ

1. ユーザーがドメイン名を入力
2. DNSサーバーがドメイン名を探し、対応するIPアドレスに変換
3. 変換されたIPアドレスで目的のウェブサイトに接続

<!-- 画像例: ユーザーのブラウザからDNSサーバー、そしてウェブサーバーへとアクセスが行われる流れを示すフローチャート -->


