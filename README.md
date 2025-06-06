# Final Project and Deployment

## Objectives
Build a fully functional web application.
Apply HTML, CSS, and JavaScript concepts learned.
Deploy the project using GitHub Pages, Netlify, or Vercel.

## Instructions
Choose one of the following project ideas:
Blog Website: Implement a multi-page site with navigation.
Ecommerce Website: Implement a multi-page site with navigation.

>[!NOTE]
> - Include at least:
> - A responsive design.
> - JavaScript interactivity.
> - A deployment link.

## Tasks

Create a well-structured HTML5 document.
Use at least 5 different HTML elements.
Ensure semantic correctness.

Good luck and happy coding! 🚀💻


//HTML Part
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="refresh" content="30">

    <title>VOH&apos;S ENTERPRISES</title>
    <link rel="stylesheet" href="voh.css">
</head>
<body oncontextmenu="return false">
   
    <nav id="navbar">
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#products">Products</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#about us">About us</a></li>
            <li><a href="#contacts">Contacts</a></li>
            <li><a href="#social media">Socials</a></li>
        </ul>
    </nav>
    <h1 class="voh">WELCOME TO VOH&apos;S ENTERPRISES</h1>
    <img class="cof" src="Images/DALL·E 2025-03-22 23.18.23 - A cozy and modern coffee shop with wooden tables and chairs, warm ambient lighting, and a welcoming atmosphere. Customers are sitting at tables, enjoy.webp" alt="Voh's Coffee Shop">
    <!--home section-->
    <section id="home">
        <h1>VOH'S COFFEE SHOP</h1>
        <p>Welcome to Voh&apos;s Enterprises where greatness meets quality</p>
        <p>We render quality and affordable services to our customers</p>
        <p>You can create an account to ensure seamless and continuous access to our services and get to be notified any time we add new products at our stores</p>
        <p>Click here to <a href="login.html">create account</a></p>
    </section>
    <!--products sction-->
    <section id="products">
        <h1>Our Products</h1>
        <h2>These are the products we offer</h2>
        <h3>Coffee Varieties</h3>
        <ul class="items">
            <li>Plain coffee</li>
            <img class="p"  src="Images/DALL·E 2025-03-22 23.17.00 - A simple cup of plain black coffee in a classic white ceramic mug, placed on a wooden table with coffee beans scattered around, minimalistic and cozy .webp" alt="Plain coffee"><br>
            <li>Lemon coffee</li>
            <img class="p" src="Images/DALL·E 2025-03-22 23.16.26 - A steaming cup of lemon coffee in a glass mug, garnished with a fresh lemon slice and a drizzle of honey, placed on a bright and fresh kitchen counter.webp" alt="Lemon coffee"><br>

            <li>Ginger coffee</li>
            <img class="p" src="Images/DALL·E 2025-03-22 23.16.43 - A steaming cup of ginger coffee in a rustic ceramic mug, garnished with fresh ginger slices and cinnamon sticks, placed on a wooden table with a cozy,.webp" alt="Ginger coffee"><br>
        </ul>
        <h3>Snacks</h3>
        <ul class="items">
            <li>Mandazi</li>
            <img class="p" src="Images/DALL·E 2025-03-22 23.54.32 - A plate of freshly made Mandazi, golden brown and fluffy, served on a wooden table with a cup of tea in the background. The setting is warm and inviti.webp" alt="Mandazi"><br>

            <li>Ngumu</li>
            <img class="p" src="Images/DALL·E 2025-03-22 23.54.40 - A plate of Ngumu, a traditional Kenyan hard-baked snack, cut into square pieces and placed on a wooden tray. The snack looks crispy and dense, served .webp" alt="Ngumu"><br>
            <li>Doughnuts</li>
            <img class="p"  src="Images/DALL·E 2025-03-22 23.54.47 - A plate of freshly baked doughnuts, golden brown and dusted with powdered sugar, arranged on a wooden table with a cup of coffee in the background. Th.webp" alt="Doughnuts"><br>
            <li>Bread</li>
            <img class="p" src="Images/DALL·E 2025-03-22 23.54.54 - A loaf of freshly baked bread with a golden crust, sliced open to reveal its soft interior, placed on a wooden cutting board with butter and a knife b.webp" alt="Bread"><br>
            <li>Cakes</li>
            <img class="p" src="Images/DALL·E 2025-03-22 23.55.00 - A beautifully decorated cake with layers of creamy frosting, topped with fresh berries and chocolate shavings, placed on a wooden cake stand. A cozy c.webp" alt="Cakes"><br>
        </ul>
    </section>
    <!--Services section-->
    <section id="services">
        <h1>Our Services</h1>
        <h2>We offer the following services:</h2>
        <ul>
            <li>Free delivery</li>
            <li>After sale services</li>
            <li>Reservations for group</li>
        </ul>
    </section>
    <!--About section-->
    <section id="about us">
        <nav class="about">
        <h1 class="about">About us</h1>
        <p>Voh's Enterprises is an entity that dealers in fast food and drinks </p>
        <p>We prepare delicious cups of coffee and snacks that leaves you longing for every sip and bite too</p>
        <p>Deliciousness is our motto</p>
        </nav>
    </section>
    <!--Contacts section-->
    <section id="contacts">
        <h1>Reach us through the following</h1>
        
        <p><strong>Address:</strong>Kagochi, off main campus,Karatina</p>
        <p><strong>Phone:</strong>+254795846971 || +25498108226</p>
        <p><strong>Email:</strong>carlosmarcus050@gmail.com</p>
        <p>Visit the <a href="https://www.voh'senterprises.com" target="_blank"> website</a> for more information </p>
    </section>
    <!--social media section-->
    <section id="social media">
        <h2>Follow us on:</h2>
        <div class="social">
        <a href=https://www.facebook.com/Vohenterprises target="_blank">Facebook</a>
        <a href=https://www.instagram.com/vohenterprises target="_blank">Instagram</a>
        <a href=https://www.tiktok.com/vohenterprises target="_blank">Tiktok</a>
        <a href=https://www.x.com/vohenterprises target="_blank">X</a>
        <a href=https://www.linkedin.com/vohenterprises target="_blank">Linkedin</a>

        
         </div>
    </section><br>
    <footer>&copy;Voh&apos;s Enterprises 2025</footer>
</body>
</html>

//CSS Part
nav{
    background-color:peachpuff;   
    padding: 10px 0;
    top: 0;
    width: 100%;
    z-index: 1000;
    border-radius: 10px;
    
}
body{
    background-attachment: fixed;
    background-color: whitesmoke;
}
nav ul {
    list-style-type: none;
    padding: 0;
    text-align:center;
    font-weight: bolder;
}
nav ul li {
    display: inline;
    margin:2px;
}
nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}
nav ul li a:active {
    text-decoration: underline;
    background-color: #00ff00;
}
@keyframes rotate{
    from { 
        transform: rotate(0deg);
    }
    to {
        transform: rotate(360deg);
    }
}
.voh{
    background-color: #00ff00;
    text-align: center;
    border-radius: 50%;
    animation-name:rotate;
    position: sticky;
    animation-duration: 5s;
    animation-timing-function: linear;
    animation-iteration-count: infinite;
}
img{
    width: 100%;
    height: auto;
    border-radius: 10px;
    align-items: center;
}
.cof{
    width: 100%;
    height: auto;
}
.items{
    list-style-type: none;
    font-weight: bolder;
    -webkit-box-reflect: right;
    
    
}
#home{
    background-color: antiquewhite;
    font-weight: bold;
}
#products{
    background-color: aquamarine;
    text-align: left;
}
#services{
    background-color: bisque;
    list-style-type: none;
    background-image: url(Photo by Lisa from Pexels from Pexels: https://www.pexels.com/photo/food-inside-display-chiller-1855214/);
}
#contacts{
    background-color: azure;
}
.about{
    background-color: dimgrey;
    font-family: Georgia, 'Times New Roman', Times, serif;
    font-weight: bolder;
}
.social a{
    color: blue;
    margin: 0 5px;
    text-decoration: none;
    border-radius: 10px;
}
.social a:hover{
    text-shadow: #00ff00;
}
footer{
    background-color: wheat;
    text-align: center;
    font-weight: bolder;
    font-size: large;
}
@keyframes bounce{
    0%, 20%, 40%, 60%, 80%, 100%{
        transform: translateY(0);   
    }
    50%{
        transform: translateY(350px);
    }
    70%{
        transform: translateY(15px);

    }
}
.p{
    background-color: #333;
    animation: forwards;
    animation-name: bounce;
    animation-duration: 4s;
    animation-timing-function: ease-in-out;
    animation-duration: 2;
    animation-iteration-count: infinite;
    display:flexbox;
}

//Deployment Link
https://Steve050-carl.github.io/Voh-Enterprises/

