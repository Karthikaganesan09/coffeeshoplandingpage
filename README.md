<!DOCTYPE html>
<html>
<head>
    <title>
        COFFEE SHOP
    </title>
    <style>
         #navbar {
    position: fixed;
    top: 0;
    width: 100%;
    background-color: #d9dad5;
    z-index: 1000;
    padding: 10px 0;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.logo {
    font-size: 1.8rem;
    font-weight: bold;
    color: #333;
    margin-left: 20px;
}


.nav-text {
    margin-right: 20px;
}

#navbar ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    display: flex;
    gap: 20px;
}

#navbar ul li {
    display: inline;
}

#navbar ul li a {
    text-decoration: none;
    color: #333;
    font-size: 3rex;
    transition: color 0.3s ease;
}

#navbar ul li a:hover {
    color: #555;
}

.header {
    width: 100%;
    padding: 5px;
    text-align: center;
    background: #d7dcdb;
    color: #333;
    font-size: 30px;
}

        .hero {
            background-image: url('images/hero-bg.jpg');
            background-size: cover;
            background-position: center;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            color: white;
            text-align: center;
            padding-top: 80px;
            font-size: larger;
            margin-bottom: 100px;
        }
        #hero-text
        {
            margin-bottom: 200px;  
        }
        .hero h1 {
            font-size: 48px;
        }

        .hero p {
            font-size: 20px;
        }
        #about
        {
            align-items: center;
            background-image: url('images/about bg.jpg');
            background-size: cover;
            background-position: center;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            color: rgb(0, 0, 0);
            text-align: center;
            padding-top: 80px;
            font-size: larger;
            
        }
        .about-text{
font-size: x-large;
text-align: center;
margin-bottom: 200px;
max-width: 600px;
        }
      

.logo {
    justify-content: center;
    padding: 10px;
    text-align:baseline ;
    color: rgb(83, 19, 10);

}

#menu {
    font-family: 'Open Sans', sans-serif;
    text-align: center;
    background-color: #f4d9d9;
    padding: 50px 20px;
    font-size: larger; 
}

#menu h1 {
    font-family: 'Times New Roman', Times, serif;
    font-style: bold;
    font-size: xx-large;
    color: #444;
    margin-bottom: 40px;
}


.menu-item {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
    justify-items: center;
}


.menu-item img {
    width: 160px;
    height: 160px;
    object-fit: cover;
    border-radius: 50%;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease;
}

.menu-item img:hover {
    transform: scale(1.1);
}

.menu-item h3 {
    font-family:Verdana, Geneva, Tahoma, sans-serif;
    font-size: 1.5;
    color: #333;
    margin-top: 60px;
    margin-bottom: 3px;
}

.menu-item p {
    font-size: 1;
    color: #413737;
    margin-top: 60px;
    margin-bottom: 3px;
}


.menu-item div {
    text-align: center;
    padding: 20px;
    background: #e7f9eb;
    border-radius: 15px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.menu-item div:hover {
    transform: translateY(-10px);
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
}

@media (max-width: 600px) {
    #menu h1 {
        font-size: 2;
    }

    .menu-item img {
        width: 120px;
        height: 120px;
    }

    .menu-item h3 {
        font-size: 1.2;
    }

    .menu-item p {
        font-size: 0.9;
    }
}

#gallery {
    background-color: #daccc5;
    padding: 40px;
    text-align: center;
    font-size: larger; 
        
}

#gallery h1 {
    
    font-size: 2.5rem;
    color: #5a4636;
    margin-bottom: 20px;
}


.gallery-grid {
    
    display: flex;
    flex-direction: column;
    gap: 30px;
    align-items: center;
}

.gallery-item {
    display: flex;
    align-items: center;
    gap: 20px;
    max-width: 800px;
    margin: 0 auto;
}

.gallery-item.reverse {
    flex-direction: row-reverse;
}


.gallery-item img {
    width: 220px;
    height: 220px;
    object-fit: cover;
    border-radius: 10px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.gallery-item p {
    font-size: 1.2rem;
    color: #5a4636;
    text-align: justify;
    max-width: 500px;
    line-height: 1.6;
}
#contact {
    background-color: #dad8d8;
    padding: 50px 20px;
    text-align: center;
    color: #333;
}

#contact h2 {
    font-size: 2rem;
    margin-bottom: 20px;
    color: #444;
}

.contact-details {
    font-size: 1.2rem;
    line-height: 1.8;
}

.contact-details p {
    margin: 10px 0;
}

footer {
    background-color: #8b8d8d;
    padding: 15px 0;
    text-align: center;
    font-size: 0.9rem;
    color: #333;
}


  html {
    scroll-behavior: smooth;
}

    </style>
    <link rel="icon" href="images/favicon.png" type="image/x-icon">
</head>
<body>
   
    <header class="header">
        
        <nav id="navbar">
            <div class="logo"> BREW BLISS</div>
            <div class=" nav-text">
                <ul>
                <li>
                    <a href="#about">About</a>
                    <a href="#menu">Menu </a>
                    <a href="#gallery">Gallery</a>
                    <a href="#contact">Contact</a>
                </li>
            </ul>
        </div>
        </nav>
    </header>
    <section class="hero">
        <div id="hero-text">
        <h1> welcome to Brew Bliss</h1>
         <p >Your perfect cup of coffee awaits for you !</p>
         <p >Welcome to Brew Bliss, we're delighted to have you here! 
            Discover our finest brews ☕ 😊</p>
        </div>

    </section>
    <section id="about">
        <div class="about-text">
            <h1>Our Story</h1>
            <p>
                Welcome to Brew Bliss ☕, where every cup tells a story. Nestled in the heart of your city, we are more than just a coffee shop – we’re a haven for coffee enthusiasts ❤️ and a retreat for dreamers.</p>
        </div>
     </section>
     <section id="menu">
        <h1>Your Menu Item Is Here </h1>
        <br>
        <div class="menu-item"> 
        <img src="images/latte.jpg" alt="Latte">
        <h3>Latte</h3>
        <p>Rs 140.00</p>
        <img src="images/Espresso.jpg" alt="Espresso">
        <h3>Espresso</h3>
        <p>Rs 214.00</p>
        <img src="images/Cappuccino.jpg" alt="Cappuccino">
        <h3>Cappuccino</h3>
        <p>Rs 184.00</p>
        <img src="images/cofamericano.jpg" alt="Americano">
        <h3>Americano</h3>
        <p>Rs 190.00</p>
        <img src="images/Mocha.jpg" alt="Mocha">
        <h3>Mocha</h3>
        <p>Rs 250.00</p>

    </div>
     </section>
     <section id="gallery">
        <h1>Gallery</h1>
        <div class="gallery-grid">
        
            <div class="gallery-item">
                <img src="images/shop1.jpg" alt="Coffee Shop">
                <p>Welcome to Our Coffee Haven. Discover the art of coffee through our curated gallery. From the rich aroma of freshly brewed espresso to the delicate swirls of frothy cappuccinos, each cup tells a story of passion and craftsmanship.</p>
            </div>
            <div class="gallery-item reverse">
                <p>More Than Just Coffee. It’s not just about the beverages—it’s about the moments. Whether you’re here for a morning pick-me-up, a cozy afternoon, or a late-night catch-up, our gallery captures the ambiance of every cup shared at our coffee shop.</p>
                <img src="images/shop2.jpg" alt="Barista">
            </div>
        </div>
    </section>
    
     <section id="contact">
        <h2>Contact Us</h2>
        <div class="contact-details">
            <p>123 Coffee Lane, Espresso City</p>
            <p>+1 234 567 890</p>
        </div>
         </section>
         <footer>
            <p>2025 Brew Bliss. All rights reserved.</p>
     </footer>
</body>
</html>
