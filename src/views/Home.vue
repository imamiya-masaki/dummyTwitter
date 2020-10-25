<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <Modal userText="hello!"/>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import Modal from '@/components/Modal.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld,
    Modal
  }
}
</script>
