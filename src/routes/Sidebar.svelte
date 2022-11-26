<script>
	let profilename = 'VINOTHKUMAR';
	let Positionheld = 'Front End Developer';
</script>

<main class="">
	<div class="bg-gray-800 w-full pb-10 lg:hidden  ">Nav</div>
	<div
		class="lg:w-[400px] h-[720px] flex flex-col items-center lg:ml-[10px] xl:ml-[312px] lg:mt-[200px] lg:pb-20  w-full  lg:mb-0 mx-auto relative md:bg-[#2F4858]/10 lg:bg-white text-center lg:border px- lg:rounded-[20px] mt-64"
	>
	
		<div>
			<img
				src="./profile.jpg"
				class=" w-[180px] h-[180px] lg:w-[240px] lg:z-20  absolute transform -translate-x-[50%] lg:h-[240px]  mx-auto rounded-full lg:-mt-[140px] -mt-56 border-4 border-white"
				alt=""
			/>
		</div>
		<div>
			<h1 class=" lg:mt-32  text-2xl font-semibold text-white lg:text-[#2F4858] ">{profilename}</h1>
			<p class="lg:text-[#7b7b7b] text-white text-base mt-3">{Positionheld}</p>
		</div>

		<div class="flex gap-5 justify-center mt-[28px]">
			<div>
				<img
					src="./facebook.svg"
					class="lg:w-7  lg:h-7 hover:bg-[#2F4858]  bg-white lg:bg-[#7b7b7b]/10  rounded p-1.5"
					alt=""
				/>
			</div>
			<img
				src="./instagram.svg"
				class="lg:w-7  lg:h-7 hover:bg-[#2F4858]  bg-white lg:bg-[#7b7b7b]/10  rounded p-1.5"
				alt=""
			/>
			<img
				src="./linkedin.svg"
				class="lg:w-7  lg:h-7 hover:bg-[#2F4858]  bg-white lg:bg-[#7b7b7b]/10  rounded p-1.5"
				alt=""
			/>
			<img
				src="./github.svg"
				class="lg:w-7  lg:h-7 hover:bg-[#2F4858]  bg-white lg:bg-[#7b7b7b]/10  rounded p-1.5"
				alt=""
			/>
		</div>
		<div class="px-4 w-full">
			<div
				class="lg:w-[352px] lg:h-[297px] w-full lg:bg-[#7b7b7b]/10 bg-white rounded-xl mt-10 flex flex-col px-5 py-5 "
			>
				<div class="flex mt-">
					<img src="./call.svg" class="lg:w-10 ml-2  lg:h-10   lg:bg-white bg-[#2F4858]  rounded p-1.5" alt="" />
					<div class="flex flex-col ml-2">
						<p class="flex justify-start  lg:text-gray-500">Phone</p>
						<h1 class="text-[#2F4858]/80 text-sm lg:text-base">7845860720</h1>
					</div>
				</div>

				<div class="flex mt-4">
					<img src="./email.svg" class="lg:w-10 ml-2  lg:h-10   lg:bg-white bg-[#2F4858]  rounded p-1.5" alt="" />
					<div class="flex flex-col ml-2">
						<p class="flex justify-start  lg:text-gray-500">Email</p>
						<h1 class="text-[#2F4858]/80  text-sm lg:text-base">Pavinoth00@gmail.com</h1>
					</div>
				</div>
				<div class="flex mt-4">
					<img
						src="./location.svg"
						class="lg:w-10 ml-2  lg:h-10 bg-[#2F4858]   lg:bg-white  rounded p-1.5"
						alt=""
					/>
					<div class="flex flex-col ml-2">
						<p class="flex justify-start  lg:text-gray-500">Location</p>
						<h1 class="text-[#2F4858]/80  text-sm lg:text-base">Chennai</h1>
					</div>
				</div>
				<div class="flex mt-4">
					<img
						src="./calender.svg"
						class="lg:w-10 ml-2  lg:h-10  bg-[#2F4858]  lg:bg-white  rounded p-1.5"
						alt=""
					/>
					<div class="flex flex-col ml-2">
						<p class="flex justify-start  lg:text-gray-500">Birthday</p>
						<h1 class="lg:text-[#2F4858]/80 text-[#2F4858]  text-sm lg:text-base">05 Mar 1996</h1>
					</div>
				</div>
			</div>
		</div>
		<div class="flex justify-center">
			<a href="/profile.jpg"
				><button
					class="rounded-full lg:px-8 px-16 py-6 	 lg:py-3 text-lg md:text-[#2F4858] text-white border-2 items-center flex mt-32 lg:mt-10 bg-yellow-500"
				>
					<img src="/fa_download.svg" class="w-4 h-4  mr-4 " alt="" /> Download CV</button
				></a
			>
		</div>
	</div>
</main>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

	main {
		font-family: poppins;
	}
</style>
