
<script>
	
	import Sidebar from './Sidebar.svelte';
</script>

<main class="">
	<div class="md:flex  pb-10">
		<Sidebar/>
		<div class="flex flex-col">
			<div class="bg-white shadow-lg rounded-xl w-[840px] h-[100px] hidden md:block mt-[200px] ml-10 border  ">
				<ul class="flex   justify-center gap-10 px-4 items-center py-3 ">
					<li
						class=" hover:font-bold w-[130px] h-20 flex justify-center items-center rounded-2xl text-base bg-[#2F4858] text-white cursor-pointer transition-all duration-300 ease-in-out"
					>
						About
					</li>
					<li
						class=" hover:font-bold w-[130px] h-20 flex justify-center items-center rounded-2xl text-base hover:bg-[#2F4858] hover:text-white cursor-pointer transition-all duration-300 ease-in-out"
					>
						Resume
					</li>
					<li
						class=" hover:font-bold w-[130px] h-20 flex justify-center items-center rounded-2xl text-base hover:bg-[#2F4858] hover:text-white cursor-pointer transition-all duration-300 ease-in-out"
					>
						Works
					</li>
					<li
						class=" hover:font-bold w-[130px] h-20 flex justify-center items-center rounded-2xl text-base hover:bg-[#2F4858] hover:text-white cursor-pointer transition-all duration-300 ease-in-out"
					>
						Blogs
					</li>
					<li
						class=" hover:font-bold w-[130px] h-20 flex justify-center items-center rounded-2xl text-base hover:bg-[#2F4858] hover:text-white cursor-pointer transition-all duration-300 ease-in-out"
					>
						Contact
					</li>
				</ul>
			</div>
			<div
				class="bg-white shadow-lg rounded-xl md:w-[840px]  mt-10 scroll-mt-12 lg:ml-10 border flex-wrap"
			>
				<h1 class="text-5xl text-black font-bold mt-10 ml-10">About Me</h1>
				<p class="text-gray-600 text-base px-10 mt-5">
					I'm Creative Director and UI/UX Designer from Sydney, Australia, working in web
					development and print media. I enjoy turning complex problems into simple, beautiful and
					intuitive designs. My aim is to bring across your message and identity in the most
					creative way. I created web design for many famous brand companies.
				</p>
				<h1 class="text-2xl text-black font-semibold mt-10 ml-10">What I do!</h1>
				<p class="text-gray-600 text-base px-10 mt-5">
					My aim is to bring across your message and identity in the most creative way. I created
					web design for many famous brand companies.
				</p>
				<div class="grid lg:grid-cols-2  px-4 md:pb-10 mt-5 place-items-center gap-5">
					<div class="md:w-[348px]  w-full h-[185px] border rounded-xl bg-yellow-100">Ui/Ux Design</div>
					<div class="md:w-[348px] w-full h-[185px] border rounded-xl bg-yellow-100">App Development</div>
					<div  class="md:w-[348px] w-full h-[185px] border rounded-xl bg-yellow-100">Photography</div>
					<div  class="md:w-[348px] w-full h-[185px] border rounded-xl bg-yellow-100">Photography</div>
					<div  class="md:w-[348px] w-full h-[185px] border rounded-xl bg-yellow-100">Managment</div>
					<div  class="md:w-[348px] w-full h-[185px] border rounded-xl bg-yellow-100">Web Development</div>
				</div>
			</div>
		</div>
	</div>
</main>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

	main {
		font-family: poppins;
	}
</style>
