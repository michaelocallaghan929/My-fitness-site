<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Online Fitness Coaching</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@500;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Montserrat', sans-serif;
      background: #f8f9fa;
      color: #333;
    }
    header {
      background: #111;
      color: #fff;
      padding: 2em;
      text-align: center;
    }
    .section {
      padding: 3em 1.5em;
      max-width: 900px;
      margin: auto;
    }
    .services h2, .testimonials h2, .contact h2 {
      text-align: center;
      margin-bottom: 1em;
    }
    .testimonial {
      background: #fff;
      padding: 1.5em;
      margin: 1em 0;
      border-left: 5px solid #2ecc71;
    }
    form {
      display: flex;
      flex-direction: column;
      gap: 1em;
      max-width: 500px;
      margin: auto;
    }
    input, textarea {
      padding: 1em;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    button {
      padding: 1em;
      background: #2ecc71;
      color: white;
      border: none;
      cursor: pointer;
      font-weight: bold;
    }
    button:hover {
      background: #27ae60;
    }
  </style>
</head>
<body>

<header>
  <h1>Get Fit. Stay Strong.</h1>
  <p>Personalized Online Fitness Coaching to Help You Crush Your Goals</p>
</header>

<section class="section services">
  <h2>What I Offer</h2>
  <p>I provide personalized workout programs, nutrition guidance, and 1-on-1 virtual coaching to help you build strength, lose fat, and live your healthiest life—all from the comfort of your home.</p>
</section>

<section class="section testimonials">
  <h2>What Clients Are Saying</h2>
  <div class="testimonial">
    <p>“I’ve never felt stronger! The weekly check-ins kept me accountable and motivated.” – Alex M.</p>
  </div>
  <div class="testimonial">
    <p>“The workout plans were easy to follow, and I saw results fast.” – Jamie R.</p>
  </div>
</section>

<section class="section contact">
  <h2>Start Your Fitness Journey</h2>
  <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
    <input type="text" name="name" placeholder="Your name" required>
    <input type="email" name="_replyto" placeholder="Your email" required>
    <textarea name="message" rows="5" placeholder="Tell me your goals" required></textarea>
    <button type="submit">Send</button>
  </form>
</section>

</body>
</html>
