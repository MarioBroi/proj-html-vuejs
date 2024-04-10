<script>
export default {
    name: 'AppHeader'
}
</script>

<template>

    <header class="site-header">

        <div class="header-dropdown">

            <a href="" class="home">
                Home <i class="fa-solid fa-chevron-down"></i>
            </a>
            <!-- /.home -->

            <div class="pages">
                Pages <i class="fa-solid fa-chevron-down"></i>
                <ul class="dropdown">
                    <li>
                        <a href="">
                            Start Here
                        </a>
                    </li>
                    <li>
                        <a href="">
                            Success Story
                        </a>
                    </li>
                    <li>
                        <a href="">
                            About me
                        </a>
                    </li>
                    <li>
                        <a href="">
                            About us 01
                        </a>
                    </li>
                    <li>
                        <a href="">
                            About us 02
                        </a>
                    </li>
                    <li>
                        <a href="">
                            About us 03
                        </a>
                    </li>
                    <li>
                        <a href="">
                            Contact me </a>
                    </li>
                    <li>
                        <a href="">
                            Contact us
                        </a>
                    </li>
                    <li>
                        <a href="">
                            Purchase Guide
                        </a>
                    </li>
                    <li>
                        <a href="">
                            Privacy Policy
                        </a>
                    </li>
                    <li>
                        <a href="" class="last-drop">
                            Terms of Service
                        </a>
                    </li>
                </ul>
            </div>
            <!-- /.pages -->

            <a href="" class="courses">
                Courses <i class="fa-solid fa-chevron-down"></i>
            </a>
            <!-- /.courses -->

            <a href="" class="features">
                Features <i class="fa-solid fa-chevron-down"></i>
            </a>
            <!-- /.features -->

            <a href="" class="blog">
                Blog <i class="fa-solid fa-chevron-down"></i>
            </a>
            <!-- /.blog -->

            <a href="" class="shop">
                Shop <i class="fa-solid fa-chevron-down"></i>
            </a>
            <!-- /.shop -->

        </div>
        <!-- /.header-dropdown -->

        <div class="logo">
            <img src="/public/img/dark-logo.png" alt="">
        </div>
        <!-- /.logo -->

        <div class="utility-buttons">

            <a href="" class="cart">
                <i class="fa-solid fa-cart-shopping"></i>
                <span class="cart-number">0</span>
            </a>
            <!-- /.cart -->

            <a href="" class="profile">
                <i class="fa-regular fa-circle-user"></i>
            </a>
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