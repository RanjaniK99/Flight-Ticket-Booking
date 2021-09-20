<template>
  <div>
    <h3>Top Flight Routes</h3>
  <div class="container">
  <div class="row mb-5 mt-3">
    <div class="col-lg-6 mb-3">
      <span class="route"> Chennai to Delhi (CHE-DEL)
        <button class="search ms-5">Search Flight</button>
      </span>
    </div>
    <div class="col-lg-6 mb-3">
      <span class="route">Delhi to Chennai (DEL-CHE)
       <a href="#"><button class="search ms-5">Search Flight</button></a>
      </span>
    </div>
    <div class="col-lg-6 mb-3">
       <span>Mumbai to Delhi (BOM-DEL)
        <button class="ms-5">Search Flight</button>
      </span>
    </div>
    <div class="col-lg-6 mb-3">
       <span>Delhi to Mumbai (DEL-BOM)
        <button class="ms-5">Search Flight</button>
      </span>
    </div>
      
    <div class="col-lg-6 mb-3">
       <span>Goa to Bangalore(GOI-BLR)
        <button class="ms-5">Search Flight</button>
      </span>
    </div>
    <div class="col-lg-6 mb-3">
       <span>Chennai to Pune(CHE-PNQ)
        <button class="ms-5">Search Flight</button>
      </span>
    </div>
      
    <div class="col-lg-6 mb-3">
       <span>Kolkata to Patna(CCU-PAT)
        <button class="ms-5">Search Flight</button>
      </span>
    </div>
    <div class="col-lg-6 mb-3">
       <span>Delhi to Chennai (DEL-CHE )
        <button class="ms-5">Search Flight</button>
      </span>
    </div>
      </div>

   </div>
  </div>
</template>

<script>
export default {
name:'Routes',
}
</script>

<style >
span button{
  padding:5px;
  background: none;
  border:2px solid orange;
  color:orange;
  border-radius:5px !important;
}
span button:hover{
  background: orange;
  color:white;
}

</style>