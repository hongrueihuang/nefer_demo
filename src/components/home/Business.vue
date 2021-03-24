<template>
    <section ref="business" class="business bg-cover py-8 d-flex align-items-center">
        <div class="container">
            <!-- Business Title -->
            <div class="row mb-10">
                <div class="col-12 col-md-11 col-lg-9">
                    <h2 class="px-2 px-md-4 py-6 text-center text-secondary bg-title display-5 font-weight-bold">
                        Company's three major businesses
                    </h2>
                </div>
            </div>
            <!-- Business Content -->
            <ul class="row align-items-center mb-5">
                <li class="col-12 col-sm-9 col-md-8 bs-item">
                    <div class="bs-item-img one bg-cover">
                        <div class="bs-item-content position-absolute d-flex flex-column justify-content-between">
                            <h3 class="d-flex flex-column text-info">
                                <span class="mb-lg-3">Online game development</span>
                                <span>線上遊戲開發</span>
                            </h3>
                            <p class="text-center bs-item-content-text">
                                專注平台與遊戲開發
                                <br>
                                具備強大的工程團隊
                            </p>
                        </div>
                    </div>
                </li>
                <li class="d-none d-md-block col-md-2">
                    <img src="../../assets/images/u76.png" class="w-100 bs-item-icon one" alt="">
                </li>
            </ul>
            <ul class="row justify-content-center align-items-center mb-5">
                <li class="col-12 col-sm-9 col-md-8">
                    <div class="bs-item-img two bg-cover">
                        <div class="bs-item-content position-absolute d-flex flex-column justify-content-between">
                            <h3 class="d-flex flex-column text-info">
                                <span class="mb-lg-3">Cloud host monitoring</span>
                                <span>雲端主機監控</span>
                            </h3>
                            <p class="text-center bs-item-content-text">
                                監控提供專業架構意見
                                <br>
                                微調架構減輕機器成本費用與智B2B後台監控
                            </p>
                        </div>
                    </div>
                </li>
                <li class="d-none d-md-block col-md-2">
                    <img src="../../assets/images/u77.png" class="w-100 bs-item-icon two" alt="">
                </li>
            </ul>
            <ul class="row align-items-center flex-row-reverse mb-5">
                <li class="col-12 col-sm-9 col-md-8">
                    <div class="bs-item-img three bg-cover">
                        <div class="bs-item-content position-absolute d-flex flex-column justify-content-between">
                            <h3 class="d-flex flex-column text-info">
                                <span class="mb-lg-3">Technical backuservice</span>
                                <span>技術支援服務</span>
                            </h3>
                            <p class="text-center bs-item-content-text">
                                我們的訴求是協助用戶
                                <br>
                                服務普惠、體驗升級、降本增效
                                <br>
                                三大核心價值
                            </p>
                        </div>
                    </div>
                </li>
                <li class="d-none d-md-block col-md-2">
                    <img src="../../assets/images/u78.png" class="w-100 bs-item-icon tri" alt="">
                </li>
            </ul>
        </div>
    </section>
</template>

<style lang="scss" scoped>
@import '../../assets/all.scss';
    .business {
        min-height: 100vh;
        background-image: url('../../assets/images/u18.png');

        h2.display-5 {
            @include mobile {
                font-size: 2rem;
            }
        }

        .bs-item-img {
            width: 100%;
            height: 200px;
            border-radius: 20px;
            position: relative;
            background-size: 110% 110%;
            transition: all .33s ease-in-out;

            h3 {
                @include mobile {
                    font-size: 24px;
                }
            }

            &.one {
                background-image: url('../../assets/images/u24.png');
                &:hover {
                    box-shadow: 3px 3px 1px #ccc;
                }
            }

            &.two {
                background-image: url('../../assets/images/u27.svg');
                &:hover {
                    box-shadow: 3px 3px 1px #ccc;
                }
            }

            &.three {
                background-image: url('../../assets/images/u21.png');
                &:hover {
                    box-shadow: 3px 3px 1px #ccc;
                }
            }
        }

        .bs-item-icon {
            transition: all .33s;

            &:hover {
                filter: drop-shadow(5px 5px 5px #aaa) saturate(5);
            }
        }

        .bs-item-content {
            background-color: #fff;
            width: 60%;
            min-height: 80%;
            top: 5%;
            right: 2%;

            .bs-item-content-text {
                line-height: 1.2;
            }
        }
    }
</style>
