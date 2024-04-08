<script>
export default {
    name: 'AppHeader'
}
</script>

<template>

    <header class="site-header">

        <div class="dropdown">

            <button class="home">
                Home <i class="fa-solid fa-chevron-down"></i>
            </button>
            <!-- /.home -->

            <button class="pages">
                Pages <i class="fa-solid fa-chevron-down"></i>
            </button>
            <!-- /.pages -->

            <button class="courses">
                Courses <i class="fa-solid fa-chevron-down"></i>
            </button>
            <!-- /.courses -->

            <button class="features">
                Features <i class="fa-solid fa-chevron-down"></i>
            </button>
            <!-- /.features -->

            <button class="blog">
                Blog <i class="fa-solid fa-chevron-down"></i>
            </button>
            <!-- /.blog -->

            <button class="shop">
                Shop <i class="fa-solid fa-chevron-down"></i>
            </button>
            <!-- /.shop -->

        </div>
        <!-- /.dropdown -->

        <div class="logo">
            <img src="/public/img/dark-logo.png" alt="">
        </div>
        <!-- /.logo -->

        <div class="utility-buttons">

            <div class="cart">
                <i class="fa-solid fa-cart-shopping"></i>
            </div>
            <!-- /.cart -->

            <div class="profile">
                <i class="fa-regular fa-user"></i>
            </div>
            <!-- /.profile -->

            <div class="search">
                <input type="text" placeholder="Search..">
                <i class="fa-solid fa-magnifying-glass"></i>
            </div>
            <!-- /.search -->

        </div>
        <!-- /.utility-buttons -->

    </header>
    <!-- site-header -->

</template>

<style></style>