<template>
    <button @click="addTasks()" 
           class="btn" :style="{background: color}">{{text}}</button>
</template>

<script>
  export default {
      name : 'Button',
      props :{
          text : String,
          color: String
      },
      methods : {
          addTasks(){
              console.log('Hello first task')
          }
      }
  }

</script>