<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home</title>
    <style>
        body {
            background-image: url('background 1.jpeg');
            color: orange;
            font-family: sans-serif; /* Added a default font */
            margin: 0; /* Reset default body margin */
        }
        h1 {
            text-align: center;
            margin-top: 20px; /* Add some top margin */
        }
        .navigation-table { /* Added a class for the navigation table */
            width: 80%;
            border-collapse: collapse;
            margin: 20px auto;
        }
        .navigation-table th, .navigation-table td {
            border: 1px solid lightgray;
            padding: 10px;
            background-color: white;
            text-align: center;
        }
        .navigation-table th a {
            text-decoration: none;
            color: inherit;
            display: block; /* Make the entire table cell clickable */
        }
        .image-marquee-table { /* Added a class for the image marquee table */
            width: 100%; /* Make the marquee table full width */
            margin-top: 20px;
        }
        .image-marquee-table td {
            padding: 10px;
            background-color: white;
            text-align: center;
        }
        .image-marquee-table marquee img {
            max-height: 300px;
            width: auto;
            vertical-align: middle; /* Align images vertically in the marquee */
            margin: 0 10px; /* Add some spacing between images */
        }
        /* Responsive design adjustments */
        @media (max-width: 768px) {
            .navigation-table {
                width: 95%;
            }
            .navigation-table th, .navigation-table td {
                padding: 8px;
                font-size: 0.9em;
            }
            .image-marquee-table marquee img {
                max-height: 200px;
            }
        }
    </style>
</head>
<body>
    <h1>COMPUTER COLLEGE</h1>
    <hr>
    <table class="navigation-table">
        <tr>
            <th><a href="HOME.html">HOME</a></th>
            <th><a href="Academic.html">ACADEMICS</a></th>
            <th><a href="ADMISSION.html">ADMISSION</a></th>
            <th><a href="ABOUT US.html">ABOUT US</a></th>
            <th><a href="LABARATORY.html">LABORATORY</a></th>
        </tr>
    </table>
    <hr>
    <table class="image-marquee-table">
        <tr>
            <td>
                <marquee behavior="scroll" direction="left">
                    <img src="images1.jpeg" alt="Picture 1">
                    <img src="images2.jpeg" alt="Picture 2">
                    <img src="images3.jpeg" alt="picture3">
                    <img src="images4.jpeg" alt="picture4">
                    <img src="images5.jpeg" alt="picture5">
                    <img src="images6.jpeg" alt="picture6">
                </marquee>
            </td>
        </tr>
    </table>
</body>
</html>
