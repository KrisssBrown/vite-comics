<script>
export default {

}


</script>

<!-- =============================================== -->
<template>
    <div class="background">
        <div class="main-container container">
            <ul class="merch-list">
                <li>
                    <img src="../assets/buy-comics-digital-comics.png">
                    <a href="#">DIGITAL COMICS</a>
                </li>
                <li>
                    <img src="../assets/buy-comics-merchandise.png">
                    <a href="#">DC MERCHANDISE</a>
                </li>
                <li>
                    <img src="../assets/buy-comics-shop-locator.png">
                    <a href="#">SUBSCRIPTION</a>
                </li>
                <li>
                    <img src="../assets/buy-comics-subscriptions.png">
                    <a href="#">COMIC SHOP LOCATOR</a>
                </li>
                <li>
                    <img src="../assets/buy-dc-power-visa.svg">
                    <a href="#">DC POWER VISA</a>
                </li>
            </ul>
        </div>
    </div>
</template>
<!-- =============================================== -->
<style lang="scss" scoped>
.background {
    background-color: #0282F9;
}

.merch-list {
    display: flex;
    padding: 20px 0;
    gap: 10px;
    justify-content: space-between;
    padding: 20px 40px;

    li {
        display: flex;
        align-items: center;
        gap: 10px;

        a {
            font-size: 11px;
            color: white;
            font-weight: bold;
        }

        img {
            width: 46px;
            height: 57px;
        }

        &:hover {
            // border-bottom: 3px solid #0282F9;
            color: black;
        }
    }
}
</style>