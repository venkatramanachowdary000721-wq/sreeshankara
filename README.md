<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sree Shankara Photo Framing</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    line-height: 1.6;
}

/* Header */
header {
    background: #222;
    color: #fff;
    padding: 15px 40px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header h1 {
    color: gold;
}

nav a {
    color: #fff;
    margin-left: 20px;
    text-decoration: none;
}

nav a:hover {
    color: gold;
}

/* Hero */
.hero {
    height: 90vh;
    background: url('https://images.unsplash.com/photo-1513364776144-60967b0f800f') no-repeat center/cover;
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    text-align: center;
}

.hero h2 {
    font-size: 40px;
}

.btn {
    background: gold;
    padding: 10px 20px;
    color: black;
    text-decoration: none;
    margin-top: 10px;
    display: inline-block;
}

/* Sections */
section {
    padding: 50px;
    text-align: center;
}

.services {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
}

.card {
    background: #f4f4f4;
    margin: 15px;
    padding: 20px;
    width: 250px;
    border-radius: 10px;
}

/* Contact */
.contact p {
    margin: 10px 0;
}

/* Footer */
footer {
    background: #222;
    color: white;
    text-align: center;
    padding: 15px;
}
</style>

</head>
<body>

<!-- Header -->
<header>
    <h1>Sree Shankara Photo Framing</h1>
    <nav>
        <a href="#home">Home</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<!-- Hero -->
<section class="hero" id="home">
    <div>
        <h2>Beautiful Frames for Divine Moments</h2>
        <p>Specialized in Gods Photo Frames</p>
        <a href="#contact" class="btn">Contact Now</a>
    </div>
</section>

<!-- Services -->
<section id="services">
    <h2>Our Services</h2>
    <div class="services">
        <div class="card">
            <h3>Gods Photo Frames</h3>
            <p>High-quality divine photo frames for your home and temples.</p>
        </div>
        <div class="card">
            <h3>Custom Framing</h3>
            <p>We create custom frames as per your needs and design.</p>
        </div>
        <div class="card">
            <h3>Wall Decoration Frames</h3>
            <p>Decorative frames to enhance your interiors.</p>
        </div>
    </div>
</section>

<!-- Contact -->
<section id="contact" class="contact">
    <h2>Contact Us</h2>
    <p><strong>Phone:</strong> 098492 93852</p>
    <p><strong>Address:</strong><br>
    H. No. 7-1-608, Beside Hanuman Temple Arch,<br>
    Ameerpet, Hyderabad, Telangana 500016</p>
</section>

<!-- Footer -->
<footer>
    <p>© 2026 Sree Shankara Photo Framing | All Rights Reserved</p>
</footer>

</body>
</html>
