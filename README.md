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
    border: 3px solid #000000; /* Updated border thickness and color */
    padding: 10px; /* Added padding for spacing */
    border-radius: 5px;
    overflow: hidden;
    width: calc(23% - 20px); /* Adjusted width for portrait to fit 4 photos in a row on larger screens */
    flex: 0 0 auto; /* Ensure the photo does not shrink */
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

.JF {
    text-align: center;
    padding: 10px;
    background-color: #fff;
    font-weight: bold; /* Added bold text */
    color: #333; /* Changed text color */
    border-radius: 5px; /* Added border radius */
    margin-top: 5px; /* Added margin for spacing */
}

.tag {
    display: inline-block;
    padding: 5px 10px;
    margin: 5px;
    border: 1px solid #ccc;
    border-radius: 5px;
    background-color: #f4f4f4;
    font-size: 14px;
    text-align: left; /* Align tag to the left */
}

.element {
    display: inline-block;
    padding: 5px 10px;
    margin: 5px;
    border: 1px solid #ccc;
    border-radius: 5px;
    background-color: #f4f4f4;
    font-size: 14px;
    text-align: right; /* Align element to the right */
}

.ambiance {
    display: inline-block;
    padding: 5px 10px;
    margin: 5px;
    background-color: #e0e0e0; /* Example ambiance color */
    border-radius: 5px;
    font-size: 14px;
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
    display: flex;
    flex-direction: row; /* Ensure buttons are in a row */
    justify-content: space-around; /* Space buttons evenly */
    flex-wrap: wrap; /* Allow buttons to wrap on smaller screens */
    margin-bottom: 20px;
    width: 100%; /* Ensure the nav takes full width */
}

.nav button {
    flex: 1; /* Allow buttons to grow and fill available space */
    margin: 5px; /* Add margin for spacing */
    min-width: 100px; /* Set a minimum width for buttons */
    padding: 10px 15px; /* Adjust padding for mobile */
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

/* Media Queries for Responsive Design */
@media (max-width: 768px) {
    .photo {
        width: calc(50% - 20px); /* Two photos per row on tablets */
    }
}

@media (max-width: 480px) {
    .nav button {
        font-size: 14px; /* Adjust font size for better readability */
        flex: 1 1 100%; /* Make buttons full width on mobile */
    }

    .photo {
        width: 100%; /* One photo per row on mobile devices */
    }

    .photo.portrait {
        width: 100%; /* Ensure portrait photos are full width on mobile */
    }
}
