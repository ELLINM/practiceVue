<script>
  import DropDown from '@/components/DropDown.vue'

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
  </body>
</template>

<style scoped>
</style>
