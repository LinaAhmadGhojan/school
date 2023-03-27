<template>

    <div class="common_style">
  
  
      <!-- admission section -->
      <section class="admission_section">
        <div class="container">
          <div class="row">
            <div class="col-md-6">
              <div class="admission_detail-box">
                <h3>
                  Admission open
                </h3>
                <p>
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et
                  dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip
                  ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate
                </p>
                <div class="">
                  <a href="" class="call_to-btn btn_white-border">
                    Read More
                  </a>
                </div>
              </div>
            </div>
            <div class="col-md-6">
              <div class="admission_img-container">
                <img src="../assets/image/images/admission.png" alt="">
              </div>
            </div>
          </div>
        </div>
      </section>
  
  
  
      <!-- end admission section -->
  
  
    </div>
  
    <!-- info section -->
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
  
    <!-- end info section -->
  
    <!-- footer section -->
    <section class="container-fluid footer_section">
      <p>
        Copyright &copy; 2019 All Rights Reserved By
        <a href="https://html.design/">Free Html Templates</a>
      </p>
    </section>
    <!-- footer section -->
  
</template>

<script>
import BlogPost from '../components/blog/BlogPost.vue';
import BlogSlid from '../components/blog/BlogSlid.vue';
export default {
  data: function()
 { 
  return {
    pagename:"blog",
    pagedescription:"This is an blog page"
  } ;
},
name:"blog",
components:{
  BlogPost,BlogSlid
}
    
  }


</script>
  <style>
  @media (min-width: 1024px) {
    .help {
      min-height: 100vh;
      display: flex;
      align-items: center;
    }

    .class-blog{
      text-align: center;
    }

    .posts-area{
      text-align: center;
      background-color: #fef8f0;
      padding: 20px;

    }

    .posts-sild{
      text-align: left;

    }
    
  }
  </style>
  