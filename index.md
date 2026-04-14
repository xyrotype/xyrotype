---
layout: default
title: "xyrotype | Home"
---

<section class="about-section">
  <img src="https://github.com/shadidsorowar.png" class="profile-pic" alt="Profile">
  
  <div class="about-text">
    <h2>Yo, I'm Shadid.</h2>
    <p>Welcome to my digital dump. I write about tech, random rants, and whatever else keeps me up at night.</p>
    
    <div class="social-links">
      <a href="https://github.com/xyrotype" class="social-btn">GitHub</a>
      <a href="https://discord.gg/FrVqEaBCtu" class="social-btn">Discord</a>
      <a href="https://www.instagram.com/xyrotype?igsh=eXJuNWowajR3NzJ6" class="social-btn">Instagram</a>
    </div>
  </div>
</section>

# Recent Dumps

<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}" class="post-link-wrapper">
        <span class="post-title">{{ post.title }}</span>
        <span class="post-date">{{ post.date | date: "%b %d, %Y" }}</span>
      </a>
    </li>
  {% endfor %}
</ul>
