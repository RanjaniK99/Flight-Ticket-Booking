<template>
  <section>
        <div class="bg1">
          <div class="road"></div>
          <img src="../assets/airplane.png" alt="" class="flight">
          </div>
      </section>
</template>

<script>
export default {
       name:'Flight', 
    }

</script>

<style>
.bg1 {
  background-image: url("../assets/bg1.jpg");
  background-size: cover;
  width: 100%;
  height: 100vh;
  position: relative;
  margin-top: -7%;
  overflow: hidden;
}
.road {
  height: 200px;
  width: 100%;
  background-image: url("../assets/road.jpg");
  position: absolute;
  left: 0;
  bottom: 0;
}
.flight {
  width: 500px;
  position: absolute;
  bottom: 100px;
  right: -200px;
  animation: flight 4s linear infinite;
  transform-origin: 100% 50%;
}
@keyframes flight {
  0% {
    transform: translateX(0px) translateY(0px) rotate(0deg);
  }
  30% {
    transform: translateX(-500px) translateY(0px) rotate(0deg);
  }
  100% {
    transform: translateX(-1500px) translateY(-200px) rotate(20deg);
  }
}
/* media query */
@media screen and (max-width: 339px) {
  .navbar-brand {
    font-size: 15px;
  }
  .bg1 {
    height: 300px;
  }
  .road {
    height: 150px;
  }
  .flight {
    width: 250px;
    position: absolute;
    bottom: 90px;
    right: -200px;
    animation: flight 4s linear infinite;
    transform-origin: 100% 50%;
  }
  @keyframes flight {
    0% {
      transform: translateX(0px) translateY(0px) rotate(0deg);
    }
    30% {
      transform: translateX(-200px) translateY(0px) rotate(0deg);
    }
    100% {
      transform: translateX(-900px) translateY(-200px) rotate(20deg);
    }
  }
}
@media (min-width: 340px) and (max-width: 460px) {
  .navbar-brand {
    font-size: 25px;
  }
  .bg1 {
    height: 400px;
  }
  .road {
    height: 160px;
  }
  .flight {
    width: 300px;
    position: absolute;
    bottom: 90px;
    right: -200px;
    animation: flight 4s linear infinite;
    transform-origin: 100% 50%;
  }
  @keyframes flight {
    0% {
      transform: translateX(0px) translateY(0px) rotate(0deg);
    }
    30% {
      transform: translateX(-200px) translateY(0px) rotate(0deg);
    }
    100% {
      transform: translateX(-900px) translateY(-200px) rotate(20deg);
    }
  }
}
@media (min-width: 461px) and (max-width: 1000px) {
  .navbar-brand {
    font-size: 25px;
  }
  .bg1 {
    height: 500px;
  }
  .road {
    height: 180px;
  }
  .flight {
    width: 300px;
    position: absolute;
    bottom: 90px;
    right: -200px;
    animation: flight 4s linear infinite;
    transform-origin: 100% 50%;
  }
  @keyframes flight {
    0% {
      transform: translateX(0px) translateY(0px) rotate(0deg);
    }
    30% {
      transform: translateX(-350px) translateY(0px) rotate(0deg);
    }
    100% {
      transform: translateX(-900px) translateY(-200px) rotate(20deg);
    }
  }
}

</style>