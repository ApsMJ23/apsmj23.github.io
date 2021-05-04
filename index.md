<!DOCTYPE html>
<html lang="en">

<head>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Apurva Singh</title>
    <link rel="icon" href="AS logo.png" type="image/icon type">
    <!--For animations in CSS-->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css" />
    <!--This is for the font-->
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Zen+Dots&display=swap" rel="stylesheet">
    <!--This is for Bootstrap Dependencies-->
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css" rel="stylesheet" />
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-eOJMYsd53ii+scO/bJGFsiCZc+5NDVN2yr8+0RDqr0Ql0h+rP48ckxlpbzKgwra6" crossorigin="anonymous">
    <link type="text/css" rel="stylesheet" href="style.css" />
    <!--For Bootstrap JS-->

    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.0/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.1.0/js/bootstrap.min.js"></script>
</head>

<body id="bdy">
    <!--Navbar-->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top" id="my-nav">
        <a href="#main_page"> <img src="AS logo.png" id="nav_logo"></a>
        <a class="navbar-brand" id="n_brand" href="#main_page">Apurva Singh</a>
        <button class="navbar-toggler" data-target="#navi" data-toggle="collapse" aria-controls="my-nav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div id="navi" class="collapse navbar-collapse">
            <ul class="navbar-nav mr-auto">
                <li class="nav-item">
                    <a class="nav-link" href="#about_us">About Us</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#experience">Experience</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#education">Eduction</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#tech_sp">Technilogical Speciality</a>
                </li>
            </ul>
        </div>
    </nav>
    <div class="parallax">
        <!--Main Page-->
        <div class="container-fluid">
            <div class="row p-5 mt-5">
                <div class="col-12 text-center mt-5">
                    <div class="text-center img-fluid">
                        <img src="dp.jpg" class="profile_img rounded-circle w-25 h-25">
                        <h1 class="display-1">Hello! I am Apurv Singh</h1>
                        <h5 id="desc">And I am a Django web developer</h5>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!--About us Section-->
    <div class="container-fluid" id="about_us">
        <div class="row align-items-center">
            <div class="col-md-3 text-center">
                <h1 id="about_heading">About Me</h1>
            </div>
            <div class="col-md-9 " style="padding: 20px;">
                Creating web applications gives me the utmost joy, it gives me a sense of achievement. The ability to code, which innovates the user interface to optimum gives me satisfaction, I believe that I am a perfectionist and this can be seen in my code. I love
                programming because it is infinite and constantly changing. It has more potential for innovation, experimentation and discovery.<br><br> I am compelled to create smoother softwares as nobody, including me, likes slow and
                outdated technology. I hope that the improvements I make can improve the world.<br> <br> My approach is simple: l think to make something great, one should think about how they would like it to be? Personal touch is important. Because
                isn’t homemade always better than fast fare? Join me, and let’s build a better modern web!
            </div>
        </div>
    </div>
    <div class="parallax" style="overflow-x: hidden;">
        <!--Experience Setion-->
        <div id="experience" class="text-center">
            <h1 id="work_title">Work Experience</h1>
        </div>
        <div class="container-fluid">
            <div class="row align-items-center">
                <div class="col-md-4 offset-mb-3 p-3">
                    <div class="flip-card">
                        <div class="flip-card-inner">
                            <div class="flip-card-front img-fluid">
                                <img src="anafins.png" class="img-fluid" id="anafins_img">
                            </div>
                            <div class="flip-card-back">
                                <h4 class="card-title" style="margin-top: 35px;">Web Development Intern</h4>
                                Company NameAnafins <br>Internship Dates EmployedApr 2019 – Aug 2019 <br>Employment Duration 5 months <br>Location New Delhi, Delhi, India <br>Helped with the maintenance and bugs on their website:
                                <br><a href="https://www.anafins.com/">https://www.anafins.com</a>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 offset-mb-3 p-3">
                    <div class="flip-card">
                        <div class="flip-card-inner">
                            <div class="flip-card-front img-fluid">
                                <img src="omfuel.png" id="omfuel_img" class="img-fluid">
                            </div>
                            <div class="flip-card-back">
                                <h4 class="card-text" style="margin-top: 35px;">Web Development Freelance</h4>
                                Company Name Vir Shahid Om Fuel Center<br> Dates Employed Apr 2020 – Jun 2020<br> Employment Duration 3 months<br> LocationBhagalpur, Bihar, India<br> Made their website in wordpress: <a href="http://www.omfuel.in/">http://www.omfuel.in</a><br>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 offset-mb-3 p-4">
                    <div class="flip-card">
                        <div class="flip-card-inner">
                            <div class="flip-card-front img-fluid">
                                <img src="awesome.png" id="awesome_img" class="img-fluid">
                            </div>
                            <div class="flip-card-back">
                                <h4 class="card-text" style="margin-top: 35px;">Web Development Freelance</h4>
                                Company Name Awesome Breuty Parlour<br> Dates Employed Jun 2020 – Aug 2020<br> Employment Duration 3 months<br> Location Gurgaon,Haryana <br> Made their website in wordpress: <a href="http://www.awesomebeauty.in/">http://www.awesomebeauty.in</a><br>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!--Education Section-->
    <div class="container-fluid" id="education">
        <div class="row pt-5 p-5">
            <div class="col-md-3 text-center pl-5">
                <h1>Educationnal Background</h1>
            </div>
            <div class="col-md-9">
                <div id="education_list">
                    <ul>
                        <li>B.Tech From Guru Gobindh Singh Indraprastha University</li>
                        <li>CS50's Web programming With Python and Javascript by HARVARDX</li>
                        <li>Android App Development By Ducat.inc</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
    <div class="container-fluid p-5" id="img_container">
        <div class="row">
            <div class="col-4 img-fluid">
                <img class="img-fluid" src="ipu.jpeg">
            </div>
            <div class="col-4 img-fluid">
                <img src="harvardx.jpeg" class="img-fluid">
            </div>
            <div class="col-4 img-fluid">
                <img src="ducat.png" class="img-fluid">
            </div>
        </div>
    </div>
    <!--Technical speciality-->
    <div class="parallax">
        <div class="container text-center" id="tech_sp">
            <h1 class="display-2" id="tech_title">Technologies I am Fluent In!!</h1>
        </div>
        <div class="container mb-5" id="tec_container">
            <div class="row">
                <div class="mr-2 col-4 img-fluid align-items-center">
                    <img src="html.png" id="html_img" class="img-fluid">
                </div>
                <div class="mr-2 col-4 img-fluid align-items-center">
                    <img src="css.png" id="css_img" class="img-fluid">
                </div>
                <div class="col-4 img-fluid align-items-center">
                    <img src="js.png" id="js_img" class="img-fluid">
                </div>
                <div class="mr-2 col-4 img-fluid align-items-center">
                    <img src="node.png" id="node_img" class="img-fluid">
                </div>
                <div class="col-4 img-fluid align-items-center">
                    <img src="django.png" id="django_img" class="img-fluid">
                </div>
                <div class="col-4 img-fluid align-items-center">
                    <img src="bootstrap.png" id="bootstrap_img" class="img-fluid">
                </div>
                <div class="col-4 img-fluid align-items-center">
                    <img src="sql.png" id="sql_img" class="img-fluid">
                </div>
                <div class="col-4 img-fluid align-items-center">
                    <img src="android.png" id="android_img" class="img-fluid">
                </div>
                <div class="col-4 img-fluid align-items-center">
                    <img src="kotlin.png" id="kotlin_img" class="img-fluid">
                </div>
            </div>
        </div>
    </div>
    <!--Contact us page-->
    <div class="container-fluid" id="about_container">
        <div class="row">
            <div class="col-4 text-center">
                <h2>Location</h2>
                <address>
                New Delhi, Delhi India,110038
                </address>
            </div>
            <div class="col-5 text-center">
                <h2>Around the web</h2>
                <a class="d-inline m-1" href="https://github.com/ApsMJ23" role="button"><i class="fab fa-github fa-xs" style="font-size: 40px;"></i></a>
                <a class="d-inline m-1" href="mailto:apurvalion@gmail.com" role="button"><i class="fab fa-google fa-xs" style="font-size: 40px;"></i></a>
                <a class="d-inline m-1" href="https://www.linkedin.com/in/apurva-singh-358151159/" role="button"><i class="fab fa-linkedin" style="font-size: 40px;"></i></a>
                <a class="d-inline m-1" href="https://www.instagram.com/apurvawithan_a/" role="button"><i class="fab fa-instagram" style="font-size: 40px;"></i></a>
            </div>

            <div class="col-3">
                <p> By Apurva Singh &#169;</p>

            </div>

        </div>
    </div>
</body>

</html>