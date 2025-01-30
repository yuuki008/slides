<script>
export default {
  name: "LTAnnouncement",
  data() {
    return {
      speakers: [
        {
          url: "https://ca.slack-edge.com/TL86R5GH1-ULKK20S21-46b788d53672-512",
          name: "池田 匠汰",
        },
        {
          url: "https://ca.slack-edge.com/TL86R5GH1-UMDSHMQ0H-9b77af366853-512",
          name: "江口 修一",
        },
        {
          url: "https://ca.slack-edge.com/TL86R5GH1-U032QAXKZQW-601573cd4de9-512",
          name: "峰 暖乃",
        },
        {
          url: "https://ca.slack-edge.com/TL86R5GH1-UMJTKUJQY-c29194eb55b2-512",
          name: "松浦 理奈",
        }
      ]
    };
  }
};
</script>

<template>
  <link href="https://fonts.googleapis.com/css?family=Comfortaa" rel="stylesheet">
  <div class="neon-background absolute top-0 bg-black left-0 w-full h-full flex flex-col items-center transition-all duration-300">
    <div class="my-30 text-yellow-neon ">
      <div class="text-center text-[5rem] text-yellow-300 font-bold italic">
        Lightning Talks #3
      </div>
      <div class="mt-4 text-[2rem] text-right">
        2025-02-25 18:30
      </div>
    </div>

    <div class="flex justify-between w-[1000px]">
      <template v-for="speaker in speakers" :key="speaker.name">
        <div class="box-blue-neon rounded-3xl overflow-hidden">
          <img :src="speaker.url" class="w-[200px]" />
        </div>
      </template>
    </div>
  </div>
</template>

<style>

.neon-background {
  background: #222;
  background-image: repeating-linear-gradient(
    to bottom,
    transparent 7px,
    rgba(0, 0, 0, 0.8) 9px,
    rgba(0, 0, 0, 0.8) 13px,
    transparent 13px
  );
}

/* box-shadow: [水平オフセット] [垂直オフセット] [ぼかし半径] [広がり半径] [色]; */
.box-blue-neon {
  box-shadow: 10px 10px 150px #00f, -10px -10px 150px #00f;
}

.text-yellow-neon {
  font-family: "BPneon", "Comfortaa", cursive;
  text-shadow: 0 0 5px #ffa500, 0 0 15px #ffa500, 0 0 20px #ffa500, 0 0 40px #ffa500, 0 0 60px #ff0000, 0 0 10px #ff8d00, 0 0 98px #ff0000;
  color: #fff6a9;
  animation: blink 5s infinite;
  -webkit-animation: blink 5s infinite;
}

@keyframes blink {
  20%,
  24%,
  55% {
    color: #111;
    text-shadow: none;
  }

  0%,
  19%,
  21%,
  23%,
  25%,
  54%,
  56%,
  100% {
    text-shadow: 0 0 5px #ffa500, 0 0 15px #ffa500, 0 0 20px #ffa500, 0 0 40px #ffa500, 0 0 60px #ff0000, 0 0 10px #ff8d00, 0 0 98px #ff0000;
    color: #fff6a9;
  }
}

</style>
