<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Suchock - Portfolio</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #e0eafc, #cfdef3);
      color: #2c3e50;
      animation: fadeIn 1s ease-in-out;
    }

    @keyframes fadeIn {
      from {opacity: 0;}
      to {opacity: 1;}
    }

    header {
      text-align: center;
      padding: 50px 20px 30px;
      background: #2c3e50;
      color: white;
    }

    header img {
      width: 140px;
      height: 140px;
      border-radius: 50%;
      border: 4px solid white;
      object-fit: cover;
      box-shadow: 0 4px 20px rgba(0,0,0,0.3);
      margin-bottom: 15px;
      transition: transform 0.3s ease;
    }

    header img:hover {
      transform: scale(1.1);
    }

    header h1 {
      font-size: 32px;
      margin: 10px 0 5px;
    }

    header p {
      font-size: 16px;
      color: #ecf0f1;
    }

    section {
      max-width: 900px;
      margin: 30px auto;
      background: white;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }

    section:hover {
      transform: translateY(-5px);
    }

    h2 {
      color: #2980b9;
      margin-bottom: 15px;
    }

    ul {
      list-style: none;
      padding-left: 0;
    }

    ul li::before {
      content: "✔️";
      margin-right: 10px;
      color: green;
    }

    ul li {
      margin-bottom: 10px;
      font-size: 16px;
    }

    a {
      color: #2980b9;
      text-decoration: none;
      font-weight: 500;
    }

    a:hover {
      text-decoration: underline;
    }

    .footer {
      text-align: center;
      padding: 20px;
      font-size: 14px;
      color: #555;
      margin-top: 30px;
    }

    /* Responsive Design */
    @media (max-width: 600px) {
      header h1 {
        font-size: 24px;
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
    <p>Hi, I'm Suchock. I recently completed my HSC exam (2025) from Dr. Mahbubur Rahman Molla College. I'm passionate about learning web design and freelancing. Currently, I'm exploring HTML, CSS, Canva, and C programming.</p>
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
    <p>Email 1: <a href="mailto:suchock849@gmail.com">suchock849@gmail.com</a></p>
    <p>Email 2: <a href="mailto:humayunrashid597@gmail.com">humayunrashid597@gmail.com</a></p>
    <p>Facebook: <a href="https://www.facebook.com/hr.suchock" target="_blank">Visit My Profile</a></p>
  </section>

  <div class="footer">
    Made with ❤️ by Suchock | Helped by Nusrat Jahan Tanisha
  </div>

</body>
</html>
