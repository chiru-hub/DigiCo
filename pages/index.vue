<template>
  <div>
    <div class="container">
      <div>
        <carousel :items="1" :nav="false" :autoplay="true">
          <img class="caro-img" src="/images/oneplusbanner.png" />

          <img class="caro-img" src="/images/oneplusbanner.png" />

          <img class="caro-img" src="/images/oneplusbanner.png" />

          <img class="caro-img" src="/images/oneplusbanner.png" />
        </carousel>
      </div>
      <div class="row" id="about" style="background-color:#f2f2f2;margin:none !important">
        <div class="col-12 col-lg-5 p-0">
          <div class="pad-new">
            <h2 class="text-center">About Us</h2>
            <hr />
            <p class="text-justify" style="color:#323232;line-height:1.4">
              orem Khaled Ipsum is a major key to success. Wraith talk. They don’t want us to eat. I’m giving you cloth talk, cloth. Special cloth alert, cut from a special cloth. Bless up. Cloth talk. You see the hedges, how I got it shaped up? It’s important to shape up your hedges
              <br />
              <br />You see that bamboo behind me though, you see that bamboo? Ain’t nothin’ like bamboo. Bless up. To be successful you’ve got to work hard, to make history, simple, you’ve got to make it
            </p>
          </div>
        </div>
        <div class="col-12 col-lg-7 p-0">
          <div class="d-flex h-100">
            <div class="row">
              <div class="col-6 px-0 border-left border-right col-sm-6 col-md-4">
                <div
                  class="services-pad d-flex flex-column justify-content-center align-items-center border-bottom"
                >
                  <div class="d-flex justify-content-center">
                    <img class="w-100" src="/images/iphonexr.png" alt />
                  </div>
                </div>
                <div
                  class="services-pad d-flex flex-column justify-content-center align-items-center"
                >
                  <div class="d-flex justify-content-center">
                    <img class="w-100" src="/images/fridge1.png" alt />
                  </div>
                </div>
              </div>
              <div class="col-6 px-0 border-right col-sm-6 col-md-4">
                <div
                  class="services-pad d-flex flex-column justify-content-center align-items-center border-bottom"
                >
                  <div class="d-flex justify-content-center">
                    <img class="w-100" src="/images/washing_machine_PNG15609.png" alt />
                  </div>
                </div>
                <div
                  class="services-pad d-flex flex-column justify-content-center align-items-center"
                >
                  <div class="d-flex justify-content-center">
                    <img class="w-100" src="/images/unnamed_2.png" alt />
                  </div>
                </div>
              </div>
              <div class="col-6 px-0 border-right col-sm-6 col-md-4">
                <div
                  class="services-pad d-flex flex-column justify-content-center align-items-center border-bottom"
                >
                  <div class="d-flex justify-content-center">
                    <img class="w-100" src="/images/amazfit_bip_smartwatch_onyx_black_hero.png" alt />
                  </div>
                </div>
                <div
                  class="services-pad d-flex flex-column justify-content-center align-items-center"
                >
                  <div class="d-flex justify-content-center">
                    <img class="w-100" src="/images/smart-led-tv-png-3.png" alt />
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div
        class="mt-5 shadow-lg"
        id="products"
        style="background-color:white;box-shadow:rgba(0, 0, 0, 0.16)"
      >
        <h2 class="py-3 pl-4 border-bottom">Explore our Product Gallery</h2>
        <carousel :items="3" :nav="false" :autoplay="true">
          <div class="img__container">
            <img class="caro-img" src="/images/ac_new.png" />
          </div>
          <div class="img__container">
            <img class="caro-img" src="/images/btspeaker_new.png" />
          </div>
          <div class="img__container">
            <img class="caro-img" src="/images/greenheadphones_new.png" />
          </div>
          <div class="img__container">
            <img class="caro-img" src="/images/iphone_new.png" />
          </div>
        </carousel>
      </div>
      <div class="mt-5" id="gallery">
        <div class="d-flex justify-content-center">
          <span class="deals">Hot Deals</span>
          <span class="deals ml-4">BestSeller</span>
        </div>
        <div class="mt-5">
          <div class="row">
            <div class="col-12 col-md-3">
              <div
                class="product-pad d-flex flex-column justify-content-between"
                style="background-color:#f7f7f7"
              >
                <img class="w-100 pt-5" src="/images/unnamed.png" alt />
                <p
                  style="margin-bottom:none"
                  class="text-center font-weight-bold mt-2"
                >Samsung Galaxy S9</p>
              </div>
              <div
                class="product-pad mt-2 d-flex flex-column justify-content-between"
                style="background-color:#f7f7f7"
              >
                <img class="w-100 pt-5" src="/images/redmi.png" alt />
                <p style="margin-bottom:none" class="text-center mt-2 font-weight-bold">Redmi Note 7</p>
              </div>
            </div>
            <div class="col-12 col-md-6">
              <div>
                <img class="w-100 h-100" src="/images/z.png" alt />
              </div>
            </div>
            <div class="col-12 col-md-3">
              <div
                class="product-pad d-flex flex-column justify-content-between"
                style="background-color:#f7f7f7"
              >
                <img class="w-100 pt-5" src="/images/2.png" alt />
                <p style="margin-bottom:none" class="text-center font-weight-bold mt-2">Xiaomi Pro</p>
              </div>
              <div
                class="product-pad mt-2 d-flex flex-column justify-content-between"
                style="background-color:#f7f7f7"
              >
                <img class="w-100 pt-5" src="/images/redminote6.png" alt />
                <p style="margin-bottom:none" class="text-center font-weight-bold mt-2">Redmi Note 6</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div
      style="margin-top:80px;height:500px;background-image:linear-gradient(123deg, #87ddce 17%, #92e2fd 75%);"
    >
      <div class="row h-100">
        <div class="col-12 col-md-6">
          <div class="d-flex flex-column h-100 align-items-center justify-content-center">
            <div class="flex-row">
              <span>
                <img style="height:70px;width:70px" src="/images/milogo.png" alt />
              </span>
              <span>Discover the new range of MI products</span>
            </div>
            <div class="mt-4">
              <span>Available</span>
              <img style="height:70px;width:230px" src="/images/logo2.png" alt />
            </div>
            <div class="mt-4">
              <button class="btn visit-now">Visit Now</button>
            </div>
          </div>
        </div>
        <div class="col-12 col-md-6">
          <img class="mobile-image w-100" src="/images/head_hd.png" alt />
        </div>
      </div>
    </div>

    <!-- Our achievements starts here -->
    <div class="achievements">
      <div class="pt-5">
        <h2 class="text-center">Our Achievements</h2>
      </div>
      <hr style="width:5%;margin:auto;size:2px" />
      <div class="container">
        <div class="row mt-5">
          <div class="col-12 col-md-4 d-flex justify-content-center">
            <img class="certificate" src="/images/certificate.png" alt />
          </div>
          <div class="col-12 col-md-4 d-flex justify-content-center mt-1 m-sm-0">
            <img class="certificate" src="/images/certificate.png" alt />
          </div>
          <div class="col-12 col-md-4 d-flex justify-content-center mt-1 mt-sm-0">
            <img class="certificate" src="/images/certificate.png" alt />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import carousel from "vue-owl-carousel";

export default {
  components: { carousel }
};
</script>

<style scoped>
.pad-new {
  padding: 27px 48px;
}

.img__container {
  width: 20rem;
  display: flex;
  justify-content: center;
  align-items: center;
}

.img__container img {
  height: 200px;
  width: auto;
  object-fit: cover;
  object-position: center;
}

.product-image {
  height: 200px;
  width: 100px;
}

.services-pad {
  padding: 19px 18px;
  height: 50%;
}

.product-pad {
  padding: 10px 10px;
  height: 50%;
}

.deals {
  font-size: 30px;
  color: #3f3849;
  opacity: 0.77;
  border-bottom: 2px solid white;
}

.deals:hover {
  opacity: 1;
  border-bottom: 2px solid #3f3849;
  transition: 0.5s linear ease-in-out;
}

.visit-now {
  height: 65px;
  width: 260px;
  background-color: #34a2db;
  color: #fefdfc;
  font-size: 30px;
  text-align: center;
}
.mobile-image {
  height: 547px;
  margin-top: -47px;
}

.achievements {
  background-image: url(/images/home-bg.png);
  height: 520px;
}

.certificate {
  height: 265px;
  width: auto;
}

@media (max-width: 600px) {
  .mobile-image {
    width: 100px;
    height: 100px;
    margin-top: 10px;
  }
}
</style>
