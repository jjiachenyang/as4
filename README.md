<html lang="zh-Hant">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>地下到舞台的旅程</title>

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Noto+Serif+TC:wght@400;600&display=swap" rel="stylesheet">

  <style>
    /* Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    html, body {
      width: 100%;
      height: 100%;
      font-family: "Noto Serif TC", serif;
      color: white;
      overflow-x: hidden;
      background-color: black;
    }

    section {
      height: 300vh;
      position: relative;
      width: 100vw;
    }

    .sticky {
      position: sticky;
      top: 0;
      width: 100vw;
      height: 100vh;
      background-position: center;
      background-size: cover;
      background-repeat: no-repeat;
      display: block;
    }

    .text-block {
      position: absolute;
      right: 5%;
      top: 30%;
      width: 32%;
      background: rgba(0,0,0,0.55);
      color: white;
      padding: 24px;
      border-radius: 12px;
      line-height: 1.9;
      font-size: 1.05rem;
    }

    /* Banner */
    .banner {
      position: relative;
      width: 100vw;
      height: 100vh;
      background: url("https://raw.githubusercontent.com/jjiachenyang/as4/main/image/photo5.jpg") center/cover no-repeat;
      display: block;
    }

    .banner h1 {
      position: absolute;
      bottom: 40px;
      right: 50px;
      font-size: 1.8rem;
      background: rgba(0,0,0,0.5);
      padding: 10px 20px;
      border-radius: 8px;
      letter-spacing: 2px;
      font-weight: 500;
    }

    /* 結尾說明 */
    .ending-section {
      height: 100vh;
      width: 100vw;
      background-color: #4a4a4a; /* 鐵灰色 */
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 40px;
    }

    .ending-section .content h1 {
      font-size: 2rem;
      margin-bottom: 20px;
    }

    .ending-section .content h2 {
      font-size: 1.5rem;
      margin-top: 20px;
      margin-bottom: 10px;
    }

    .ending-section .content p {
      font-size: 1.05rem;
      line-height: 1.8;
      margin-bottom: 15px;
    }

    .ending-section .content strong {
      color: inherit;
      text-decoration: none;
      cursor: default;
    }
  </style>
</head>
<body>

  <!-- Banner -->
  <div class="banner">
    <h1>地下到舞台的旅程</h1>
  </div>

  <!-- Section 1 -->
  <section id="section1">
    <div class="sticky" style="background-image: url('https://raw.githubusercontent.com/jjiachenyang/as4/main/image/photo1.jpg');"></div>
    <div class="text-block">
      <p>在一棟老公寓的地下室裡，四個年輕人每天放學後就聚在一起排練。牆壁貼滿破舊的海報，地上堆著打開的泡麵與纏滿膠帶的線材。外頭的世界與他們無關——在這個僅容身的空間裡，他們相信，只要有音樂，就還能呼吸。</p>
      <p>「Echo Drift」這個名字，來自一次失敗的錄音。那段模糊卻真實的迴聲，像極了他們的狀態——不完美、卻真切。於是他們決定，就從這裡開始。</p>
    </div>
  </section>

  <!-- Section 2 -->
  <section id="section2">
    <div class="sticky" style="background-image: url('https://raw.githubusercontent.com/jjiachenyang/as4/main/image/photo2.jpg');"></div>
    <div class="text-block">
      <p>他們開始在各地的Live House與小型音樂節演出。觀眾有時只有十幾個人，有時更多，但他們總是盡全力唱到最後一刻。樂手的手指被吉他弦磨破，主唱的聲音沙啞，卻沒有人想停下來。</p>
      <p>每次演出結束，他們都把微薄的報酬存進同一個鐵盒裡。那是他們的小小夢想基金——總有一天，要錄一張屬於自己的專輯。</p>
    </div>
  </section>

  <!-- Section 3 -->
  <section id="section3">
    <div class="sticky" style="background-image: url('https://raw.githubusercontent.com/jjiachenyang/as4/main/image/photo3.jpg');"></div>
    <div class="text-block">
      <p>經過無數個深夜的演出與練習，他們終於靠著積蓄與支持者的小額贊助，籌到了錄音的資金。那一天，他們帶著興奮與不安走進錄音室。</p>
      <p>玻璃窗的另一側，他們錄製著第一張EP——每一次呼吸、每一個節拍，都是夢想的具體形狀。錄音師的指示聲、樂手的專注表情、紅色錄音燈的閃爍，組成了他們生命中最純粹的時光。</p>
    </div>
  </section>

  <!-- Section 4 -->
  <section id="section4">
    <div class="sticky" style="background-image: url('https://raw.githubusercontent.com/jjiachenyang/as4/main/image/photo4.jpg');"></div>
    <div class="text-block">
      <p>夏日的夜空下，他們終於站上了夢想的舞台。燈光閃爍、人潮湧動，音樂在空氣中迴盪。主唱閉上眼，感受著從觀眾席傳來的回聲——那不是幻覺，而是真實的迴響。</p>
      <p>他們知道，這一刻，是從地下室一路走來最燦爛的答案。而舞台上那道光，正照亮著他們曾經灰暗的青春。</p>
    </div>
  </section>

  <!-- 結尾說明 -->
  <section class="ending-section">
    <div class="content">
      <h1>圖片生成與故事設計過程</h1>
      <p>本網頁先透過 <strong>ChatGPT</strong> 生成故事大綱與章節，向 ChatGPT 提出圖片設計要求，請它翻成英文指令，再到 <strong>nano banana</strong> 上生成圖片。</p>
      <h2>故事大綱（第一道指令）</h2>
      <p>我想設計一個故事，關於一個地下樂團（名字隨便你取）從默默無名因為努力練團最後登上音樂祭圓夢的故事，可以先幫我生成一個四段文字構成的故事嗎（待會再以四段故事設計圖片）</p>
      <h2>圖片設計（第一道指令）</h2>
      <p>我要用 <strong>nano banana</strong> 生成四張圖片，我希望風格是像日本漫畫一樣，線條感明顯、有張力。</p>
    </div>
  </section>

</body>
</html>
