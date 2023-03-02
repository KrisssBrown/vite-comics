<script>
export default {
    data() {
        return {
            // social: [
            //     'footer-facebook.png',
            //     'footer-twitter.png',
            //     'footer-youtube.png',
            //     'footer-pinterest.png',
            //     'footer-periscope.png',
            // ]
        }
    }
}


</script>

<!-- =============================================== -->
<template>
    <div class="background">
        <div class="container">
            <h1>FOLLOW US</h1>
            <img src="/footer-facebook.png">
            <img src="/footer-twitter.png">
            <img src="/footer-youtube.png">
            <img src="/footer-pinterest.png">
            <img src="/footer-periscope.png">
        </div>
    </div>
</template>
<!-- =============================================== -->
<style lang="scss" scoped>
.container {
    display: flex;
    align-items: center;
    gap: 10px;

    h1 {
        font-size: 20px;
        color: #0282F9;
    }
}
</style>