<script>
  import DropDown from '@/components/DropDown.vue'
  import Input from '@/components/Input.vue'
  import Table from '@/components/Table.vue'

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
    Table : Table,
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
    <Table />
    <br>
  </body>
</template>



<style scoped>
</style>
