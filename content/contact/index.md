---
title: "Contact"
description: Contact page
type: contact
---

Contact via email below (or possibly twitter/X if notifications are working).

<style>
    form {
      max-width: 800px;
      margin: 0 auto;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 16px 24px rgba(0, 0, 0, 0.1);
    }

    input[type="text"], input[type="email"], textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 15px;
      border: 1px solid #ccc; /* Border to make fields visible */
      border-radius: 4px;
      font-size: 16px;
    }

    input[type="text"]:focus, input[type="email"]:focus, textarea:focus {
      border-color: #007BFF; /* Highlight border on focus */
      outline: none;
      box-shadow: 0 0 5px rgba(0, 123, 255, 0.5);
    }

    button {
      width: 100%;
      padding: 10px;
      border: none;
      border-radius: 4px;
      font-size: 16px;
      cursor: pointer;
      background-color: color-mix(in oklab, var(--color-black) 20%, transparent);
    }

    button:hover {
        background-color: color-mix(in oklab, var(--color-black) 50%, transparent);
    }
  </style>
<form
  action="https://formspree.io/f/mleavwvj"
  method="POST"
>
  <label>
    Your email:
    <input type="email" name="_replyto">
  </label>
  <br/>
  <label>
    Your message:
    <textarea name="message" rows="10" cols="80" ></textarea>
  </label>
  <button type="submit">Send</button>
</form>
