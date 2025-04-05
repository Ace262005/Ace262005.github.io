<!DOCTYPE html>
<html>
<head>
<title>Home</title>
<style>
  body {
    background-image: url('background 1.jpeg');
    color: orange;
  }
  h1 {
    text-align: center;
  }
  table {
    width: 80%; /* Increased width for better responsiveness */
    border-collapse: collapse;
    margin: 20px auto;
  }
  th, td {
    border: 1px solid lightgray; /* Reduced border thickness */
    padding: 10px;
    background-color: white;
    text-align: center; /* Center text in table cells */
  }
  th a {
    text-decoration: none;
    color: inherit;
  }
  td marquee img {
    max-height: 300px; /* Made image height responsive */
    width: auto; /* Maintain aspect ratio */
  }
  /* Responsive design adjustments */
  @media (max-width: 768px) {
    table {
      width: 95%;
    }
    th, td {
      padding: 8px;
      font-size: 0.9em;
    }
    td marquee img {
      max-height: 200px;
    }
  }
</style>
</head>
<body>
  <h1>COMPUTER COLLEGE</h1>
  <hr>
  <center>
    <table>
      <tr>
        <th><a href="HOME.html">HOME</a><th>
        <th><a href="Academic.html">ACADEMICS</a></th>
        <th><a href="ADMISSION.html">ADMISSION</a></th>
        <th><a href="ABOUT US.html">ABOUT US</a></th>
        <th><a href="LABARATORY.html">LABORATORY</a></th>
      </tr>
    </table>
  </center>
  <hr>
  <center>
    <table>
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
  </center>
</body>
</html> width as needed */
    max-width: 600px; /* Set a maximum width */
  }
  th {
    background-color: lightgray;
    border: 1px solid gray;
    padding: 10px;
    text-align: center;
  }
  h2 {
    color: green;
  }
  ul {
    color: green;
    list-style-type: square; /* Use square bullets for the list */
    padding-left: 20px; /* Add some left padding for better readability */
  }
  li {
    margin-bottom: 5px; /* Add some spacing between list items */
  }
  h4 {
    margin-top: 0; /* Remove default top margin for h4 within list items */
  }
</style>
</head>

<body>

  <h1>COMPUTER COLLEGE</h1>
  <hr>
  <center>
    <table>
      <tr>
        
        <th><a href="HOME.html">HOME</a><th>
        <th><a href="ADMISSION.html">ADMISSION</a><th>
        <th><a href="ABOUT US.html">ABOUT US</a><th>
        <th><a href="LABARATORY.html">LABARATORY</a><th>
      </tr>
    </table>
  </center>

  <div style="color: green; padding: 20px;"> <h1>COURSES OFFERED</h1>
    <h2>TWO-YEAR COURSES</h2>
    <ul>
      <li><h4>TWO-YEAR COMPUTER TECHNICIAN</h4></li>
      <li><h4>TWO-YEAR INFORMATION TECHNOLOGY</h4></li>
    </ul>
    <br><br>
    <h1>FOUR-YEAR COURSES</h1>
    <ul>
      <li><h4>BACHELOR OF SCIENCE IN COMPUTER SCIENCE</h4></li>
      <li><h4>BACHELOR OF SCIENCE IN COMPUTER INFORMATION TECHNOLOGY</h4></li>
      <li><h4>BACHELOR OF SCIENCE IN INFORMATION SYSTEMS</h4></li>
    </ul>
  </div>

</body>
</html>        
