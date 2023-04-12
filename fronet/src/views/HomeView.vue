<template>
   <helloWorld />

</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
	name: 'homeView',
	components: {
    HelloWorld
  }
}
</script>
<style scoped>
</style>
