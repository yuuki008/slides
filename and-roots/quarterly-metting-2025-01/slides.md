---
theme: ./theme
title: グロースハック | 総会資料
favicon: /ando_icon.webp
mdc: true
transition: slide-left
colorSchema: light
fonts:
  # basically the text
  sans: Robot
  serif: Robot Slab
  mono: Fira Code
---

<img src="/ando_icon.webp" alt="and roots" class="w-[200px] h-auto mx-auto mb-5 rounded-xl" />

## グロースハック総会資料

---
transition: slide-left
---

## 目次

1. ビジョン
2. 業務内容
3. これから
4. 宣伝

---
transition: slide-left
---

## ビジョン

```
デジタル技術の専門家として、and roots の 1 人ひとりが事業の本質と向き合える時間を創る
```

---
transition: slide-up
---

### 業務内容

- データの基盤を作る
- データを活用する

---
src: ./pages/datawarehouse/index.md
hide: false
---

---
transition: slide-up
---

# これから

---
transition: slide-up
---

<div className="font-bold text-[4.5rem]">
  来期から<span v-mark.yellow="1">基盤</span>と<span v-mark.purple="1">活用</span>にグループが分かれる
</div>

---
transition: slide-left
---

<div className="relative flex items-center w-[1400px] space-x-8 mx-auto h-full">
    <div className="border rounded-xl shadow-xl p-8 flex-1">
        <div className="text-[45px] font-semibold text-center mb-6">
            基盤グループ
            <div className="text-gray-500 text-[28px]">
            3 members+
            </div>
        </div>
        <div className="space-y-8">
            <MemberCard
              name="谷口 健太"
              nickname="たぬー"
              imageSrc="https://ca.slack-edge.com/TL86R5GH1-UL86R5GV9-42d14dbc2420-512"
            />
            <MemberCard
              name="國分 拓也"
              nickname="くぶたく"
              imageSrc="https://ca.slack-edge.com/TL86R5GH1-U04DD6NLZQ9-8fe529d0275b-72"
            />
            <MemberCard
              name="笹本 卓臣"
              nickname="もてぃ"
              imageSrc="https://ca.slack-edge.com/TL86R5GH1-UMFSB9SNQ-69f53e3cc465-72"
            />
        </div>
    </div>
    <div className="border rounded-xl shadow-xl p-8 flex-1">
        <div className="text-[45px] font-semibold text-center mb-6">
            活用グループ
            <div className="text-gray-500 text-[28px]">
            3 members+
            </div>
        </div>
        <div className="space-y-8">
            <MemberCard
              name="堀 順郎"
              nickname="のぶろー"
              imageSrc="https://ca.slack-edge.com/TL86R5GH1-U04QAP3048N-8b3f5f4127ed-512"
            />
            <MemberCard
              name="崎本 育直"
              nickname="いっくん"
              imageSrc="https://ca.slack-edge.com/TL86R5GH1-U039MJ5HN91-d2db0181d802-512"
            />
            <MemberCard
              name="能村 優希"
              nickname="のむ"
              imageSrc="https://ca.slack-edge.com/TL86R5GH1-U0281NV010D-b0903e6ed514-512"
            />
        </div>
    </div>
</div>

---
transition: slide-up
---

# 宣伝

---
src: ./pages/yuru-d/index.md
hide: false
---

---
src: ./pages/data-office-hours/index.md
hide: false
---

---

### thank you for listening...
