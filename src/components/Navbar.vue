<template>
 <div>
			 <div class="max-w-auto mx-auto ">
				<div class="flex justify-between pt-6 px-12">
					<div class="flex ">
						<div>
       
							<!-- Website Logo -->
							<a href="#" class="flex items-center  hover:skew-y-12  ">
								<img src="../assets/images.jpg" alt="Logo" class="h-12  rounded-xl ">
								<span class="font-semibold  text-[26px] font-[800] text-black pl-4">rainbow</span>
							</a>
						</div>

						<!-- Primary Navbar items -->
						
					</div>
     <div class="hidden md:flex  justify-center items-center pl-32 md:pl-14  ">
      
														<label class="relative block">
																		<span class="sr-only">Search</span>
																		<span class="absolute inset-y-0 left-0 flex items-center pl-2">
																				<svg class="h-5 w-5 fill-slate-300" viewBox="0 0 20 20"><!-- ... --></svg>
																		</span>
																		<input class=" flex text-center placeholder:italic placeholder:text-slate-400 block bg-white  border border-slate-300 rounded-md w-[429px] h-[40px] pr-3 shadow-sm focus:outline-none focus:border-sky-500 focus:ring-sky-500 focus:ring-1 sm:text-sm" placeholder="Search for any ENS or Ethereum address" type="text" name="search"/>
														</label>
						</div>
					<!-- Secondary Navbar items -->
					<div class="hidden md:flex items-center space-x-3 text-[#8a8e97] text-[20px] font-[700] px-8 md:space-x-6 ">
						<a href="" class="flex justify-center items-center"> <img src="../assets/bird_1f426.png" alt="" class="w-[20px] ">
       twitter</a>
						<a href="" class="flex  justify-center items-center   "> <img src="../assets/12130-brain-icon.png" alt="" class="w-[20px]  ">
       learn</a>
					</div>
					<!-- Mobile menu button -->

     
					<div class="md:hidden flex items-center">
						<button class="outline-none mobile-menu-button" @click="toggle">
						<svg class=" w-6 h-6 text-gray-500 hover:text-green-500 "
							x-show="!showMenu"
							fill="none"
							stroke-linecap="round"
							stroke-linejoin="round"
							stroke-width="2"
							viewBox="0 0 24 24"
							stroke="currentColor"
						>
							<path d="M4 6h16M4 12h16M4 18h16"></path>
						</svg>
					</button>
					</div>
				</div>
			</div>
			<!-- mobile menu -->
			<div class="hidden mobile-menu">
				<ul class="">
					<li class="active"><a href="index.html" class="block text-sm px-2 py-4 text-white bg-green-500 font-semibold">Home</a></li>
					<li><a href="#services" class="block text-sm px-2 py-4 hover:bg-green-500 transition duration-300">Services</a></li>
					<li><a href="#about" class="block text-sm px-2 py-4 hover:bg-green-500 transition duration-300">About</a></li>
					<li><a href="#contact" class="block text-sm px-2 py-4 hover:bg-green-500 transition duration-300">Contact Us</a></li>
				</ul>
			</div>
 </div>
 	
</template>
<script>
export default {
 methods :{
  toggle(){
 
   // const btn = document.querySelector("button.mobile-menu-button");
    const menu = document.querySelector(".mobile-menu");

    
        menu.classList.toggle("hidden");
    
  },

 }
 
}
</script>
<style lang="css">
input{
  width:300px;
  -moz-transition-duration:1s;
  -webkit-transition-duration:1s;
  -o-transition-duration:1s;
  transitition-duration:1s;
}
input:hover{
  width:400px;
		height: 60px;
		position: relative;
		;
}
input:focus{
  width:500px;
}

</style>
