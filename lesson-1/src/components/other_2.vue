/**
* @description: 文件或模块描述
* @author: zengtiansheng
* @update: 2017/8/14
*/
<style scoped>

</style>
<template>
    <div>o 2</div>
</template>
<script>

    export default {
        data() {
            return {
                msg: ''
            }
        },
        methods: {},
        mounted() {
        },
        created() {
            this.bus.$on('busData',(data)=>{
                console.log(data)
            })
        }
    }
</script>
