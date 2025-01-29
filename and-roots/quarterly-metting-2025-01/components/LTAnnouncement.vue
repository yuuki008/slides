
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
  font-family: "BPneon", "Comfortaa", cursive;
  padding-top: 20px;
  text-align: center;
  color: rgba(255, 232, 50, 0.9);
  text-shadow: 0 0 5px rgba(255, 245, 0, 1), 0 0 28px rgba(255, 44, 0, 0.9),
    0 8px 38px black, 0 8px 10px black, 0 2px 12px black,
    0 0 50px rgba(255, 120, 0, 0.5), 0 0 24px rgba(255, 255, 255, 0.8);
  -webkit-text-stroke: 1px rgba(255, 160, 0, 0.45);
  -webkit-animation: flicker 1s 1s, glow 1.5s ease-in-out infinite 2s;
  -moz-animation: flicker 1s 1s, glow 1.5s ease-in-out infinite 2s;
  animation: flicker 1s 1s, glow 1.5s ease-in-out infinite 2s;
}

@-webkit-keyframes flicker {
    0% {
        color: #fff;
        text-shadow: 0 0 10px #fff, 0 0 20px #fff, 0 0 30px #fff, 0 0 40px rgba(255, 232, 50, 0.9), 0 0 70px rgba(255, 232, 50, 0.9), 0 0 80px rgba(255, 232, 50, 0.9), 0 0 100px rgba(255, 232, 50, 0.9), 0 0 150px rgba(255, 232, 50, 0.9);
    }
    15% {
        color: #222;
        text-shadow: none;
    }
    25% {
        color: #fff;
        text-shadow: 0 0 10px #fff, 0 0 20px #fff, 0 0 30px #fff, 0 0 40px rgba(255, 232, 50, 0.9), 0 0 70px rgba(255, 232, 50, 0.9), 0 0 80px rgba(255, 232, 50, 0.9), 0 0 100px rgba(255, 232, 50, 0.9), 0 0 150px rgba(255, 232, 50, 0.9);
    }
    50% {
        color: #222;
        text-shadow: none;
    }
    75% {
        color: #fff7cc;
        text-shadow: 0 0 10px #b39800, 0 0 20px #fff, 0 0 30px #fff, 0 0 40px rgba(255, 232, 50, 0.9), 0 0 70px rgba(255, 232, 50, 0.9), 0 0 80px rgba(255, 232, 50, 0.9), 0 0 75px rgba(255, 232, 50, 0.9), 0 0 100px rgba(255, 232, 50, 0.9);
    }
    100% {
        color: #fff7cc;
        text-shadow: 0 0 4px #b39800, 0 0 15px #fff099, 0 0 30px #fff099, 0 0 30px rgba(255, 232, 50, 0.9), 0 0 50px rgba(255, 232, 50, 0.9), 0 0 60px rgba(255, 232, 50, 0.9), 0 0 75px rgba(255, 232, 50, 0.9), 0 0 100px rgba(255, 232, 50, 0.9);
    }
}
</style>
