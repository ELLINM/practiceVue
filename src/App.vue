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
    <Input validType="password" ref="current_password" label="사용중인 비밀번호" type="password" placeholder="사용중인 비밀번호를 입력해주세요"/>
  </body>
</template>



<style scoped>
</style>
