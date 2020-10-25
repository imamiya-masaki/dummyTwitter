<template>
  <div>
    <b-button @click="modalShow = !modalShow">Open Modal</b-button>
    <b-modal v-model="modalShow">{{ userText }}</b-modal>
  </div>
</template>

<script>
export default {
  name: 'Modal',
  props: {
    userName: String,
    userText: String
  },
  data () {
    return {
      modalShow: false
    }
  }
}
</script>
