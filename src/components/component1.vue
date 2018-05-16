<template>
<div>
<div>
<h1>{{ msg }}</h1>
<component2></component2>
</div>
</div>
</template>
<script>
import component2 from '@/components/component2'
export default {
  name: 'component1',
  data () {
    return {
      msg: 'Form'
    }
  },
  components: {
    component2
  }
}
</script>
<style>
</style>
