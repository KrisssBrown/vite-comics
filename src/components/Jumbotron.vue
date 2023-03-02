<script>
import Comics from './Comics.vue'
export default {
    components:{
        Comics
    }
}


</script>

<!-- =============================================== -->
<template>
    <div class="background">
        <img class="jumbo" src="../assets/jumbotron.jpg">
        <div class="main-container container">

            <div class="comics">
                <!-- <Comics/> -->
            </div>
        </div>
    </div>
</template>
<!-- =============================================== -->
<style lang="scss" scoped>

.container {
    height: 130px;
    display: flex;
    align-items: center;

    h1{
        color: white;
        font-size: 14px;
    }
}

.background{
    background-color: #1C1C1C;

    .jumbo{
        max-width: 100%;
    }
}
</style>