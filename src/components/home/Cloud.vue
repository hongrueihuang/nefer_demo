<template>
    <section ref="cloud" class="cloud bg-cover py-10 d-flex align-items-center">
        <div class="cloud-mask"></div>
        <div class="container text-warning">
            <!-- Cloud Title -->
            <div class="row justify-content-center mb-8 mb-lg-15">
                <div class="col-12 col-lg-6">
                    <h2 class="d-flex flex-column cloud-title align-items-center py-5 font-weight-bold">
                        <span class="mb-5">雲端主機監控</span>
                        <span>Cloud host monitoring</span>
                    </h2>
                </div>
            </div>
            <!-- Cloud List -->
            <div class="row mb-5 mb-lg-20">
                <div class="col-12 col-lg-11">
                    <p class="cloud-list-item d-flex flex-column align-items-center py-5 text-center">
                        <span class="mb-5">無論是哪種網路裝置、伺服器、儲存和無線裝置位於雲端或是內部網路中</span>
                        <span>可以觀察上線/離線狀態和效能資訊一目了然，擴展您的管理工具組</span>
                    </p>
                </div>
            </div>
            <div class="row mb-5 mb-lg-20 flex-row-reverse">
                <div class="col-12 col-lg-10">
                    <p class="cloud-list-item d-flex flex-column align-items-center py-5 text-center">
                        <span class="mb-5">網路傳輸流量，應用程式，虛擬作業環境和裝置配置加入主動監控工具，</span>
                        <span>全部在同一個直覺式操作的網路介面中執行</span>
                    </p>
                </div>
                <div class="col-lg-2 d-none d-lg-flex align-items-center justify-content-center">
                    <img src="../../assets/images/u43.png" class="cloud-list-icon" alt="">
                </div>
            </div>
            <div class="row mb-5 mb-lg-20">
                <div class="col-12 col-lg-11">
                    <p class="cloud-list-item d-flex flex-column align-items-center py-5 text-center">
                        <span class="mb-5">我們的監控提供專業架構意見，協助使用者微調架構減輕機器成本費用</span>
                        <span>與智能B2B後台監控</span>
                    </p>
                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
@import '../../assets/all.scss';
    .cloud {
        min-height: 100vh;
        background-image: url('../../assets/images/u37.svg');
        position: relative;

        .cloud-mask {
            position: absolute;
            top: 0;
            right: 0;
            bottom: 0;
            left: 0;
            background-color: rgba(256, 256, 256, .23);
        }

        .cloud-title {
            color: $warning;
            border: 2px solid $warning;
            background-color: $transparent;
            font-size: 36px;
            transition: all .15s;

            &:hover {
                background-color: #015478;
            }

            @include mobile {
                font-size: 28px;
            }

            @include mobile-sm {
                font-size: 24px;
            }
        }

        .cloud-list-item {
            border: 2px solid $warning;
            font-size: 24px;
            transition: all .15s;

            &:hover {
                box-shadow: 1px 1px 5px 5px #aaa inset;
                letter-spacing: 1px;
            }

            @include mobile {
                font-size: 20px;
            }

            @include mobile-sm {
                font-size: 16px;
            }
        }

        .cloud-list-icon {
            height: 111px;
        }
    }
</style>
