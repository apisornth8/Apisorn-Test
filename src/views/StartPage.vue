<template lang="">
        <div class="picstart">
            <img src="../assets/image/Background.png">
            <button class="btnstart" @click="redirectPage()">เริ่มเลย!</button>  
        </div>
</template>
<script>
export default {
    methods:{
        redirectPage(){
            this.$router.push('/question')
        }
    }
};
</script>
<style lang="">
</style>