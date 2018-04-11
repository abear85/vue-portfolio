<template>
  <div>
    <p>{{ greeting }} World!</p>
  </div>
</template>
<script>
export default {
  name: 'helloworld',
  props: ['greeting'],
  data () {
    return {}
  }
}
</script>
<style lang="scss" scoped=""></style>