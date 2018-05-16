<template>
<div class="container">
    <div>
    <form>
            <p>
            <label for="name">Name</label>
            <input type="text" placeholder="name" v-model="name">
            </p>
            <p>
            <label for="email">Email</label>
            <input type="text" placeholder="email" v-model="email">
            </p>
            <p>
            <label for="dob">DOB</label>
            <input type="date" placeholder="dob" v-model="dob">
            </p>
            <p>
            <label for="place">Place</label>
            <input type="text" placeholder="place" v-model="place">
            </p>
    </form>
    </div>
    <component3 :title1='name' :title2='email' :title3='dob' :title4='place'></component3>
</div>
</template>
<script>
import component3 from '@/components/component3'

export default {
  name: 'component2',
  data () {
    return {
      name: '',
      email: '',
      dob: '',
      place: ''
    }
  },
  components: {
    component3
  }
}
</script>
<style>
.p {
  align-items: center;
}
.container {
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 20px;
}
</style>
