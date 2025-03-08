<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pameran Fotografi</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <h1>Pameran Fotografi</h1>

    <div class="nav">
        <button onclick="showPage('home')">Home</button>
        <button onclick="showPage('portrait')">Portrait</button>
        <button onclick="showPage('landscape')">Landscape</button>
    </div>

    <div id="home" class="page active">
        <div class="bio">
            <h2>Biografi saya</h2>
            <p>Selamat datang di pameran fotografi saya! Saya adalah seorang fotografer yang mencintai keindahan alam dan kehidupan kota. Melalui lensa saya, saya berusaha menangkap momen-momen yang unik dan indah.</p>
            <h3>Perangkat yang Digunakan</h3>
            <ul>
                <li>Kamera: Canon EOS 90D</li>
                <li>Objektif: 18-55mm f/3.5-5.6</li>
                <li>Tripod: Manfrotto Befree</li>
                <li>Software Editing: Adobe Lightroom</li>
            </ul>
            <img src="gelap1.jpg" alt="Foto Gelap 1">
        </div>
    </div>

    <div id="portrait" class="page">
        <h2>Potrait</h2>
        <div class="gallery">
            <div class="photo">
                <img src="portrait_urban1.jpg" alt="Foto Urban 1">
                <div class="category">Urban</div>
            </div>
            <div class="photo">
                <img src="portrait_urban2.jpg" alt="Foto Urban 2">
                <div class="category">Urban</div>
            </div>
            <div class="photo">
                <img src="portrait_rural1.jpg" alt="Foto Rural 1">
                <div class="category">Rural</div>
            </div>
            <div class="photo">
                <img src="portrait_rural2.jpg" alt="Foto Rural 2">
                <div class="category">Rural</div>
            </div>
            <div class="photo">
                <img src="portrait_nature1.jpg" alt="Foto Nature 1">
                <div class="category">Nature</div>
            </div>
            <div class="photo">
                <img src="portrait_nature2.jpg" alt="Foto Nature 2">
                <div class="category">Nature</div>
            </div>
            <!-- Adding empty photo templates -->
            <div class="photo">
                <img src="placeholder.jpg" alt="Placeholder">
                <div class="category">Empty</div>
            </div>
            <div class="photo">
                <img src="placeholder.jpg" alt="Placeholder">
                <div class="category">Empty</div>
            </div>
            <div class="photo">
                <img src="placeholder.jpg" alt="Placeholder">
                <div class="category">Empty</div>
            </div>
            <div class="photo">
                <img src="placeholder.jpg" alt="Placeholder">
                <div class="category">Empty</div>
            </div>
            <div class="photo">
                <img src="placeholder.jpg" alt="Placeholder">
                <div class="category">Empty</div>
            </div>
            <div class="photo">
                <img src="placeholder.jpg" alt="Placeholder">
                <div class="category">Empty</div>
            </div>
            <div class="photo">
                <img src="placeholder.jpg" alt="Placeholder">
                <div class="category">Empty</div>
            </div>
            <div class="photo">
                <img src="placeholder.jpg" alt="Placeholder">
                <div class="category">Empty</div>
            </div>
            <div class="photo">
                <img src="placeholder.jpg" alt="Placeholder">
                <div class="category">Empty</div>
            </div>
            <div class="photo">
                <img src="placeholder.jpg" alt="Placeholder">
                <div class="category">Empty</div>
            </div>
        </div>
    </div>

    <div id="landscape" class="page">
        <h2>Pemandangan</h2>
        <div class="gallery">
            <div class="photo">
                <img src="pemandanganFT (21).jpg" alt="image" height="210" width="420" style="border-radius: 5px;"/>
                <div class="category">Dark</div>
            </div>
            <div class="photo">
                <img src="landscape_dark2.jpg" alt="Foto Dark 2">
                <div class="category">Dark</div>
            </div>
            <div class="photo">
                <img src="landscape_bright1.jpg" alt="Foto Bright 1">
                <div class="category">Bright</div>
            </div>
            <div class="photo">
                <img src="landscape_bright2.jpg" alt="Foto Bright 2">
                <div class="category">Bright</div>
            </div>
            <div class="photo">
                <img src="landscape_gradation1.jpg" alt="Foto Gradation 1">
                <div class="category">Gradation</div>
            </div>
            <div class="photo">
                <img src="landscape_gradation2.jpg" alt="Foto Gradation 2">
                <div class="category">Gradation</div>
            </div>
            <!-- Adding empty photo templates -->
            <div class="photo">
                <img src="placeholder.jpg" alt="Placeholder">
                <div class="category">Empty</div>
            </div>
            <div class="photo">
                <img src="placeholder.jpg" alt="Placeholder">
                <div class="category">Empty</div>
            </div>
            <div class="photo">
                <img src="placeholder.jpg" alt="Placeholder">
                <div class="category">Empty</div>
            </div>
            <div class="photo">
                <img src="placeholder.jpg" alt="Placeholder">
                <div class="category">Empty</div>
            </div>
            <div class="photo">
                <img src="placeholder.jpg" alt="Placeholder">
                <div class="category">Empty</div>
            </div>
            <div class="photo">
                <img src="placeholder.jpg" alt="Placeholder">
                <div class="category">Empty</div>
            </div>
            <div class="photo">
                <img src="placeholder.jpg" alt="Placeholder">
                <div class="category">Empty</div>
            </div>
            <div class="photo">
                <img src="placeholder.jpg" alt="Placeholder">
                <div class="category">Empty</div>
            </div>
        </div>
    </div>

    <footer style="background-color: #f4f4f4; color: #333; padding: 20px; text-align: center; position: relative; margin-top: 20px;">
    <p style="margin: 0;">&copy; 2024 Web page Kurosaki Rafi Yeager. All rights reserved.</p>
    </footer>

    <script>
        function showPage(category) {
            // Sembunyikan semua halaman
            const pages = document.querySelectorAll('.page');
            pages.forEach(page => {
                page.classList.remove('active');
            });

            // Tampilkan halaman yang dipilih
            const selectedPage = document.getElementById(category);
            selectedPage.classList.add('active');
        }
    </script>

</body>
</html>
