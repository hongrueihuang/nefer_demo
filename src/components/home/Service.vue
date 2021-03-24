<template>
    <section ref="service" class="service bg-cover d-flex align-items-center">
        <div class="service-mask"></div>
        <div class="container py-15">
            <h2 class="text-white font-weight-bold display-3 text-center mb-15 mb-md-25">OUR SERVICES</h2>
            <div class="row justify-content-end">
                <div class="col-12 col-lg-7 text-center">
                    <h3 class="h1 font-weight-bold d-flex flex-column align-items-center mb-15 mb-lg-20">
                        <span class="text-warning mb-15 mb-md-25">Online game development</span>
                        <span class="d-inline-block px-12 py-5 btn-service">線上遊戲開發</span>
                    </h3>
                    <p class="d-flex text-white flex-column align-items-center justify-content-center h4">
                        <span class="mb-5 mb-md-10">專注平台與遊戲開發，具備強大的工程團隊</span>
                        <span>不斷拓展互動娛樂產業生態圈，構建精品遊戲服務平臺</span>
                    </p>
                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
@import '../../assets/all.scss';
    .service {
        min-height: 100vh;
        background-image: url('../../assets/images/u30.png');
        position: relative;

        .service-mask {
            position: absolute;
            top: 0;
            right: 0;
            left: 0;
            bottom: 0;
            background-color: rgba(256, 256, 256, .23);
        }

        .btn-service {
            background-color: $info;
            border: 2px solid $light;
            color: $warning;
            transition: all .15s;
        }

        &:hover {
            .btn-service {
            background-color: #015478;
            }
        }

        .display-3 {
            @include mobile-sm {
                font-size: 32px;
            }
        }

        .h1 {
            @include mobile-sm {
                font-size: 28px;
            }
        }

        .h4 {
            @include mobile-sm {
                font-size: 20px;
            }
        }
    }
</style>
