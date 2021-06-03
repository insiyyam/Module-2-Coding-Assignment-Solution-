# Module-2-Coding-Assignment-Solution-
DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Our Menu</title>
<style>

/********** Base styles **********/
* {
  box-sizing: border-box;
}
h1 {
  margin-bottom: 15px;
}

p {
  border: 1px solid black;
  background-color: #A52A2A;
  width: 90%;
  height: 150px;
  margin-right: auto;
  margin-left: auto;
  font-family: Helvetica;
  color: white;
}

/* Simple Responsive Framework. */
.row {
  width: 100%;
}

/********** Large devices only **********/
@media (min-width: 992px) and (min-width: 1200px) {
  .col-lg-1, .col-lg-2, .col-lg-3,  {
    float: left;
    border: 1px solid green;
  }
  .col-lg-1 {
    width: 80%;
  }
  .col-lg-2 {
    width:150%;
    height:150%;
  }
  .col-lg-3 {
    width: 25%;
 
  }

/********** Medium devices only **********/
@media (min-width: 991px) and (max-width: 1199px) {
  .col-md-1, .col-md-2, .col-md-3, {
    float: left;
    border: 1px solid green;
  }
  .col-md-1 {
    width: 50%;
  }
  .col-md-2 {
    width: 100%;
    Height: 100%
  }
  .col-md-3 {
    width: 125%;
  }
  
  

</style>
</head>
<body>
<h1>Responsive Layout</h1>

<div class="row">
  <div class="col-lg-3 col-md-6"><p>Item 1</p></div>
  <div class="col-lg-3 col-md-6"><p>Item 2</p></div>
  <div class="col-lg-3 col-md-6"><p>Item 3</p></div>
  <div class="col-lg-3 col-md-6"><p>Item 4</p></div>
  <div class="col-lg-3 col-md-6"><p>Item 5</p></div>
  <div class="col-lg-3 col-md-6"><p>Item 6</p></div>
  <div class="col-lg-3 col-md-6"><p>Item 7</p></div>
  <div class="col-lg-3 col-md-6"><p>Item 8</p></div>
</div>

</body>
</html>
© 2021 GitHub, Inc.
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
