<template>
  <link href="https://fonts.googleapis.com/css?family=Comfortaa" rel="stylesheet">
  <div class="neon-background absolute top-0 bg-black left-0 w-full h-full flex flex-col items-center transition-all duration-300">
    <img src="../../pages/yuru-d/lt_01.jpg" class="w-[850px] rounded-2xl absolute top-10 right-10 grayscale-70 opacity-15" alt="LT Announcement" />
    <img src="../../pages/yuru-d/lt_02.jpg" class="w-[700px] rounded-2xl absolute bottom-10 left-10 grayscale-70 opacity-10" alt="LT Announcement" />
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
          <img :src="speaker.url" class="w-[200px] opacity-80" alt="Speaker Image" />
        </div>
      </template>
    </div>
  </div>
</template>

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

.box-blue-neon {
  animation: box-shadow-blink 2s infinite alternate;
  -webkit-animation: box-shadow-blink 2s infinite alternate;
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

@keyframes box-shadow-blink {
  0% {
    box-shadow: 0 0 3px #fff, 0 0 10px #fff, 0 0 20px #fff, 0 0 40px #0ba9ca,
                0 0 70px #0ba9ca, 0 0 80px #0ba9ca;
  }
  50% {
    box-shadow: 0 0 10px #fff, 0 0 20px #fff, 0 0 30px #fff, 0 0 60px #0ba9ca,
                0 0 100px #0ba9ca, 0 0 120px #0ba9ca;
  }
  100% {
    box-shadow: 0 0 3px #fff, 0 0 10px #fff, 0 0 20px #fff, 0 0 40px #0ba9ca,
                0 0 70px #0ba9ca, 0 0 80px #0ba9ca;
  }
}

.text-yellow-neon {
  transition: color 0.5s ease, text-shadow 0.5s ease;
}

/* カーソルをポインターに変更 */
.cursor-pointer {
  cursor: pointer;
}
</style>

