//html code

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us -Muu Furniture Store</title>
    <link rel="stylesheet" href="/CSS/about.css">
</head>
<body>

<header>
    <div class="container">
        <h1><a href="Home.html">Muu Furniture Store</a> </h1>
        <nav>
            <ul>
                <li><a href="Home.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="login.html">Login</a></li>
            </ul>
        </nav>
    </div>
</header>

<section class="about">
    <div class="container">
        <h2>About Us</h2>
        <p>Welcome to Muu Furniture Store, where quality meets affordability. Since our establishment in 2024, we have been dedicated to providing our customers with stylish and durable furniture solutions for every room in their homes.</p>
        <p>At Furniture Store, we understand that furnishing your home is more than just filling empty spaces; it's about creating comfort, style, and a reflection of your unique personality. That's why we carefully curate our collection to offer a wide range of designs from modern and minimalist to classic and timeless pieces.<




//css code


* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header h1 a {

    color: #fff;
    text-decoration: none;
}
header {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
    
}
header .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header nav ul {
    list-style-type: none;
}

header nav ul li {
    display: inline-block;
    margin-right: 20px;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
}

/* About Section */
.about {
    padding: 50px 0;
    text-align: center;
}
body{
    background-image: url('/Source/WhatsApp\ Image\ 2024-07-26\ at\ 20.54.49_3dddd8fe.jpg');
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
}

.about .container {
    max-width: 800px;
    margin: 0 auto;
    padding: 0 20px;
}

.about h2 {
    font-size: 2.5em;
    margin-bottom: 20px;
    color: #333;
}

.about p {
    font-size: 1.2em;
    line-height: 1.6;
    margin-bottom: 20px;
    color: #666;
}

/* Footer */
footer {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

footer .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

footer nav ul {
    list-style-type: none;
}

footer nav ul li {
    display: inline-block;
    margin-right: 20px;
}

footer nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
}
