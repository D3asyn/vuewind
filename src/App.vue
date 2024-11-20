<template>
	<div class="min-h-screen flex flex-col">
		<!-- Main Content -->
		<div class="flex-1">
			<nav class="bg-blue-500 p-4">
				<div
					class="container mx-auto flex justify-between items-center"
				>
					<div class="text-white text-lg font-bold">My App</div>
					<div class="flex space-x-4">
						<router-link
							to="/"
							class="text-white hover:text-blue-200"
							active-class="font-semibold"
						>
							Home
						</router-link>
						<router-link
							to="/about"
							class="text-white hover:text-blue-200"
							active-class="font-semibold"
						>
							About
						</router-link>
					</div>
				</div>
			</nav>
			<router-view />
		</div>

		<!-- Footer -->
		<footer class="bg-blue-900 text-white py-6">
			<div class="container mx-auto text-center">
				<p class="text-sm">© 2024 My App. All rights reserved.</p>
				<p class="text-sm mt-2">
					Made with ❤️ using Vue.js and Tailwind CSS.
				</p>
			</div>
		</footer>
	</div>
</template>

<script>
export default {
	name: "App",
};
</script>

<style>
/* Optional: Add global styles if necessary */
</style>
