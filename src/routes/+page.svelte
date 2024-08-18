<script>
	import headshot from '$lib/assets/me.png';
	import gt from '$lib/assets/gt.png';
	import capitalone from '$lib/assets/capitalone.png';
	import humana from '$lib/assets/humana.png';
	import resume from '$lib/assets/dylan-van-bunnik-resume.pdf';
</script>

<div class="text-slate-300 font-display flex flex-col items-center h-full pt-8">
	<!--HEADER-->
	<div class="flex items-center gap-16 mb-8">
		<img
			alt="Headshot of Dylan van Bunnik"
			src={headshot}
			class="rounded-full w-28 border-slate-300 border-2 hidden md:block"
		/>
		<div class="flex flex-col gap-1">
			<h1 class="text-3xl md:text-5xl">Dylan <span class="font-bold">van Bunnik</span></h1>
			<h2 class="text-xl md:text-3xl text-gray-400">Software Engineer</h2>
		</div>
	</div>
	<!-- QUICK LINKS -->
	<div class="flex gap-2 mb-8">
		<a href={resume} target="_blank">
			<svg
				class="w-8 h-8 text-zinc-400 hover:text-white transition-all duration-200 hover:cursor-pointer"
				aria-hidden="true"
				xmlns="http://www.w3.org/2000/svg"
				fill="currentColor"
				viewBox="0 0 24 24"
			>
				<path
					fill-rule="evenodd"
					d="M5 3a2 2 0 0 0-2 2v14a2 2 0 0 0 2 2h11.5c.07 0 .14-.007.207-.021.095.014.193.021.293.021h2a2 2 0 0 0 2-2V7a1 1 0 0 0-1-1h-1a1 1 0 1 0 0 2v11h-2V5a2 2 0 0 0-2-2H5Zm7 4a1 1 0 0 1 1-1h.5a1 1 0 1 1 0 2H13a1 1 0 0 1-1-1Zm0 3a1 1 0 0 1 1-1h.5a1 1 0 1 1 0 2H13a1 1 0 0 1-1-1Zm-6 4a1 1 0 0 1 1-1h6a1 1 0 1 1 0 2H7a1 1 0 0 1-1-1Zm0 3a1 1 0 0 1 1-1h6a1 1 0 1 1 0 2H7a1 1 0 0 1-1-1ZM7 6a1 1 0 0 0-1 1v3a1 1 0 0 0 1 1h3a1 1 0 0 0 1-1V7a1 1 0 0 0-1-1H7Zm1 3V8h1v1H8Z"
					clip-rule="evenodd"
				/>
			</svg>
		</a>
		<a href="https://linkedin.com/in/dylan-van-bunnik" target="_blank">
			<svg
				class="w-8 h-8 text-zinc-400 hover:text-white transition-all duration-200 hover:cursor-pointer"
				aria-hidden="true"
				xmlns="http://www.w3.org/2000/svg"
				fill="currentColor"
				viewBox="0 0 24 24"
			>
				<path
					fill-rule="evenodd"
					d="M12.51 8.796v1.697a3.738 3.738 0 0 1 3.288-1.684c3.455 0 4.202 2.16 4.202 4.97V19.5h-3.2v-5.072c0-1.21-.244-2.766-2.128-2.766-1.827 0-2.139 1.317-2.139 2.676V19.5h-3.19V8.796h3.168ZM7.2 6.106a1.61 1.61 0 0 1-.988 1.483 1.595 1.595 0 0 1-1.743-.348A1.607 1.607 0 0 1 5.6 4.5a1.601 1.601 0 0 1 1.6 1.606Z"
					clip-rule="evenodd"
				/>
				<path d="M7.2 8.809H4V19.5h3.2V8.809Z" />
			</svg>
		</a>
		<a href="https://discord.com/users/223200575515394048" target="_blank">
			<svg
				class="w-8 h-8 text-zinc-400 hover:text-white transition-all duration-200 hover:cursor-pointer"
				aria-hidden="true"
				xmlns="http://www.w3.org/2000/svg"
				fill="currentColor"
				viewBox="0 0 24 24"
			>
				<path
					d="M18.942 5.556a16.3 16.3 0 0 0-4.126-1.3 12.04 12.04 0 0 0-.529 1.1 15.175 15.175 0 0 0-4.573 0 11.586 11.586 0 0 0-.535-1.1 16.274 16.274 0 0 0-4.129 1.3 17.392 17.392 0 0 0-2.868 11.662 15.785 15.785 0 0 0 4.963 2.521c.41-.564.773-1.16 1.084-1.785a10.638 10.638 0 0 1-1.706-.83c.143-.106.283-.217.418-.331a11.664 11.664 0 0 0 10.118 0c.137.114.277.225.418.331-.544.328-1.116.606-1.71.832a12.58 12.58 0 0 0 1.084 1.785 16.46 16.46 0 0 0 5.064-2.595 17.286 17.286 0 0 0-2.973-11.59ZM8.678 14.813a1.94 1.94 0 0 1-1.8-2.045 1.93 1.93 0 0 1 1.8-2.047 1.918 1.918 0 0 1 1.8 2.047 1.929 1.929 0 0 1-1.8 2.045Zm6.644 0a1.94 1.94 0 0 1-1.8-2.045 1.93 1.93 0 0 1 1.8-2.047 1.919 1.919 0 0 1 1.8 2.047 1.93 1.93 0 0 1-1.8 2.045Z"
				/>
			</svg>
		</a>
		<a href="https://github.com/dpvb" target="_blank">
			<svg
				class="w-8 h-8 text-zinc-400 hover:text-white transition-all duration-200 hover:cursor-pointer"
				aria-hidden="true"
				xmlns="http://www.w3.org/2000/svg"
				fill="currentColor"
				viewBox="0 0 24 24"
			>
				<path
					fill-rule="evenodd"
					d="M12.006 2a9.847 9.847 0 0 0-6.484 2.44 10.32 10.32 0 0 0-3.393 6.17 10.48 10.48 0 0 0 1.317 6.955 10.045 10.045 0 0 0 5.4 4.418c.504.095.683-.223.683-.494 0-.245-.01-1.052-.014-1.908-2.78.62-3.366-1.21-3.366-1.21a2.711 2.711 0 0 0-1.11-1.5c-.907-.637.07-.621.07-.621.317.044.62.163.885.346.266.183.487.426.647.71.135.253.318.476.538.655a2.079 2.079 0 0 0 2.37.196c.045-.52.27-1.006.635-1.37-2.219-.259-4.554-1.138-4.554-5.07a4.022 4.022 0 0 1 1.031-2.75 3.77 3.77 0 0 1 .096-2.713s.839-.275 2.749 1.05a9.26 9.26 0 0 1 5.004 0c1.906-1.325 2.74-1.05 2.74-1.05.37.858.406 1.828.101 2.713a4.017 4.017 0 0 1 1.029 2.75c0 3.939-2.339 4.805-4.564 5.058a2.471 2.471 0 0 1 .679 1.897c0 1.372-.012 2.477-.012 2.814 0 .272.18.592.687.492a10.05 10.05 0 0 0 5.388-4.421 10.473 10.473 0 0 0 1.313-6.948 10.32 10.32 0 0 0-3.39-6.165A9.847 9.847 0 0 0 12.007 2Z"
					clip-rule="evenodd"
				/>
			</svg>
		</a>
	</div>
	<!-- EDUCATION -->
	<div class="flex flex-col gap-4 items-center">
		<div class="border-[1px] rounded-md border-zinc-700 p-2 md:w-[450px] w-11/12">
			<div class="flex gap-2 items-center justify-center">
				<svg
					class="w-6 h-6 text-gray-800 dark:text-white"
					aria-hidden="true"
					xmlns="http://www.w3.org/2000/svg"
					width="24"
					height="24"
					fill="none"
					viewBox="0 0 24 24"
				>
					<path
						stroke="currentColor"
						stroke-linecap="round"
						stroke-linejoin="round"
						stroke-width="2"
						d="M19 7h1v12a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1V5a1 1 0 0 0-1-1H5a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h11.5M7 14h6m-6 3h6m0-10h.5m-.5 3h.5M7 7h3v3H7V7Z"
					/>
				</svg>

				<p class="text-xl">Education</p>
			</div>
			<hr class="border-zinc-700 my-2 w-1/2 mx-auto" />
			<div class="flex w-full gap-4">
				<img src={gt} alt="Georgia Tech Logo" class="w-10 h-10" />
				<div class="flex flex-col w-full">
					<div class="flex justify-between">
						<p>Georgia Institute of Technology</p>
						<p>2020 - 2024</p>
					</div>
					<p class="text-sm text-gray-400">BS in Computer Science</p>
				</div>
			</div>
		</div>
		<!-- EXPERIENCE -->
		<div class="border-[1px] rounded-md border-zinc-700 p-2 md:w-[450px] w-11/12">
			<div class="flex gap-2 items-center justify-center">
				<svg
					class="w-6 h-6 text-gray-800 dark:text-white"
					aria-hidden="true"
					xmlns="http://www.w3.org/2000/svg"
					width="24"
					height="24"
					fill="none"
					viewBox="0 0 24 24"
				>
					<path
						stroke="currentColor"
						stroke-linecap="round"
						stroke-linejoin="round"
						stroke-width="2"
						d="M9 16H5a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v1M9 12H4m8 8V9h8v11h-8Zm0 0H9m8-4a1 1 0 1 0-2 0 1 1 0 0 0 2 0Z"
					/>
				</svg>
				<p class="text-xl">Experience</p>
			</div>
			<hr class="border-zinc-700 my-2 w-1/2 mx-auto" />
			<div class="flex flex-col gap-2">
				<div class="flex w-full gap-4">
					<img src={capitalone} alt="Capital One Logo" class="w-10 h-10" />
					<div class="flex flex-col w-full">
						<div class="flex justify-between">
							<p>Capital One</p>
							<p>Aug 2024 - Present</p>
						</div>
						<p class="text-sm text-gray-400">SWE (TDP)</p>
					</div>
				</div>
				<div class="flex w-full gap-4">
					<img src={capitalone} alt="Capital One Logo" class="w-10 h-10" />
					<div class="flex flex-col w-full">
						<div class="flex justify-between">
							<p>Capital One</p>
							<p>Summer 2023</p>
						</div>
						<p class="text-sm text-gray-400">SWE Intern</p>
					</div>
				</div>
				<div class="flex w-full gap-4">
					<img src={humana} alt="Humana Logo" class="w-10 h-10" />
					<div class="flex flex-col w-full">
						<div class="flex justify-between">
							<p>Humana</p>
							<p>Summer 2022</p>
						</div>
						<p class="text-sm text-gray-400">SWE Intern</p>
					</div>
				</div>
			</div>
		</div>
	</div>
</div>
