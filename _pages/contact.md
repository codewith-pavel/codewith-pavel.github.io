---
permalink: /contact/
title: "Contact"
author_profile: true
---

<div class="contact-content-only" style="max-width: 780px; margin: 0 auto; padding: 2rem 1rem 4rem;">
  <h1 style="font-size: 2.2rem; margin-bottom: 1rem;">I would love to hear from you :)</h1>

  <p style="margin-bottom: 2rem; color: inherit;">
    For research collaborations, academic inquiries, or internship opportunities, please get in touch.
  </p>

  <form class="contact-form" id="contact-form" method="post" style="display: flex; flex-direction: column; gap: 1rem; max-width: 560px;">
    <input type="text" id="name" name="name" placeholder="Your Name" required style="padding: 0.9rem 1rem; border: 1px solid rgba(0,0,0,0.15); border-radius: 8px; width: 100%; font: inherit;">
    <input type="email" id="email" name="email" placeholder="Your Email" required style="padding: 0.9rem 1rem; border: 1px solid rgba(0,0,0,0.15); border-radius: 8px; width: 100%; font: inherit;">
    <textarea id="message" name="message" rows="5" placeholder="Your Message" required style="padding: 0.9rem 1rem; border: 1px solid rgba(0,0,0,0.15); border-radius: 8px; width: 100%; resize: vertical; font: inherit;"></textarea>
    <button type="submit" style="padding: 0.9rem 1.5rem; border: none; border-radius: 8px; background: #111; color: #fff; cursor: pointer; width: fit-content; font: inherit;">Send Message</button>
    <div id="form-message" style="min-height: 24px; color: inherit;"></div>
  </form>

  <div style="margin-top: 2rem;">
    <p style="margin-bottom: 0.75rem;">
      Email at <strong>mahir.pavel@gmail.com</strong> or click the icon below:
    </p>
    <a href="mailto:mahir.pavel@gmail.com" target="_blank" rel="noopener noreferrer" aria-label="Email Mahir Afser Pavel">
      <img src="https://img.icons8.com/fluent/48/000000/gmail.png" alt="Gmail" style="width: 42px; height: 42px; vertical-align: middle;" />
    </a>
  </div>

  <div style="margin-top: 2rem;">
    <h3 style="margin-bottom: 0.8rem;">Communicate with me via other social media channels.</h3>
    <div style="display: flex; flex-wrap: wrap; gap: 0.8rem; align-items: center;">
      <a href="https://www.facebook.com/mahir.afser.19115/" target="_blank" rel="noopener noreferrer"><img src="https://img.icons8.com/fluent/48/000000/facebook-new.png" alt="Facebook" style="width: 34px; height: 34px;" /></a>
      <a href="https://www.linkedin.com/in/mahir-afser-pavel/" target="_blank" rel="noopener noreferrer"><img src="https://img.icons8.com/fluent/48/000000/linkedin.png" alt="LinkedIn" style="width: 34px; height: 34px;" /></a>
      <a href="https://twitter.com/Pavel1911580" target="_blank" rel="noopener noreferrer"><img src="https://img.icons8.com/fluent/48/000000/twitter.png" alt="Twitter" style="width: 34px; height: 34px;" /></a>
      <a href="https://github.com/mahir-afser-pavel" target="_blank" rel="noopener noreferrer"><img src="https://img.icons8.com/fluent/48/000000/github.png" alt="GitHub" style="width: 34px; height: 34px;" /></a>
      <a href="https://wa.me/8801873742510" target="_blank" rel="noopener noreferrer"><img src="https://img.icons8.com/fluent/48/000000/whatsapp.png" alt="WhatsApp" style="width: 34px; height: 34px;" /></a>
      <a href="https://t.me/mahirafserpavel" target="_blank" rel="noopener noreferrer"><img src="https://img.icons8.com/fluent/48/000000/telegram-app.png" alt="Telegram" style="width: 34px; height: 34px;" /></a>
      <a href="https://join.skype.com/invite/EkbI8cMGpoiI" target="_blank" rel="noopener noreferrer"><img src="https://img.icons8.com/fluent/48/000000/skype.png" alt="Skype" style="width: 34px; height: 34px;" /></a>
      <a href="https://youtube.com/@user-wd9cg7iq5x?si=l_1MVj6c7_tgKOKM" target="_blank" rel="noopener noreferrer"><img src="https://img.icons8.com/fluent/48/000000/youtube-play.png" alt="YouTube" style="width: 34px; height: 34px;" /></a>
    </div>
  </div>
</div>

<script>
  document.addEventListener('DOMContentLoaded', function() {
    const form = document.getElementById('contact-form');
    const messageContainer = document.getElementById('form-message');

    if (!form || !messageContainer) return;

    form.addEventListener('submit', function(event) {
      event.preventDefault();

      const name = document.getElementById('name').value;
      const email = document.getElementById('email').value;
      const message = document.getElementById('message').value;

      fetch('https://formspree.io/f/mgvwwrwy', {
        method: 'POST',
        headers: { 'Content-Type': 'application/json' },
        body: JSON.stringify({ name, email, message })
      })
      .then(response => response.json())
      .then(data => {
        if (data.ok) {
          messageContainer.style.color = '#111';
          messageContainer.innerText = 'Message sent successfully!';
          form.reset();
        } else {
          messageContainer.style.color = '#b00020';
          messageContainer.innerText = 'An error occurred while sending your message. Please try again later.';
        }
      })
      .catch(() => {
        messageContainer.style.color = '#b00020';
        messageContainer.innerText = 'An error occurred while sending your message. Please try again later.';
      });
    });
  });
</script>
