<template>
  
  <!-- contact section -->

  <section class="contact_section ">

    <div class="container">

      <div class="row">
        <div class="col-md-6">
          <div class="d-flex justify-content-center d-md-block">
            <h2>
              Contact Us
            </h2>
          </div>
          <form action="">
            <div class="contact_form-container">
              <div>
                <div>
                  <input type="text" placeholder="Name">
                </div>
                <div>
                  <input type="email" placeholder="Email">
                </div>
                <div>
                  <input type="text" placeholder="Phone Number">
                </div>
                <div class="mt-5">
                  <input type="text" placeholder="Message">
                </div>
                <div class="mt-5">
                  <button type="submit">
                    send
                  </button>
                </div>
              </div>

            </div>

          </form>
        </div>
        <div class="col-md-6">
          <div class="contact_img-box">
            <img src="../assets/image/images/students.jpg" alt="">
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- end contact section -->
  <section class="info_section layout_padding-top">
    <div class="info_logo-box">
      <h2>
        Fanadesh
      </h2>
    </div>
    <div class="container layout_padding2">
      <div class="row">
        <div class="col-md-3">
          <h5>
            About Us
          </h5>
          <p>
            dolor sit amet, consectetur magna aliqua. Ut enim ad minim veniam, quisdotempor incididunt r
          </p>
        </div>
        <div class="col-md-3">
          <h5>
            Useful Link
          </h5>
          <ul>
            <li>
              <a href="">
                Video games
              </a>
            </li>
            <li>
              <a href="">
                Remote control
              </a>
            </li>
            <li>
              <a href="">
                3d controller
              </a>
            </li>
          </ul>
        </div>
        <div class="col-md-3">
          <h5>
            Contact Us
          </h5>
          <p>
            dolor sit amet, consectetur magna aliqua. quisdotempor incididunt ut e
          </p>
        </div>
        <div class="col-md-3">

          <div class="subscribe_container">
            <h5>
              Newsletter
            </h5>
            <div class="form_container">
              <form action="">
                <input type="email" placeholder="Enter your email">
                <button type="submit">
                  Subscribe
                </button>
              </form>
            </div>
          </div>

        </div>
      </div>
    </div>
    <div class="container">
      <div class="social_container">

        <div class="social-box">
          <a href="">
            <img src="../assets/image/images/fb.png" alt="">
          </a>

          <a href="">
            <img src="../assets/image/images/twitter.png" alt="">
          </a>
          <a href="">
            <img src="../assets/image/images/linkedin.png" alt="">
          </a>
          <a href="">
            <img src="../assets/image/images/instagram.png" alt="">
          </a>
        </div>
      </div>
    </div>
  </section>

  <!-- footer section -->
  <section class="container-fluid footer_section">
    <p>
      Copyright &copy; 2019 All Rights Reserved By
      <a href="https://html.design/">Free Html Templates</a>
    </p>
  </section>
  
</template>

<script>

export default {
  data: function()
 { 
  return {
    pagename:"Help",
    pagedescription:"This is an help page"
  } ;
},
name:"help"
    
  }


</script>
  <style>
  @media (min-width: 1024px) {
    .help {
      min-height: 100vh;
      display: flex;
      align-items: center;
    }

    .class-help{
      text-align: center;
    }
  }
  </style>
  