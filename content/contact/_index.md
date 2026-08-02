---
title: "Contact"
layout: "contact-form"
---

<!-- Import Cloudflare Turnstile CAPTCHA Library Script Script -->
<script src="https://cloudflare.com" async defer></script>

<div style="max-width: 550px; margin: 0 auto; padding: 2rem 0; font-family: 'Roboto Mono', monospace;">
  
  <!-- Sleek Ink/Minimalist Header Prompt -->
  <div style="border-bottom: 2px dashed #7c2d12; padding-bottom: 1rem; margin-bottom: 2.5rem;">
    <p style="font-size: 1.1rem; letter-spacing: -0.5px; color: #d4d4d8; margin: 0;">
      // Leave a mark in ink. Drop a message below.
    </p>
  </div>

  <form action="https://formspree.io" method="POST" style="display: flex; flex-direction: column; gap: 2rem;">
    
    <!-- Custom Thank You Redirect Target Link -->
    <input type="hidden" name="_next" value="https://github.io">

    <!-- Name Field Input Wrapper -->
    <div style="position: relative;">
      <input type="text" name="name" required placeholder="Your Name" style="width: 100%; padding: 0.75rem 0; border: none; border-bottom: 1px solid #444; background: transparent; color: #f5f5f5; font-size: 1rem; outline: none; transition: border-color 0.3s;" onfocus="this.style.borderColor='#7c2d12'" onblur="this.style.borderColor='#444'">
    </div>
    
    <!-- Email Field Input Wrapper -->
    <div style="position: relative;">
      <input type="email" name="email" required placeholder="Your Email Address" style="width: 100%; padding: 0.75rem 0; border: none; border-bottom: 1px solid #444; background: transparent; color: #f5f5f5; font-size: 1rem; outline: none; transition: border-color 0.3s;" onfocus="this.style.borderColor='#7c2d12'" onblur="this.style.borderColor='#444'">
    </div>

    <!-- Subject Dropdown Selection Element -->
    <div style="position: relative;">
      <select name="subject" required style="width: 100%; padding: 0.75rem 0; border: none; border-bottom: 1px solid #444; background: #1a120b; color: #a1a1aa; font-size: 1rem; outline: none; cursor: pointer; transition: border-color 0.3s;" onfocus="this.style.borderColor='#7c2d12'; this.style.color='#f5f5f5'" onblur="this.style.borderColor='#444'">
        <option value="" disabled selected hidden>Choose Subject...</option>
        <option value="General Inquiry">General Inquiry</option>
        <option value="Feedback / Critique">Feedback & Critique</option>
        <option value="Academic Discussion">Academic Discussion</option>
        <option value="Just Saying Hi">Just Saying Hi</option>
      </select>
    </div>
    
    <!-- Message Field Text Area Container Box -->
    <div style="position: relative;">
      <textarea name="message" rows="4" required placeholder="Write your message here..." style="width: 100%; padding: 0.75rem 0; border: none; border-bottom: 1px solid #444; background: transparent; color: #f5f5f5; font-size: 1rem; outline: none; resize: none; transition: border-color 0.3s;" onfocus="this.style.borderColor='#7c2d12'" onblur="this.style.borderColor='#444'"></textarea>
    </div>

    <!-- Cloudflare Turnstile Invisible/Minimal CAPTCHA Injection Box -->
    <div class="cf-turnstile" data-sitekey="YOUR_CLOUDFLARE_TURNSTILE_SITE_KEY" data-theme="dark" style="margin-top: 0.5rem;"></div>
    
    <!-- Sleek Minimalist Submit Trigger Button Widget Layout -->
    <button type="submit" style="background-color: transparent; color: #7c2d12; border: 1px solid #7c2d12; padding: 0.75rem 2rem; cursor: pointer; font-weight: bold; font-family: inherit; font-size: 0.95rem; text-transform: uppercase; letter-spacing: 1px; align-self: flex-start; transition: all 0.3s ease;" onmouseover="this.style.backgroundColor='#7c2d12'; this.style.color='#ffffff'" onmouseout="this.style.backgroundColor='transparent'; this.style.color='#7c2d12'">
      Transmit Signatures →
    </button>
  </form>
</div>
