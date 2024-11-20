<template>
	<div>
		<!-- Page Header -->
		<div class="text-center mt-8">
			<h1 class="text-4xl font-bold text-blue-500">Meet Our Team</h1>
			<p class="text-gray-600 mt-2">
				Lorem ipsum dolor sit amet, consectetur adipiscing elit.
			</p>
		</div>

		<!-- Profile Pictures Section -->
		<div class="flex justify-center mt-8 space-x-8">
			<div class="text-center">
				<img
					src="https://via.placeholder.com/150"
					alt="Profile Placeholder"
					class="rounded-full mx-auto"
				/>
				<p class="mt-2 text-lg font-semibold">John Doe</p>
			</div>
			<div class="text-center">
				<img
					src="https://via.placeholder.com/150"
					alt="Profile Placeholder"
					class="rounded-full mx-auto"
				/>
				<p class="mt-2 text-lg font-semibold">Jane Smith</p>
			</div>
			<div class="text-center">
				<img
					src="https://via.placeholder.com/150"
					alt="Profile Placeholder"
					class="rounded-full mx-auto"
				/>
				<p class="mt-2 text-lg font-semibold">Alex Johnson</p>
			</div>
		</div>

		<!-- Large Placeholder Image Section -->
		<div class="mt-12 text-center">
			<img
				src="https://via.placeholder.com/800x400"
				alt="Large Placeholder"
				class="mx-auto"
			/>
			<p class="mt-4 text-gray-600 text-lg">A beautiful placeholder</p>
		</div>

		<!-- "Get in Touch" Section -->
		<div class="bg-blue-100 mt-12 py-8">
			<div class="text-center">
				<h2 class="text-2xl font-semibold">Get in Touch</h2>
				<p class="mt-2 text-gray-700">Have any questions?</p>
				<button
					class="mt-4 bg-blue-500 text-white py-2 px-6 rounded hover:bg-blue-600"
				>
					Contact Us
				</button>
			</div>
		</div>

		<!-- Features Section -->
		<div class="flex justify-center space-x-4 mt-12">
			<div class="bg-blue-100 p-4 rounded shadow-md w-1/3 text-center">
				<h3 class="text-xl font-bold">Feature 1</h3>
				<p class="mt-2 text-gray-600">
					Detailed description of Feature 1. Lorem ipsum dolor sit
					amet.
				</p>
			</div>
			<div class="bg-blue-100 p-4 rounded shadow-md w-1/3 text-center">
				<h3 class="text-xl font-bold">Feature 2</h3>
				<p class="mt-2 text-gray-600">
					Detailed description of Feature 2. Lorem ipsum dolor sit
					amet.
				</p>
			</div>
			<div class="bg-blue-100 p-4 rounded shadow-md w-1/3 text-center">
				<h3 class="text-xl font-bold">Feature 3</h3>
				<p class="mt-2 text-gray-600">
					Detailed description of Feature 3. Lorem ipsum dolor sit
					amet.
				</p>
			</div>
		</div>
	</div>
</template>

<script>
export default {
	name: "Home",
};
</script>

<style scoped>
/* You can add additional styles here if needed */
</style>
