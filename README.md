<!doctype html>
<html lang="ko">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>영화 산책</title>

    <!-- Bootstrap CDN -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">   
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.3/font/bootstrap-icons.css">

    <!-- 스타일시트 -->
    <link rel="stylesheet" href="movie.css">

    <!--폰트-->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Gowun+Batang&display=swap" rel="stylesheet">
     </head>

  <body>
    <nav class="navbar navbar-expand-lg bg-light navbar-light fixed-top bg-body-tertiary">
        <div class="container">
          <a class="navbar-brand gugi-font " href="#home">
            <img src="images/영화산책로고01.png" alt="로고" class="navbar-brand">영화산책</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" 
                  data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" 
                aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ms-auto my-2">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#home">홈</a>
              </li>
              <li class="nav-item"><a class="nav-link" href="#service">영화산책</a></li>
              <li class="nav-item"><a class="nav-link" href="#movie_introduction">추천영화</a></li>
              <li class="nav-item"><a class="nav-link" href="#portfolio">이 달의 영화</a></li>
              
              <li class="nav-item"><a class="nav-link" href="#new">영화티저</a></li>
            </ul>
          </div>
        </div>
    </nav>
      <!-- 네비게이션 영역 끝 -->

          <!--헤더영역시작-->
    <header id="home" class="d-flex flex-column justify-content-center align-items-left text-white vh-100 ">
        <h1 id="hometitle" class="display-3 fw-bold mb-5">겨울을 채우는<br> 독립영화(獨立映畵)</h1>
        <h4 id="hometitle" class="fs-2 mb-3  ml-100">2024년 12월</h4>
        <p id="hometitle" class="lead mb-5 text-muted">이번 겨울, 주목할만한 독립영화를 소개합니다.</p>
    </header>
    <!--헤더영역 끝-->

    <!--서비스소개영역시작-->
    <section class="container py-5" id="service">
      <div class="text-center py-5">
          <h2 class="fw-bold text-black">영화산책</h2>
          <p class="lead text-muted">산책로를 거닐듯, 편안한 영화 감상을 위해 영화를 공유합니다. </p>
      </div>
      <div class="row justify-content-center align-items-center mb-1">
          <div class="d-flex flex-column justify-content-center align-items-left  vh-50">
              <img src="images/발자국.jpg" alt="웹툰소개" 
                  class="img-fluid">
          </div>
          <div>
              <h4 class="fw-bold mt-5 text-muted text-center">영화를 산책하다</h4>
              <p class="text-white text-muted text-center  mt-3">영화를 보는 것은 사유의 시작이 되는 행위이다.<br>영화는 하나의 세계를 품고있다. 영화를 제작하는 사람들은 그들만의 의도를 전달하고자 노력한다.<br>영화를 보는 사람들은 그 모든 의도를 이해하려고 하지 않아도 된다. 그저 그 자리를 지키는 것 만으로도 영화 산업을 지키는 일이다. 마치 산책처럼 말이다.</p>
          </div>
      </div>
  </section>
  <!--소개영역끝-->

  <!--영화소개시작-->
  <section class="container py-5 overflow-hidden" id="movie_introduction">
    <div class="text-center py-5">
        <h2 class="fw-bold mb-3 text-muted highlight">ㅤ지금 주목받는 영화 TOP3ㅤ</h2>
    </div>
    <div class="row mb-5 g-4">
        <div class="col-md-12">
            <div class="card-hover shadow rounded p-4 mb-4">
                <div class="service-card position-relative ">
                    <img src="images/헤더1.png" alt="그 겨울, 나는" class="img-fluid w-100">
                    <div class="service-info position-absolute top-50 start-50 translate-middle-y" style="right: 0;">
                        <h3 id="schooltitle" class="fw-bold text-black">그 겨울, 나는</h3>
                        <h5 id="schooltitle" class="text-muted">오성호 감독</h5>
                    </div>
                    <h4 class="fw-bold mt-4 text-black">Through My Midwinter</h4>
                    <p class="text-muted">스물아홉 동갑내기 커플 '경학'과 '혜진'은 내일을 위해 뜨겁게 공부하고, 오늘을 위해 열심히 사랑한다. 하지만 혜진이 먼저 취업하게 되자 점점 서로의 내일과 오늘이 변하기 시작한다. <br>설상가상 경학이 엄마의 빚을 떠안으며 공부도 사랑도 위기를 맞게 되는데... 사랑조차 피곤했던 그 겨울, 우리는 서로에게 얼마나 솔직했을까?</p>
                </div>
            </div>
        </div>
        <div class="col-md-12">
            <div class="card1-hover shadow rounded p-4 mb-4">
                <div class="service-card position-relative text-start">
                    <img src="images/헤더2.png" alt="한국이 싫어서" class="img-fluid w-100">
                    <div class="service-info position-absolute top-50 start-0 translate-middle-y" style="right: 0;">
                        <h3 id="schooltitle" class="fw-bold text-black">ㅤ한국이 싫어서</h3>
                        <h5 id="schooltitle" class="text-muted">ㅤ장건재 감독</h5>
                    </div>
                    <h4 class="fw-bold mt-4 text-end text-black">Because I Hate Korea</h4>
                    <p class="text-muted text-end">"행복을 찾아 새롭게 시작하기로 했다" 내가 왜 한국을 떠나느냐고? 두 마디로 요약하자면 '한국이 싫어서'. 세 마디로 줄이면 '여기서는 못 살겠어서'.<br>'계나'는 지금 이 순간의 행복을 좇아 떠나기로 했다.</p>
                </div>
            </div>
        </div>
        <div class="col-md-12">
            <div class="card2-hover shadow rounded p-4 mb-4">
                <div class="service-card position-relative">
                    <img src="images/헤더3.png" alt="서비스3 이미지" class="img-fluid w-100">
                    <div class="service-info position-absolute top-50 start-50 translate-middle-y" style="right: 0;">
                        <h3 id="schooltitle" class="fw-bold text-black">로봇 드림</h3>
                        <h5 id="schooltitle" class="text-muted">파블로 베르헤르 감독</h5>
                    </div>
                    <h4 class="fw-bold mt-4 text-black">Robot Dreams</h4>
                    <p class="text-muted">맨해튼에서 외롭게 살던 도그는 TV를 보다 홀린 듯 반려 로봇을 주문하고, 그와 둘도 없는 단짝이 된다. 행복한 나날을 보내던 어느 날, 해수욕장에 놀러 간 도그와 로봇은 예기치 못한 상황에 휩쓸려 이별을 맞이한다.</p>
                </div>
            </div>
        </div>
    </div>
</section>
<!--소개끝-->

<!--명예의전당영역시작-->
<section class=" py-5" id="portfolio">
  <div class="container overflow-hidden">
      <div class="text-center text-white py-5">
          <h2 class="fw-bold mb-3 text-muted highlight">ㅤ이 달의 영화ㅤ</h2>
      </div>
      <div class="row pb-5 g-4">
          <div class="col-sm-6 col-lg-4">
              <img src="images/m1.png" alt="포트폴리오1" class="img-fluid img-thumbnail">
          </div>
          <div class="col-sm-6 col-lg-4">
              <img src="images/m2.png" alt="포트폴리오2" class="img-fluid img-thumbnail">
          </div>
          <div class="col-sm-6 col-lg-4">
              <img src="images/m3.png"  alt="포트폴리오3" class="img-fluid img-thumbnail">
          </div>
          <div class="col-sm-6 col-lg-4">
              <img src="images/m4.png" alt="포트폴리오4" class="img-fluid img-thumbnail">
          </div>
          <div class="col-sm-6 col-lg-4">
              <img src="images/m5.png" alt="포트폴리오5" class="img-fluid img-thumbnail">
          </div>
          <div class="col-sm-6 col-lg-4">
              <img src="images/m6.png" alt="포트폴리오6" class="img-fluid img-thumbnail">
          </div>
      </div>
  </div>
</section>
<!--포트폴리오영역끝-->

<!-- 신제품영역시작 -->
<section class="container overflow-hidden py-5"  id="new">
    <div class="text-center py-5">
        <h2 class="fw-bold mb-3 text-muted highlight">ㅤ영화 티저ㅤ</h2><br>
        <p class="fw mt-3 mb-3 text-muted">올 겨울 낭만적 영화에 빠져드세요.</p>
    </div>
    <div class="row pb-5 gy-4 justify-content-center">
        <div class="col-sm-6 col-lg-3 mx-auto">
            <div class="card">
                <img src="images/m01.png" class="card-img-top" alt="블로그 이미지1" >
                <div class="card-body text-center">
                    <h3 class="card-title fs-4 text-black">close your eyes</h3>
                    <p class="card-text text-muted">노년의 영화 감독 미겔은 22년 전 실종된 배우 훌리오 아레나스에 대해 증언하게 된다. 그에 대해 온갖 추측만이 무성한 가운데, 미겔은 훌리오의 흔적을 찾으며 잊고 지내던 자신의 과거와 조우한다.</p>
                    <a href="https://youtu.be/JUTRMBR_xpE?si=x7cM9kzyh3eithr6" class="btn btn-primary btn-sm">티저 보기</a>
                </div>
            </div>
        </div>
        <div class="col-sm-6 col-lg-3 mx-auto">
            <div class="card">
                <img src="images/m02.png" class="card-img-top" alt="블로그 이미지2">
                <div class="card-body text-center">
                    <h3 class="card-title fs-4 text-black"> The Room Next Door</h3>
                    <p class="card-text text-muted">1980년대 뉴욕에서 함께 일했던 잉그리드와 마사
                        오랜 시간 연락이 닿지 않았던 두 사람이 그때와 달라진 모습으로 다시 만나
                        사랑과 우정, 삶과 죽음에 대한 진실하고 내밀한 이야기를 나눈다.</p>
                    <a href="https://youtu.be/lcp__Vek4gQ?si=3RO5WVNgmGjLclcd" class="btn btn-primary btn-sm">티저 보기</a>
                </div>
            </div>
        </div>
        <div class="col-sm-6 col-lg-3 mx-auto">
            <div class="card">
                <img src="images/m03.png" class="card-img-top" alt="블로그 이미지3">
                <div class="card-body text-center">
                    <h3 class="card-title fs-4 text-black">Carol</h3>
                    <p class="card-text text-muted">일생에 단 한 번, 모든 것을 내던질 수 있는 사랑을 만난 두 여인의 이야기를 그린 감성 드라마로 케이트 블란쳇과 루니 마라가 대담하고도 아름다운 로맨스를 <br>그려낸다.</p>
                    <a href="https://youtu.be/EH3zcuRQXNo?si=v2ho1KUU6_YbF2fl" class="btn btn-primary btn-sm">티저 보기</a>
                </div>
            </div>
        </div>
    </div>
</section>
 <!-- 신제품섹션끝 -->

 <!--푸터 영역시작-->
<footer class="bg-dark text-white py-4">
    <div class="container">
        <div class="row">
            <div class="col-md-4 mb-3">
                <h5>영화산책</h5>
                <p>서울특별시 노원구 화랑로 621</p>
                <p>전화: 02-970-5114</p>
                <p>공식 홈페이지: https://www.koreafilm.or.kr<p>
            </div>
            <div class="col-md-4 mb-3">
                <h5>소셜 미디어</h5>
                <a href="https://www.facebook.com/indieground.kr" class="text-white me-2">
                    <i class="bi bi-facebook"></i> Facebook
                </a>
                <a href="https://x.com/kofic_kr" class="text-white me-2">
                    <i class="bi bi-twitter"></i> Twitter
                </a>
                <a href="https://www.instagram.com/indieground.kr/" class="text-white">
                    <i class="bi bi-instagram"></i> Instagram
                </a>
            </div>
            <div class="col-md-4 mb-3">
                <h5>월간 영화산책 이메일 매거진</h5>
                <form>
                    <div class="mb-3">
                        <label for="email" class="form-label">이메일 주소</label>
                        <input type="email" class="form-control" id="email" placeholder="이메일을 입력하세요">
                    </div>
                    <button type="submit" class="btn btn-warning">구독하기</button>
                </form>
            </div>
        </div>
        <div class="text-center pt-3 border-top border-secondary">
            <p>&copy; 영화산책. All rights reserved.</p>
        </div>
    </div>
</footer>
<!--푸터 영역 끝-->

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>  
  </body>
</html>
