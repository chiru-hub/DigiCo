<template>
  <div>
    <div class="social d-flex justify-content-center align-items-center">
      <img class="social-icons" src="/images/facebook.png" alt />
      <img class="social-icons ml-5" src="/images/facebook.png" alt />
      <img class="social-icons ml-5" src="/images/facebook.png" alt />
      <img class="social-icons ml-5" src="/images/facebook.png" alt />
    </div>
    <div style="background-color:#f4f4f4">
      <div class="container p-5">
        <div>
          <h6 style="color:#34a2db">CONTACT US</h6>
          <h2 class="mt-2" style="color:#3f3849">GET IN TOUCH</h2>
          <h6 class="mt-4">SEND US A MESSAGE IF YOU NEED ANY HELP</h6>
          <div class="row">
            <div class="col-12 col-md-12 col-lg-6">
              <form class="mt-5" action method="post">
                <div class="form-group">
                  <span>
                    <input type="text" name="fname" id placeholder="First Name" required />
                  </span>
                  <span>
                    <input type="text" name="lname" id placeholder="Last Name" required />
                  </span>
                </div>
                <div class="form-group">
                  <span>
                    <input type="tel" name="phnno" id placeholder="Phone" required />
                  </span>
                  <span>
                    <input type="email" name="e_mail" id placeholder="Email" required />
                  </span>
                </div>
                <div class="form-group">
                  <textarea name="msg" id cols="48" rows="5" placeholder="Your Message" required></textarea>
                </div>
                <button class="btn btn-send">Send Message</button>
              </form>
            </div>
            <div class="col-12 col-md-12 col-lg-6">
              <div class="mt-5 d-flex justify-content-between">
                <div
                  class="px-4 py-2 card-details d-flex flex-column justify-content-center align-items-lg-center"
                >
                  <img style="height:18px;width:13px" src="/images/maps-and-flags.png" alt />
                  <p
                    class="text-justify"
                    style="font-size:14px"
                  >4920 Northwest 2 Avenue Medford, MN 55049</p>
                </div>
                <div
                  class="px-4 py-2 card-details d-flex flex-column justify-content-center align-items-lg-center"
                >
                  <img style="height:18px;width:13px" src="/images/maps-and-flags.png" alt />
                  <p
                    class="text-justify"
                    style="font-size:14px"
                  >4920 Northwest 2 Avenue Medford, MN 55049</p>
                </div>
              </div>
              <div class="d-flex justify-content-between mt-5">
                <div
                  class="px-4 py-2 card-details d-flex flex-column justify-content-center align-items-lg-center"
                >
                  <img style="height:18px;width:13px" src="/images/maps-and-flags.png" alt />
                  <p
                    class="text-justify"
                    style="font-size:14px"
                  >4920 Northwest 2 Avenue Medford, MN 55049</p>
                </div>
                <div
                  class="px-4 py-2 card-details d-flex flex-column justify-content-center align-items-lg-center"
                >
                  <img style="height:18px;width:13px" src="/images/maps-and-flags.png" alt />
                  <p
                    class="text-justify"
                    style="font-size:14px"
                  >4920 Northwest 2 Avenue Medford, MN 55049</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div style="background-color:#363636">
      <div class="container py-5">
        <div class="row">
          <div class="col-12 col-md-4">
            <div>
              <img src="/images/logo-white.png" alt />
              <p
                class="text-white w-75"
                style="opacity:0.45"
              >Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam at</p>
            </div>
          </div>
          <div class="offset-lg-2 col-12 col-md-6">
            <div class="d-flex justify-content-around">
              <div>
                <p class="text-white">EXPLORE</p>
                <p class="text-white" style="opacity:0.45">
                  Cookies
                  <br />About
                  <br />Privacy Policy
                  <br />Licenses
                  <br />
                </p>
              </div>
              <div>
                <p class="text-white">MARKETING</p>
                <p class="text-white" style="opacity:0.45">
                  Timeline
                  <br />News
                  <br />Insight
                  <br />Licensing
                </p>
              </div>
              <div>
                <p class="text-white">CATEGORIES</p>
                <p class="text-white" style="opacity:0.45">
                  About
                  <br />Offices
                  <br />Terms & conditions
                  <br />Services
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
.social {
  height: 135px;
  background-color: #34a2db;
}

.social-icons {
  height: 14px;
  width: 11px;
}

input[type="text"],
[type="email"],
[type="tel"] {
  background-color: white;
  padding: 5px 7px;
  border: solid 1px rgba(112, 112, 112, 0.47);
  border-radius: 2px;
}

.btn-send {
  background-color: #34a2db;
  color: white;
  font-size: 16px;
  height: 50px;
  width: 180px;
}

.card-details {
  height: 110px;
  width: 260px;
  border-radius: 5px;
  border: solid 1px rgba(112, 112, 112, 0.51);
  background-color: #ffffff;
}

input::placeholder {
  font-size: 14px;
  color: #3f3849;
  opacity: 0.56;
}

textarea {
  background-color: white;
  padding: 5px 7px;
  border: solid 1px rgba(112, 112, 112, 0.47);
  border-radius: 2px;
}
</style>
