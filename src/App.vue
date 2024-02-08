<script>
  import DropDown from '@/components/DropDown.vue'
  import Input from '@/components/Input.vue'

  export default {
  name: 'App',
  data(){
    return {
      current_password: ""
    }
  },

  methods : {

  },
  components: {
    DropDown : DropDown,
    Input : Input,
  }
}
</script>

<template>
  <header>
    <div class="wrapper">
      Practice Vue
    </div>
  </header>
  <body>
    <DropDown />
    <br>
    <Input />
    <br>
  </body>
</template>



<style scoped>
</style>
