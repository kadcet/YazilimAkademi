<script setup></script>

<template>
  <div class="header">
    <div class="container mt-2">
      <nav class="navbar navbar-expand-lg navbar-light">
        <div class="container-fluid">
          <img
            src="/src/assets/img/logo.png"
            style="height: 36px"
            alt="idealwork logo"
            class="me-4"
          />

          <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarSupportedContent"
            aria-controls="navbarSupportedContent"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item me-2">
                <a class="nav-link active" aria-current="page" href="#">Kurslar</a>
              </li>

              <li class="nav-item me-2">
                <a class="nav-link active" aria-current="page" href="#">Video Galeri</a>
              </li>
              <li class="nav-item me-2">
                <a class="nav-link active" aria-current="page" href="#">Hakkımızda</a>
              </li>
              <li class="nav-item me-2">
                <a class="nav-link active" aria-current="page" href="#">Bize Ulaşın</a>
              </li>
            </ul>
            <form class="d-flex">
              <div class="idealButton me-3">
                <span>Online Kampüs</span>
              </div>
              <div class="idealButton idealButtonSignUp">
                <span>Yeni Kayıt</span>
              </div>
            </form>
          </div>
        </div>
      </nav>
    </div>
  </div>

  <div style="background-color: #052044">
    <div
      class="image-cover hero_banner shadow"
      style="background: url(/src/assets/img/banner-2.jpg) no-repeat"
    ></div>
  </div>

  <div class="p-0 trips_top">
    <div class="container">
      <div class="trips_wrap">
        <div class="row m-0">
          <div class="col-lg-4 col-md-4 col-sm-12">
            <div class="trips">
              <div class="trips_icons">
                <i class="bi bi-camera-reels"></i>
              </div>
              <div class="trips_detail">
                <h4>100,000 online courses</h4>
                <p>Nor again is there anyone who loves or pursues or desires</p>
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-md-4 col-sm-12">
            <div class="trips">
              <div class="trips_icons">
                <i class="bi bi-patch-check"></i>
              </div>
              <div class="trips_detail">
                <h4>100,000 online courses</h4>
                <p>Nor again is there anyone who loves or pursues or desires</p>
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-md-4 col-sm-12">
            <div class="trips">
              <div class="trips_icons">
                <i class="bi bi-infinity"></i>
              </div>
              <div class="trips_detail">
                <h4>100,000 online courses</h4>
                <p>Nor again is there anyone who loves or pursues or desires</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <section class="min-sec">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-lg-12 col-md-12 mb-3">
          <div class="sec-heading2">
            <div class="sec-left">
              <h3>Featured Courses</h3>
            </div>
            <div class="sec-right">
              <ul class="nav nav-tabs side-cates">
                <li class="nav-item">
                  <a class="nav-link active" href="javascript:void(0);">Design</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="javascript:void(0);">Development</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="javascript:void(0);">Business</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="javascript:void(0);">Accounting</a>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-lg-12 col-md-12 col-sm-12 p-0">
          <div class="uk-slider-container-offset" uk-slider>
            <div class="uk-position-relative uk-visible-toggle uk-light" tabindex="-1">
              <ul class="uk-slider-items uk-child-width-1-3@s uk-grid">
                <li>
                  <div class="uk-card uk-card-default">
                    <div class="uk-card-media-top">
                      <img src="@/assets/img/co-1.jpg" width="400" height="400" alt="" />
                    </div>
                    <div class="uk-card-body">
                      <h3 class="uk-card-title cardTitle">ASP .Net Core Web API Kursu</h3>

                      <div class="d-flex flex-row justify-content-between">
                        <div>
                          <i class="bi bi-eye"></i><span class="ms-1 iconText">158 İnceleme</span>
                        </div>
                        <div>
                          <i class="bi bi-clock"></i><span class="ms-1 iconText">240 Saat</span>
                        </div>
                        <div>
                          <i class="bi bi-star" style="color: #ff9b20"></i
                          ><span class="ms-1 iconText">4.5 Puanlı Eğitim</span>
                        </div>
                      </div>

                      <p>
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
                        tempor incididunt.
                      </p>
                    </div>
                    <div class="uk-card-footer p-2">
                      <div class="d-flex align-items-center justify-content-between">
                        <span>10 Nisan 2024 Kurs Başlangıcı </span>
                        <div class="idealButton">
                          <span>Eğitime Katıl</span>
                        </div>
                      </div>
                    </div>
                  </div>
                </li>
                <li>
                  <div class="uk-card uk-card-default">
                    <div class="uk-card-media-top">
                      <img src="@/assets/img/co-2.jpg" width="400" height="400" alt="" />
                    </div>
                    <div class="uk-card-body">
                      <h3 class="uk-card-title cardTitle">FrontEnd</h3>
                      <div class="d-flex flex-row justify-content-between">
                        <div>
                          <i class="bi bi-eye"></i><span class="ms-1 iconText">100 İnceleme</span>
                        </div>
                        <div>
                          <i class="bi bi-clock"></i><span class="ms-1 iconText">500 Saat</span>
                        </div>
                        <div>
                          <i class="bi bi-star" style="color: #ff9b20"></i
                          ><span class="ms-1 iconText">5.0 Puanlı Eğitim</span>
                        </div>
                      </div>
                      <p>
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
                        tempor incididunt.
                      </p>
                    </div>
                    <div class="uk-card-footer p-2">
                      <div class="d-flex align-items-center justify-content-between">
                        <span>10 Nisan 2024 Kurs Başlangıcı </span>
                        <div class="idealButton">
                          <span>Eğitime Katıl</span>
                        </div>
                      </div>
                    </div>
                  </div>
                </li>
                <li>
                  <div class="uk-card uk-card-default">
                    <div class="uk-card-media-top">
                      <img src="@/assets/img/co-3.jpg" width="400" height="400" alt="" />
                    </div>
                    <div class="uk-card-body">
                      <h3 class="uk-card-title cardTitle">BackEnd</h3>
                      <div class="d-flex flex-row justify-content-between">
                        <div>
                          <i class="bi bi-eye"></i><span class="ms-1 iconText">200 İnceleme</span>
                        </div>
                        <div>
                          <i class="bi bi-clock"></i><span class="ms-1 iconText">600 Saat</span>
                        </div>
                        <div>
                          <i class="bi bi-star" style="color: #ff9b20"></i
                          ><span class="ms-1 iconText">5.5 Puanlı Eğitim</span>
                        </div>
                      </div>
                      <p>
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
                        tempor incididunt.
                      </p>
                    </div>
                    <div class="uk-card-footer p-2">
                      <div class="d-flex align-items-center justify-content-between">
                        <span>10 Nisan 2024 Kurs Başlangıcı </span>
                        <div class="idealButton">
                          <span>Eğitime Katıl</span>
                        </div>
                      </div>
                    </div>
                  </div>
                </li>
                <li>
                  <div class="uk-card uk-card-default">
                    <div class="uk-card-media-top">
                      <img src="@/assets/img/co-4.jpg" width="400" height="400" alt="" />
                    </div>
                    <div class="uk-card-body">
                      <h3 class="uk-card-title cardTitle">Mentorlük</h3>
                      <div class="d-flex flex-row justify-content-between">
                        <div>
                          <i class="bi bi-eye"></i><span class="ms-1 iconText">100 İnceleme</span>
                        </div>
                        <div>
                          <i class="bi bi-clock"></i><span class="ms-1 iconText">1 Yıl</span>
                        </div>
                        <div>
                          <i class="bi bi-star" style="color: #ff9b20"></i
                          ><span class="ms-1 iconText">5.1 Puanlı Eğitim</span>
                        </div>
                      </div>
                      <p>
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
                        tempor incididunt.
                      </p>
                    </div>
                    <div class="uk-card-footer p-2">
                      <div class="d-flex align-items-center justify-content-between">
                        <span>10 Nisan 2024 Kurs Başlangıcı </span>
                        <div class="idealButton">
                          <span>Eğitime Katıl</span>
                        </div>
                      </div>
                    </div>
                  </div>
                </li>
                <li>
                  <div class="uk-card uk-card-default">
                    <div class="uk-card-media-top">
                      <img src="@/assets/img/co-5.jpg" width="400" height="400" alt="" />
                    </div>
                    <div class="uk-card-body">
                      <h3 class="uk-card-title cardTitle">Yazılım İngilizcesi</h3>
                      <div class="d-flex flex-row justify-content-between">
                        <div>
                          <i class="bi bi-eye"></i><span class="ms-1 iconText">350 İnceleme</span>
                        </div>
                        <div>
                          <i class="bi bi-clock"></i><span class="ms-1 iconText">50 Saat</span>
                        </div>
                        <div>
                          <i class="bi bi-star" style="color: #ff9b20"></i
                          ><span class="ms-1 iconText">5.3 Puanlı Eğitim</span>
                        </div>
                      </div>
                      <p>
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
                        tempor incididunt.
                      </p>
                    </div>
                    <div class="uk-card-footer p-2">
                      <div class="d-flex align-items-center justify-content-between">
                        <span>10 Nisan 2024 Kurs Başlangıcı </span>
                        <div class="idealButton">
                          <span>Eğitime Katıl</span>
                        </div>
                      </div>
                    </div>
                  </div>
                </li>
              </ul>

              <a
                class="uk-position-center-left uk-position-small uk-hidden-hover"
                style="border-radius: 99px; background-color: #fc6e51; opacity: 0.5"
                href
                uk-slidenav-previous
                uk-slider-item="previous"
              ></a>
              <a
                class="uk-position-center-right uk-position-small uk-hidden-hover"
                style="border-radius: 99px; background-color: #fc6e51; opacity: 0.5"
                href
                uk-slidenav-next
                uk-slider-item="next"
              ></a>
            </div>

            <ul class="uk-slider-nav uk-dotnav uk-flex-center uk-margin"></ul>
          </div>
        </div>
      </div>
    </div>
  </section>

  <div class="container-fluid py-5" style="background-color: #f4f8fa">
    <div class="row">
      <div class="col-12">
        <div class="container">
          <div class="row mb-2">
            <div class="col-12">
              <h3 class="m-0 py-1" style="font-size: 18px; font-weight: 700">
                Sıkca Sorulan Sorular
              </h3>
            </div>
          </div>

          <div class="row">
            <div class="col-4">
              <div
                class="container"
                style="
                  border-radius: 10px;
                  box-shadow: rgba(0, 0, 0, 0.16) 0px 1px 4px;
                  background-color: white;
                "
              >
                <div class="row">
                  <div class="col-12 p-0">
                    <img class="imgTopRadius" src="@/assets/img/res1.jpg" />
                  </div>
                </div>

                <div class="row">
                  <div class="col-12">
                    <h3 class="cardTitle mt-3 ms-2">
                      The National Minimum Wage Is An Important Part
                    </h3>
                  </div>
                </div>

                <div class="row pb-2 border border-bottom pt-2">
                  <div class="col-2">
                    <img class="ms-2 rounded-5" src="@/assets/img/avatar1.jpg" />
                  </div>
                  <div class="col-10 d-flex align-items-center">
                    <span style="font-size: 14px; font-weight: 400; color: #7182a7"
                      >Adam Willsone</span
                    >
                  </div>
                </div>
              </div>
            </div>

            <div class="col-4">
              <div
                class="container"
                style="
                  border-radius: 10px;
                  box-shadow: rgba(0, 0, 0, 0.16) 0px 1px 4px;
                  background-color: white;
                "
              >
                <div class="row">
                  <div class="col-12 p-0">
                    <img class="imgTopRadius" src="@/assets/img/res2.jpg" />
                  </div>
                </div>

                <div class="row">
                  <div class="col-12">
                    <h3 class="cardTitle mt-3 ms-2">
                      The National Minimum Wage Is An Important Part
                    </h3>
                  </div>
                </div>

                <div class="row pb-2 border border-bottom pt-2">
                  <div class="col-2">
                    <img class="ms-2 rounded-5" src="@/assets/img/avatar1.jpg" />
                  </div>
                  <div class="col-10 d-flex align-items-center">
                    <span style="font-size: 14px; font-weight: 400; color: #7182a7"
                      >Adam Willsone</span
                    >
                  </div>
                </div>
              </div>
            </div>
            <div class="col-4">
              <div
                class="container"
                style="
                  border-radius: 10px;
                  box-shadow: rgba(0, 0, 0, 0.16) 0px 1px 4px;
                  background-color: white;
                "
              >
                <div class="row">
                  <div class="col-12 p-0">
                    <img class="imgTopRadius" src="@/assets/img/res3.jpg" />
                  </div>
                </div>

                <div class="row">
                  <div class="col-12">
                    <h3 class="cardTitle mt-3 ms-2">
                      The National Minimum Wage Is An Important Part
                    </h3>
                  </div>
                </div>

                <div class="row pb-2 border border-bottom pt-2">
                  <div class="col-2">
                    <img class="ms-2 rounded-5" src="@/assets/img/avatar1.jpg" />
                  </div>
                  <div class="col-10 d-flex align-items-center">
                    <span style="font-size: 14px; font-weight: 400; color: #7182a7"
                      >Adam Willsone</span
                    >
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="container-fluid mb-5 mt-5 py-5 confluid">
    <div class="confluid-opacity"></div>

    <div
      class="d-flex justify-content-center align-items-center flex-column"
      style="position: relative"
    >
      <h2 class="mb-0" style="color: #fff; font-weight: 600; font-size: 30px; line-height: 36px">
        Join Thousand Of Happy Students!
      </h2>
      <p style="color: #fff">Subscribe our newsletter & get latest news and updation!</p>

      <div class="d-flex pt-2 pb-2 ps-2 pe-2" style="background-color: #fff; border-radius: 5px">
        <input
          type="email"
          placeholder="E Mail Adresi Yazın"
          required="true"
          style="padding: 20px 20px 18px; border: 0; outline: none"
        />
        <input
          type="submit"
          value="Get Started"
          style="padding: 14px 25px 14px; background-color: #fc6e51; border: 0; border-radius: 5px"
        />
      </div>
    </div>
  </div>

  <div class="container">
    <div class="row justify-content-between">
      <div class="col-sm-4 col-md-3 col-lg-3 col-12">
        <img src="./assets/img/logo.png" class="img-fluid" style="height: 36px" alt="" />
        <p class="footer-p">Güneştepe Mahallesi Reyyan Sokak BURSA</p>
        <P class="footer-p">+ 0244 444 44 44</P>
        <P class="footer-p">uergun@gmail.com</P>
      </div>
      <div class="col-sm-4 col-md-3 col-lg-2 col-12">
        Navigations
        <ul class="footer-p p-0 mt-3" style="list-style-type: none">
          <li class="mb-2">Hakkımızda</li>
          <li class="mb-2">SSS</li>
          <li class="mb-2">Referanslarımız</li>
          <li class="mb-2">İletişim</li>
          <li>Blog</li>
        </ul>
      </div>
      <div class="col-sm-4 col-md-3 col-lg-2 col-12">
        New Categories
        <ul class="footer-p p-0 mt-3" style="list-style-type: none">
          <li class="mb-2">Tasarım</li>
          <li class="mb-2">İşletme</li>
          <li class="mb-2">Yazılım</li>
          <li class="mb-2">WordPress</li>
          <li>PHP</li>
        </ul>
      </div>
      <div class="col-sm-6 col-md-3 col-lg-2 col-12">
        Help & Support
        <ul class="footer-p p-0 mt-3" style="list-style-type: none">
          <li class="mb-2">Dökümantasyon</li>
          <li class="mb-2">whatsap</li>
          <li class="mb-2">Bize Ulaşın</li>
          <li class="mb-2">Gizlilik</li>
          <li>SSS</li>
        </ul>
      </div>
      <div class="col-sm-6 col-md-12 col-lg-3 col-12 ">
        Download Apps
        <div
          class="d-flex border border-1 p-3 justify-content-start align-items-center mt-3"
          style="width: 100%; border-radius: 5px"
        >
          <div class="me-3">
            <i class="bi bi-google" style="font-size: 26px; color: #da0b4e"></i>
          </div>
          <div class="d-flex flex-column">
            <div class="footer-p" style="font-size: 18px; font-weight: 600; color: #4a5682">
              Google Play
            </div>
            <div class="footer-p">Get It Now</div>
          </div>
        </div>
        <div
          class="d-flex border border-1 p-3 justify-content-start align-items-center mt-3 mb-5"
          style="width: 100%; border-radius: 5px"
        >
          <div class="me-3">
            <!-- <i class="bi bi-google" style="font-size: 26px; color: #da0b4e;"></i> -->
            <i class="bi bi-apple" style="font-size: 26px; color: #da0b4e"></i>
          </div>
          <div class="d-flex flex-column">
            <div class="footer-p" style="font-size: 18px; font-weight: 600; color: #4a5682">
              App Store
            </div>
            <div class="footer-p">Now it Available</div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="border-top pb-4">
    
    <div class="container mt-3">
      <div class=" row justify-content-between">
        <div class="col-6" style="color: #4d5868;">
          @ Idealworks Bilişim Hizmetleri
        </div>
        <div class="col-6 text-end"> 
          <i class="bi bi-facebook me-4"></i>
          <i class="bi bi-twitter-x me-4"></i>
          <i class="bi bi-instagram me-4"></i>
          <i class="bi bi-linkedin me-4"></i>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.header {
  background-color: #fff;
}

.confluid {
  background: url(assets/img/banner-2.jpg);
  background-size: cover;
  background-position: center;
  position: relative;
}
.confluid-opacity {
  background-color: #052044;
  opacity: 0.9;
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}

.idealButton {
  background-color: #fc6e51;
  color: #fff;
  padding: 10px 10px 10px 10px;
  border-radius: 10px;
}

.idealButtonSignUp {
  background-color: #ff3838;
}

.image-cover {
  background-size: cover !important;
  background-position: center !important;
}

.hero_banner {
  min-height: 620px;
  height: 90vh;
  padding: 0;
}

.rit {
  position: relative;
}

.shadow {
  opacity: 0.3;
}

.trips_top {
  position: relative;
  margin-top: -50px;
}

.trips_wrap {
  background: #ffffff;
  border-radius: 15px;
  padding: 0;
  box-shadow: 0 0 20px 0 rgba(62, 28, 131, 0.1);
}

.trips {
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 1.5rem 1rem;
  flex-wrap: wrap;
  width: 100%;
  flex-direction: row;
}

.trips_icons {
  width: 55px;
  height: 55px;
  align-items: center;
  display: flex;
  justify-content: center;
  margin-right: 12px;
  background: rgba(0, 186, 116, 0.1);
  border-radius: 50%;
  color: #00ba74;
  font-size: 1.3rem;
}

.trips_detail {
  display: flex;
  flex-direction: column;
  flex: 1;
}

.trips_detail h4 {
  font-size: 15px;
  margin-bottom: 0px;

  color: #202124;
  font-weight: 600;
  text-transform: capitalize;
  font-family: 'Outfit', sans-serif;
}
.trips_detail p {
  margin: 0;
  margin-top: 10px;
  font-size: 15px;
  line-height: 1.8;
  color: #4d5868;
  font-weight: 400;
}

.min-sec {
  padding: 80px 0 50px;
  position: relative;
}

.sec-heading2 {
  width: 100%;
  display: flex;
  flex-wrap: wrap;
  align-items: center;
}

.sec-left {
  flex: 1;
}

.side-cates {
  border-bottom: 1px solid #dde2f1;
}

.side-cates .nav-link {
  padding: 10px 15px !important;
  border: none !important;
  background: transparent !important;
  color: #3f4752;
  opacity: 1;
}
.sec-right a {
  font-size: 14px;
  font-weight: 600;
  text-decoration: none;
}
.sec-right a:hover {
  color: #fc6e51;
}

.nav-tabs.side-cates .nav-item.show .nav-link,
.nav-tabs.side-cates .nav-link.active {
  color: #fc6e51;
}

.cardTitle {
  font-size: 18px;
  font-weight: 700;
}

.iconText {
  font-size: 14px;
}

.imgTopRadius {
  border-top-right-radius: 10px;
  border-top-left-radius: 10px;
}

.footer-p {
  /* style="color: #858b9f; font-size: 13px;" */
  color: #858b9f;
  font-size: 13px;
}
</style>
