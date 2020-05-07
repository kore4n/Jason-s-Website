<!DOCTYPE html>
<html lang="en">
<head>
    <title>Jason Kwan</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <style>

    * {
      box-sizing: border-box;
    }

    body {
      background-image: url('CrimsonChin.png');
      background-repeat: no-repeat;
      background-attachment: fixed;
      background-size: cover;
      font-family: Arial, Helvetica, sans-serif;
      margin: 0;
    }

    /* Style the header */
    .header {
      padding: 250px;
      text-align: center;
      color: white;
    }

    /* Increase the font size of the h1 element */
    .header h1 {
      font-size: 50px;
    }

    /* Style the top navigation bar */
    .navbar {
      position: relative;
      overflow: hidden;
      background-color: #333;
    }

    /* Style the navigation bar links */
    .navbar a {
      float: left;
      display: block;
      color: white;
      text-align: center;
      padding: 20px 14px;
      text-decoration: none;
    }

    /* Change color on hover */
    .navbar a:hover {
      background-color: #ddd;
      color: black;
    }

    /* Column container */
    .row {
      display: flex;
      flex-wrap: wrap;
    }

    /* Create two unequal columns that sits next to each other */
    /* Sidebar/left column */
    .side {
      flex: 40%;
      background: rgba(204, 204, 204, 0.5);
      padding: 20px;
    }

    /* Main column */
    .main {
      flex: 60%;
      background: rgba(255, 255, 255, 0.5);
      padding: 20px;
    }

    /* Footer */
    .footer {
      padding: 20px;
      text-align: center;
      background: #ddd;
    }

    /* Responsive layout - when the screen is less than 700px wide, make the two columns stack on top of each other instead of next to each other */
    @media screen and (max-width: 700px) {
      .row {
        flex-direction: column;
      }
    }

    /* Responsive layout - when the screen is less than 400px wide, make the navigation links stack on top of each other instead of next to each other */
    @media screen and (max-width: 400px) {
      .navbar a {
        float: none;
        width:100%;
      }
    }
    </style>
</head>

<body>
    <div class="navbar">
      <a href="https://github.com/Leo-Wang-Toronto">GitHub</a>
      <a href="https://www.linkedin.com/in/leo-wang-955982193/">LinkedIn</a>
    </div>

    <div class="header">
      <h1>Leo Wang</h1>
      <h2>Hi, I'm a Computer Science Student at UofT!</h2>
    </div>

    <div class="row">
      <div class="side">
        <h1 style="text-align:center;">Resume</h1>
        <div class="container">
          <embed src="Resume.pdf" width="100%" height="800px" />
        </div>
      </div>
      <div class="main">
        <h2>under maintenance</h2>
        <div class="row">
          <div class="side">
            <h2> SIDE <h2>
          </div>
          <div class="main">
            <h2> MAIN </h2>
          </div>
        </div>

      </div>
    </div>

    <div class="footer">
      <h2>Footer</h2>
    </div>

</body>
</html>
