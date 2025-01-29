
<template>
  <link href="https://fonts.googleapis.com/css?family=Comfortaa" rel="stylesheet">
  <div className="neon-background absolute top-0 bg-black left-0 w-full h-full flex flex-col items-center transition-all duration-300">
    <div className="mt-30">
      <div className="yellow-neon text-center text-[5rem] text-yellow-300 font-bold italic">
        Lightning Talks
      </div>
      <div className="yellow-neon mt-4 text-[2rem] text-right">
        2025-02-25 18:30
      </div>
    </div>

    <div className="flex space-x-20 mt-20">
    <img
      src="../pages/yuru-d/lt_01.jpg"
      alt="LT"
      className="w-[440px] h-auto grayscale-80 rounded-lg"
    />
    <img
      src="../pages/yuru-d/lt_02.jpg"
      alt="LT"
      className="w-[440px] h-auto grayscale-80 rounded-lg"
      />
    </div>
  </div>
</template>

<script>
export default {
  name: "LTAnnouncement",
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

.yellow-neon {
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
