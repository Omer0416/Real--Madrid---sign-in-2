# Real--Madrid---sign-in-2
Real Madrid training session 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Real Madrid Sign-In</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body, html {
      height: 100%;
      font-family: Arial, sans-serif;
    }

    /* 🔁 Video Background */
    .video-bg {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      object-fit: cover;
      z-index: -1;
    }

    /* 🔒 Form Container */
    .form-container {
      position: relative;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      z-index: 1;
    }

    .form-box {
      background-color: rgba(255, 255, 255, 0.85);
      padding: 40px;
      border-radius: 10px;
      box-shadow: 0 0 15px rgba(0, 0, 0, 0.3);
      text-align: center;
    }

    input {
      padding: 10px;
      width: 100%;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    button {
      padding: 10px 20px;
      background-color: #007bff;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    button:hover {
      background-color: #0056b3;
    }
  </style>
</head>
<body>

  <!-- 🔁 Background Video -->
  <video autoplay loop muted playsinline class="video-bg">
    <source src="real.mp4" type="video/mp4" />
    Your browser does not support the video tag.
  </video>

  <!-- 🔐 Sign-In Form -->
  <div class="form-container">
    <div class="form-box">
      <h2>Sign In</h2>
      <form>
        <input type="text" placeholder="Username" required />
        <input type="password" placeholder="Password" required />
        <button type="submit">Sign In</button>
      </form>
    </div>
  </div>

</body>
</html>
