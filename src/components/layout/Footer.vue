<template>
    <footer class="container-fuild py-10 px-5">
        <ul class="row justify-content-between align-items-end">
            <li class="col-12 col-md-4 col-lg-3 mb-5">
                <h2 class="d-flex justify-content-center">
                    <a href="#" class="footer-brand">
                        <div class="footer-logo bg-contain mr-1 mr-lg-3"></div>
                        <h3 class="d-none d-lg-flex flex-column justify-content-between">
                            <span>Nefer Digital</span>
                            <span>完美數位</span>
                        </h3>
                    </a>
                </h2>
            </li>
            <li class="col-12 col-md-4 col-lg-3 mb-5">
                <ul>
                    <li class="mb-3">
                        <p class="text-center text-xl-left">電話：
                            <a href="tel:+02-2627-2999#1002" class="text-decoration-none">02-2627-2999#1002</a>
                        </p>
                    </li>
                    <li class="mb-3">
                        <p class="text-center text-xl-left">地址：台北市內湖區瑞光路298號5F之1</p>
                    </li>
                    <li class="mb-3">
                        <p class="text-center text-xl-left">Copyright © 2020 Nefer Digital Co., LTD. All rights reserved</p>
                    </li>
                </ul>
            </li>
            <li class="col-12 col-md-4 col-lg-3 mb-5">
                <ul class="d-flex justify-content-around">
                    <li>
                        <a href="#" class="d-inline-block bg-cover footer-icon one"></a>
                    </li>
                    <li>
                        <a href="#" class="d-inline-block bg-cover footer-icon two"></a>
                    </li>
                    <li>
                        <a href="#" class="d-inline-block bg-cover footer-icon tri"></a>
                    </li>
                </ul>
            </li>
        </ul>
    </footer>
</template>

<style lang="scss" scoped>
@import '../../assets/all.scss';
    .footer-brand {
        display: flex;
        color: $secondary;

        &:hover {
            text-decoration: none;
            color: $secondary;
        }

        h3 {
            @include mobile {
                font-size: 20px;
            }
        }

        .footer-logo {
            width: 119px;
            height: 113px;
            background-image: url('../../assets/images/u4.png');

            @include mobile {
                width: 96px;
                height: 92px;
            }
        }
    }
    .footer-icon {
        width: 77px;
        height: 75px;

        &.one {
            background-image: url('../../assets/images/u73.png');
        }

        &.two {
            background-image: url('../../assets/images/u74.png');
        }

        &.tri {
            background-image: url('../../assets/images/u75.png');
        }
    }
</style>
