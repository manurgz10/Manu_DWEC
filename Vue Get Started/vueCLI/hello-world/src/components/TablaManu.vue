<template>
    <div>
        <table>
            <caption> {{ titulo }} </caption>
            <slot> </slot>
        </table>
    </div>
</template>
  <script>
  export default {
    name: 'TablaManu',
    props: {
        titulo: String,


    }
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped lang="scss">
  table {
    border: solid 1px blue;
  }
  </style>
  