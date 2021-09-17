<template>
  <div id="app">
    <VueScrollFixedNavbar>
      <header>
        <Navbar />
      </header>
    </VueScrollFixedNavbar>
     <router-view />
     <footer>
       <Ftr />
     </footer>
        </div>
</template>
<script>
import Navbar from "./components/Navbar.vue";
import Ftr from "./components/Ftr.vue";
export default {
  name: "app",
  components: {
    Navbar,
    Ftr,
  },
};
</script>

<style>
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
body {
  font-family: Verdana, Geneva, Tahoma, sans-serif;
}
header {
  width: 100%;
  height: 70px;
  background-color: black;
}
VueScrollFixedNavbar{
   width: 100%;
  height: 70px;
  background-color: black;
}
</style>
