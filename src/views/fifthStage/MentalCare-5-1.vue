<template>
    <div>
      <main>
        <!-- 麵包屑 -->
        <section class="container" data-aos="fade-down"  data-aos-delay="500">
          <nav style="--bs-breadcrumb-divider: '>'" aria-label="breadcrumb" class="badge">
            <ol class="breadcrumb">
                <li class="breadcrumb-item"><a href="/">首頁</a></li>
                <li class="breadcrumb-item" aria-current="page"><a href="#">我意外懷孕了</a></li>
                <li class="breadcrumb-item" aria-current="page"><a href="#">我想要生下來</a></li>
                <li class="breadcrumb-item" aria-current="page"><a href="#">身心照顧</a></li>
                <li class="breadcrumb-item active" aria-current="page"><a href="#">面對第一次懷孕</a></li>
            </ol>
          </nav>
        </section>

        <!-- 主要區塊 -->
        <section class="container step-rwd">
          <div class="step">
            <!-- 裝飾用圖片 -->
            <img class="step-circle" src="../../assets/image/front/image_circleword.svg">
            <img class="image1" src="../../assets/image/front/page02_image1.svg">
            <img class="image2" src="../../assets/image/front/page02_image2.svg">
            <img class="image3" src="../../assets/image/front/page02_image3.svg">
            <!-- 結束 -->
            <div class="text-box">
              <p class="step-text" data-aos="fade-up">ANSEWR</p>
              <h2 class="step-title" data-aos="fade-up" >選擇・答案</h2>
              <img class="title-line" src="../../assets/image/front/choose_title_line.svg" data-aos="fade-up" >
              <p class="step-sologan" data-aos="fade-up">為自己所想，為自己所選。</p>
            </div>
            <div class="container step-box">
              <div class="select-box-inner">
                <div class="box-title" data-aos="fade-up">
                  <h2>｜面對第一次懷孕｜</h2>
                </div>
                <div class="select-menu">
                  <img class="mb-60" data-aos="fade-up" src='../../assets/image/front/page02_pic3.jpg'>
                  <hr data-aos="fade-up">
                    <!-- 選項開始 -->
                    <ul class="select-item container-inner mt-60">
                      <li data-aos="fade-up">
                        <h3>心情、情緒</h3>
                        <p>有了寶寶，生活中不再只有自己，是甜蜜也是沈重的負荷，你的理想、你的生涯規劃也都因此需要調整，也許轉個彎，也許延長路程，甚至必須改道，必須思考清楚，該如何抉擇才能兼顧你與孩子的未來。</p>
                      </li>
                    </ul>
                    <!-- 選項結束 -->
                    <hr data-aos="fade-up">
                    <div data-aos="fade-up">
                      <a class="goBack" onclick="history.back()" value="回到上一頁">回到上一頁</a>
                      <a class="goBack" href="#">返回首頁</a>
                    </div>
                </div>
              </div>
            </div>
          </div>
        </section>
        <Circle></Circle>
      </main>
    </div>
</template>

<script>
export default {
  data () {
    return {
      data: [

      ]
    }
  }
}
</script>
