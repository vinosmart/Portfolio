<script>
	import Sidebar from './Sidebar.svelte';
</script>

<main class="">
	<div class="flex">

	<div class="flex flex-col">
		

		<div class="bg-white shadow-lg rounded-xl w-[840px] h-[100px]  mt-[200px] ml-10 border  ">
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
		<div class="bg-white shadow-lg rounded-xl w-[840px] h-[900px] mt-10 scroll-mt-12 ml-10 border flex-wrap  "></div>
	</div>
</div>
</main>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

	main {
		font-family: poppins;
	}
</style>
