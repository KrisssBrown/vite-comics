<script>
import FooterMenu from './FooterMenu.vue'
export default {
    components: {
        FooterMenu
    }
}


</script>

<!-- =============================================== -->
<template>
    <div class="background">
        <div class="main-container container">
            <FooterMenu />
            <img src="../assets/dc-logo-bg.png" alt="">
        </div>
    </div>
</template>
<!-- =============================================== -->
<style lang="scss" scoped>
.background {
    background-image: url(/footer-bg.jpg);
    display: flex;
    position: relative;
    z-index: -2;
    height: 497px;
    width: 100%;
    background-repeat: no-repeat;
    background-size: cover;

}

.container {
    display: flex;

    img {
        position: absolute;
        z-index: -1;
        top: -32px;
    }
}
</style>