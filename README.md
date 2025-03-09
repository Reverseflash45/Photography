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

            

            <p style="text-indent: 45px;">Hello!! Welcome to my photo exhibition! My name is Rafi Fernandito Setiawan, I am a photographer as a hobby. I am currently studying at unair majoring in informatics engineering. So this website is a website that I use to practice making websites as well as to exhibit my photos.</p>
            
            <p><ul><b><u><br>Biodata</u>
                <li>Name: Rafi Fernandito Setiawan</li>
                <li>Gender: Male</li>
                <li>University: UNAIR</li></ul></p>
            
            
            <ul>
                <b><u>Equipment Used</b></u>
                <li>Camera: Canon EOS 550D</li>
                <li>Smartphone: Infinix GT 20 Pro</li>
                <li>Editing Software: Adobe Lightroom</li>
            </ul>

            <ul>
                <b><u>Contact</u>
                <li>Email: rffernanditoo@gmail.com</li>
                <li>No Telp: 087704521979</li>
                <li>No Whatsapp:62+ 87704521979</li>
                <li>Instagram: @Raffstw</li>
                <li>Github: Reverseflash45 </li>
                <li>Linkedin: https://www.linkedin.com/in/rafi-fernandito-setiawan-683b30307/ </li>
            </ul>
    </div>

    <div id="portrait" class="page">
        <h2>Portraits</h2>
        <div class="gallery">
            <div class="photo portrait">
                <img src="PT (1).jpg" alt="City Portrait">
                <div class="JF">Empty Forest</div>
                <div class="tag" onclick="selectItem('Building')">Building</div>
                <div class="element" onclick="selectItem('Cloudy')">Cloudy</div>
            </div>
            <div class="photo portrait">
                <img src="PT (2).jpg" alt="Rural Portrait">
                <div class="JF">Sky Gradient River</div>
                <div class="tag" onclick="selectItem('Sky')">Sky</div>
                <div class="element" onclick="selectItem('Gradation')">Gradation</div>
            </div>
            <div class="photo portrait">
                <img src="PT (3).jpg" alt="Crowd in City">
                <div class="JF">The Terrifying Sky</div>
                <div class="tag" onclick="selectItem('Object')">Object</div>
                <div class="element" onclick="selectItem('Cloudy')">Cloudy</div>
            </div>
            <div class="photo portrait">
                <img src="PT (4).jpg" alt="Night Portrait">
                <div class="JF">The Lonely Swamp</div>
                <div class="tag" onclick="selectItem('Sky')">Sky</div>
                <div class="element" onclick="selectItem('Bright')">Bright</div>
            </div>
            <div class="photo portrait">
                <img src="PT (5).jpg" alt="Color Gradient">
                <div class="JF">Dark Tunnel</div>
                <div class="tag" onclick="selectItem('Building')">Building</div>
                <div class="element" onclick="selectItem('Dark')">Dark</div>
            </div>
            <div class="photo portrait">
                <img src="PT (6).jpg" alt="Bright Light">
                <div class="JF">The Dark Connecting Bridge</div>
                <div class="tag" onclick="selectItem('Object')">Object</div>
                <div class="element" onclick="selectItem('Dark')">Dark</div>
            </div>
            <div class="photo portrait">
                <img src="PT (7).jpg" alt="City Portrait">
                <div class="JF">Urban Beauty</div>
                <div class="tag" onclick="selectItem('Urban')">Urban</div>
                <div class="element" onclick="selectItem('Dark')">Dark</div>
            </div>
            <div class="photo portrait">
                <img src="PT (8).jpg" alt="Rural Scene">
                <div class="JF">The Scarriest</div>
                <div class="tag" onclick="selectItem('Sky')">Sky</div>
                <div class="element" onclick="selectItem('Dark')">Dark</div>
            </div>
            <div class="photo portrait">
                <img src="PT (9).jpg" alt="Crowd in City">
                <div class="JF">The Stopped Rain</div>
                <div class="tag" onclick="selectItem('Object')">Object</div>
                <div class="element" onclick="selectItem('Bright')">Bright</div>
            </div>
            <div class="photo portrait">
                <img src="PT (10).jpg" alt="Night Portrait">
                <div class="JF">The Building of the Sky</div>
                <div class="tag" onclick="selectItem('Building')">Building</div>
                <div class="element" onclick="selectItem('Cloudy')">Cloudy</div>
            </div>
            <div class="photo portrait">
                <img src="PT (11).jpg" alt="Color Gradient">
                <div class="JF">Nature Beach</div>
                <div class="tag" onclick="selectItem('Beach')">Beach</div>
                <div class="element" onclick="selectItem('Bright')">Bright</div>
            </div>
            <div class="photo portrait">
                <img src="PT (12).jpg" alt="Bright Light">
                <div class="JF">Lonely x</div>
                <div class="tag" onclick="selectItem('Object')">Object</div>
                <div class="element" onclick="selectItem('Bright')">Bright</div>
            </div>
            <div class="photo portrait">
                <img src="PT (13).jpg" alt="City Portrait">
                <div class="JF">Infinity Bridge</div>
                <div class="tag" onclick="selectItem('Object')">Object</div>
                <div class="element" onclick="selectItem('Dark')">Dark</div>
            </div>

        </div>
    </div>

    <div id="landscape" class="page">
        <h2>Landscapes</h2>
        <div class="gallery">
            <div class="photo">
                <img src="LS (1).jpg" alt="Dark Landscape" height="210" width="420" style="border-radius: 5px;"/>
                <div class="JF">Empty Building</div>
                <div class="tag" onclick="selectItem('Object')">Object</div>
                <div class="element" onclick="selectItem('Dark')">Dark</div>
            </div>
            <div class="photo">
                <img src="LS (2).jpg" alt="Gradient Landscape">
                <div class="JF">The Silence of Going Merry</div>
                <div class="tag" onclick="selectItem('Object')">Object</div>
                <div class="element" onclick="selectItem('Dark')">Dark</div>
            </div>
            <div class="photo">
                <img src="LS (3).jpg" alt="Bright Landscape">
                <div class="JF">The Calming Gradation of the City</div>
                <div class="tag" onclick="selectItem('City')">City</div>
                <div class="element" onclick="selectItem('Bright')">Bright</div>
            </div>
            <div class="photo">
                <img src="LS (4).jpg" alt="City Landscape">
                <div class="JF">Sheltered Building</div>
                <div class="tag" onclick="selectItem('City')">City</div>
                <div class="element" onclick="selectItem('Cloudy')">Cloudy</div>
            </div>
            <div class="photo">
                <img src="LS (5).jpg" alt="Rural Landscape">
                <div class="JF">Shooting Sky Gradation</div>
                <div class="tag" onclick="selectItem('Sky')">Sky</div>
                <div class="element" onclick="selectItem('Bright')">Bright</div>
            </div>
            <div class="photo">
                <img src="LS (6).jpg" alt="Crowd Landscape">
                <div class="JF">Cloudy Intersection</div>
                <div class="tag" onclick="selectItem('Sky')">Sky</div>
                <div class="element" onclick="selectItem('Bright')">Bright</div>
            </div>
            <!-- Replacing empty photo templates -->
            <div class="photo">
                <img src="LS (7).jpg" alt="Dark Landscape" height="210" width="420" style="border-radius: 5px;"/>
                <div class="JF">The Sky of the Shady Beach</div>
                <div class="tag" onclick="selectItem('Beach')">Beach</div>
                <div class="element" onclick="selectItem('Dark')">Dark</div>
            </div>
            <div class="photo">
                <img src="LS (8).jpg" alt="Gradient Landscape" height="210" width="420" style="border-radius: 5px;"/>
                <div class="JF">Gripping Theater</div>
                <div class="tag" onclick="selectItem('Building')">Building</div>
                <div class="element" onclick="selectItem('Dark')">Dark</div>
            </div>
            <div class="photo">
                <img src="LS (9).jpg" alt="Bright Landscape" height="210" width="420" style="border-radius: 5px;"/>
                <div class="JF">Shady Cloudy River</div>
                <div class="tag" onclick="selectItem('River')">River</div>
                <div class="element" onclick="selectItem('Bright')">Bright</div>
            </div>
            <div class="photo">
                <img src="LS (10).jpg" alt="City Landscape" height="210" width="420" style="border-radius: 5px;"/>
                <div class="JF">Aesthetic Beach Plaque</div>
                <div class="tag" onclick="selectItem('Beach')">Beach</div>
                <div class="element" onclick="selectItem('Bright')">Bright</div>
            </div>
            <div class="photo">
                <img src="LS (11).jpg" alt="Rural Landscape" height="210" width="420" style="border-radius: 5px;"/>
                <div class="JF">L Train</div>
                <div class="tag" onclick="selectItem('Automotive')">Automotive</div>
                <div class="element" onclick="selectItem('Bright')">Bright</div>
            </div>
            <div class="photo">
                <img src="LS (12).jpg" alt="Crowd Landscape" height="210" width="420" style="border-radius: 5px;"/>
                <div class="JF">Majestic Foreground Buildings</div>
                <div class="tag" onclick="selectItem('Building')">Building</div>
                <div class="element" onclick="selectItem('Bright')">Bright</div>
            </div>
            <div class="photo">
                <img src="LS (13).jpg" alt="Dark Landscape" height="210" width="420" style="border-radius: 5px;"/>
                <div class="JF">Mysterious Lampions</div>
                <div class="tag" onclick="selectItem('Building')">Building</div>
                <div class="element" onclick="selectItem('Dark')">Dark</div>
            </div>
            <div class="photo">
                <img src="LS (14).jpg" alt="Gradient Landscape" height="210" width="420" style="border-radius: 5px;"/>
                <div class="JF">Stunning Gradations</div>
                <div class="tag" onclick="selectItem('Sky')">Sky</div>
                <div class="element" onclick="selectItem('Bright')">Bright</div>
            </div>
            <div class="photo">
                <img src="LS (15).jpg" alt="Bright Landscape" height="210" width="420" style="border-radius: 5px;"/>
                <div class="JF">Illuminated Views</div>
                <div class="tag" onclick="selectItem('Object')">Object</div>
                <div class="element" onclick="selectItem('Bright')">Bright</div>
            </div>
            <div class="photo">
                <img src="LS (16).jpg" alt="City Landscape" height="210" width="420" style="border-radius: 5px;"/>
                <div class="JF">A Glimmer of Light</div>
                <div class="tag" onclick="selectItem('Object')">Object</div>
                <div class="element" onclick="selectItem('Dark')">Dark</div>
            </div>
            <div class="photo">
                <img src="LS (17).jpg" alt="Rural Landscape" height="210" width="420" style="border-radius: 5px;"/>
                <div class="JF">Serene Flower</div>
                <div class="tag" onclick="selectItem('Flower')">Flower</div>
                <div class="element" onclick="selectItem('Bright')">Bright</div>
            </div>
            <div class="photo">
                <img src="LS (18).jpg" alt="Crowd Landscape" height="210" width="420" style="border-radius: 5px;"/>
                <div class="JF">UNAIR EXPO Crowd</div>
                <div class="tag" onclick="selectItem('Hustle')">Hustle</div>
                <div class="element" onclick="selectItem('Bright')">Bright</div>
            </div>
            <div class="photo">
                <img src="LS (19).jpg" alt="Dark Landscape" height="210" width="420" style="border-radius: 5px;"/>
                <div class="JF">The end of the Sky</div>
                <div class="tag" onclick="selectItem('Sky')">Sky</div>
                <div class="element" onclick="selectItem('Dark')">Dark</div>
            </div>
            <div class="photo">
                <img src="LS (20).jpg" alt="Gradient Landscape" height="210" width="420" style="border-radius: 5px;"/>
                <div class="JF">Dark Lampions</div>
                <div class="tag" onclick="selectItem('Object')">Object</div>
                <div class="element" onclick="selectItem('Dark')">Dark</div>
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
