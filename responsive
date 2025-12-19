<!DOCTYPE html>
<html>
<head>
<meta name="viewport"
  content="width=device-width, initial-scale=1.0">
  
<style>

/* Desktop view*/
body {
    font-family: Arial, sans-serif;
    margin: 0; 
    padding: 20px;
    background-color: rgb(187, 11, 11);
    color: blue;

}
.container {
    display: flex;
    gap: 20px;
}

.box {
    flex: 1;
    padding: 20px;
    border: 2px solid blue;
    background-color: lightblue;
    text-align: center;
    font-size: 20px;
}

/* Max-width:mobile */
@media (max-width: 600px) {
    .container {
        flex-direction: column;
    }
    .box {
        background-color: lightgreen;
    }
}
/* Min-width for the large screens */
@media (min-width: 1000px) {
    .box {
        background-color: lightcoral;
        font-size: 24px;
    }
}

/* Orientation */
@media (orientation: landscape) {
    body {
        background-color: #f0f0f0;
    }
}

/* Screen & print */
@media print {
    body {
        background-color: white;
        color: black;
    }

    .box {
        border: 1px solid black;
        background-color: white;
    }
}

/* Resolution */
@media (min-resolution: 2dppx) {
    .box {
        border-width: 4px;
    }
}

/* color scheme */
@media (prefers-color-scheme: dark) {
    body {
        background-color: #121212;
        color: white;
    }

    .box {
        background-color: #333;
        border-color: white;
    }
    h2{
      text-align: center;  
    }
}

</style>  
</head>

<body>

 <h2>Responsive Web Design concepts</h2>
 
 <div class="container">
    <div class="box">India</div>
    <div class="box">America</div>
    <div class="box">Canada</div>
 </div>
</body>
</html>
