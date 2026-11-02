# commercial-website
## Date:02.11.2026
## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
## STEP 1
Create an HTML file (index.html)

## STEP 2
Create a CSS file (style.css)

## STEP 3
Include a navigation bar with links to different sections.

## STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

## STEP 5
Include social media links at the footer with copyright information.

## STEP 6
Define global styles for fonts, colors, and layout.

## STEP 7
Style the header, navigation bar, and sections.

## STEP 8
Use Flexbox for layout design.

## STEP 9
Add hover effects and transitions for interactivity.

## STEP 10
Add Images and Media.

## STEP 11
Use optimized images for a professional look.

## STEP 12
Open the HTML file in a browser to check layout and functionality.

## STEP 13
Fix styling issues and refine content placement.

## STEP 14
Deploy the website.

## STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
## index.html
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>StudyBloom | Stationery & Study Essentials</title>

    <link rel="stylesheet" href="style.css">

    <link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&family=Playfair+Display:wght@500;600;700&display=swap" rel="stylesheet">
</head>

<body>

    <!-- ANNOUNCEMENT BAR -->
    <div class="announcement">
        ✿ A little happiness in every order · Free shipping above ₹999 ✿
    </div>

    <!-- HEADER -->
    <header>
        <div class="logo">Study<span>Bloom.</span></div>

        <nav>
            <a href="#home">Home</a>
            <a href="#shop">Shop</a>
            <a href="#categories">Categories</a>
            <a href="#about">Our Story</a>
            <a href="#contact">Contact</a>
        </nav>

        <a href="#account" class="account">My Account ♡</a>
    </header>

    <!-- HERO SECTION -->
    <section class="hero" id="home">

        <div class="hero-content">
            <p class="small-title">✿ YOUR HAPPY LITTLE CORNER ✿</p>

            <h1>Make every day<br>
                a little more <span>beautiful.</span>
            </h1>

            <p class="description">
                Pretty stationery, thoughtful essentials
                and little things that make studying
                feel like a dream.
            </p>

            <a href="#shop" class="shop-btn">Explore Collection →</a>
        </div>

        <div class="hero-image">
            <img src="https://images.unsplash.com/photo-1455390582262-044cdead277a?w=900"
                 alt="Aesthetic study desk">
        </div>

    </section>

    <!-- CATEGORIES -->
    <section id="categories" class="categories">

        <p class="small-title">FIND YOUR FAVOURITES</p>
        <h2>Shop by Category</h2>

        <div class="category-container">

            <div class="category-card">
                <img src="https://images.unsplash.com/photo-1531346878377-a5be20888e57?w=500"
                     alt="Notebooks">
                <h3>Notebooks</h3>
            </div>

            <div class="category-card">
                <img src="https://images.unsplash.com/photo-1455390582262-044cdead277a?w=500"
                     alt="Pens">
                <h3>Study Essentials</h3>
            </div>

            <div class="category-card">
                <img src="https://images.unsplash.com/photo-1495446815901-a7297e633e8d?w=500"
                     alt="Books">
                <h3>Books & Journals</h3>
            </div>

        </div>
    </section>

    <!-- PRODUCTS -->
    <section id="shop" class="products">

        <p class="small-title">HANDPICKED WITH LOVE</p>
        <h2>Our Little Collection</h2>

        <div class="product-container">

            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1531346878377-a5be20888e57?w=500"
                     alt="Notebook">
                <h3>Pastel Dream Notebook</h3>
                <p>₹299</p>
                <button onclick="addToCart('Pastel Dream Notebook')">
                    Add to Cart ♡
                </button>
            </div>

            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1455390582262-044cdead277a?w=500"
                     alt="Journal">
                <h3>Daily Journal</h3>
                <p>₹399</p>
                <button onclick="addToCart('Daily Journal')">
                    Add to Cart ♡
                </button>
            </div>

            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1517842645767-c639042777db?w=500"
                     alt="Planner">
                <h3>Pretty Study Planner</h3>
                <p>₹349</p>
                <button onclick="addToCart('Pretty Study Planner')">
                    Add to Cart ♡
                </button>
            </div>

            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1516979187457-637abb4f9353?w=500"
                     alt="Books">
                <h3>Reading Journal</h3>
                <p>₹449</p>
                <button onclick="addToCart('Reading Journal')">
                    Add to Cart ♡
                </button>
            </div>

        </div>

    </section>

    <!-- SPECIAL BANNER -->
    <section class="offer">
        <p>✿ A LITTLE TREAT FOR YOU ✿</p>
        <h2>Make room for more creativity.</h2>
        <p>Discover your next favourite study essential.</p>
        <a href="#shop">Shop Now →</a>
    </section>

    <!-- ABOUT -->
    <section id="about" class="about">

        <div>
            <p class="small-title">A NOTE FROM US</p>
            <h2>Made for the love of little things.</h2>
        </div>

        <p>
            StudyBloom is a happy little space for stationery lovers.
            We believe that beautiful notebooks, lovely pens and
            thoughtful study essentials can make everyday moments
            feel special. Let's make learning a little more lovely!
        </p>

    </section>

    <!-- CUSTOMER REVIEWS -->
    <section class="reviews">

        <p class="small-title">KIND WORDS</p>
        <h2>Little notes from our customers</h2>

        <div class="review-container">

            <div class="review-card">
                <p>"Everything is so pretty! Loved my order."</p>
                <h4>— Happy Customer ♡</h4>
            </div>

            <div class="review-card">
                <p>"My study desk feels so much more special."</p>
                <h4>— Stationery Lover ♡</h4>
            </div>

            <div class="review-card">
                <p>"Beautiful products and lovely collection."</p>
                <h4>— Book Lover ♡</h4>
            </div>

        </div>
    </section>

    <!-- ACCOUNT -->
    <section id="account" class="account-section">

        <p class="small-title">JOIN OUR LITTLE WORLD</p>
        <h2>Create Your Account ♡</h2>

        <form onsubmit="createAccount(event)">
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <input type="password" placeholder="Create Password" required>
            <button type="submit">Sign Up</button>
        </form>

    </section>

    <!-- CONTACT -->
    <section id="contact" class="contact">

        <h2>Let's stay in touch!</h2>

        <p>Email: hello@studybloom.com</p>
        <p>Location: Chennai, Tamil Nadu</p>
        <p>We'd love to hear from you ♡</p>

    </section>

    <!-- FOOTER -->
    <footer>

        <h2>Study<span>Bloom.</span></h2>

        <p>Making everyday a little more beautiful ✿</p>

        <div class="social-links">
            <a href="https://www.instagram.com/">Instagram</a>
            <a href="https://www.pinterest.com/">Pinterest</a>
            <a href="https://www.facebook.com/">Facebook</a>
        </div>

        <p class="copyright">
            © 2026 StudyBloom. All Rights Reserved.
        </p>

    </footer>

    <script src="script.js"></script>

</body>
</html>
```
## style.css
```
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: Arial, sans-serif;
    background: #fff8f6;
    color: #493c42;
}

/* HEADER */

header {
    width: 100%;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    padding: 20px 5%;
    background: #f4dce4;
}

.logo {
    font-size: 28px;
    white-space: nowrap;
}

.logo span {
    color: #b65e7c;
}

nav {
    display: flex;
    flex-direction: row;
    gap: 25px;
}

nav a {
    text-decoration: none;
    color: #493c42;
}

/* HERO */

.hero {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
    gap: 40px;
    padding: 50px 7%;
    min-height: 450px;
    background: #fff0f2;
}

.hero-content {
    flex: 1;
}

.hero h1 {
    font-size: 45px;
    margin: 20px 0;
}

.hero h1 span {
    color: #c77f96;
}

.description {
    line-height: 1.8;
    margin: 20px 0;
}

.hero-image {
    flex: 1;
}

.hero-image img {
    width: 100%;
    height: 350px;
    object-fit: cover;
    border-radius: 15px;
}

.shop-btn {
    display: inline-block;
    padding: 13px 25px;
    background: #c77f96;
    color: white;
    text-decoration: none;
    border-radius: 25px;
}

/* ALL SECTIONS */

section {
    padding: 50px 5%;
    text-align: center;
}

section h2 {
    font-size: 30px;
    margin: 15px 0 30px;
}

/* CATEGORIES */

.category-container {
    display: flex;
    flex-direction: row;
    justify-content: center;
    gap: 25px;
    flex-wrap: nowrap;
}

.category-card {
    flex: 1;
    background: white;
    padding: 15px;
    border-radius: 12px;
}

.category-card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    border-radius: 10px;
}

/* PRODUCTS */

.products {
    background: #fff0f2;
}

.product-container {
    display: flex;
    flex-direction: row;
    justify-content: center;
    gap: 20px;
    flex-wrap: nowrap;
}

.product-card {
    flex: 1;
    min-width: 0;
    background: white;
    padding: 12px;
    border-radius: 12px;
}

.product-card img {
    width: 100%;
    height: 180px;
    object-fit: cover;
    border-radius: 10px;
}

.product-card h3 {
    margin: 15px 0;
}

.product-card p {
    margin: 10px;
    color: #b65e7c;
}

button {
    padding: 10px 18px;
    background: #c77f96;
    color: white;
    border: none;
    border-radius: 20px;
    cursor: pointer;
}

/* OFFER */

.offer {
    background: #eee8f8;
    padding: 55px 20px;
}

.offer a {
    display: inline-block;
    margin-top: 20px;
    color: white;
    background: #b69bcf;
    padding: 12px 25px;
    text-decoration: none;
    border-radius: 25px;
}

/* ABOUT */

.about {
    display: flex;
    flex-direction: row;
    align-items: center;
    gap: 40px;
    text-align: left;
}

.about > * {
    flex: 1;
}

/* REVIEWS */

.review-container {
    display: flex;
    flex-direction: row;
    gap: 20px;
}

.review-card {
    flex: 1;
    padding: 25px;
    background: white;
    border-radius: 12px;
}

/* ACCOUNT */

.account-section form {
    display: flex;
    flex-direction: column;
    gap: 15px;
    max-width: 350px;
    margin: auto;
}

.account-section input {
    padding: 13px;
    border: 1px solid #e5cbd3;
    border-radius: 20px;
}

/* FOOTER */

footer {
    background: #493c42;
    color: white;
    padding: 35px;
    text-align: center;
}

footer h2 {
    margin-bottom: 15px;
}

.social-links {
    display: flex;
    flex-direction: row;
    justify-content: center;
    gap: 25px;
    margin: 20px;
}

.social-links a {
    color: #f4b8ca;
    text-decoration: none;
}

/* HOVER EFFECTS */

.product-card,
.category-card,
.review-card {
    transition: 0.3s;
}

.product-card:hover,
.category-card:hover,
.review-card:hover {
    transform: translateY(-7px);
}

/* MOBILE RESPONSIVE */

@media (max-width: 768px) {

    header,
    nav,
    .hero,
    .about,
    .category-container,
    .product-container,
    .review-container {
        flex-direction: column;
    }

    .product-card,
    .category-card {
        width: 100%;<img width="1897" height="1011" alt="Screenshot 2026-11-02 143519" src="https://github.com/user-attachments/assets/f8d92cea-6f95-4495-a6b6-b6805ac474da" />

    }

    .hero h1 {
        font-size: 32px;
    }
}
```
## script.js
```
function addToCart(productName) {
    alert(productName + " added to your cart! ♡");
}

function createAccount(event) {
    event.preventDefault();
    alert("Welcome to StudyBloom! Your form was submitted successfully.");
}
```
## OUTPUT
<img width="1897" height="1011" alt="Screenshot 2026-11-02 143519" src="https://github.com/user-attachments/assets/cc942802-53ea-4070-8e73-3776a26b4852" />
<img width="1896" height="1015" alt="Screenshot 2026-11-02 143553" src="https://github.com/user-attachments/assets/1d3c081c-558e-4265-ab86-5b401a0699c3" />
<img width="1883" height="1015" alt="Screenshot 2026-11-02 143611" src="https://github.com/user-attachments/assets/188ee285-7c7e-4d3e-bd47-ef4c3e203e71" />
<img width="1896" height="965" alt="Screenshot 2026-11-02 143630" src="https://github.com/user-attachments/assets/d4fe1799-c8b7-48cd-ad49-d48ab54c581e" />


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
