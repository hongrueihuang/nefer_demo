<template>
    <section ref="info" class="info bg-cover d-flex align-items-center">
        <div class="info-mask"></div>
        <div class="container py-20">
            <ul class="row text-dblue info-list">
                <li class="col-12 mb-10">
                    <h3 class="info-list-title mb-3">源頭：減少客戶求助，明確服務來源及訴求</h3>
                    <p class="info-list-content">以海量客戶服務歷史數據為基礎，通過監控工具分析洞察客戶主機服務狀態，並定位用戶主要服務訴求，源頭實現了客戶的體驗評估與優化，用戶端的主動服務和用戶教育，以及服務端的整體服務規劃，從根本上減少了用戶在各種產品使用場景下的障礙。</p>
                    <div class="d-none d-md-flex justify-content-center">
                        <div class="info-list-img-wrap">
                            <img src="../../assets/images/u61.png" class="info-list-img" alt="">
                        </div>
                    </div>
                </li>
                <li class="col-12 mb-10">
                    <h3 class="info-list-title mb-3">端：結合大數據及運營手段，為客戶提供千人千面的個性化服務</h3>
                    <p class="info-list-content">數字生活無處不在隨處可及，用戶接觸服務的渠道和方式凸顯垂直的態勢，基於數據分析的服務“端”已經超越了傳統的服務渠道定位，需要堅持更加精細的佈局。通過分析用戶訴求，端可利用線上諮詢為用戶提供人性化，個性化的服務體驗，將問題識別，問題自助解決，分流人工等服務流程全部打通，提供7x24不間斷的服務。為實現服務對用戶觸手可及，端需基於用戶習慣和使用場景持續擴展服務端類型的能力（如對雲端主機等）。目前大多數核心的服務端為在線端。</p>
                    <div class="d-none d-md-flex justify-content-center">
                        <div class="info-list-img-wrap">
                            <img src="../../assets/images/u60.png" class="info-list-img" alt="">
                        </div>
                    </div>
                </li>
                <li class="col-12 mb-10">
                    <h3 class="info-list-title mb-3">人工服務：靈活調度擴大資源最大化，同時提升人效</h3>
                    <p class="info-list-content">我們通過對人工服務資源進行科學，有效的管控，提升了人工服務的承接能力和服務彈性，讓客戶能夠得到最高快速，便利的服務。總體而言，在智能化輔助工具的幫助下，客服人員的工作績效及客戶令人滿意得到了雙重提升。</p>
                    <div class="d-none d-md-flex justify-content-center">
                        <div class="info-list-img-wrap">
                            <img src="../../assets/images/u59.png" class="info-list-img" alt="">
                        </div>
                    </div>
                </li>
            </ul>
        </div>
    </section>
</template>

<style lang="scss" scoped>
@import '../../assets/all.scss';
    .info {
        min-height: 100vh;
        position: relative;
        background-image: url('../../assets/images/u55.jpg');

        .info-mask {
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: rgba(256, 256, 256, .5);
        }

        .info-list {
            list-style: disc;

            .info-list-title {
                font-size: 28px;
                font-weight: bold;
            }

            .info-list-content {
                font-size: 22px;
            }

            .info-list-img-wrap {
                width: 200px;
                overflow: hidden;

                &:hover {
                    .info-list-img {
                        transform: translateX(0);
                    }
                }
            }

            .info-list-img {
                height: 150px;
                transform: translateX(-150px);
                transition: all .5s ease-in-out;
            }
        }
    }
</style>
