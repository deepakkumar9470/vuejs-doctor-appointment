<template>
    <header>
        <h1>{{title}}</h1>
         <Button text="Add Task" color="green"/>
    </header>
</template>



<script>
import Button from './Button.vue'

    export default {
        name : 'Header',
        components : {
            Button
        },
        props : {
            title : String
        }
    }

</script>



<style scoped>

header{
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-bottom: 20px;
}

</style>