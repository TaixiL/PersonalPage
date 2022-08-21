## Hi, I am Taixi Lu.

I am an undergraduate student majoring in Computer Science and Statistics and Analytics at University of North Carolina at Chapel Hill.

<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
        <style>
        body {
          font-family: "Lato", sans-serif;
        }

        /* Fixed sidenav, full height */
        .sidenav {
          height: 100%;
          width: 200px;
          position: fixed;
          z-index: 1;
          top: 0;
          left: 0;
          background-color: #111;
          overflow-x: hidden;
          padding-top: 20px;
        }

        /* Style the sidenav links and the dropdown button */
        .sidenav a, .dropdown-btn {
          padding: 6px 8px 6px 16px;
          text-decoration: none;
          font-size: 20px;
          color: #818181;
          display: block;
          border: none;
          background: none;
          width: 100%;
          text-align: left;
          cursor: pointer;
          outline: none;
        }

        /* On mouse-over */
        .sidenav a:hover, .dropdown-btn:hover {
          color: #f1f1f1;
        }

        /* Main content */
        .main {
          margin-left: 200px; /* Same as the width of the sidenav */
          font-size: 20px; /* Increased text to enable scrolling */
          padding: 0px 10px;
        }

        /* Add an active class to the active dropdown button */
        .active {
          background-color: grey;
          color: white;
        }

        /* Dropdown container (hidden by default). Optional: add a lighter background color and some left padding to change the design of the dropdown content */
        .dropdown-container {
          display: none;
          background-color: #262626;
          padding-left: 8px;
        }

        /* Optional: Style the caret down icon */
        .fa-caret-down {
          float: right;
          padding-right: 8px;
        }
         
        .teamName {
          padding: 12px 16px 12px 32px;
          text-decoration: none;
          font-size: 30px;
          color: white;
          display: block;
          border: none;
          background: none;
          width: 100%;
          text-align: middle;  
          font-weight: bold;
        }

        /* Some media queries for responsiveness */
        @media screen and (max-height: 450px) {
          .sidenav {padding-top: 15px;}
          .sidenav a {font-size: 18px;}
        }
        </style>
    </head>
        
    <body>
     
        <div class="sidenav">
          <p class="teamName">Outliers</p>
          <a href="https://taixil.github.io/STOR-565-Final-Project/">Home</a>
          <button class="dropdown-btn">Biweekly Reports 
            <i class="fa fa-caret-down"></i>
          </button>
          <div class="dropdown-container">
            <a href="https://taixil.github.io/STOR-565-Final-Project/biweekly-report1">Report 1</a>
            <a href="https://taixil.github.io/STOR-565-Final-Project/biweekly-report2">Report 2</a>
            <a href="https://taixil.github.io/STOR-565-Final-Project/biweekly-report3">Report 3</a>
          </div>
          <a href="https://taixil.github.io/STOR-565-Final-Project/project-proposal">Project Proposal</a>
          <a href="https://taixil.github.io/STOR-565-Final-Project/final-report">Final Report</a>
        </div>

        <script>
        /* Loop through all dropdown buttons to toggle between hiding and showing its dropdown content - This allows the user to have multiple dropdowns without any conflict */
        var dropdown = document.getElementsByClassName("dropdown-btn");
        var i;

        for (i = 0; i < dropdown.length; i++) {
          dropdown[i].addEventListener("click", function() {
          this.classList.toggle("active");
          var dropdownContent = this.nextElementSibling;
          if (dropdownContent.style.display === "block") {
          dropdownContent.style.display = "none";
          } else {
          dropdownContent.style.display = "block";
          }
          });
        }
        </script>
            
        <h1>Home</h1>
        
        <div>
            <p>Our Dataset: <a href="https://www.kaggle.com/datatattle/covid-19-nlp-text-classification">Tweets during COVID pandenmic.</a> </p>
        </div>
    
    </body>
    
    
