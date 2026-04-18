# Ignite
Streetwear
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ignite</title>

<!-- Font Graffiti -->
<link href="https://fonts.googleapis.com/css2?family=Permanent+Marker&display=swap" rel="stylesheet">

<style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    body {
        background: #000;
        color: #fff;
        font-family: Arial, sans-serif;
        overflow-x: hidden;
    }

    /* Navbar */
    .navbar {
        display: flex;
        justify-content: space-between;
        padding: 20px 40px;
        align-items: center;
    }

    .logo {
        font-family: 'Permanent Marker', cursive;
        font-size: 30px;
        color: #fff;
        text-shadow: 0 0 10px #ff0000, 0 0 20px #ff0000;
    }

    .nav-links a {
        color: #fff;
        margin-left: 20px;
        text-decoration: none;
        transition: 0.3s;
    }

    .nav-links a:hover {
        color: red;
    }

    /* Hero */
    .hero {
        height: 90vh;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        text-align: center;
    }

    .hero h1 {
        font-size: 80px;
        font-family: 'Permanent Marker', cursive;
        color: #fff;
        text-shadow: 
            0 0 10px #ff0000,
            0 0 20px #ff0000,
            0 0 40px #ff0000;
        animation: glow 1.5s infinite alternate;
    }

    @keyframes glow {
        from { text-shadow: 0 0 10px red; }
        to { text-shadow: 0 0 30px red; }
    }

    .hero p {
        margin-top: 20px;
        color: #aaa;
    }

    .btns {
        margin-top: 30px;
    }

    .btn {
        padding: 12px 25px;
        margin: 10px;
        border: none;
        background: red;
        color: #fff;
        cursor: pointer;
        transition: 0.3s;
    }

    .btn:hover {
        background: #fff;
        color: #000;
    }

    /* Footer */
    .footer {
        text-align: center;
        padding: 20px;
        border-top: 1px solid #222;
        margin-top: 50px;
    }
</style>
</head>

<body>

<!-- Navbar -->
<div class="navbar">
    <div class="logo">IGNITE</div>
    <div class="nav-links">
        <a href="#">Home</a>
        <a href="#">Shop</a>
        <a href="#">Contact</a>
    </div>
</div>

<!-- Hero Section -->
<div class="hero">
    <h1>IGNITE</h1>
    <p>Streetwear that speaks louder than words</p>

    <div class="btns">
        <button class="btn" onclick="openInstagram()">Instagram</button>
        <button class="btn" onclick="openWhatsApp()">WhatsApp</button>
    </div>
</div>

<!-- Footer -->
<div class="footer">
    <p>© 2026 Ignite Brand</p>
</div>

<script>
    function openInstagram() {
        window.open("https://instagram.com/YOUR_USERNAME", "_blank");
    }

    function openWhatsApp() {
        window.open("https://wa.me/201XXXXXXXXX", "_blank");
    }
</script>

</body>
</html>
