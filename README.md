
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Photography Exhibition</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>



    <div class="nav">
        <button class="long-button" onclick="showPage('home')">Home</button>
    </div>
    <div class="nav">
        <button onclick="showPage('portrait')">Portrait</button>
        <button onclick="showPage('landscape')">Landscape</button>
    </div>

    <div id="selected-items"></div> <!-- New section for displaying selected tags/elements -->

    <div id="home" class="page active">
        <div class="bio">
            <h2>About Me</h2>
            <p>Welcome to my photography exhibition! I am a photographer who loves the beauty of nature and urban life. Through my lens, I strive to capture unique and beautiful moments.</p>
            <h3>Equipment Used</h3>
            <ul>
                <li>Camera: Canon EOS 90D</li>
                <li>Lens: 18-55mm f/3.5-5.6</li>
                <li>Tripod: Manfrotto Befree</li>
                <li>Editing Software: Adobe Lightroom</li>
            </ul>
        </div>
    </div>

    <div id="portrait" class="page">
        <h2>Portraits</h2>
        <div class="gallery">
            <div class="photo portrait">
                <img src="PT (1).jpg" alt="City Portrait">
                <div class="JF">Urban Elegance</div>
                <div class="tag" onclick="selectItem('urban')">Urban</div>
                <div class="element" onclick="selectItem('dark')">Dark</div>
            </div>
            <div class="photo portrait">
                <img src="PT (2).jpg" alt="Rural Portrait">
                <div class="JF">Rural Serenity</div>
                <div class="tag" onclick="selectItem('rural')">Rural</div>
                <div class="element" onclick="selectItem('bright')">Bright</div>
            </div>
            <div class="photo portrait">
                <img src="PT (3).jpg" alt="Crowd in City">
                <div class="JF">City Life</div>
                <div class="tag" onclick="selectItem('crowd')">Urban</div>
                <div class="element" onclick="selectItem('bright')">Bright</div>
            </div>
            <div class="photo portrait">
                <img src="PT (4).jpg" alt="Night Portrait">
                <div class="JF">Nighttime Charm</div>
                <div class="tag" onclick="selectItem('urban')">Urban</div>
                <div class="element" onclick="selectItem('dark')">Dark</div>
            </div>
            <div class="photo portrait">
                <img src="PT (5).jpg" alt="Color Gradient">
                <div class="JF">Colorful Gradation</div>
                <div class="tag" onclick="selectItem('nature')">Nature</div>
                <div class="element" onclick="selectItem('gradient')">Gradient</div>
            </div>
            <div class="photo portrait">
                <img src="PT (6).jpg" alt="Bright Light">
                <div class="JF">Radiant Light</div>
                <div class="tag" onclick="selectItem('urban')">Urban</div>
                <div class="element" onclick="selectItem('bright')">Bright</div>
            </div>
            <div class="photo portrait">
                <img src="PT (7).jpg" alt="City Portrait">
                <div class="JF">Urban Beauty</div>
                <div class="tag" onclick="selectItem('urban')">Urban</div>
                <div class="element" onclick="selectItem('dark')">Dark</div>
            </div>
            <div class="photo portrait">
                <img src="PT (8).jpg" alt="Rural Scene">
                <div class="JF">Peaceful Countryside</div>
                <div class="tag" onclick="selectItem('rural')">Rural</div>
                <div class="element" onclick="selectItem('bright')">Bright</div>
            </div>
            <div class="photo portrait">
                <img src="PT (9).jpg" alt="Crowd in City">
                <div class="JF">Vibrant City Life</div>
                <div class="tag" onclick="selectItem('crowd')">Urban</div>
                <div class="element" onclick="selectItem('bright')">Bright</div>
            </div>
            <div class="photo portrait">
                <img src="PT (10).jpg" alt="Night Portrait">
                <div class="JF">Charming Night</div>
                <div class="tag" onclick="selectItem('urban')">Urban</div>
                <div class="element" onclick="selectItem('dark')">Dark</div>
            </div>
            <div class="photo portrait">
                <img src="PT (11).jpg" alt="Color Gradient">
                <div class="JF">Vivid Gradation</div>
                <div class="tag" onclick="selectItem('nature')">Nature</div>
                <div class="element" onclick="selectItem('gradient')">Gradient</div>
            </div>
            <div class="photo portrait">
                <img src="PT (12).jpg" alt="Bright Light">
                <div class="JF">Illuminated Moments</div>
                <div class="tag" onclick="selectItem('urban')">Urban</div>
                <div class="element" onclick="selectItem('bright')">Bright</div>
            </div>
            <div class="photo portrait">
                <img src="PT (13).jpg" alt="City Portrait">
                <div class="JF">Urban Delight</div>
                <div class="tag" onclick="selectItem('urban')">Urban</div>
                <div class="element" onclick="selectItem('dark')">Dark</div>
            </div>

        </div>
    </div>

    <div id="landscape" class="page">
        <h2>Landscapes</h2>
        <div class="gallery">
            <div class="photo">
                <img src="LS (1).jpg" alt="Dark Landscape" height="210" width="420" style="border-radius: 5px;"/>
                <div class="JF">Mysterious Darkness</div>
                <div class="tag" onclick="selectItem('dark')">Dark</div>
                <div class="element" onclick="selectItem('dark')">Dark</div>
            </div>
            <div class="photo">
                <img src="LS (2).jpg" alt="Gradient Landscape">
                <div class="JF">Stunning Gradation</div>
                <div class="tag" onclick="selectItem('nature')">Nature</div>
                <div class="element" onclick="selectItem('gradient')">Gradient</div>
            </div>
            <div class="photo">
                <img src="LS (3).jpg" alt="Bright Landscape">
                <div class="JF">Bright Horizons</div>
                <div class="tag" onclick="selectItem('bright')">Bright</div>
                <div class="element" onclick="selectItem('bright')">Bright</div>
            </div>
            <div class="photo">
                <img src="LS (4).jpg" alt="City Landscape">
                <div class="JF">Urban Scenery</div>
                <div class="tag" onclick="selectItem('urban')">Urban</div>
                <div class="element" onclick="selectItem('cloudy')">Cloudy</div>
            </div>
            <div class="photo">
                <img src="LS (5).jpg" alt="Rural Landscape">
                <div class="JF">Tranquil Countryside</div>
                <div class="tag" onclick="selectItem('rural')">Rural</div>
                <div class="element" onclick="selectItem('bright')">Bright</div>
            </div>
            <div class="photo">
                <img src="LS (6).jpg" alt="Crowd Landscape">
                <div class="JF">Lively Gatherings</div>
                <div class="tag" onclick="selectItem('crowd')">Urban</div>
                <div class="element" onclick="selectItem('bright')">Bright</div>
            </div>
            <!-- Replacing empty photo templates -->
            <div class="photo">
                <img src="LS (7).jpg" alt="Dark Landscape" height="210" width="420" style="border-radius: 5px;"/>
                <div class="JF">Enigmatic Shadows</div>
                <div class="tag" onclick="selectItem('dark')">Dark</div>
                <div class="element" onclick="selectItem('dark')">Dark</div>
            </div>
            <div class="photo">
                <img src="LS (8).jpg" alt="Gradient Landscape" height="210" width="420" style="border-radius: 5px;"/>
                <div class="JF">Colorful Gradients</div>
                <div class="tag" onclick="selectItem('nature')">Nature</div>
                <div class="element" onclick="selectItem('gradient')">Gradient</div>
            </div>
            <div class="photo">
                <img src="LS (9).jpg" alt="Bright Landscape" height="210" width="420" style="border-radius: 5px;"/>
                <div class="JF">Radiant Landscapes</div>
                <div class="tag" onclick="selectItem('bright')">Bright</div>
                <div class="element" onclick="selectItem('bright')">Bright</div>
            </div>
            <div class="photo">
                <img src="LS (10).jpg" alt="City Landscape" height="210" width="420" style="border-radius: 5px;"/>
                <div class="JF">Urban Vistas</div>
                <div class="tag" onclick="selectItem('urban')">Urban</div>
                <div class="element" onclick="selectItem('cloudy')">Cloudy</div>
            </div>
            <div class="photo">
                <img src="LS (11).jpg" alt="Rural Landscape" height="210" width="420" style="border-radius: 5px;"/>
                <div class="JF">Peaceful Pastures</div>
                <div class="tag" onclick="selectItem('rural')">Rural</div>
                <div class="element" onclick="selectItem('bright')">Bright</div>
            </div>
            <div class="photo">
                <img src="LS (12).jpg" alt="Crowd Landscape" height="210" width="420" style="border-radius: 5px;"/>
                <div class="JF">Vibrant Gatherings</div>
                <div class="tag" onclick="selectItem('crowd')">Urban</div>
                <div class="element" onclick="selectItem('bright')">Bright</div>
            </div>
            <div class="photo">
                <img src="LS (13).jpg" alt="Dark Landscape" height="210" width="420" style="border-radius: 5px;"/>
                <div class="JF">Mysterious Landscapes</div>
                <div class="tag" onclick="selectItem('dark')">Dark</div>
                <div class="element" onclick="selectItem('dark')">Dark</div>
            </div>
            <div class="photo">
                <img src="LS (14).jpg" alt="Gradient Landscape" height="210" width="420" style="border-radius: 5px;"/>
                <div class="JF">Stunning Gradations</div>
                <div class="tag" onclick="selectItem('nature')">Nature</div>
                <div class="element" onclick="selectItem('gradient')">Gradient</div>
            </div>
            <div class="photo">
                <img src="LS (15).jpg" alt="Bright Landscape" height="210" width="420" style="border-radius: 5px;"/>
                <div class="JF">Illuminated Views</div>
                <div class="tag" onclick="selectItem('bright')">Bright</div>
                <div class="element" onclick="selectItem('bright')">Bright</div>
            </div>
            <div class="photo">
                <img src="LS (16).jpg" alt="City Landscape" height="210" width="420" style="border-radius: 5px;"/>
                <div class="JF">Urban Landscapes</div>
                <div class="tag" onclick="selectItem('urban')">Urban</div>
                <div class="element" onclick="selectItem('dark')">Dark</div>
            </div>
            <div class="photo">
                <img src="LS (17).jpg" alt="Rural Landscape" height="210" width="420" style="border-radius: 5px;"/>
                <div class="JF">Serene Countryside</div>
                <div class="tag" onclick="selectItem('rural')">Rural</div>
                <div class="element" onclick="selectItem('bright')">Bright</div>
            </div>
            <div class="photo">
                <img src="LS (18).jpg" alt="Crowd Landscape" height="210" width="420" style="border-radius: 5px;"/>
                <div class="JF">Lively Scenes</div>
                <div class="tag" onclick="selectItem('crowd')">Urban</div>
                <div class="element" onclick="selectItem('bright')">Bright</div>
            </div>
            <div class="photo">
                <img src="LS (19).jpg" alt="Dark Landscape" height="210" width="420" style="border-radius: 5px;"/>
                <div class="JF">Enigmatic Views</div>
                <div class="tag" onclick="selectItem('dark')">Dark</div>
                <div class="element" onclick="selectItem('dark')">Dark</div>
            </div>
            <div class="photo">
                <img src="LS (20).jpg" alt="Gradient Landscape" height="210" width="420" style="border-radius: 5px;"/>
                <div class="JF">Colorful Landscapes</div>
                <div class="tag" onclick="selectItem('nature')">Nature</div>
                <div class="element" onclick="selectItem('gradient')">Gradient</div>
            </div>

        </div>
    </div>

    <footer style="background-color: #f4f4f4; color: #333; padding: 20px; text-align: center; position: relative; margin-top: 20px;">
    <p style="margin: 0;">&copy; 2024 Web page Kurosaki Rafi Yeager. All rights reserved.</p>
    </footer>

    <script>
        function selectItem(item) {
            console.log("Item clicked:", item); // Debugging line
            // Redirect to a new page based on the selected item
            window.location.href = item + '.html'; // Assuming each item has a corresponding HTML page
        }

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
