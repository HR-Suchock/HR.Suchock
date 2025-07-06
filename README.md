<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Suchock - My Portfolio</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(120deg, #f0f2f5, #dff9fb);
      animation: fadeIn 1s ease-in-out;
    }

    @keyframes fadeIn {
      from {opacity: 0;}
      to {opacity: 1;}
    }

    header {
      background-color: #2c3e50;
      color: white;
      padding: 40px 20px;
      text-align: center;
    }

    header img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      border: 4px solid white;
      margin-bottom: 15px;
      transition: transform 0.3s;
    }

    header img:hover {
      transform: scale(1.1);
    }

    section {
      max-width: 800px;
      margin: 30px auto;
      background: white;
      padding: 30px;
      border-radius: 15px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.1);
      animation: slideUp 1s ease-out;
    }

    @keyframes slideUp {
      from { transform: translateY(40px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }

    h2 {
      color: #2980b9;
      margin-bottom: 15px;
    }

    ul {
      list-style: square;
      padding-left: 20px;
      line-height: 1.8;
    }

    a {
      color: #2980b9;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    .footer {
      text-align: center;
      padding: 20px;
      color: #555;
      font-size: 14px;
    }

    @media (max-width: 600px) {
      header img {
        width: 100px;
        height: 100px;
      }
      section {
        margin: 20px;
        padding: 20px;
      }
    }
  </style>
</head>
<body>

  <header>
    <img src="https://i.ibb.co/nNWsXKVJ/IMG-20230704-WA0013.jpg" alt="Suchock Photo">
    <h1>Humayun Rashid Suchock</h1>
    <p>Beginner Web Developer & Future Freelancer</p>
  </header>

  <section>
    <h2>About Me</h2>
    <p>Hi, I'm Suchock. I recently gave my HSC exam (2025) from Dr. Mahbubur Rahman Molla College. I'm learning HTML, CSS, C programming, and Canva to build my freelancing career.</p>
  </section>

  <section>
    <h2>Skills</h2>
    <ul>
      <li>HTML (Beginner)</li>
      <li>CSS (Learning)</li>
      <li>C Programming (Basic)</li>
      <li>Canva Design (Learning)</li>
    </ul>
  </section>

  <section>
    <h2>Contact</h2>
    <p>Email: suchock@example.com</p>
    <p>
      Facebook:
      <a href="https://www.facebook.com/hr.suchock" target="_blank">
        Visit My Profile
      </a>
    </p>
  </section>

  <div class="footer">
    Made with ❤️ by Suchock | Helped by Nusrat Jahan Tanisha
  </div>

</body>
</html>
