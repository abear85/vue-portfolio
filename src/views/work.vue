<template>
	<div>
		{{ msg }}
		<HelloWorld greeting="Work"></HelloWorld>
	</div>
</template>
<script>
import HelloWorld from '@/components/HelloWorld'
export default {
  name: 'about',
  components: {
  	HelloWorld
  },
  data () {
    return {
      msg: 'About'
    }
  }
}
</script>
<style lang="scss" scoped></style>
