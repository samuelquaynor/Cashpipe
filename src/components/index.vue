<template>
    <section class="main-content">
        <div class="container">
            <div class="row justify-vertical">
                <div class="col-12 col-md-6">
                        <div>
                            <h2>We Are Launching Soon!<br>Join Today For Early Access
                            </h2>
                            <p>Enter details below so we can contact you</p>
                        </div>
                        <form style="max-width: 500px;">
                            <div class="form-group">
                            <input type="Name" name="name" v-model="name" class="form-control" id="inputName" placeholder="Name">
                            </div>
                            <div class="form-group">
                            <input type="email" v-model="email" name="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Email">
                            </div>
                            <button type="submit" value="Send" class="btn btn-primary">GET EARLY ACCESS</button>
                        </form>
                </div>
                <div class="col-12 col-md-6">
                    <div class="header-image">
                        <img src="../assets/static/images/header.png" alt="Header">
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section class="about" id="about">
        <div class="container">
            <div class="section-title text-center mb-5">
                <h6>About</h6>
                <h2>We Help To Secure Your System</h2>
            </div>
            <div class="row justify-vertical">
                <div class="col-12 col-md-6 col-lg-7">
                    <div class="about-thumb mb-3 mb-lg-0">
                        <img src="../assets/static/images/about.png" alt="About">
                    </div>
                </div>
                <div class="col-12 col-md-6 col-lg-5">
                    <div class="about-content pt-lg-5">
                        <p class="text-muted">Nunc rhoncus nulla quis mi ultrices vestibulum. Sed molestie nisl viverra,
                            accumsan odio
                            vitae, sollicitudin nisl. Donec vitae urna nec arcu sodales bibendum. Fusce nec venenatis
                            augue.</p>
                        <p class="text-muted">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur tempus
                            elementum ipsum
                            vitae ullamcorper. Nullam dignissim condimentum dui at egestas.</p>
                        <ul class="about-feature">
                            <li>
                                <h3>50k+</h3>
                                <h6 class="space text-muted">Happy Clients</h6>
                            </li>
                            <li>
                                <h3>750k+</h3>
                                <h6 class="space text-muted">Total Download</h6>
                            </li>
                            <li>
                                <h3>50+</h3>
                                <h6 class="space text-muted">Team Members</h6>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section class="section section-two bg-white">
        <div class="container">
          <h2 class="text-9 text-center">Why should you choose Cashpipe?</h2>
          <p class="lead text-center mb-5">Here’s Top 4 reasons why using a Cashpipe account for manage your money.</p>
          <div class="row">
            <div class="col-sm-6 col-lg-3 mb-5 mb-lg-0">
              <div class="featured-box">
                <div class="featured-box-icon text-primary"> <i class="fas fa-hand-pointer"></i> </div>
                <h3>Easy to use</h3>
                <p class="text-3">Lisque persius interesset his et, in quot quidam persequeris vim, ad mea essent possim iriure.</p>
                <a href="#" class="btn-link text-3">Learn more<i class="fas fa-chevron-right text-1 ml-2"></i></a> </div>
            </div>
            <div class="col-sm-6 col-lg-3 mb-5 mb-lg-0">
              <div class="featured-box">
                <div class="featured-box-icon text-primary"> <i class="fas fa-share"></i> </div>
                <h3>Instant Payments</h3>
                <p class="text-3">Persius interesset his et, in quot quidam persequeris vim, ad mea essent possim iriure.</p>
                <a href="#" class="btn-link text-3">Learn more<i class="fas fa-chevron-right text-1 ml-2"></i></a> </div>
            </div>
            <div class="col-sm-6 col-lg-3 mb-5 mb-sm-0">
              <div class="featured-box">
                <div class="featured-box-icon text-primary"> <i class="fas fa-dollar-sign"></i> </div>
                <h3>No Fees</h3>
                <p class="text-3">Essent lisque persius interesset his et, in quot quidam persequeris vim, ad mea essent possim iriure.</p>
                <a href="#" class="btn-link text-3">Learn more<i class="fas fa-chevron-right text-1 ml-2"></i></a> </div>
            </div>
            <div class="col-sm-6 col-lg-3">
              <div class="featured-box">
                <div class="featured-box-icon text-primary"> <i class="fas fa-lock"></i> </div>
                <h3>100% secure</h3>
                <p class="text-3">Quidam lisque persius interesset his et, in quot quidam persequeris vim, ad mea essent possim iriure.</p>
                <a href="#" class="btn-link text-3">Learn more<i class="fas fa-chevron-right text-1 ml-2"></i></a> </div>
            </div>
          </div>
        </div>
    </section>
    <section class="service pt-120" id="service">
        <div class="container mb-5">
            <div class="section-title text-center">
                <h6 style="margin-bottom: 20px;">Service</h6>
                <h2 >Our Best Quality Of Services</h2>
            </div>
            <div class="row justify-vertical" style="margin-bottom: 70px;">
                <div class="col-12 col-md-6 col-lg-6 align-self-center">
                    <div class="service-item">
                        <h2 style="margin-bottom: 20px;">Share &amp; Rewards</h2>
                        <ul class="nav nav-tabs service1" id="myTab" role="tablist">
                            <li class="nav-item">
                                <a class="nav-link active" id="ser1-tab" data-toggle="tab" href="#ser1" role="tab" aria-controls="ser1" aria-selected="true">Charges</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" id="ser2-tab" data-toggle="tab" href="#ser2" role="tab" aria-controls="ser2" aria-selected="false">Transition</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" id="ser3-tab" data-toggle="tab" href="#ser3" role="tab" aria-controls="ser3" aria-selected="false">Security</a>
                            </li>
                        </ul>
                        <div class="tab-content" id="myTabContent">
                            <div class="tab-pane fade" id="ser1" role="tabpanel" aria-labelledby="ser1-tab">
                                <p class="text-muted">Donec id felis sollicitudin, egestas nisl quis, tempus est.
                                    Interdum et malesuada
                                    fames ac ante ipsum primis in faucibus. Duis facilisis pretium nunc, quis congue
                                    arcu consequat ut. Donec quis imperdiet diam, eget blandit neque. Curabitur nec
                                    mauris eget enim scelerisque condimentum. Vestibulum ante ipsum primis in faucibus
                                    orci luctus</p>
                            </div>
                            <div class="tab-pane fade active show" id="ser2" role="tabpanel" aria-labelledby="ser2-tab">
                                <p class="text-muted">Donec2 id felis sollicitudin, egestas nisl quis, tempus est.
                                    Interdum et malesuada
                                    fames ac ante ipsum primis in faucibus. Duis facilisis pretium nunc, quis congue
                                    arcu consequat ut. Donec quis imperdiet diam, eget blandit neque. Curabitur nec
                                    mauris eget enim scelerisque condimentum. Vestibulum ante ipsum primis in faucibus
                                    orci luctus</p>
                            </div>
                            <div class="tab-pane fade" id="ser3" role="tabpanel" aria-labelledby="ser3-tab">
                                <p class="text-muted">Donec3
                                    id felis sollicitudin, egestas nisl quis, tempus est. Interdum et malesuada fames ac
                                    ante ipsum primis in faucibus. Duis facilisis pretium nunc, quis congue arcu
                                    consequat
                                    ut. Donec quis imperdiet diam, eget blandit neque. Curabitur nec mauris eget enim
                                    scelerisque condimentum. Vestibulum ante ipsum primis in faucibus orci luctus</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-12 col-md-6 col-lg-6">
                    <div class="service-thumb p-3">
                        <img src="../assets/static/images/service1.png" alt="Service">
                    </div>
                </div>
            </div>
            <div class="row justify-vertical">
                <div class="col-12 col-md-6 col-lg-6">
                    <div class="service-thumb p-3">
                        <img src="../assets/static/images/service2.png" alt="Service">
                    </div>
                </div>
                <div class="col-12 col-md-6 col-lg-6">
                    <div class="service-item">
                        <h2 class="mb-4">Increase Affiliate Program</h2>
                        <ul class="service2">
                            <li>
                                <img class="box" src="../assets/static/images/box1.png" alt="Service Box">
                                <div class="service-title">
                                    <h4><a href="#">Share &amp; Earn Money</a></h4>
                                    <p class="text-muted">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                                </div>
                            </li>
                            <li>
                                <img class="box" src="../assets/static/images/box2.png" alt="Service Box">
                                <div class="service-title">
                                    <h4><a href="#">Fast &amp; Easy Transfer</a></h4>
                                    <p class="text-muted">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                                </div>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>
      <section class="section section-four">
        <div class="container">
          <h2 class="text-9 text-center">What can you do with Cashpipe?</h2>
          <p class="lead text-center mb-5">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
          <div class="row">
            <div class="col-sm-6 col-lg-3 mb-4"> <a href="#">
              <div class="featured-box style-5 rounded">
                <div class="featured-box-icon text-primary"> <i class="fas fa-share-square"></i> </div>
                <h3>Send Money</h3>
              </div>
              </a> </div>
            <div class="col-sm-6 col-lg-3 mb-4"> <a href="#">
              <div class="featured-box style-5 rounded">
                <div class="featured-box-icon text-primary"> <i class="fas fa-check-square"></i> </div>
                <h3>Receive Money</h3>
              </div>
              </a> </div>
            <div class="col-sm-6 col-lg-3 mb-4"> <a href="#">
              <div class="featured-box style-5 rounded">
                <div class="featured-box-icon text-primary"> <i class="fas fa-user-friends"></i> </div>
                <h3>Pay for a friend</h3>
              </div>
              </a> </div>
            <div class="col-sm-6 col-lg-3 mb-4"> <a href="#">
              <div class="featured-box style-5 rounded">
                <div class="featured-box-icon text-primary"> <i class="fas fa-shopping-bag"></i> </div>
                <h3>Sell Bitcoin</h3>
              </div>
              </a> </div>
          </div>
          <div class="text-center mt-4"><a href="#" class="btn-link text-4">See more can you do<i class="fas fa-chevron-right text-2 ml-2"></i></a></div>
        </div>
      </section>
      <footer id="contact">
        <div class="container">
            <div class="row">
              <div class="col">
                <img src="../assets/static/images/CashpipeLogoVertical.png" class="logo" alt="">
                <p>Get started swiftly & easily by importing a demo of your choice in a single click. Build your website using a fully visual interface.</p>
              </div>
              <div class="col">
                <h5>Features</h5>
                <ul>
                    <li>Customer Support</li>
                    <li>Terms</li>
                    <li>Pricing Policy</li>
                    <li>Refunds</li>
                    <li>Careers</li>
                </ul>
              </div>
              <div class="col">
                <h5>Contact</h5>
                <ul>
                    <i class="fas fa-headphones-alt"></i>
                    <li>+233-20-556-4646</li>
                    <i class="far fa-envelope"></i>
                    <li>Cashpipe@gmail.com</li>
                    <i class="far fa-compass"></i>
                    <li>Express Chambers II Spaces Works, Level</li>
                </ul>
              </div>
              <div class="col">
                  <ul>
                      <li><img class="footer-image" src="../assets/static/images/google-play.svg" alt=""></li>
                      <li><img class="footer-image" src="../assets/static/images/apple-store.svg" alt=""></li>
                  </ul>
              </div>
            </div>
            <hr>
        </div>
        <div class="container">
            <div class="media">
                <p>Copyright 2019 @ Brand Exponents. All rights reserved.</p>
                <ul>
                    <a href=""><li><i class="fab fa-google-plus-g"></i></li></a>
                    <a href=""><li><i class="fab fa-instagram"></i></li></a>
                    <a href=""><li><i class="fab fa-linkedin-in"></i></li></a>
                    <a href=""><li><i class="fab fa-twitter"></i></li></a>
                </ul>
            </div>
        </div>
    </footer>
</template>
<script>
export default {
    name: 'Get Early Access',
    data() {
        return {
            name: '',
            email: '',
        }
    },
    methods: {
        sendEmail(e) {
            try {
                emailjs.sendForm('service_8o2c2d1', 'template_1x253tl', e.target, 'user_cI3L1ml1nC5YfR67xNL0W',{
                    name: this.name,
                    email: this.email,
                })
            } catch(error){
                console.log({error})
            }
            //Reset form field
            this.name = ''
            this.email = ''
        }
    }
}
import emailjs from 'emailjs-com';
</script>
<style scoped>
img{
    width: 100%;
    height: auto;
}

.main-content{
    background-color: #E7EFFF;
}
.section-title h6{
    text-transform: uppercase;
    color: var(--clr-blue);
    letter-spacing: 1px;
}
.service-item .box{
    width: 100px;
    margin-right: 20px;
    float: left;
}

a{
    color: var(--clr-black);
}
</style>