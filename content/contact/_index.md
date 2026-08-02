---
layout: "list"
---

<div style="max-w: 600px; padding-top: 2rem;">
  <p style="margin-bottom: 1.5rem; font-size: 1.1rem;">If you would like to get in touch, please use the form below:</p>

  <form action="https://formspree.io" method="POST" style="display: flex; flex-direction: column; gap: 1.25rem;">
    
    <input type="hidden" name="_next" value="https://github.io">

    <div>
      <label style="display: block; font-weight: bold; margin-bottom: 0.5rem; color: #f5f5f5;">Your Name</label>
      <input type="text" name="name" required style="width: 100%; padding: 0.75rem; border: 1px solid #7c2d12; border-radius: 4px; background: #2a1f15; color: #f5f5f5; outline: none;">
    </div>
    
    <div>
      <label style="display: block; font-weight: bold; margin-bottom: 0.5rem; color: #f5f5f5;">Your Email</label>
      <input type="email" name="email" required style="width: 100%; padding: 0.75rem; border: 1px solid #7c2d12; border-radius: 4px; background: #2a1f15; color: #f5f5f5; outline: none;">
    </div>
    
    <div>
      <label style="display: block; font-weight: bold; margin-bottom: 0.5rem; color: #f5f5f5;">Message</label>
      <textarea name="message" rows="5" required style="width: 100%; padding: 0.75rem; border: 1px solid #7c2d12; border-radius: 4px; background: #2a1f15; color: #f5f5f5; outline: none; resize: vertical;"></textarea>
    </div>
    
    <button type="submit" style="background-color: #7c2d12; color: white; padding: 0.75rem 1.5rem; border: none; border-radius: 4px; cursor: pointer; font-weight: bold; align-self: flex-start; transition: background 0.2s;" onmouseover="this.style.backgroundColor='#9a3412'" onmouseout="this.style.backgroundColor='#7c2d12'">
      Send Message
    </button>
  </form>
</div>
