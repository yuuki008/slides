
<template>
<link href="https://fonts.googleapis.com/css?family=Comfortaa" rel="stylesheet">
  <div className="absolute top-0 bg-black text-white left-0 w-full h-full flex items-center justify-center transition-all duration-300">
      <div className="yellow-neon text-[5rem] text-yellow-300 font-bold italic">
        LIGHTNING TALKS
      </div>
  </div>

</template>

<script>
export default {
  name: "LTAnnouncement",
};
</script>

<style>
.yellow-neon {
  font-size: 5rem;
  font-family: "BPneon", "Comfortaa", cursive;
  text-shadow: 0 0 5px #ffa500, 0 0 15px #ffa500, 0 0 20px #ffa500, 0 0 40px #ffa500, 0 0 60px #ff0000, 0 0 10px #ff8d00, 0 0 98px #ff0000;
    color: #fff6a9;
  text-align: center;
  animation: blink 12s infinite;
  -webkit-animation: blink 12s infinite;
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
