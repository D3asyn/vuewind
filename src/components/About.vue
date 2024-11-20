<template>
	<div>
		<!-- Top Section: Who We Are -->
		<div class="text-center mt-8">
			<h1 class="text-4xl font-bold">Who We Are</h1>
			<p class="text-gray-600 mt-2">
				Lorem ipsum dolor sit amet, consectetur adipiscing elit.
			</p>
		</div>

		<!-- Vision Section -->
		<div class="bg-blue-100 mt-12 py-8">
			<div class="container mx-auto text-center">
				<h2 class="text-2xl font-semibold">Our Vision</h2>
				<p class="text-gray-700 mt-2">
					Lorem ipsum dolor sit amet, consectetur adipiscing elit.
				</p>
				<div class="mt-6">
					<img
						src="https://via.placeholder.com/800x400"
						alt="Vision Placeholder"
						class="mx-auto"
					/>
				</div>
			</div>
		</div>

		<!-- Features Section -->
		<div class="mt-12 text-center">
			<h2 class="text-2xl font-semibold">Our Features</h2>
			<div class="flex justify-center space-x-4 mt-8">
				<!-- Feature 1 -->
				<div class="bg-blue-100 p-4 rounded shadow-md w-1/3">
					<h3 class="text-xl font-bold">Innovation</h3>
					<p class="mt-2 text-gray-600">
						Lorem ipsum dolor sit amet, consectetur adipiscing elit.
					</p>
				</div>
				<!-- Feature 2 -->
				<div class="bg-blue-100 p-4 rounded shadow-md w-1/3">
					<h3 class="text-xl font-bold">Collaboration</h3>
					<p class="mt-2 text-gray-600">
						Lorem ipsum dolor sit amet, consectetur adipiscing elit.
					</p>
				</div>
				<!-- Feature 3 -->
				<div class="bg-blue-100 p-4 rounded shadow-md w-1/3">
					<h3 class="text-xl font-bold">Integrity</h3>
					<p class="mt-2 text-gray-600">
						Lorem ipsum dolor sit amet, consectetur adipiscing elit.
					</p>
				</div>
			</div>
		</div>

		<!-- Call to Action Section -->
		<div class="bg-blue-100 mt-12 py-8">
			<div class="container mx-auto text-center">
				<h2 class="text-2xl font-semibold">Want to work with us?</h2>
				<p class="mt-2 text-gray-700">
					Contact us to learn more about our opportunities.
				</p>
				<button
					class="mt-4 bg-blue-500 text-white py-2 px-6 rounded hover:bg-blue-600"
				>
					Contact Us
				</button>
			</div>
		</div>
	</div>
</template>

<script>
export default {
	name: "About",
};
</script>

<style scoped>
/* Add additional styles if necessary */
</style>
