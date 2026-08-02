---
title: "Contact"
layout: "contact-form"
---

<!-- Native Cloudflare Turnstile Library Endpoint Integration -->
<script src="https://cloudflare.com" async defer></script>

<div style="max-width: 600px; margin: 0 auto; padding: 3rem 1rem; font-family: 'Roboto Mono', Courier, monospace; background-color: #1a120b; color: #f5f5f5;">
  
  <!-- Subtle Typewriter Notebook Style Header Accent Banner -->
  <div style="border-left: 3px solid #7c2d12; padding-left: 1rem; margin-bottom: 3.5rem;">
    <p style="font-size: 1.1rem; letter-spacing: -0.3px; color: #d4d4d8; margin: 0; font-weight: bold;">
      // TRANSMIT SIGNATURES
    </p>
    <p style="font-size: 0.9rem; color: #a1a1aa; margin: 0.25rem 0 0 0;">
      Leave a mark in ink. Your message will be relayed privately.
    </p>
  </div>

  <!-- PASTE YOUR FORMSPREE ENDPOINT IN THE ACTION TAG BELOW -->
  <form action="https://formspree.io/f/meeybyvy" method="POST" style="display: flex; flex-direction: column; gap: 2.5rem;">
    
    <!-- Custom Page Redirection Path Target Trigger -->
    <input type="hidden" name="_next" value="https://github.io">

    <!-- Name Parameter Input Row Element -->
    <div style="display: flex; flex-direction: column; gap: 0.5rem;">
      <label style="font-size: 0.85rem; text-transform: uppercase; letter-spacing: 1px; color: #7c2d12; font-weight: bold;">01. Identification</label>
      <input type="text" name="name" required placeholder="Enter your name..." style="width: 100%; padding: 0.75rem; border: 1px dashed #444; border-radius: 4px; background: #2a1f15; color: #f5f5f5; font-size: 0.95rem; font-family: inherit; outline: none; transition: border-color 0.3s;" onfocus="this.style.borderColor='#7c2d12'" onblur="this.style.borderColor='#444'">
    </div>
    
    <!-- Email Parameter Input Row Element -->
    <div style="display: flex; flex-direction: column; gap: 0.5rem;">
      <label style="font-size: 0.85rem; text-transform: uppercase; letter-spacing: 1px; color: #7c2d12; font-weight: bold;">02. Return Address</label>
      <input type="email" name="email" required placeholder="Enter your email address..." style="width: 100%; padding: 0.75rem; border: 1px dashed #444; border-radius: 4px; background: #2a1f15; color: #f5f5f5; font-size: 0.95rem; font-family: inherit; outline: none; transition: border-color 0.3s;" onfocus="this.style.borderColor='#7c2d12'" onblur="this.style.borderColor='#444'">
    </div>

    <!-- Structured Subject Selection Category Row Component -->
    <div style="display: flex; flex-direction: column; gap: 0.5rem;">
      <label style="font-size: 0.85rem; text-transform: uppercase; letter-spacing: 1px; color: #7c2d12; font-weight: bold;">03. Classification</label>
      <select name="subject" required style="width: 100%; padding: 0.75rem; border: 1px dashed #444; border-radius: 4px; background: #2a1f15; color: #a1a1aa; font-size: 0.95rem; font-family: inherit; outline: none; cursor: pointer; transition: border-color 0.3s;" onfocus="this.style.borderColor='#7c2d12'; this.style.color='#f5f5f5'" onblur="this.style.borderColor='#444'">
        <option value="" disabled selected hidden>Select context topic...</option>
        <option value="General Inquiry">General Inquiry</option>
        <option value="Blog Feedback / Critique">Blog Feedback & Critique</option>
        <option value="Academic Discussion">Academic Discussion</option>
        <option value="Just Saying Hi">Just Saying Hi</option>
      </select>
    </div>
    
    <!-- Text Area Message Layout Box Row Container -->
    <div style="display: flex; flex-direction: column; gap: 0.5rem;">
      <label style="font-size: 0.85rem; text-transform: uppercase; letter-spacing: 1px; color: #7c2d12; font-weight: bold;">04. Content Log</label>
      <textarea name="message" rows="6" required placeholder="Write your text message here..." style="width: 100%; padding: 0.75rem; border: 1px dashed #444; border-radius: 4px; background: #2a1f15; color: #f5f5f5; font-size: 0.95rem; font-family: inherit; outline: none; resize: vertical; line-height: 1.6; transition: border-color 0.3s;" onfocus="this.style.borderColor='#7c2d12'" onblur="this.style.borderColor='#444'"></textarea>
    </div>

    <!-- Frictionless Silent Cloudflare Turnstile Verification Intercept Frame -->
    <div style="margin-top: 0.5rem; display: flex; justify-content: flex-start;">
      <!-- If you set up Cloudflare Turnstile, swap out YOUR_CLOUDFLARE_TURNSTILE_SITE_KEY below. Otherwise, you can safely delete this complete <div> line and use Formspree's native fallback CAPTCHA protection -->
      <div class="cf-turnstile" data-sitekey="YOUR_CLOUDFLARE_TURNSTILE_SITE_KEY" data-theme="dark"></div>
    </div>
    
    <!-- Premium Industrial Styled Action Button Widget -->
    <button type="submit" style="background-color: transparent; color: #7c2d12; border: 1px solid #7c2d12; border-radius: 4px; padding: 1rem 2.5rem; cursor: pointer; font-weight: bold; font-family: inherit; font-size: 0.85rem; text-transform: uppercase; letter-spacing: 1.5px; align-self: flex-start; transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);" onmouseover="this.style.backgroundColor='#7c2d12'; this.style.color='#ffffff'; this.style.letterSpacing='2px'" onmouseout="this.style.backgroundColor='transparent'; this.style.color='#7c2d12'; this.style.letterSpacing='1.5px'">
      Commit to Log →
    </button>
  </form>
</div>
