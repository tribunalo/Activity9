<!DOCTYPE html>
<html>
<head>
  <title>Box Model Sample</title>
  <style>
    .box {
      width: 250px;
      height: 250px;
      border: 2px solid black;
      padding: 20px;
      margin: 30px;
      background-color: white;
      text-align: center; /* Center-align the content */
      display: flex;
      flex-direction: column;
      justify-content: center;
    }
    
    .box img {
      border-radius: 50%;
      max-width: 95%;
      max-height: 80%;
    }
  </style>
</head>
<body>
  <div class="box">
    <img src="https://images.pexels.com/photos/14440674/pexels-photo-14440674.jpeg" alt="Sample Image">
    <h6>I am a Cat!</h6>
  </div>
</body>
</html>
