/**
* @description: 文件或模块描述
* @author: zengtiansheng
* @update: 2017/8/14
*/
<style scoped>

</style>
<template>
    <div></div>
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
            this.$emit('commit', 'commit msg to parent')
        },
        created() {
        }
    }
</script>
