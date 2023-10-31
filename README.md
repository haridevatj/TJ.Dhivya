@@ -0,0 +1,249 @@
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>bootstrap</title>

    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
<link rel="stylesheet" href="index.css">
</head>
<body>
    <nav class="navbar navbar-expand-sm bg-dark navbar-bg-dark">
    <div class="container-fluid">
        <a class="navbar-brand  nav justify-content-start text-white" href="#">
            <img src="images (1).png" height="40px" width="60px" class="rounded-pill">&nbsp;The Great OutDoors
        </a>
        <ul class="nav nav-tabs nav-bg-dark text-white" role="tablist"  >
            <li class="nav-item nav-item-center">
            <a class="nav-link" data-bs-toggle="tab" href="#home">Home</a></li>
            <li class="nav-item">
            <a class="nav-link" data-bs-toggle="tab" href="#about">About</a></li>
            <li class="nav-item">
            <a class="nav-link"  data-bs-toggle="tab" href="#Tour">Tour</a></li>  
            <li class="nav-item">
            <a class="nav-link" data-bs-toggle="tab" href="#Packages">Packages</a></li>  
            <li class="nav-item">
            <a class="nav-link"  data-bs-toggle="tab" href="#Contact">Contact</a></li>   
            <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" data-bs-toggle="dropdown">Blogs</a>
                 <ul class="dropdown-menu">
                    <li><a class="dropdown-item" data-bs-toggle="tab" href="#Tour">Tour</a></li>
                    <li><a class="dropdown-item"  data-bs-toggle="tab" href="#packages">packages</a></li>
                    <li><a class="dropdown-item" data-bs-toggle="tab" href="#contact">contact</a></li>
                 </ul></li>
            <button type="button" class="btn btn-primary">Book now</button>
            </ul>
        </nav>

        <div class="tab-content">
        <div class=" tab-pane container" id="Tour"><br>
         <div class="rows">
            <div class="card p-4 card-outline" width="200px">
                <img  class="img-rounded-corners" src="dubai.jpg" width="220px">
                <h4 class="card-title">Must-do experiences in Abu Dhabi</h4>
                <p class="card-content">
                Treat yourself to a once-in-a-lifetime holiday
                experience and stay at one of Abu Dhabi's most luxurious hotels.
                Choose from vibrant private island retreats, majestic desert escapes
                and exciting glamping experiences.</p><br>
            </div>
            &nbsp;&nbsp;
             <div class="card card-rounded-corners  p-4">
                <img class="img-rounded-corners" src="PARIS.jpg" width="250px">
                <h4 class="card-title">Paris
                    Capital of France</h4>
                    <p class="card-content">Paris, France's capital, is a major 
                European city and a
                 global center for art, fashion, gastronomy and culture. Its 19th-century
                cityscape is crisscrossed by wide boulevards and the River Seine. 
                     Beyond such landmarks as the Eiffel Tower and the 12th-century.</p><br>

             </div>&nbsp;&nbsp;
             <div class="card card-rounded-corners card-outline p-4">
                <img class="img-rounded-corners" src="manali.jpg" width="200px">
                <h4 class="card-title">
                    ManaliTown in Himachal Pradesh</h4>
                    <p class="card-content">Manali is a high-altitude Himalayan resort town 
                        in India’s northern Himachal Pradesh state. It has a reputation as a 
                        backpacking center and honeymoon destination. Set on the Beas River, it’s 
                        a gateway for skiing in the Solang Valley and trekking in Parvati Valley.</p><br>
            </div>&nbsp;
            <div class="card card-rounded-corners card-outline p-4">
                <img class="img-rounded-corners" src="montreal-canada.jpg" width="200px">
                <h4 class="card-title">
                    Montreal, Canada </h4>
                    <p class="card-content">This is the best place in the entire nation of 
                        Canada with tourists flooding the area. The city is majestic with
                         a French tone to it. The historic area is filled with quaint shops
                          and cafés which is why this city gives an experience of Europe in 
                          North America. One must always visit the Notre Dame Basilica when here. 
                        </p><br>
            </div>&nbsp;
            <div class="card card-rounded-corners card-outline p-4">
                <img class="img-rounded-corners" src="arizona-canyon.jpg" width="200px">
                <h4 class="card-title">
                    Arizona, The Grand Canyon:</h4>
                    <p class="card-content">This place is a natural wonder situated 
                        in Arizona state of the United States of America. It is one 
                        of the most beautiful places on the entire planet. 
                        The place's geology has been formed over the past two billion 
                        years and it is 277 miles long canyon itself. It was formed 
                        by River Colorado which still flows through it.        

                        </p><br>&nbsp;&nbsp;
            </div>
            <div class="card card-rounded-corners p-4">
                <img class="img-rounded-corners" src="turkey.jpg" width="200px">
                <h4 class="card-title">
                    Turkey</h4>
                    <p class="card-content">
             This country is situated on Asia and Europe border
            and Istanbul is its capital city. This country
            is a great mix of culture, food and ancient monuments.
             It has a rich cultural history and significance.
            It is an Islamic country with a secular government, 
            so it's a good place for Western tourists to experience Islamic culture. This country is a mix of the new and old altogether.  
           </p>&nbsp;&nbsp;           
            </div>

                </div>
            </div>
          </div>

            </div>
          </div>
        <div id="sample" class="carousel slide" data-bs-ride="carousel">
            <div class="carousel-indicators">
                <button type="button"  data-bs-target="#sample" data-bs-slide-to="0" class="active"></button>
                <button type="button"  data-bs-target="#sample" data-bs-slide-to="1"></button>
                <button type="button"  data-bs-target="#sample" data-bs-slide-to="2"></button>
            </div>
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img src="down.jpg" width="100%" height="550px">
                    <div class="absolute">
                        <h3>EXPLORE DISCOVER TRAVEL</h3>
                    </div>
                    <div class="absolute1">
                        <h1>Adventure.....</h1>
                    </div>
                </div>
                <div class="carousel-item">
                    <img src="img4.jpg" width="100%" height="550px">
                    <div class="absolute2">
                        <h5>
                            “When life gives you mountains, put on your boots and hike.” — ...<br>
                            “The mountains whisper for me to wander; my soul hikes to the call.” — ...<br>
                            “Today is your day! ...
                        </h5>
                    </div>
                </div>
                <div class="carousel-item ">
                    <img src="three.jpg" width="100%" height="550px">
                    <div class="absolute3">
                        <h1>Explore the Beauty of <br>
                            the Beautiful World</h1>
                            <br>
                        <button type="button1" class="btn btn-outline-primary btn-rounded-corners">Explore!</button>
                    </div>
                </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#sample" data-bs-slide="prev">
                <span class="carousel-control-prev-icon"></span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#sample" data-bs-slide="next">
                <span class="carousel-control-next-icon"></span>
            </button>
        </div>
    </div>
    <br>

    </div>
    <div class="container mt-3 p-2">
        <div class="row">
        <div class="card p-4" >
            <img src="dubai.jpg" class="img-rounded-pill" width="200px">
            <h3 class="card-title justify-content-center">Dubai <br>
            4 days trip<br>30,000</h3>
            <button type="button" class="btn btn-outline-success">Book this tour</button>
        </div>&nbsp;&nbsp;&nbsp;&nbsp;
        <br>
        <div class="card p-4" >
            <img src="PARIS.jpg" class="img-rounded-pill" width="250px">
            <h3 class="card-title justify-content-center">Paris <br>
            3 days trip<br>1,00,000</h3>
            <button type="button" class="btn btn-outline-success">Book this tour</button>
    </div>&nbsp;&nbsp;&nbsp;&nbsp;
    <br>
    <div class="card p-4" >
        <img src="manali.jpg" class="img-rounded-pill" width="250px">
        <h3 class="card-title justify-content-center">Manali <br>
        5 days trip<br>80,000</h3>
        <button type="button" class="btn btn-outline-success">Book this tour</button>
</div>&nbsp;&nbsp;&nbsp;&nbsp;
<br>
<div class="card p-4" >
    <img src="montreal-canada.jpg" class="img-rounded-pill" width="250px">
    <h3 class="card-title justify-content-center">Montreal Canada <br>
    1 week trip<br>3,00,000</h3>
    <button type="button" class="btn btn-outline-success">Book this tour</button>
</div>&nbsp;&nbsp;&nbsp;&nbsp;
<br>
<div class="card p-4" >
    <img src="turkey.jpg" class="img-rounded-pill" width="250px">
    <h3 class="card-title justify-content-center">Turkey <br>
    3 days trip<br>1,00,000</h3>
    <button type="button" class="btn btn-outline-success">Book this tour</button>
</div>&nbsp;&nbsp;&nbsp;&nbsp;
<br>
<div class="card p-4" >
    <img src="arizona-canyon.jpg" class="img-rounded-pill" width="250px">
    <h3 class="card-title justify-content-center">Ariyzona Canyon<br>
    3 days trip<br>1,00,000</h3>
    <button type="button" class="btn btn-outline-success">Book this tour</button>
</div>&nbsp;&nbsp;&nbsp;&nbsp;
<br>
</div>
<br>
<br>
<div class="container-fluid bg-dark text-white">
    <div class="row">
        <div class="col p-5 bg-dark">
        <h5 class="justify-content-center">  Contact us</h5>
        <p>Responsibility<br>
            Google.org<br>
            Sustainability<br>
            Crisis Response<br>
            Diversity & Inclusion<br>
            Accessibility<br>
            Transparency<br>
            Digital Wellbeing<br>
            Safety Centre<br>
            Human Rights</p>
    </div>
    <div class="col p-5 bg-dark">
        <p>More about us<br>
            Contact us<br>
            Investor relations<br>
            Careers<br>
            Locations<br>
            Blog<br>
            Think with Google</p>
    </div>
    <div class="col p-5 bg-dark">
        <p>Policy
            Application security<br>
            Software principles<br>
            Unwanted software policy<br>
            Responsible supply chain<br>
            Extended workforce<br>
            Community guidelines<br>
            How our business works</p>
    </div>
</div>
</div>

</body>
</html>
