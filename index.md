# Welcome to my blog

I'm glad you are here. I plan to talk about ...

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing page</title>
    <link href="style.css" type="text/css" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2? family = Roboto: ital @ 1 & display = swap" rel="stylesheet">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
</head>

<body>
    <header id="header">
        <div>
            <img id="header-img" src="images/barbecue.png"  width="160vw"  alt="barbecue logo" >
        </div>

        <nav id="nav-bar">
            <ul>
                <li><a class="nav-link" href="#features">Features</a></li>
                <li><a class="nav-link" href="#howItWorks">How It Works</a></li>
                <li><a class="nav-link" href="#pricing">Pricing</a></li>
            </ul>
        </nav>
    </header>

    <div class="container">
        <section>
            <h1 id="heading">Handcrafted, home-made masterpieces</h1>
            <form id="form" action="https://www.freecodecamp.com/email-submit">
                <input id="email" type="email" name="email" placeholder="Enter your email address" required>
                <input id="submit" type="submit" value="Get started" class="button">
            </form>
        </section>
        <section id="features">
            <div id="items">
                <div id="icon">
                    <img src="images/mejor-eleccion.png" alt="logo" width="50px">
                </div>
                <div>
                    <h2>Premium Materials</h2>
                    <p id="text" >Our grills with stainless steel high quality control panel, bringing beautiful silvery metal
                        gloss and more durable than regular panel, easy to clean.</p>
                </div>
            </div>
            <div id="items">
                <div id="icon">
                    <img src="images/envio-gratis.png" alt="free shipping logo" width="51px">
                </div>
                <div>
                    <h2>Fast Shipping</h2>
                    <p id="text">We make sure you recieve your grill as soon as we have finished making it. We also provide
                        free returns if you are not satisfied.</p>
                </div>
            </div>

            <div id="items">
                <div id="icon">
                    <img src="images/Sello de garantía.png" alt="warranty seal logo" width="50px">
                </div>
                <div>
                    <h2>Quality Assurance</h2>
                    <p id="text">For every purchase you make, we will ensure there are no damages or faults and we will check and
                        test your grill.</p>
                </div>
            </div>
        </section>

        <section id="howItWorks">
            <iframe id="video" width="600" height="340" src="https://www.youtube.com/embed/5r6wdOSQHl0" frameborder="0"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                allowfullscreen></iframe>
        </section>

        <section id="pricing">
            <div id="product">
                <p id="grill">Char-Broil Classic</p>
                <P id="price">US $799.00</P>
                <ul>
                    <li>Brand: Weber</li>
                    <li>Mat.: Porcelain, aluminum</li>
                    <li>Color: Black</li>
                    <li>31 x 59 x 62 inches</li>
                </ul>
                <button type="submit">SELECT</button>
            </div>
            <div id="product">
                <p id="grill">Weber Genesis II</p>
                <P id="price">US $ 139.99</P>
                <ul>
                    <li>Brand: Char-Broil</li>
                    <li>Material: Other Materials</li>
                    <li>Color: Black</li>
                    <li>Weight: 43 Pounds</li>
                </ul>
                <button type="submit">SELECT</button>
            </div>
            <div id="product">
                <p id="grill">Cuisinart Portable</p>
                <p id="price">US $ 24.87 </p>
                <ul>
                    <li>Brand: Cuisinart</li>
                    <li>Material: Steel</li>
                    <li>Color: Red</li>
                    <li>4.5 x 14.5 x 15 inches</li>
                </ul>
                <button type="submit">SELECT</button>
            </div>
        </section>
    </div>
    <footer>
        <nav id="nav-footer">
            <ul id="nav-footer">
                <li><a href="#features">Privacy</a></li>
                <li><a href="#features">Terms</a></li>
                <li><a href="#features">Contact</a></li>
            </ul>
        </nav>
        <p id="copyright">&copy;Copyright 2021, BBQ Elements</p>
    </footer>
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
</body>

</html>
