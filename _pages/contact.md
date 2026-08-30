---
permalink: /contact/
title: "Contact"
author_profile: true
---

<div id="particles-js"></div>

<style>
  * {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }

  body {
    font-family: 'Montserrat', sans-serif;
    color: #fff;
    background: url('https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=1600&q=80') no-repeat center center/cover fixed;
    line-height: 1.6;
    user-select: none;
  }

  .contact-page {
    min-height: 100vh;
    background: rgba(0, 0, 0, 0.7);
  }

  nav {
    background-color: rgba(0, 0, 0, 0.8);
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    z-index: 1000;
    padding: 15px 0;
    text-align: center;
    backdrop-filter: blur(8px);
  }

  nav a {
    color: #fff;
    text-decoration: none;
    padding: 10px 20px;
    transition: background-color 0.3s ease, color 0.3s ease;
    font-size: 15px;
    display: inline-block;
  }

  nav a:hover,
  nav a.active {
    background-color: rgba(255, 255, 255, 0.14);
    color: #fff;
    border-radius: 6px;
  }

  .toggle-menu {
    display: none;
    background: none;
    border: none;
    font-size: 1.5em;
    cursor: pointer;
    color: white;
    position: relative;
  }

  #contact {
    text-align: center;
    padding: 100px 20px 40px;
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .contact-content {
    max-width: 820px;
    width: 100%;
    background-color: rgba(0, 0, 0, 0.62);
    padding: 40px;
    border-radius: 16px;
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.45);
    border: 1px solid rgba(255, 255, 255, 0.08);
  }

  .title {
    font-size: clamp(2rem, 3vw, 2.5rem);
    margin-bottom: 20px;
    font-weight: 700;
  }

  .subtitle {
    font-size: 15px;
    margin-bottom: 30px;
    font-weight: 400;
    color: rgba(255,255,255,0.9);
  }

  .contact-form {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 0;
  }

  .contact-form input,
  .contact-form textarea {
    width: 100%;
    max-width: 520px;
    padding: 15px;
    margin-bottom: 20px;
    border: none;
    border-radius: 10px;
    font-size: 14px;
    font-family: 'Montserrat', sans-serif;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.15);
    transition: box-shadow 0.3s ease, transform 0.2s ease;
  }

  .contact-form input:focus,
  .contact-form textarea:focus {
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.22);
    outline: none;
    transform: translateY(-1px);
  }

  .contact-form button {
    background-color: #7a7a7a;
    color: #fff;
    border: none;
    cursor: pointer;
    padding: 15px 30px;
    font-size: 16px;
    transition: background-color 0.3s ease, transform 0.3s ease;
    border-radius: 8px;
    font-family: 'Montserrat', sans-serif;
    margin-bottom: 12px;
  }

  .contact-form button:hover {
    background-color: #111;
    transform: translateY(-2px);
  }

  .contact-form button:active {
    transform: translateY(1px);
  }

  .email-button {
    display: inline-block;
    margin-inline: 5px;
    padding: 6px 12px;
    background-color: rgba(255,255,255,0.08);
    color: #fff;
    text-decoration: none;
    border-radius: 10px;
    transition: background-color 0.3s ease;
    user-select: text;
  }

  .email-button:hover {
    background-color: rgba(255,255,255,0.16);
  }

  .social-links {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 12px;
    margin-top: 16px;
  }

  .social-links a {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    width: 52px;
    height: 52px;
    border-radius: 50%;
    background: rgba(255,255,255,0.08);
    transition: transform 0.3s ease, background 0.3s ease;
  }

  .social-links a:hover {
    transform: translateY(-2px) scale(1.05);
    background: rgba(255,255,255,0.18);
  }

  .social-links img {
    width: 26px;
    height: 26px;
  }

  #form-message {
    font-size: 18px;
    min-height: 28px;
    margin: 8px 0 12px;
    color: #fff;
  }

  footer {
    background-color: rgba(0, 0, 0, 0.8);
    color: #fff;
    text-align: center;
    padding: 24px 20px;
    width: 100%;
  }

  footer p {
    margin-bottom: 8px;
  }

  #particles-js {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    z-index: -1;
  }

  @media (max-width: 768px) {
    nav {
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: row;
      gap: 8px;
      padding: 12px 10px;
    }

    nav a {
      font-size: 13px;
      padding: 8px 10px;
    }

    .contact-content {
      padding: 24px 18px;
    }
  }
</style>

<div class="contact-page">
  <nav>
    <a href="{{ '/' | relative_url }}" style="font-size: 15px;">About</a>
    <a href="{{ '/publications/' | relative_url }}" style="font-size: 15px;">Publications</a>
    <a href="{{ '/cv/' | relative_url }}" style="font-size: 15px;">CV</a>
    <a href="{{ '/contact/' | relative_url }}" class="active" style="font-size: 15px;">Contact</a>
  </nav>

  <div id="contact" class="section active">
    <div class="contact-content">
      <h1 class="title">I would love to hear from you :)</h1>

      <form class="contact-form" id="contact-form" method="post">
        <input type="text" id="name" name="name" placeholder="Your Name" required>
        <input type="email" id="email" name="email" placeholder="Your Email" required>
        <textarea id="message" name="message" rows="5" placeholder="Your Message" required></textarea>
        <button type="submit">Send Message</button>
        <div id="form-message"></div>

        <h6 class="subtitle">
          Email at <span class="email-button">mahir.pavel@gmail.com</span> or click below:
          <br>
          <a href="mailto:mahir.pavel@gmail.com" target="_blank" rel="noopener noreferrer"><img src="https://img.icons8.com/fluent/48/000000/gmail.png" alt="Gmail" style="width: 42px; height: 42px; margin-top: 10px;" /></a>
        </h6>

        <h3>Communicate with me via other social media channels.</h3>
      </form>
    </div>
  </div>

  <footer>
    <p>&copy; Personal Portfolio. All rights reserved.</p>
    <p>Developed &amp; Maintained by Owner</p>
    <p>Follow me for more info.</p>
    <div class="social-links">
      <a href="https://www.facebook.com/mahir.afser.19115/" target="_blank" rel="noopener noreferrer"><img src="https://img.icons8.com/fluent/48/000000/facebook-new.png" alt="Facebook" /></a>
      <a href="https://www.linkedin.com/in/mahir-afser-pavel/" target="_blank" rel="noopener noreferrer"><img src="https://img.icons8.com/fluent/48/000000/linkedin.png" alt="LinkedIn" /></a>
      <a href="https://twitter.com/Pavel1911580" target="_blank" rel="noopener noreferrer"><img src="https://img.icons8.com/fluent/48/000000/twitter.png" alt="Twitter" /></a>
      <a href="https://github.com/mahir-afser-pavel" target="_blank" rel="noopener noreferrer"><img src="https://img.icons8.com/fluent/48/000000/github.png" alt="GitHub" /></a>
      <a href="https://wa.me/8801873742510" target="_blank" rel="noopener noreferrer"><img src="https://img.icons8.com/fluent/48/000000/whatsapp.png" alt="WhatsApp" /></a>
      <a href="https://t.me/mahirafserpavel" target="_blank" rel="noopener noreferrer"><img src="https://img.icons8.com/fluent/48/000000/telegram-app.png" alt="Telegram" /></a>
      <a href="https://join.skype.com/invite/EkbI8cMGpoiI" target="_blank" rel="noopener noreferrer"><img src="https://img.icons8.com/fluent/48/000000/skype.png" alt="Skype" /></a>
      <a href="https://youtube.com/@user-wd9cg7iq5x?si=l_1MVj6c7_tgKOKM" target="_blank" rel="noopener noreferrer"><img src="https://img.icons8.com/fluent/48/000000/youtube-play.png" alt="YouTube" /></a>
    </div>
  </footer>
</div>

<script src="https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js"></script>
<script>
  document.addEventListener('DOMContentLoaded', function() {
    const form = document.getElementById('contact-form');
    const messageContainer = document.getElementById('form-message');

    if (form) {
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
            messageContainer.style.color = '#ffffff';
            messageContainer.innerText = 'Message sent successfully!';
            form.reset();
          } else {
            messageContainer.style.color = '#ff0000';
            messageContainer.innerText = 'An error occurred while sending your message. Please try again later.';
          }
        })
        .catch(() => {
          messageContainer.style.color = '#ff0000';
          messageContainer.innerText = 'An error occurred while sending your message. Please try again later.';
        });
      });
    }
  });

  if (window.particlesJS) {
    particlesJS('particles-js', {
      particles: {
        number: { value: 80, density: { enable: true, value_area: 800 } },
        color: { value: '#ffffff' },
        shape: { type: 'circle', stroke: { width: 0, color: '#000000' }, polygon: { nb_sides: 5 } },
        opacity: { value: 0.5, random: false, anim: { enable: false, speed: 1, opacity_min: 0.1, sync: false } },
        size: { value: 3, random: true, anim: { enable: false, speed: 40, size_min: 0.1, sync: false } },
        line_linked: { enable: true, distance: 150, color: '#ffffff', opacity: 0.4, width: 1 },
        move: {
          enable: true,
          speed: 6,
          direction: 'none',
          random: false,
          straight: false,
          out_mode: 'out',
          bounce: false,
          attract: { enable: false, rotateX: 600, rotateY: 1200 }
        }
      },
      interactivity: {
        detect_on: 'canvas',
        events: {
          onhover: { enable: true, mode: 'grab' },
          onclick: { enable: true, mode: 'push' },
          resize: true
        },
        modes: {
          grab: { distance: 140, line_linked: { opacity: 1 } },
          bubble: { distance: 400, size: 40, duration: 2, opacity: 8, speed: 3 },
          repulse: { distance: 200, duration: 0.4 },
          push: { particles_nb: 4 },
          remove: { particles_nb: 2 }
        }
      },
      retina_detect: true
    });
  }
</script>
