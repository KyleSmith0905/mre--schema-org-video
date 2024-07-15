<script setup lang="ts">
useSchemaOrg([
	defineVideo({
		name: 'Title of video',
		description: 'Description of video',
		url: 'https://yskkyle.com',
		thumbnailUrl: {url: 'https://yskkyle.com/icons/logo192.png'},
		uploadDate: new Date(),
	})
])
</script>
<template>
  <div>
    <NuxtRouteAnnouncer />
    <NuxtWelcome />
  </div>
</template>
