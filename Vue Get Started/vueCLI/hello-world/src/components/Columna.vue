<template>
    <div>
        <td><slot></slot></td>
      
    </div>
</template>
  <script>
  export default {
    name: 'Columna',
  props: {
    valor: String
  }
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped lang="scss">
  td {
    border: 1px solid purple;
    background-color: rgb(163, 110, 110);
  }
  </style>
  