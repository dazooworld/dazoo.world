# dazoo.world
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>DAZOO.WORLD</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #fff;
        }

        header {
            padding: 30px;
        }

        header img {
            width: 175px;
            height: 75px;
        }

        header h1 {
            font-size: 48px;
            color: navy;
            margin: 10px 0;
        }

        header h2 {
            font-size: 20px;
            color: #444;
        }

        nav {
            background-color: #f0f0f0;
            padding: 15px 0;
            margin-bottom: 30px;
        }

        nav a {
            text-decoration: none;
            margin: 0 15px;
            color: navy;
            font-weight: bold;
            font-size: 18px;
        }

        nav a:hover {
            text-decoration: underline;
        }

        section {
            padding: 20px;
            display: none;
        }

        section.active {
            display: block;
        }

        img.gallery-img {
            width: 400px;
            margin: 10px;
            border-radius: 10px;
        }

        footer {
            margin-top: 40px;
            padding: 20px;
            background: #f0f0f0;
        }

        .social-links a {
            display: block;
            margin: 5px;
            color: navy;
            text-decoration: none;
        }
    </style>
    <script>
        function showPage(id) {
            const sections = document.querySelectorAll('section');
            sections.forEach(section => section.classList.remove('active'));
            document.getElementById(id).classList.add('active');
        }

        // Tampilkan homepage saat pertama dibuka
        window.onload = function () {
            showPage('home');
        };
    </script>
</head>
<body>

    <!-- HEADER -->
    <header>
        <img src="1.jpg" alt="Logo Dazoo"style="width: 300px;">
        <h1>DAZOO.WORLD</h1>
        <h2>HOME OF CREATIVITY</h2>
    </header>

    <!-- NAVIGATION -->
    <nav>
        <a href="#" onclick="showPage('home')">HOMEPAGE</a>
        <a href="#" onclick="showPage('gallery')">GALERY</a>
        <a href="#" onclick="showPage('about')">ABOUT US</a>
        <a href="#" onclick="showPage('contact')">CONTACT US</a>
    </nav>

    <!-- HOMEPAGE SECTION -->
    <section id="home" class="active">
        <h2>Selamat Datang di Dazoo World</h2>
        <p>Dazoo World adalah rumah kreativitas. Kami menyediakan:</p>
        <ul style="list-style: none; padding: 0;">
            <li>✔ Desain grafis menarik</li>
            <li>✔ Vector siap pakai</li>
            <li>✔ Galeri karya profesional</li>
        </ul>
        <img src="2.jpg" alt="Contoh karya" style="width: 600px; margin-top: 20px;">
        <p><i>.</i></p>
    </section>

  

    <!-- GALLERY SECTION -->
    <section id="gallery">
        <h2>Produk kami</h2>
        <div>
            <img src="3.jpg" class="gallery-img" alt="Vector 1">
            <img src="4.jpg" class="gallery-img" alt="Vector 2">
            <img src="5.jpg" class="gallery-img" alt="Vector 3">
            <img src="6.jpg" class="gallery-img" alt="Vector 4">
            <img src="7.jpg" class="gallery-img" alt="Vector 5">
            <img src="8.jpg" class="gallery-img" alt="Vector 6">
	    <img src="9.jpeg" class="gallery-img" alt="Vector 7">
            <img src="10.jpeg" class="gallery-img" alt="Vector 8">
        </div>
    </section>

    <!-- ABOUT US SECTION -->
    <section id="about">
        <h2>Tentang Kami</h2>
        <p>Dazoo World mulai beroperasi sejak <strong>Januari 2020</strong>, pada masa awal pandemi COVID-19. Dengan semangat berkarya dari rumah, kami membangun komunitas desain untuk membantu bisnis dan personal branding di masa sulit.</p>
        <p>Kami percaya bahwa desain visual yang kuat dapat menggerakkan perubahan, membangun merek, dan menghubungkan emosi.</p>
        <img src="2.jpg" alt="Tim Dazoo" style="width: 400px; margin-top: 20px;">
    </section>

    <!-- CONTACT US SECTION -->
    <section id="contact">
        <h2>Hubungi Kami</h2>
        <div class="social-links">
            <a href="https://lynk.id/dazoo.world" target="_blank">🌐 Lynk ID: dazoo.world</a>
            <a href="https://instagram.com/dazoo.idn" target="_blank">📸 Instagram: @dazoo.idn</a>
            <a href="https://tiktok.com/@dazoo.world" target="_blank">🎵 TikTok: @dazoo.world</a>
        </div>
    </section>

    <footer>
        &copy; 2020 - 2025 DAZOO.WORLD | All Rights Reserved
    </footer>

</body>
</html>
