<template>
  <div class="home">
    <header class="showcase">
        <div class="showcase-top">
            <img src="../assets/logo-netflix.png" alt="NETFLIX">
            
            <router-link class="btn" :to="{name:'sign-in'}">Sign In</router-link>
			
        </div>
        <div class="showcase-content">
            <h1>Unlimited movies, TV shows, and more.</h1>
            <p>Watch anywhere. Cancel anytime</p>
            <span class="text-light">Ready to watch? Enter your email to create or restart your membership.</span>
        </div>
        <div class="register container">
            <form action="">
                <input class="email" id="email" type="email" placeholder="Enter Email">
                <button class="submit" id="submit" type="submit">Get Started <i class="fa fa-chevron-right"></i></button>
            </form>
            
        </div>
    </header>

    <!-- Enjoy Begins -->
    <div class="container-fluid" id="enjoy">
      <div class="container py-5 px-lg-5">
        <div class="row g-5 align-items-center">
            <div class="col-lg-7">
                <h1>Enjoy on your TV.</h1>
                        
                <p class="mb-4">Watch on Smart TVs, Playstation, Xbox, Chromecast, Apple TV, Blu-ray players, and more.</p>
            </div>
            <div class="col-lg-5">
                <img class="img-fluid wow fadeInUp" data-wow-delay="0.5s" src="https://assets.nflxext.com/ffe/siteui/acquisition/ourStory/fuji/desktop/tv.png">
            </div>
        </div>
      </div>
    </div>
    <!-- Enjoy Ends -->

    <!-- Download Begins -->
    <div class="container-fluid" id="download">
      <div class="container py-5 px-lg-5">
        <div class="row g-5 align-items-center">
            <div class="col-lg-5">
                <img class="img-fluid wow fadeInUp" data-wow-delay="0.5s" src="https://assets.nflxext.com/ffe/siteui/acquisition/ourStory/fuji/desktop/mobile-0819.jpg">
            </div>
                    
            <div class="col-lg-7">
                <h1>Download your shows to watch offline.</h1>
                        
                <p class="mb-4">Save your favorites easily and always have something to watch.</p>
            </div>
        </div>
      </div>
    </div>
    <!-- Download Ends -->

    <!-- Watch Begins -->
    <div class="container-fluid" id="watch">
      <div class="container py-5 px-lg-5">
        <div class="row g-5 align-items-center">
            <div class="col-lg-7 wow fadeInUp" data-wow-delay="0.1s">
                <h1 class=" fw-medium">Watch everywhere.</h1>
                        
                <p class="mb-4">Stream unlimited movies and TV shows on your phone, tablet, laptop, and TV.</p>
            </div>
            <div class="col-lg-5">
                <img class="img-fluid wow fadeInUp" data-wow-delay="0.5s" src="https://assets.nflxext.com/ffe/siteui/acquisition/ourStory/fuji/desktop/tv.png">
            </div>
        </div>
      </div>
    </div>
    <!-- Watch Ends -->

    <!-- Profile Begins -->
    <div class="container-fluid" id="profile">
      <div class="container py-5 px-lg-5">
        <div class="row g-5 align-items-center">
            <div class="col-lg-5">
                <img class="img-fluid wow fadeInUp" data-wow-delay="0.5s" src="https://occ-0-299-300.1.nflxso.net/dnm/api/v6/19OhWN2dO19C9txTON9tvTFtefw/AAAABfpnX3dbgjZ-Je8Ax3xn0kXehZm_5L6-xe6YSTq_ucht9TI5jwDMqusWZKNYT8DfGudD0_wWVVTFLiN2_kaQJumz2iivUWbIbAtF.png?r=11f">
            </div>
            <div class="col-lg-7 wow fadeInUp" data-wow-delay="0.1s">
                <h1 class="fw-medium">Create profiles for kids.</h1>
                        
                <p class="mb-4">Send kids on adventures with their favorite characters in a space made just for them—free with your membership.</p>
            </div>
        </div>
      </div>
    </div>
    <!-- Profile Ends -->


    <!-- Footer Begins -->
    <section class="footer" id="footer">
        <div class="top">
            <a href="">Questions? Contact us.</a>
        </div>
        <div class=" container footer-cols">
            <ul>
                <li><a href="#">FAQ</a></li>
                <li><a href="#">Investor Relations</a></li>
                <li><a href="#">Ways To Watch</a></li>
                <li><a href="#">Corporate Information</a></li>
                <li><a href="#">Netflix Originals</a></li>
            </ul>
            <ul>
                <li><a href="#">Help Center</a></li>
                <li><a href="#">Jobs</a></li>
                <li><a href="#">Terms Of Use</a></li>
                <li><a href="#">Contact Us</a></li>
            </ul>
            <ul>
                <li><a href="#">Account</a></li>
                <li><a href="#">Redeem Gift Cards</a></li>
                <li><a href="#">Privacy</a></li>
                <li><a href="#">Speed Test</a></li>
            </ul>
            <ul>
                <li><a href="#">Media Center</a></li>
                <li><a href="#">Buy Gift Cards</a></li>
                <li><a href="#">Cookie Preferences</a></li>
                <li><a href="#">Legal Notices</a></li>
            </ul>
        </div>
        <div class="bottom">
            <p>Designed by <a href="github.io/turnrcode">Timilehin A.</a></p>
        </div>
    </section>
    <!-- Footer Ends -->
  </div>
</template>

<!-- <script>
// @ is an alias to /src


export default {
  name: 'HomeView',
  components: {
    
  }
}
</script> -->

<style scoped>
.showcase {
	width: 100%;
	height: 93vh;
	position: relative;
	background: url('../assets/Netflix-Background.jpg') no-repeat center center/cover;
}
.btn {
	display: inline-block;
	background: var(--primary-color);
	color: #fff;
	padding: 0.4rem 1.3rem;
	font-size: 1rem;
	text-align: center;
	border: none;
	cursor: pointer;
	margin-right: 0.5rem;
	transition: opacity 0.2s ease-in;
	outline: none;
	box-shadow: 0 1px 0 rgba(0, 0, 0, 0.45);
	border-radius: 2px;
}
.btn:hover{
    background: var(--primary-color);
    color: var(--light-color);
}
</style>