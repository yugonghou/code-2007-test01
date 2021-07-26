<template>
    <div id="app">
      <t-button @test="handleClick"></t-button>  
    </div>
</template>
<script>
import TButton from './Button.vue'
export default {
    comments: {
        TButton
    },
    methods: {
        handleClick () {
            console.log(333)
        }
    }
}
</script>
<style lang="less">
    
</style>