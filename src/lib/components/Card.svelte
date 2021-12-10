<script>
</script>

<div class="my-12 flex flex-col md:flex-row relative bg-coolGray-100 md:bg-opacity-0 rounded-md">
	<div class="flex md:w-2/3 px-4 md:pr-0 py-2 md:pt-0 justify-between ">
		<div class="space-y-2 md:px-4">
			<h1 class="text-3xl">
				<slot name="header" />
			</h1>
			<div class="leading-snug">
				<slot name="content" />
			</div>
		</div>
	</div>
</div>
