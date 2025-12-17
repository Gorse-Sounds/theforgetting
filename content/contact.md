---
title: "Contact"
url: "/contact/"
layout: "single"
---

Thoughts on an article? Questions? Other feedback?

<button id="reveal-email" style="
  background: #333;
  color: #fff;
  border: none;
  padding: 10px 20px;
  border-radius: 4px;
  cursor: pointer;
  font-size: 16px;
  margin: 20px 0;
">
  Click to reveal email
</button>

<div id="email-container" style="display: none; margin-top: 20px;">
  <a id="email-link" href="" style="font-size: 18px;"></a>
</div>

<script>
document.getElementById('reveal-email').addEventListener('click', function() {
  // Obfuscated email - decode on click
  const user = 'contact';
  const domain = 'theforgetting.org';
  const email = user + '@' + domain;

  const container = document.getElementById('email-container');
  const link = document.getElementById('email-link');
  const button = document.getElementById('reveal-email');

  link.href = 'mailto:' + email;
  link.textContent = email;

  container.style.display = 'block';
  button.style.display = 'none';
});
</script>
