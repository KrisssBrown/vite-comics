<script>
import Social from './Social.vue'
import SignUp from './SignUp.vue'

export default {
    components:{
        Social,
        SignUp

    },

    data(){
        return{

        }
    }
}
</script>

<!-- =============================================== -->
<template>
    <div class="background">
        <div class="main-container container">
            <SignUp/>
            <Social/>
        </div>
    </div>
</template>
<!-- =============================================== -->
<style lang="scss" scoped>

.background{
    background-color: #303030;
}

.container{
    padding: 40px 0;
    display: flex;
    justify-content: space-between;
    align-items: center;
}


</style>