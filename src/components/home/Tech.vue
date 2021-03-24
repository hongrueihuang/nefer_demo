<template>
    <section ref="tech" class="tech bg-cover">
        <div class="container-fluid">
            <div class="row">
                <div class="col-12 col-xl-3 py-10 position-relative">
                    <div class="d-none d-xl-flex tech-title-bg bg-cover align-items-center justify-content-center">
                        <h2 class="tech-title font-weight-bold d-flex flex-column justify-content-center align-items-center">
                            <span class="mb-5">技術支援服務</span>
                            <span>Technical backuservice</span>
                        </h2>
                    </div>
                    <h2 class="tech-title text-center font-weight-bold d-flex flex-column justify-content-center align-items-center d-xl-none">
                        <span>技術支援服務</span>
                        <span>Technical backuservice</span>
                    </h2>
                </div>
                <div class="col-12 col-xl-9">
                    <div class="row">
                        <div class="col-12 col-sm-6 col-xl-3 order-1 tech-list">
                            <img src="../../assets/images/green1.png" alt="" class="w-100">
                            <div class="tech-list-text">服務普惠</div>
                        </div>
                        <div class="col-12 col-sm-6 col-xl-3 order-3 order-xl-2 tech-list even">
                            <img src="../../assets/images/Pink1.png" alt="" class="w-100">
                            <div class="tech-list-text">服務普惠</div>
                        </div>
                        <div class="col-12 col-sm-6 col-xl-3 order-2 order-xl-3 tech-list">
                            <img src="../../assets/images/blue.png" alt="" class="w-100">
                            <div class="tech-list-text">服務普惠</div>
                        </div>
                        <div class="col-12 col-sm-6 col-xl-3 order-4 order-xl-4 tech-list even">
                            <img src="../../assets/images/Orange1.png" alt="" class="w-100">
                            <div class="tech-list-text">服務普惠</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
@import '../../assets/all.scss';
    .tech {
        min-height: 100vh;
        background-image: url('../../assets/images/u44.png');

        .tech-title-bg {
            position: absolute;
            z-index: 0;
            width: 100%;
            height: 400px;
            background-image: url('../../assets/images/u45.svg');
        }

        .tech-title {
            font-size: 36px;
            &:hover {
                filter: drop-shadow(5px 5px 5px #000);
                color: $dblue;
            }
        }

        .tech-list {
            position: relative;
            display: flex;
            justify-content: center;
            height: 600px;

            .tech-list-text {
                position: absolute;
                bottom: 130px;
            }

            &.even {
                height: 500px;
            }

            .tech-list-text {
                color: #fff;
                font-size: 32px;
            }
        }
    }
</style>
