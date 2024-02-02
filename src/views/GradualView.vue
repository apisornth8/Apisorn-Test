<template lang="">
    <head><link rel="stylesheet"href="https://fonts.googleapis.com/css?family=Kanit"></head>
    <div class="forquestion">
        <div class="card" id="summarystyle">
            <div class="container1">
                <h1>ผลลัพธ์ของคุณคือ</h1>
                <img src="../assets/image/Gradual.png">
                <h2>คุณรู้จัก Globish ผ่าน Instagram, เพื่อนแนะนำมา</h2>
            </div>
        </div>
        <label class="back">
            <button class="finishbtn" @click="redirectPage()">เสร็จสิ้น!</button>
        </label>
        <form>
  </form>
    </div>
</template>
<script>
export default {
    methods:{
        redirectPage(){
            this.$router.push('/StartPage')
        }
    }
};
</script>
<style lang="">
</style>