
<html lang="en">
<head>
  <title>Business Website</title>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
  <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" ></script>
  <style>
      /*--------Nav-Bar--------*/
       #nav-bar{
        position: sticky;
        top: 0;
        z-index: 10;   
          }
       .navbar-brand{
           background-color: black;
           color: red;
           font-size: 25px;
           padding: 10px;
       }
       .navbar-nav li{
           padding: 0 10px;
       }
       .navbar-nav li a{
           float: right;
           text-align: left;
       }
       #nav-bar ul li a:hover{
           color: #007bff!important;
          }
          .navbar {
              background: #fff;
          }
          .navbar-toogler{
              border: none!important;
          }
          .nav-link{
              color: #555!important;
              font-weight: 600;
              font-size: 16px;
          }
          /*-----Slider------*/
          #slider{
              width: 100;
          }
          .carousel-caption{
              top: 50%;
              transform: translateY(-50%);
              bottom: initial!important;
          }
          .carousel-caption h5{
              
              color: rgb(0, 0, 0);
              font-size: 42px;
          }
         

       /*-------About-----------*/
       #about{
        padding-top: 50px;
        padding-bottom: 50px;
        color: #555;
       }  
       #about .btn {
           margin-top: 20px;
           margin-bottom: 20px;
       } 
       .about-content{
           padding-top: 20px;
       }
       .skills-bar p{
           margin-bottom: 6px;
           font-weight: 600;
       }
       .progress-bar{
           border-radius: 16px;
       }
       .progress{
           border-radius: 16px!important;
           margin-bottom: 20px;
       }
        
        /*--------Services-----*/
        
         #services{
              background-image: linear-gradient(rgba(0,0,0,0.8),rgba(0,0,0,0.8)),url(bsn4.jpg);
              background-size: cover;
              background-position: center;
              color: #f8e5e5!important;
              background-attachment: fixed;
              padding-top: 50px;
              padding-bottom: 50px;
          }
          #services h1{
              text-align: center;
              color: #efefef!important;
              padding-bottom: 10px;

          }
          #services h1::after{
              content: '';
              background: #efefef;
              display: block;
              height: 3px;
              width: 170px;
              margin: 20px auto 5px;
          }
          .icon{
              font-size-adjust: 40px;
              margin: 10px auto;
              padding: 30px;
              height: 80px;
              width: 80px;
              border: 1px solid #fff;
              border-radius: 90%;
          }
          #services p{
              font-size: 14px;
              margin-top: 20px;
              color: #ccc;
          }
          .services .col-md-3:hover{
              background: #0a76e9;
              cursor: pointer;
              transition: 0.5s;
          }
          /*----team----*/
          #team{
              padding-top: 50px;
              padding-bottom: 50px;
              color: #555;
          }
          h1{
              text-align: center;
              color: #555;
              padding-bottom: 10px;
          }
          h1::after{
              content: '';
              background: #007bff;
              display: block;
              height: 3px;
              width: 170px;
              margin: 20px auto 5px;

          }
          .profile-pic{
              margin-top: 25px;
          }
          .profile-pic .img-box img{
              filter: grayscale(1);
          }
          .profile-pic .img-box img:hover{
              filter: grayscale(0);
              cursor: pointer;
          }
          .profile-pic h2{
              font-size: 22px;
              font-weight: bold;
              margin-top: 15px;
              color: #007bff!important;
          }
          .profile-pic h3{
            font-size: 15px;
              font-weight: bold;
              margin-top: 15px;
          }
          #team .fa{
              height: 25px;width: 25px;
              color: #007bff!important;
              background: #fff;
              padding: 4px;
              border-radius: 50%;
          }
          .img-box ul{
              padding: 15px 0;
              position: absolute;
              z-index: 2;
              bottom: 0;
              left: 50%;
              transform: translateX(-50%);
              opacity: 0;
          }
          .img-box ul li{
              padding: 10px;
              
          }
          .img-box:hover ul{
              opacity: 1;
          }
          .img-box ul, .im ul li{
              transition: 0.5s;
          }
          /*promo*/
          #promo{
              background-image: linear-gradient(rgba(0,0,0,0.7),rgba(0,0,0,0.7)),url(bsn4.jpg);
              background-size: cover;
              background-position: center;
              color: #fff;
              background-attachment: fixed;
              text-align: center;
              padding: 100px; 
              font-family: sans-serif;
              font-size: 38px;
          }
          /*----Price plan----*/
          #price{
              padding: 40px 0;
              background-color: #efefef;

          }
          .single-price{
              margin: 10px auto;
              display: inline;
              float: left;
              width: 100%;
              background-color: #fff;
              transition: 0.5s;
          }
          .single-price:hover{
              box-shadow: 0 2px 20px #333;
          }
          .price-head{
              background-color: #2196f3;
              display: inline;
              float: left;
              padding: 10px 5px;
              text-align: center;
              width: 100%;
          }
          .price-headh2{
              color: #333;
              font-size: 30px;
              font-weight: bold;
              margin-bottom: 5px;
              padding: 5px;
              text-transform: uppercase;

          }
          .price-head p{
              font-size: 25px;
              color: #ccc;
              font-weight: bold;
              line-height: 30px;
          }
          #price span{
              font-size:15px;
          }
          .price-content{
              display: inline;
              float: left;
              width: 100%;
              padding: 0 15px;
          }
          .price-content ul li{
           border-bottom: 1px solid #efefef;
           padding: 15px 10px;
           list-style: none;   
          }
          ul li:last-child{
              border: none;
          }
          .fa-check-circle{
              color: aquamarine;
              margin-right: 10px;
              font-size: 20px;
          }
          .price-button{
              display: inline;
              float: left;
              padding: 15px 15px 30px;
              text-align: center;
              width: 100%;

          }
          .buy-btn{
              background-color: #2196f3;
              border-radius: 3px;
              display: inline-block;
              font-size: 18px;
              padding: 15px 50px;
              transition: 0.5s;
          }
          .buy-btn:hover{
              border-color: 1px solid #fff;
              background-color: #3f51b5;
          }
          a{
              text-decoration: none!important;
              color: #fff!important;
          }
          /*--------testimonials----------*/
          #testimonials{
                padding-top: 50px;
                padding-bottom: 50px;
          }
          .sentence{
              font-size: 35px;
          }
          #testimonials .row{
              margin-top: 30px;
          }
          .col-md-4{
              margin: 45px auto;
          }
          .profile{
              padding: 70px 10px 10px;
              background-color: #efefef;
          }
          .user{
              width: 120px;
              height: 120px;
              border-radius: 50%;
          }
          .profile img{
              top: -60px;
              position: absolute;
              left: calc(50% - 60px);
              border: 10px solid #fff;
          }
          .profile h3{
              font-size: 20px;
              margin-top: 15px;
              color: #007bff;
          }
          #testimonials span{
              font-size: 12px;
              color: #333;
          }
          blockquote{
              font-size: 16px;
              line-height: 30px;
          }/*
          blockquote::before{
              content: '\93';
              font-size: 50px;
              color: #007bff;
              position: relative;
              line-height: 20px;
              bottom: -15px;
              right: 5px;
          }
          blockquote::after{
              content: '\94';
              font-size: 50px;
              color: #007bff;
              position: relative;
              line-height: 20px;
              bottom: -15px;
              left: 5px;
          }*/
          .profile:hover{
              box-shadow: 0 0 15px rgba(0,0,0,0.2);
              cursor: pointer;
              transition: 0.5s;
          }
          /*------------GET IN  TOUCH----**/
          #contact{
               background: #efefef;
               padding-top: 40px;
               padding-bottom: 40px;
               color: #777;
            }
            .contact-form{
               padding: 15px;
           }
           .form-control{
               border-radius: 0!important;
               border: none!important;
           }
           ::placeholder{
               color: #333!important;
           }
           .follow{
               padding: 10px;
               background: #fff;
               margin: 15px;
           }
           .contant-info .fa{
               margin: 10px;
               color: #007bff;
               font-weight: bold;
           }
          /*----footer--*/
          #footer{
              background: #333;
              color: #fff;
              padding: 12px;

          }
          .fa-heart-o{
              margin: 3px;
              color: red;
          }
          </style>  
  <body>
      <div class="col-md-12">
    <section id="nav-bar">  
    <nav class="navbar navbar-expand-lg navbar-light t">
    <!----<a class="navbar-brand" href="#"><img src=".png"></a>---->
    <a class="navbar-brand" href="#" >LOGO</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ml-auto">
        <li class="nav-item active">
          <a class="nav-link" href="#">Home </a>
        </li>
        <li class="nav-item">
          <a class="nav-link" data-target=".navbar-collapse" href="#about">About US</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" data-target=".navbar-collapse" href="#services">Services</a>
        </li>
        <li class="nav-item">
          <a class="nav-link " data-target=".navbar-collapse" href="#team">Our Team</a>
        </li>
        <li class="nav-item">
           <a class="nav-link " data-target=".navbar-collapse" href="#price">Price Plans</a>
        </li>
        <li class="nav-item">
            <a class="nav-link " data-target=".navbar-collapse" href="#testimonials">Testimonials</a>
        </li>
        <li class="nav-item">
           <a class="nav-link " data-target=".navbar-collapse" href="#contact">Contacts </a>
        </li>
      </ul>
    </div>
  </nav>
</section>
<!-----slider---->
  <div id="slider">
        <div id="headerslider" class="carousel slide" data-ride="carousel">
                <ol class="carousel-indicators">
                  <li data-target="#headerslide" data-slide-to="0" class="active"></li>
                  <li data-target="#headerslide" data-slide-to="1"></li>
                  <li data-target="#headerslide" data-slide-to="2"></li>
                </ol>
                <div class="carousel-inner">
                  <div class="carousel-item active">
                    <img src="webi4.jpg" class="d-block img-fluid w-100  " alt=".."  >
                    <div class="carousel-caption">
                        <h5>WEB SITE NAME</h5>
                    </div>
                  </div>
                  <div class="carousel-item">
                    <img src="webi4.jpg" class="d-block img-fluid w-100" alt=".." >
                    
                    <div class="carousel-caption">
                            
                        </div>
                    
                  </div>
                  <div class="carousel-item">
                    <img src="webi4.jpg" class="d-block img-fluid w-100" alt=".." >
                    <div class="carousel-caption">
                            
                        </div>
                  </div>
                </div>
                <a class="carousel-control-prev" href="#headerslide" role="button" data-slide="prev">
                  <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                  <span class="sr-only">Previous</span>
                </a>
                <a class="carousel-control-next" href="#headerslide" role="button" data-slide="next">
                  <span class="carousel-control-next-icon" aria-hidden="true"></span>
                  <span class="sr-only">Next</span>
                </a>
              </div>
  </div>
  
  <!-----About---->
  
  <section id="about">
      <div class="container">
            <br>
          <div class="row">
              <div class=" col-md-6">
                  <h2>About Us</h2>
                  <div class="about-content">
                        When people in a company or organization are responsible for deciding when or how to perform certain tasks or aspects of the work, based on their knowledge and ability to judge, the responsibility for the decision is said to be at their discretion.
                  </div>
                  <button type="button" class=" btn btn-primary">Read more>>
                  </button>
              </div>
              <div class="col-md-6 skills-bar">
                  <p>Program name 1</p>
                  <div class="progress">
                      <div class="progress-bar" style="width:80%;">80%</div>
                  </div>
                  <p>Program name 2</p>
                  <div class="progress">
                        <div class="progress-bar" style="width:85%;">85%</div>
                    </div>
                    <p>Program name 3</p>
                    <div class="progress">
                            <div class="progress-bar" style="width:70%;">70%</div>
                        </div>
                        <p>Program name 4</p>
                        <div class="progress">
                                <div class="progress-bar" style="width:65%;">65%</div>
                            </div>            
              </div>
          </div>
      </div>
  </section>
  <!-----Services-->
  
  <section id="services">
      <div class="container">
            <br>
          <h1>Our Services</h1>
      </div>
      <div class="row services">
          <div class="col-md-3 text-center">
              <div class="icon">
                    <i class="fa fa-desktop" ></i>
              </div>
              <h3>Program name 1 </h3>
              <p>When people in a company or organization are responsible for deciding when or how to perform certain tasks or aspects of the work</p>
          </div>
          <div class="col-md-3 text-center">
                <div class="icon">
                      <i class="fa fa-desktop" ></i>
                </div>
                <h3> Program name 2</h3>
                <p>When people in a company or organization are responsible for deciding when or how to perform certain tasks or aspects of the work</p>
            </div>
            <div class="col-md-3 text-center">
                    <div class="icon">
                          <i class="fa fa-desktop" ></i>
                    </div>
                    <h3> Program name 3</h3>
                    <p>When people in a company or organization are responsible for deciding when or how to perform certain tasks or aspects of the work</p>
                </div>
                <div class="col-md-3 text-center">
                        <div class="icon">
                              <i class="fa fa-desktop" ></i>
                        </div>
                        <h3> Program name 4</h3>
                        <p>When people in a company or organization are responsible for deciding when or how to perform certain tasks or aspects of the work</p>
                    </div>      
      </div>
  </section>
  <!-----team member-->
  
  <section id="team">
      <div class="container">
            <br>
          <h1>Our Team</h1>
          <div class="row">
              <div class="col-md-3 profile-pic text-center">
                  <div class="img-box">
                      <img src="per.png" class="img-responsive">
                      <ul>
                          <a href="#"><li><i class="fa fa-paint-brush" aria-hidden="true"></i></li></a>
                          <a href="#"><li><i class="fa fa-paint-brush" aria-hidden="true"></i></li></a>
                          <a href="#"><li><i class="fa fa-paint-brush" aria-hidden="true"></i></li></a>
                      </ul>
                  </div>
                  <h2>NAME</h2>
                    <h3>CREATER</h3>
                    <p>Description about the person</p>
              </div>
              <div class="col-md-3 profile-pic text-center">
                    <div class="img-box">
                        <img src="per.png" class="img-responsive">
                        <ul>
                            <a href="#"><li><i class="fa fa-paint-brush" aria-hidden="true"></i></li></a>
                            <a href="#"><li><i class="fa fa-paint-brush" aria-hidden="true"></i></li></a>
                            <a href="#"><li><i class="fa fa-paint-brush" aria-hidden="true"></i></li></a>
                        </ul>
                    </div>
                    <h2>NAME</h2>
                    <h3>CREATER</h3>
                    <p>Description about the person</p>
                </div>
                <div class="col-md-3 profile-pic text-center">
                        <div class="img-box">
                            <img src="per.png" class="img-responsive">
                            <ul>
                                <a href="#"><li><i class="fa fa-paint-brush" aria-hidden="true"></i></li></a>
                                <a href="#"><li><i class="fa fa-paint-brush" aria-hidden="true"></i></li></a>
                                <a href="#"><li><i class="fa fa-paint-brush" aria-hidden="true"></i></li></a>
                            </ul>
                        </div>
                        <h2>NAME</h2>
                    <h3>CREATER</h3>
                    <p>Description about the person</p>
                    </div>
                    <div class="col-md-3 profile-pic text-center">
                            <div class="img-box">
                                <img src="per.png" class="img-responsive">
                                <ul>
                                    <a href="#"><li><i class="fa fa-paint-brush" aria-hidden="true"></i></li></a>
                                    <a href="#"><li><i class="fa fa-paint-brush" aria-hidden="true"></i></li></a>
                                    <a href="#"><li><i class="fa fa-paint-brush" aria-hidden="true"></i></li></a>
                                </ul>
                            </div>
                            <h2>NAME</h2>
                            <h3>CREATER</h3>
                            <p>Description about the person</p>
                        </div>
          </div>
      </div>
  </section>
  <!-----Promo---->
  <section id="promo">
      <div class="container">
          <p>THE EXTRA THINGS ABOUT THE COMPANY</p>
          <a href="#" class="btn btn-primary">Contact Us</a>
      </div>
  </section>
  <!---Preic plans-->
  <section id="price">
      <div class="container">
            <br><br>
          <h1>Price Plans</h1>
          <div class="row">
              <div class="col-md-4">
                  <div class="single-price">
                      <div class="price-head">
                          <h2>Free</h2>
                          <p>$0/<span>month</span></p>
                      </div>
                      <div class="price-content">
                          <ul> 
                              <li><i class="fa fa-check-circle" ></i>asecuvw</li>
                              <li><i class="fa fa-check-circle" ></i>asecuvw</li>
                              <li><i class="fa fa-check-circle" ></i>asecuvw</li>
                              <li><i class="fa fa-check-circle" ></i>asecuvw</li>
                          </ul>
                      </div>
                      <div class="price-button">
                          <a class="buy-btn" href="#">Join Free</a>
                      </div>
                  </div>
              </div>
              <div class="col-md-4">
                    <div class="single-price">
                        <div class="price-head">
                            <h2>Free</h2>
                            <p>$0/<span>month</span></p>
                        </div>
                        <div class="price-content">
                            <ul> 
                                    <li><i class="fa fa-check-circle" ></i>asecuvw</li>
                                    <li><i class="fa fa-check-circle" ></i>asecuvw</li>
                                    <li><i class="fa fa-check-circle" ></i>asecuvw</li>
                                    <li><i class="fa fa-check-circle" ></i>asecuvw</li>
                            </ul>
                        </div>
                        <div class="price-button">
                            <a class="buy-btn" href="#">Join Free</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                        <div class="single-price">
                            <div class="price-head">
                                <h2>Free</h2>
                                <p>$0/<span>month</span></p>
                            </div>
                            <div class="price-content">
                                <ul> 
                                        <li><i class="fa fa-check-circle" ></i>asecuvw</li>
                                        <li><i class="fa fa-check-circle" ></i>asecuvw</li>
                                        <li><i class="fa fa-check-circle" ></i>asecuvw</li>
                                        <li><i class="fa fa-check-circle" ></i>asecuvw</li>
                                </ul>
                            </div>
                            <div class="price-button">
                                <a class="buy-btn" href="#">Join Free</a>
                            </div>
                        </div>
                    </div>
          </div>
      </div>

  </section>
  <!---Testimonials----->
  <section id="testimonials">
      <div class="container">
            <br>
          <h1>Testimonials</h1>
          <p class="text-center sentence">We thank you all for the support</p>
          <div class="row">
              <div class="col-md-4 text-center">
                  <div class="profile">
                      <img src="per.png" class="user">
                      <blockquote>When people in a company or organization are responsible for deciding when or how to perform certain tasks or aspects of the work
                      </blockquote>
                      <h3>NAME <span>POST IN THE JOB</span></h3>
                  </div>
              </div>
              <div class="col-md-4 text-center">
                    <div class="profile">
                        <img src="per.png" class="user">
                        <blockquote>When people in a company or organization are responsible for deciding when or how to perform certain tasks or aspects of the work
                        </blockquote>
                        <h3>NAME <span>POST IN THE JOB</span></h3>
                    </div>
                </div>
                <div class="col-md-4 text-center">
                        <div class="profile">
                            <img src="per.png" class="user">
                            <blockquote>When people in a company or organization are responsible for deciding when or how to perform certain tasks or aspects of the work
                            </blockquote>
                            <h3>NAME <span>POST IN THE JOB</span></h3>
                        </div>
                    </div>
          </div>
      </div>
  </section>
  <!----Get in touch----->
  <section id="contact">
      <div class="container">
          <h1>GET IN TOUCH</h1>
          <div class="row">
              <div class="col-md-6">
                  <form class="contact-form">
                      <div class="form-group">
                          <input type="text" class="form-control" placeholder="your name">
                      </div>
                      <div class="form-group">
                            <input type="number" class="form-control" placeholder="mobile number">
                        </div>
                        <div class="form-group">
                                <input type="email" class="form-control" placeholder=" mail address">
                            </div>
                            <div class="form-group">
                                    <textarea class="form-control" rows="4" cols="16" placeholder="your Message">
                                        </textarea>
                                </div>
                                <button type=" submit" class="btn btn-primary">Send Message</button>
                  </form>
              </div>
              <div class="col-md-6 contant-info">
               
                    <div class="follow"><b>Address:</b> <i class="fa fa-map-marker" ></i> XYZ Road,Banglore INDIA</div>
                    <div class="follow"><b>Phone:</b> <i class="fa fa-phone-square" ></i> +919999999999</div>
                    <div class="follow"><b>Email: </b><i class="fa fa-envelope-o" ></i> wenavu@gmail.com</div>
                    <div class="follow"><label><b>GET Social</b></label>
                    <a href="#"><i class="fa fa-facebook"></i></a>
                    <a href="#"><i class="fa fa-youtube-play"></i></a>
                    <a href="#"><i class="fa fa-twitter"></i></a>
                    <a href="#"><i class="fa fa-google-plus"></i></a>
                    </div>
              </div>
          </div>
      </div>
  </section>
  <!------footer---->
  <section id="footer">
      <div class="container text-center">
          <p>Made with by rjcreaters</p>
      </div>
  </section>

  
    </div>
  </body>
  </html>
