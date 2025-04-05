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
            <img src="images (4).jpeg" alt="Picture 1">
            <img src="images (5).jpeg" alt="Picture 2">
            <img src="images (7).jpeg"
            <img src="images (6).jpeg"
          </marquee>
        </td>
      </tr>
    </table>
  </center>
</body>
</html>
