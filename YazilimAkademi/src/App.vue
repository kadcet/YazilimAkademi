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
      class="image-cover hero_banner shadow rlt"
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
                      <div class="d-flex  align-items-center justify-content-between ">
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
                      <div class="d-flex  align-items-center justify-content-between ">
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
                      <div class="d-flex  align-items-center justify-content-between ">
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
                      <div class="d-flex  align-items-center justify-content-between ">
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
                      <div class="d-flex  align-items-center justify-content-between ">
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
</template>

<style scoped>
.header {
  background-color: #fff;
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
</style>
