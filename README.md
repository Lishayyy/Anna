<!DOCTYPE html>
<html lang="en">

<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Gifts by Anna | Custom Resin Art & Gifts</title>
<link rel="stylesheet" href="style.css">

<style>
body {
    font-family: Arial;
    margin: 0;
}

nav {
    display: flex;
    justify-content: space-between;
    padding: 15px;
    background: white;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.logo {
    font-size: 22px;
    font-weight: bold;
    color: #d4a373;
}

.nav-links a {
    margin-left: 20px;
    text-decoration: none;
    color: black;
}

.hero {
    height: 70vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    color: white;
    text-align: center;
    background:
        linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)),
        url("https://images.unsplash.com/photo-1513201099705-a9746e1e201f") center/cover;
}

.hero-btn {
    background: #e5989b;
    color: white;
    padding: 12px 20px;
    border-radius: 5px;
    text-decoration: none;
    margin-top: 15px;
}

.section {
    padding: 50px 10%;
}

.section-title {
    text-align: center;
    font-size: 30px;
    margin-bottom: 40px;
}

.grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
}

.card {
    background: white;
    border-radius: 10px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    overflow: hidden;
    text-align: center;
}

.card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
}

.card-content {
    padding: 15px;
}

footer {
    background: #222;
    color: white;
    text-align: center;
    padding: 30px;
}

.whatsapp-btn {
    background: #25D366;
    color: white;
    padding: 10px 20px;
    display: inline-block;
    margin-top: 10px;
    text-decoration: none;
    border-radius: 5px;
}
</style>
</head>

<body>

<nav>
    <div class="logo">Gifts by Anna</div>
    <div class="nav-links">
        <a href="#resin">Resin</a>
        <a href="#gifts">Gifts</a>
        <a href="#contact">Contact</a>
    </div>
</nav>

<section class="hero">
    <h1>Uniquely Yours. Uniquely Anna.</h1>
    <p>Customized resin art and personalized gifts.</p>
    <a href="#contact" class="hero-btn">Order Now</a>
</section>

<section id="resin" class="section">
    <h2 class="section-title">Resin Art</h2>
    <div class="grid">
        <div class="card">
            <img src="images/clock.jpeg.jpeg" alt="Wall Clock">
            <div class="card-content"><h3>Wall Clock</h3></div>
        </div>
        <div class="card">
            <img src="images/jhumkas.jpeg.jpeg" alt="Jhumkas">
            <div class="card-content"><h3>Jhumkas</h3></div>
        </div>
        <div class="card">
            <img src="images/weddingplate.jpeg.jpeg" alt="Wedding Plate">
            <div class="card-content"><h3>Wedding Plate</h3></div>
        </div>
        <div class="card">
            <img src="images/ring.jpeg.jpeg" alt=" Rings">
            <div class="card-content"><h3> Rings</h3></div>
        </div>
        <div class="card">
            <img src="images/phonecase.jpeg.jpeg" alt="Phone Case">
            <div class="card-content"><h3>Phone Case</h3></div>
        </div>
        <div class="card">
            <img src="images/locket.jpeg.jpeg" alt="Lockets">
            <div class="card-content"><h3>Lockets</h3></div>
        </div>
        <div class="card">
            <img src="images/keychain.jpeg.jpeg" alt="Keychains">
            <div class="card-content"><h3>Keychains</h3></div>
        </div>
    </div>
</section>

<section id="gifts" class="section">
    <h2 class="section-title">General Gifts</h2>
    <div class="grid">
        <div class="card">
            <img src="images/bouquet.jpeg.jpeg" alt="Bouquets">
            <div class="card-content"><h3>Bouquets</h3></div>
        </div>
        <div class="card">
            <img src="images/giftbox.jpeg.jpeg" alt="Gift Boxes">
            <div class="card-content"><h3>Gift Boxes</h3></div>
        </div>
        <div class="card">
            <img src="images/giftbasket.jpeg.jpeg" alt="Gift Basket">
            <div class="card-content"><h3>Gift Basket</h3></div>
        </div>
        <div class="card">
            <img src="images/bookmark.jpeg.jpeg" alt="Bookmark">
            <div class="card-content"><h3>Bookmark</h3></div>
        </div>
        <div class="card">
            <img src="images/sorrybox.jpeg.jpeg" alt="Sorry Box">
            <div class="card-content"><h3>Sorry Box</h3></div>
        </div>
        <div class="card">
            <img src="images/birthdaycard.jpeg.jpeg" alt="Birthday Cards">
            <div class="card-content"><h3>Birthday Cards</h3></div>
        </div>
    </div>
</section>

<footer id="contact">
    <h3>Contact Us</h3>
    <p>Email: qulain215@gmail.com</p>
    <p>WhatsApp: 03153066532</p>
    <a href="https://wa.me/923153066532" class="whatsapp-btn">Chat on WhatsApp</a>
</footer>

</body>
</html>
