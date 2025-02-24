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
transition: slide-up
---

### インターネットの仕組み

IP アドレスと呼ばれる数字で通信している

---
transition: slide-up
---

### インターネット初期

通信相手 IP アドレスをの宛先に指定してやり取りしていた
<br/>
相手の IP アドレスを全て覚えなければならない

---
transition: slide-up
---

<img
  className="w-[1000px] h-auto"
  src="./01.png"
/>
<div v-click className="absolute backdrop-blur-md top-0 left-0 w-full h-full flex items-center justify-center transition-all duration-300">
    <h2>
      相手の住所を覚えられない
    </h2>
</div>

---
transition: slide-up
---

### 1 箇所で名前と住所を管理

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

---
transition: slide-up
---

<img src="./02.jpg" className="w-[1200px] h-auto"/>
<div v-click className="absolute backdrop-blur-md top-0 left-0 w-full h-full flex items-center justify-center transition-all duration-300">
    <h2>
      住所を知らなくても通信できる
    </h2>
</div>

