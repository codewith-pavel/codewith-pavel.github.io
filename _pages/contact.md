---
permalink: /contact/
title: "Communication"
author_profile: true
---

<style>
  .contact-page { max-width: 780px; margin: 0 auto; padding: 2rem 1rem 4rem; }
  .contact-page > h1 { margin: 0 0 0.75rem; padding-bottom: 0.85rem; border-bottom: 3px solid var(--global-text-color); font-size: 2.2rem; }
  .contact-page > h1::before { content: "01 / CONTACT"; display: block; margin-bottom: 0.65rem; color: var(--global-text-color-light); font-size: 0.72rem; letter-spacing: 0.16em; font-weight: 700; }
  .contact-page .contact-form { max-width: 560px; padding: 1.35rem; border: 1px solid var(--global-border-color); border-left: 4px solid var(--global-text-color); background: var(--global-bg-color); box-shadow: 0 10px 24px rgba(17,24,39,0.08); }
  .contact-page .contact-form input, .contact-page .contact-form textarea { border-color: var(--global-border-color) !important; border-radius: 4px !important; background: var(--global-bg-color) !important; color: var(--global-text-color) !important; outline: none; }
  .contact-page .contact-form input:focus, .contact-page .contact-form textarea:focus { border-color: var(--global-text-color) !important; box-shadow: 0 0 0 2px var(--global-text-color); }
  .contact-page .contact-form button { border: 1px solid var(--global-text-color) !important; border-radius: 4px !important; background: var(--global-text-color) !important; color: var(--global-bg-color) !important; font-weight: 700; }
  .contact-page .contact-form button:hover { opacity: 0.78; }
  .contact-page .contact-details { margin-top: 2.5rem; padding: 1.5rem; border: 1px solid var(--global-border-color); border-top: 3px solid var(--global-text-color); border-radius: 0; background: var(--global-bg-color); }
  .contact-page .contact-details a { color: var(--global-text-color) !important; }
  .contact-page .contact-details img { filter: grayscale(1) contrast(1.25); }
  .contact-page .contact-details a[aria-label], .contact-page .contact-details a[href^="mailto:"] { border-color: var(--global-border-color) !important; border-radius: 4px !important; background: var(--global-bg-color) !important; }
</style>

<div class="contact-page contact-content-only">
  <h1 style="font-size: 2.2rem; margin-bottom: 1rem;">Let's Connect</h1>

  <p style="margin-bottom: 2rem; color: inherit;">
    For research collaborations, or academic inquiries, please get in touch.
  </p>

  <form class="contact-form" id="contact-form" method="post" style="display: flex; flex-direction: column; gap: 1rem; max-width: 560px;">
    <input type="text" id="name" name="name" placeholder="Your Name" required style="padding: 0.9rem 1rem; border: 1px solid var(--global-border-color, rgba(0,0,0,0.15)); border-radius: 8px; width: 100%; font: inherit; background: transparent; color: var(--global-text-color, #111);">
    <input type="email" id="email" name="email" placeholder="Your Email" required style="padding: 0.9rem 1rem; border: 1px solid var(--global-border-color, rgba(0,0,0,0.15)); border-radius: 8px; width: 100%; font: inherit; background: transparent; color: var(--global-text-color, #111);">
    <textarea id="message" name="message" rows="5" placeholder="Your Message" required style="padding: 0.9rem 1rem; border: 1px solid var(--global-border-color, rgba(0,0,0,0.15)); border-radius: 8px; width: 100%; resize: vertical; font: inherit; background: transparent; color: var(--global-text-color, #111);"></textarea>
    <button type="submit" style="padding: 0.9rem 1.5rem; border: none; border-radius: 8px; background: var(--global-link-color, #111); color: var(--global-bg-color, #fff); cursor: pointer; width: fit-content; font: inherit;">Send Message</button>
    <div id="form-message" style="min-height: 24px; color: var(--global-text-color, inherit);"></div>
  </form>

  <div style="margin-top: 2.5rem; padding: 1.5rem; border: 1px solid var(--global-border-color, rgba(15, 23, 42, 0.12)); border-radius: 18px; background: transparent;">
    <div style="display: flex; flex-wrap: wrap; gap: 1rem; align-items: center; justify-content: space-between; margin-bottom: 1.25rem;">
      <div>
        <p style="margin: 0 0 0.5rem; font-size: 0.8rem; font-weight: 700; letter-spacing: 0.08em; text-transform: uppercase; color: var(--global-text-color-light, #64748b);">Direct contact</p>
        <p style="margin: 0; font-size: 1rem; color: var(--global-text-color, #111827);">
          Email at <strong><a href="mailto:mahir.pavel@gmail.com" style="color: inherit; text-decoration: underline; text-underline-offset: 0.18em; text-decoration-thickness: 1.5px;">mahir.pavel@gmail.com</a></strong>
        </p>
      </div>
      <a href="mailto:mahir.pavel@gmail.com" target="_blank" rel="noopener noreferrer" aria-label="Email Mahir Afser Pavel" style="display: inline-flex; align-items: center; justify-content: center; gap: 0.75rem; padding: 0.8rem 1rem; border: 1px solid var(--global-border-color, rgba(15, 23, 42, 0.12)); border-radius: 999px; text-decoration: none; color: var(--global-text-color, #111827); background: transparent; transition: transform 0.2s ease, border-color 0.2s ease;">
        <img src="https://img.icons8.com/fluent/48/000000/gmail.png" alt="Gmail" style="width: 28px; height: 28px; vertical-align: middle;" />
        <span style="font-weight: 700;">Send an email</span>
      </a>
    </div>

    <div style="margin-top: 1.25rem;">
      <p style="margin: 0 0 0.9rem; font-size: 0.8rem; font-weight: 700; letter-spacing: 0.08em; text-transform: uppercase; color: var(--global-text-color-light, #64748b);">Connect elsewhere</p>
      <div style="display: flex; flex-wrap: wrap; gap: 0.8rem; align-items: center;">
        <a href="https://www.facebook.com/mahir.afser.19115/" target="_blank" rel="noopener noreferrer" style="display: inline-flex; align-items: center; justify-content: center; width: 42px; height: 42px; border: 1px solid var(--global-border-color, rgba(15, 23, 42, 0.12)); border-radius: 12px; background: transparent; transition: transform 0.2s ease, border-color 0.2s ease;">
          <img src="https://img.icons8.com/fluent/48/000000/facebook-new.png" alt="Facebook" style="width: 22px; height: 22px;" />
        </a>
        <a href="https://www.linkedin.com/in/mahirafserpavel/" target="_blank" rel="noopener noreferrer" style="display: inline-flex; align-items: center; justify-content: center; width: 42px; height: 42px; border: 1px solid var(--global-border-color, rgba(15, 23, 42, 0.12)); border-radius: 12px; background: transparent; transition: transform 0.2s ease, border-color 0.2s ease;">
          <img src="https://img.icons8.com/fluent/48/000000/linkedin.png" alt="LinkedIn" style="width: 22px; height: 22px;" />
        </a>
        <a href="https://github.com/codewith-pavel" target="_blank" rel="noopener noreferrer" style="display: inline-flex; align-items: center; justify-content: center; width: 42px; height: 42px; border: 1px solid var(--global-border-color, rgba(15, 23, 42, 0.12)); border-radius: 12px; background: transparent; transition: transform 0.2s ease, border-color 0.2s ease;">
          <img src="https://img.icons8.com/fluent/48/000000/github.png" alt="GitHub" style="width: 22px; height: 22px;" />
        </a>
        <a href="https://wa.me/8801873742510" target="_blank" rel="noopener noreferrer" style="display: inline-flex; align-items: center; justify-content: center; width: 42px; height: 42px; border: 1px solid var(--global-border-color, rgba(15, 23, 42, 0.12)); border-radius: 12px; background: transparent; transition: transform 0.2s ease, border-color 0.2s ease;">
          <img src="https://img.icons8.com/fluent/48/000000/whatsapp.png" alt="WhatsApp" style="width: 22px; height: 22px;" />
        </a>
        <a href="https://t.me/map19115" target="_blank" rel="noopener noreferrer" style="display: inline-flex; align-items: center; justify-content: center; width: 42px; height: 42px; border: 1px solid var(--global-border-color, rgba(15, 23, 42, 0.12)); border-radius: 12px; background: transparent; transition: transform 0.2s ease, border-color 0.2s ease;">
          <img src="https://img.icons8.com/fluent/48/000000/telegram-app.png" alt="Telegram" style="width: 22px; height: 22px;" />
        </a>
      </div>
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
          messageContainer.style.color = getComputedStyle(document.documentElement).getPropertyValue('--global-text-color') || '#111';
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
