# Kariakor--orphanage
Website for Kariakor orphanage -supporting Children in Kenya
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Kariakor Orphanage | Every Child Deserves Hope</title>
<style>
  body {
    font-family: "Poppins", sans-serif;
    margin: 0;
    background-color: #fff;
    color: #333;
    overflow-x: hidden;
  }
  header {
    background: linear-gradient(rgba(220,0,0,0.6), rgba(220,0,0,0.6)),
      url('YOUR_FIRST_PHOTO.jpg') center/cover no-repeat;
    color: #fff;
    text-align: center;
    padding: 100px 20px;
    animation: fadeIn 2s ease-in;
  }
  header img.logo {
    width: 160px;
    margin-bottom: 15px;
  }
  header h1 {
    font-size: 2.4em;
    margin: 0;
  }
  header p {
    font-size: 1.2em;
    margin-top: 10px;
  }
  .donate-btn {
    background: #e60000;
    color: white;
    padding: 15px 30px;
    border: none;
    border-radius: 25px;
    cursor: pointer;
    font-size: 1em;
    margin-top: 20px;
    transition: background 0.3s;
  }
  .donate-btn:hover { background: #b30000; }

  section {
    padding: 60px 20px;
    text-align: center;
  }

  h2 {
    color: #e60000;
    margin-bottom: 20px;
  }

  .mission {
    max-width: 800px;
    margin: 0 auto;
    line-height: 1.7;
    font-size: 1.1em;
  }

  .progress-container {
    background: #f3f3f3;
    border-radius: 30px;
    overflow: hidden;
    max-width: 600px;
    margin: 40px auto;
  }
  .progress-bar {
    height: 25px;
    background: #e60000;
    width: 8%;
    transition: width 1s;
  }
  .progress-text {
    margin-top: 10px;
    font-weight: 600;
  }

  .gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 15px;
    max-width: 900px;
    margin: 0 auto;
  }
  .gallery img {
    width: 100%;
    border-radius: 10px;
    animation: fadeInUp 1.5s ease;
  }

  .socials {
    margin-top: 30px;
  }
  .socials a {
    text-decoration: none;
    color: #e60000;
    margin: 0 10px;
    font-size: 1.4em;
  }

  footer {
    background: #e60000;
    color: white;
    padding: 15px 10px;
    text-align: center;
    font-size: 0.9em;
  }

  @keyframes fadeIn {
    from {opacity: 0;}
    to {opacity: 1;}
  }
  @keyframes fadeInUp {
    from {opacity: 0; transform: translateY(20px);}
    to {opacity: 1; transform: translateY(0);}
  }
</style>
</head>
<body>

<header>
  <img src="YOUR_LOGO.png" alt="Kariakor Orphanage Logo" class="logo">
  <h1>Kariakor Orphanage</h1>
  <p>Every child deserves love, food, and hope.</p>
  <button class="donate-btn" id="donateBtn">Donate Now</button>
</header>

<section>
  <h2>Our Mission</h2>
  <p class="mission">
    Kariakor Orphanage in Kenya is a haven of hope and care for children in need.
    We believe that every child deserves love, food, shelter, education, and a bright future.
    Through the generosity of kind-hearted people like you, we strive to provide nutritious meals,
    safe housing, quality education, and clothing for every orphan and vulnerable child.
    Your contribution gives them not only the essentials of life, but also the joy of feeling valued
    and loved. Together, we can build a brighter tomorrow — one child at a time.
  </p>

  <div class="progress-container">
    <div class="progress-bar"></div>
  </div>
  <div class="progress-text">KES 230,000 raised of 3,000,000 goal</div>
</section>

<section>
  <h2>Our Children</h2>
  <div class="gallery">
    <img src="YOUR_SECOND_PHOTO.jpg" alt="Children photo 1">
    <img src="YOUR_THIRD_PHOTO.jpg" alt="Children photo 2">
  </div>
</section>

<section>
  <h2>Connect With Us</h2>
  <p>We would love to hear from you! You can reach us at: <br>
  <strong>Email:</strong> baharirashid32@gmail.com</p>
  <div class="socials">
    <a href="#">🌐</a>
    <a href="#">📘</a>
    <a href="#">📸</a>
    <a href="#">🐦</a>
  </div>
</section>

<footer>
  © 2025 Kariakor Orphanage | All Rights Reserved
</footer>

<script>
document.getElementById("donateBtn").addEventListener("click", function() {
  window.open("https://www.paypal.com/donate?business=baharirashid32@gmail.com", "_blank");
  setTimeout(function() {
    alert("Thank you for supporting Kariakor Orphanage — your kindness changes lives!");
  }, 800);
});
</script>

</body>
</html>
