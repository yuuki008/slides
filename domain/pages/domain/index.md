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
transition: slide-up
---

## ドメインの歴史

<!-- ここでは、初期のIPアドレスでの通信から、名前と住所の一元管理、DNS誕生までの流れを説明します。 -->

---
transition: slide-up
---

### インターネットの仕組み

- コンピューター同士は「IP アドレス」と呼ばれる数字で通信している

---
transition: slide-up
---

### インターネット初期

- 通信相手のIPアドレスを直接宛先に指定してやり取りしていた
- 相手のIPアドレスを全て覚えなければならなかった

---
transition: slide-up
---

<img
  className="w-[1000px] h-auto"
  src="./01.png"
/>
<div v-click className="absolute backdrop-blur-xl top-0 left-0 w-full h-full flex items-center justify-center transition-all duration-300">
    <h2>
      相手の住所を覚えてられない
    </h2>
</div>

<!-- ※ 画像 "./01.png" は、数字だけのIPアドレスが羅列されたリストや、混乱する様子を表す図が効果的です。 -->

---
transition: slide-up
---

### 名前と住所を一括管理

<div>
    <table className="max-w-[500px] max-auto">
      <thead>
        <tr>
          <th>名前</th>
          <th>住所</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>androots.co.jp</td>
          <td>157.7.107.156</td>
        </tr>
        <tr>
          <td>youtube.com</td>
          <td>172.217.161.46</td>
        </tr>
        <tr>
          <td>google.com</td>
          <td>142.250.207.14</td>
        </tr>
      </tbody>
    </table>
</div>

<!-- ※ 表は、ドメイン（名前）とIPアドレス（住所）の対応表を示し、名前で管理するメリットを直感的に伝えるのに役立ちます。 -->

---
transition: slide-left
---

<img src="./02.jpg" className="w-[1200px] h-auto"/>
<div v-click className="absolute backdrop-blur-xl top-0 left-0 w-full h-full flex items-center justify-center transition-all duration-300">
    <h2>
      住所を知らなくても通信できる
    </h2>
</div>

<!-- ※ 画像 "./02.jpg" は、DNSの仕組みにより、ユーザーがドメイン名を入力するだけで目的のウェブサイトに接続できる様子を表現した図やイラストを使用すると良いでしょう。 -->

