<template>
<div class=" pt-12">
 <div class="  text-center text-[#25292e] font-[800] text-[2.125em] md:text-[3.125em] ">
  <p>Explore the new world</p>
  <div>
  <p>of Ethereum </p>
  <p class="animate-bounce">🪐 🖼 ✨</p>
  </div>
 </div>

 <div class="text-center mt-[20px]">
  <div class="  ">

   

  </div>
     <div class="md:flex md:justify-between md:w-[629px] md:mx-auto">

     
    <div class=" mx-auto md:w-[229px]  w-[329px] relative btn3 mt-12 border rounded-lg uppercase font-semibold tracking-wider leading-none" type="button">
      <span class="absolute inset-0 "></span>
      <div class="relative px-10 py-5 bg-black text-white rounded-lg    cursor-pointer">
           <p>Download the betta on</p>
           <p>App Store</p>     
      </div>
    </div>
     
    <div class=" mx-auto md:w-[209px] w-[329px] relative btn3 mt-12 border rounded-lg uppercase font-semibold tracking-wider leading-none" type="button">
      <span class="absolute inset-0 "></span>
      <div class="relative px-10 py-5 bg-black text-white rounded-lg    cursor-pointer">
            <p>Download the betta on</p>
           <p>App Store</p>      
      </div>
    </div>
  </div>
<Phone />
 </div>
</div> 
</template>




<script>
import Phone from './Phone.vue';
export default {
    components: { Phone }
    
}
</script>

<style>
.btn3{
  transform: scale(1);
  transition: transform .2s ease-in
}

.btn3:hover{
  transform: scale(1.2);
}

.btn3 span{
  transform: scale(1);
  transition: transform .3s ease-in
}

.btn3:hover span{
  transform: scale(1.1, 1.2);
}
:root {
  --white: whitesmoke;
  --yellow: #ffd60a;
  --darkblue: #001d3d;
}

::selection {
  background: var(--yellow);
  color: var(--darkblue);
}

body {
  margin: 10vh 0;
  font: 20px / 28px "Nunito", sans-serif;
  color: var(--yellow);
  background: var(--darkblue);
}

h1 {
  margin-bottom: 30px;
}

section + section {
  margin-top: 10vh;
}

.copyright .col-auto:not(:last-child) {
  position: relative;
}

.copyright .col-auto:not(:last-child)::before {
  content: "•";
  position: absolute;
  top: 50%;
  right: -7.5px;
  transform: translateY(-50%);
}

.line-animation,
.line-animation:hover {
  color: var(--white);
}

.cursor {
  position: fixed;
  pointer-events: none;
  opacity: 0;
}

.cursor-bee {
  top: -15px;
  left: -13px;
  z-index: -1;
}

.cursor-eye {
  top: -50px;
  left: -50px;
  padding: 20px;
  z-index: 1;
  border-radius: 50%;
  background-color: var(--darkblue);
}


/* FOOTER STYLES
–––––––––––––––––––––––––––––––––––––––––––––––––– */
.page-footer {
  position: fixed;
  right: 0;
  bottom: 60px;
  display: flex;
  align-items: center;
  font-size: 1rem;
  padding: 5px;
  color: black;
  background: rgba(255, 255, 255, 0.65);
}

.page-footer a {
  display: flex;
  margin-left: 9px;
}

</style>