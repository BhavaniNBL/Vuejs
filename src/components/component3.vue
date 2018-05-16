<template>
<div>
    <p>Name</p>
    <p>{{title1}}</p>
    <p>Email</p>
    <p>{{title2}}</p>
    <p>DOB</p>
    <p>{{title3}}</p>
    <p>Place</p>
    <p>{{title4}}</p>
</div>
</template>
<script>
export default {
  props: ['title1', 'title2', 'title3', 'title4']
}
</script>
<style>
</style>
