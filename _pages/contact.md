---
layout: page
title: "Contact"
nav: true
nav_order: 4
permalink: /contact/
---

<style>
  .contact-container {
    max-width: 600px;
    margin: 50px auto;
    padding: 20px;
    background: #292929;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
    text-align: center;
  }

  h1 {
    margin-bottom: 20px;
  }

  p {
    margin-bottom: 20px;
    font-size: 16px;
  }

  form {
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  label {
    align-self: flex-start;
    margin-bottom: 5px;
    font-weight: bold;
  }

  input, textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 15px;
    border: 1px solid #444;
    border-radius: 5px;
    font-size: 16px;
    background: #333;
    color: white;
  }

  .g-recaptcha {
    margin: 15px 0;
  }

  button {
    width: 100%;
    padding: 12px;
    font-size: 18px;
    color: white;
    background-color: #007BFF;
    border: none;
    border-radius: 5px;
    cursor: pointer;
  }

  button:hover {
    background-color: #0056b3;
  }
</style>

<div class="contact-container">
  <h1>Send Email</h1>
  <p>If you have any questions or would like to get in touch, feel free to use the form below.</p>

  <form accept-charset="UTF-8" action="https://getform.io/f/bmdkmvja" method="POST" enctype="multipart/form-data">
    <label for="name">Name:</label>
    <input type="text" name="name" id="name" required>

    <label for="email">Email:</label>
    <input type="email" name="email" id="email" required>

    <label for="message">Message:</label>
    <textarea name="message" id="message" required></textarea>

    <!-- Google reCAPTCHA -->
    <div class="g-recaptcha" data-sitekey="6LdJvOYqAAAAAGkKgAbF8226grEoc_gGPgsfNcU4"></div>

    <button type="submit">Send</button>
  </form>
</div>
<!-- S*cret: 6LdJvOYqAAAAABcuzaZHafmwMgvQ_U9XfhZAjq1x -->

<!-- Load reCAPTCHA Script -->
<script src="https://www.google.com/recaptcha/api.js" async defer></script>
