<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="link.css">
    <title>Home Milk Delivery Service</title>
    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <!-- Custom CSS -->
    <style>
        /* Light mode styles */
        body {
            background-color: #f8f9fa;
            color: #000;
            font-family: Arial, sans-serif;
        }
        .navbar, .footer {
            background-color: #343a40;
        }
        .jumbotron {
            background-color: #007bff;
            color: #fff;
            padding: 50px 0;
        }
        .feature-box {
            border: 1px solid #ccc;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 5px;
            background-color: #fff;
        }
        .jumbotron .row {
            align-items: center;
        }
        .jumbotron img {
            max-width: 100%;
            border-radius: 50%;
        }

        /* Dark mode styles */
        body.dark-mode {
            background-color: #121212;
            color: #fff;
        }
        .navbar.dark-mode, .footer.dark-mode {
            background-color: #212529;
        }
        .jumbotron.dark-mode {
            background-color: #333;
            color: #fff;
        }
        .feature-box.dark-mode {
            background-color: #1f1f1f;
            border-color: #333;
        }

        .social-container {
            
            margin: 40vh auto;
            text-align: center;
            width: 500px;


        }

        .social-icons {
            padding: 0;
            list-style: none;
            margin: 1em;

            li {
                 display: inline-block;
                 margin: 0.15em;
                 position: relative;
                 font-size: 1.2em;

                }

             i {
                 color: #fff;
                 position: absolute;
                 top: 21px;
                 left: 21px;
                 transition: all $timing ease-out;
                }
        }

        .related-products {
  margin-top: 40px;
}

.related-products h3 {
  margin-bottom: 20px;
}

.related-products .product {
  display: inline-block;
  margin-right: 20px;
}

.related-products .product img {
  width: 150px;
}
    
       
  

    </style>
</head>
<body>
    <header>
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
            <div class="container">
                <a class="navbar-brand" href="https://www.instagram.com/maziwa_fresh_mtindi?igsh=NTc4MTwNjQ2YQ">MAZIWA_FRESH_MTINDI</a>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>

                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav ml-auto">
                        <li class="nav-item active">
                            <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#features">Features</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#contact">Contact</a>
                        </li>
                        <li class="nav-item">
                            <button class="btn btn-outline-light ml-3" id="dark-mode-toggle">Toggle Dark Mode</button>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>

    <section class="jumbotron">
        <div class="container">
            <div class="row">
                <div class="col-md-6">
                    <img src="./IMG-20240522-WA0002~2.jpg" alt="Your Photo">
                </div>
                <div class="col-md-6 text-right">
                    <h1 class="display-4">Fresh Milk Delivered to Your Doorstep</h1>
                    <p class="lead">Subscribe now for daily delivery and join our WhatsApp channel!</p>
                    <a href="https//whatsapp.com/channel/0029VaauMwuLNSa86Gc37W2u" class="btn btn-primary btn-lg">Subscribe</a>
                </div>
            </div>
        </div>
    </section>

    <section id="features" class="container">
        <h2 class="text-center mb-5">Features</h2>
        <div class="row">
            <div class="col-md-4">
                <div class="feature-box">
                    <h3>My Passion for Dairy</h3>
                    <p>I come from a long line of dairy farmers and have been perfecting my craft for over 20 years.
                         Providing high-quality, fresh milk is my mission.</p>
                </div>
            </div>
            <div class="col-md-4">
                <div class="feature-box">
                    <h3>Sustainable Practices</h3>
                    <p>My farm utilizes eco-friendly methods to ensure the health and happiness of my herd. We prioritize animal welfare and environmental stewardship.</p>
                </div>
            </div>
            <div class="col-md-4">
                <div class="feature-box">
                    <h3>Community-Focused</h3>
                    <p>By offering local milk delivery, I hope to build strong relationships with my neighbors and support our close-knit community..</p>
                </div>
            </div>
        </div>
    </section>

    <div class="related-products">
        <h3>Our Milk Products and Pricing</h3>
        <div class="product">
          <img src="./IMG-20240522-WA0005~2.jpg" alt="Related Product 1">
          <h4>Fresh Milk</h4>
          <p>Price: 1000Tshs</p>
          
        </div>
        <div class="product">
          <img src="./IMG-20240522-WA0003~2.jpg" alt="Related Product 2">
          <h4>Mtindi Mzito</h4>
          <p>Price: 2000Tshs</p>
          
        </div>
        <div class="product">
          <img src="./IMG-20240522-WA0002~2.jpg" alt="Related Product 2">
          <h4>3 litres bottle</h4>
          <p>Price: 7000Tshs</p>
          
        </div>
        <div class="product">
          <img src="./-1138307988.jpg" alt="Related Product 2">
          <h4>Yogat</h4>
          <p>Price: 1500Tshs</p>
          
        </div>
        
          <div class="product">
            <img src="./IMG-20240522-WA0000~2.jpg" alt="Related Product 2">
            <h4>5 litres bottle</h4>
            <p>Price: 15000Tshs</p>
            
          </div>
          <div class="product">
            <img src="./IMG-20240522-WA0003~2.jpg" alt="Related Product 2">
            <h4>KARIBU UPATE BIDHAA DORE</h4>
            <p>////     ////</p>
            
          </div>
      </div>

    <footer id="contact" class="text-center py-4 footer">
       
            <div class="social-container">
                <ul class="social-icons">
                    <li><a href="https://www.instagram.com/maziwa_fresh_mtindi?igsh=NTc4MTwNjQ2YQ"><i class="fa fa-instagram"></i></a></li>
                   
                    <li><a href="selimweliandrew@gmail.com"><i class="fa fa-email"></i></a></li>
                    <li><a href="#"><i class="fa fa-facebook"></i></a></li>
                </ul>
            
        </div>
    </footer>

    <!-- Bootstrap JS and jQuery (optional) -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.4/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
    <!-- Dark Mode Toggle Script -->
    <script>
        document.getElementById('dark-mode-toggle').addEventListener('click', function () {
            document.body.classList.toggle('dark-mode');
            document.querySelector('.navbar').classList.toggle('dark-mode');
            document.querySelector('.jumbotron').classList.toggle('dark-mode');
            document.querySelector('.footer').classList.toggle('dark-mode');
            var featureBoxes = document.querySelectorAll('.feature-box');
            featureBoxes.forEach(function (box) {
                box.classList.toggle('dark-mode');
            });
        });
    </script>
</body>
</html>
