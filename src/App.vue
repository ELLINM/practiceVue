<script>
  import DropDown from '@/components/DropDown.vue'
  import Input from '@/components/Input.vue'
  import Table from '@/components/Table.vue'
  import Move from '@/components/Move2.vue'

  export default {
  name: 'App',
  data(){
    return {
    }
  },

  methods : {

  },
  components: {
    DropDown : DropDown,
    Input : Input,
    Table : Table,
    Move : Move,
  }
}
</script>

<template>
  <header>
    <div class="wrapper">
      Practice Vue
    </div>
    <Move />
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
