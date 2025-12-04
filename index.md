Hello - I am trying out an idea to support reading: the "Read_Easy_Quiz"

Looks like the last line is always in bigger font? Maybe all this above is the 'Title'?
---
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Custom Flashcard & Quiz Apps</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #fafafa;
      color: #333;
    }

    header {
      background: linear-gradient(135deg, #6a9cff, #4d7bff);
      color: white;
      padding: 60px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 42px;
      margin-bottom: 10px;
    }

    header p {
      font-size: 20px;
      opacity: 0.95;
    }

    .section {
      padding: 50px 20px;
      max-width: 900px;
      margin: auto;
    }

    h2 {
      text-align: center;
      margin-bottom: 20px;
      font-size: 32px;
    }

    .demo-box {
      text-align: center;
      padding: 20px;
      border: 2px solid #ccc;
      border-radius: 10px;
      background: white;
    }

    .feature-list {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }

    .feature {
      flex: 1 1 260px;
      background: white;
      border-radius: 10px;
      padding: 20px;
      border: 1px solid #ddd;
      text-align: center;
    }

    .pricing-box {
      background: white;
      border-radius: 10px;
      border: 1px solid #ddd;
      padding: 30px;
      max-width: 500px;
      margin: auto;
      text-align: center;
    }

    button, .contact-btn {
      background: #4d7bff;
      color: white;
      border: none;
      padding: 12px 22px;
      font-size: 18px;
      border-radius: 8px;
      cursor: pointer;
      margin-top: 10px;
      text-decoration: none;
      display: inline-block;
    }

    button:hover, .contact-btn:hover {
      background: #3d64d6;
    }

    form {
      display: flex;
      flex-direction: column;
      gap: 10px;
      max-width: 500px;
      margin: auto;
    }

    input, textarea {
      padding: 12px;
      font-size: 16px;
      border-radius: 6px;
      border: 1px solid #ccc;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #eee;
      margin-top: 60px;
    }
  </style>
</head>
<body>

<header>
  <h1>Custom Flashcard & Quiz Apps</h1>
  <p>Personalised learning tools for children, language learners, schools, and fun games.</p>
</header>

<div class="section" id="demo">
  <h2>Try the Demo</h2>
  <div class="demo-box">
    <p>Here’s a simple flashcard demo:</p>
    <a class="contact-btn" href="flashcards-demo.html">Open Demo</a>
  </div>
</div>

<div class="section" id="features">
  <h2>What I Offer</h2>
  <div class="feature-list">
    <div class="feature">
      <h3>✔ Custom Topics</h3>
      <p>Animals, history, science, languages, maths — anything you want.</p>
    </div>
    <div class="feature">
      <h3>✔ Images & Audio</h3>
      <p>Flashcards can include images, sounds, or even animations.</p>
    </div>
    <div class="feature">
      <h3>✔ Multiple Formats</h3>
      <p>Web apps, downloadable Python apps, or mobile-friendly versions.</p>
    </div>
    <div class="feature">
      <h3>✔ Kid-Friendly Designs</h3>
      <p>Colours, cartoon icons, large buttons — perfect for young learners.</p>
    </div>
  </div>
</div>

<div class="section" id="pricing">
  <h2>Pricing</h2>
  <div class="pricing-box">
    <h3>Custom Flashcard / Quiz App</h3>
    <p>Tailored to your topic, age group, images, audio, and special requests.</p>
    <p style="font-size:24px; font-weight:bold;">From £10</p>
    <a href="#contact" class="contact-btn">Request a Custom App</a>
  </div>
</div>

<div class="section" id="contact">
  <h2>Contact Me</h2>

  <!-- OPTION A: Simple email link -->
  <p style="text-align:center;">
    For custom requests, email me at:<br>
    <strong>yourname@example.com</strong>
  </p>
  
  <!-- OPTION B: OR use a contact form (Formspree example) -->
  <!-- 
  <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
    <input type="email" name="email" placeholder="Your email" required>
    <textarea name="message" rows="5" placeholder="Tell me what you’d like…" required></textarea>
    <button type="submit">Send Message</button>
  </form>
  -->
</div>

<footer>
  <p>© 2025 Custom Flashcard Apps — Made with ♡</p>
</footer>

</body>
</html>
