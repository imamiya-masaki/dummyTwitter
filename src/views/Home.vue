<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <Modal userText="hello!"/>
    <Profile />
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import Modal from '@/components/Modal.vue'
import Profile from '@/components/Profile.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld,
    Modal,
    Profile
  }
}
</script>
