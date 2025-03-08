body {
    font-family: Arial, sans-serif;
    background-color: #ffffff;
    margin: 0;
    padding: 20px;
}

h1 {
    text-align: center;
}
.gallery {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}
.photo {
    margin: 10px;
    border: 3px solid #007BFF; /* Updated border thickness and color */
    padding: 10px; /* Added padding for spacing */
    border: 3px solid #000000; /* Updated border thickness and color */
    padding: 10px; /* Added padding for spacing */

    border-radius: 5px;
    overflow: hidden;
    width: 100%; /* Changed to 100% for responsiveness */
    max-width: 300px; /* Set max width for larger screens */
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s; /* Smooth scaling transition */
}




.photo:hover {
    transform: scale(1.05); /* Scale up on hover */
}

.photo img {
    width: 100%;
    height: auto;
}
.category {
    text-align: center;
    padding: 10px;
    background-color: #fff;
    font-weight: bold; /* Added bold text */
    color: #333; /* Changed text color */
    border-radius: 5px; /* Added border radius */
    margin-top: 5px; /* Added margin for spacing */
    border: 1px solid #000001; /* Yellow border for Bright category */

}

h2 {
    color: #007BFF; /* Added color for h2 elements */
    text-align: center; /* Centered h2 elements */
    margin-top: 20px; /* Added margin for spacing */
}

h3 {
    color: #555; /* Changed color for h3 elements */
    text-align: center; /* Centered h3 elements */
    margin-top: 15px; /* Added margin for spacing */
}

.nav {
    text-align: center;
    margin-bottom: 20px;
}
.nav button {
    padding: 10px 15px;
    margin: 0 5px;
    cursor: pointer;
    background-color: #007BFF; /* Added background color */
    color: white; /* Added text color */
    border: none; /* Removed border */
    border-radius: 5px; /* Rounded corners */
    transition: background-color 0.3s; /* Smooth transition */
}

.nav button:hover {
    background-color: #0056b3; /* Darker background on hover */
}

.page {
    display: none;
}
.active {
    display: block;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
    margin: 0 auto;
    justify-content: center;
    display: flex;
}

