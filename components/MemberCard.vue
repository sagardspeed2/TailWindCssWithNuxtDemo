<template>
	<div class="main-card-block">
		<div class="max-w-sm rounded overflow-hidden shadow-lg">
			<img class="w-full" :src=srcPath alt="Sunset in the mountains">
			<div>
				<div class="px-6 py-4">
					<p class="text-gray-700 text-base">
					  {{about}}
					</p>
				</div>
				<div class="px-6">
					<div class="name font-semibold">{{name}}</div>
					<div class="designation">{{designation}}</div>
				</div>
			</div>
		</div>
	</div>
</template>

<script>
	export default {
	    props: {
	    	about: String,
	    	name: String,
	    	designation: String,
	    	srcPath: String
	    }
	};
</script>