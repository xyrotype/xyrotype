---
layout: default
title: "xyrotype | Home"
---

<section class="about-section">
  <img src="https://github.com/xyrotype.png" class="profile-pic" alt="Profile">
  
  <div class="about-text">
    <h2>It's me, xyrotype</h2>

<p>Alternate Aliases: Lightz, Shad</p>
<p>Years active: Mar 2021 - Nov 2025</p>
<p>I began my journey as a Discord administrator, managing several well-known servers and building strong online communities. Over time, I expanded my presence into content creation as a music-focused YouTuber under the name “Lightz,” where I produced music visualizers and edited content, reaching over 650,000 views and 3,100+ subscribers.</p>
<p>I am a 19-year-old college graduate from Bangladesh with a strong interest in music, gaming, and digital communities. In June 2021, I founded my first Discord server, “Shadid’s Café,” which reached peak engagement between 2022 and 2023 and became the foundation of my online recognition.</p>
<p>Following this, I transitioned into esports by forming a team called “R4GEST0RM,” where I am also known as “xyrotype.” Alongside this, I continue to manage and lead multiple group communities.</p>
<p>Currently, I am on a temporary break from my online activities to focus on my 12th national board examinations and university admission preparations, with plans to resume and further expand my work in content creation and community building.</p>
    
    <div class="social-links">
      <a href="https://youtube.com/@Xyrotype" class="social-btn">YouTube</a>
      <a href="https://discord.gg/FrVqEaBCtu" class="social-btn">Discord</a>
      <a href="https://www.instagram.com/xyrotype?igsh=eXJuNWowajR3NzJ6" class="social-btn">Instagram</a>
      <a href="https://x.com/Xyrotype" class="social-btn">X</a>
      <a href="https://github.com/xyrotype" class="social-btn">Github</a>
      <a href="https://steamcommunity.com/id/TheLightz/" class="social-btn">Steam</a>
       <a href="mailto:xyrotype@gmail.com?subject=Hi%20there!%20&body=I%20wanna%20react%20out%20to%20you%20personally%20about%20the%20following%20reason%3A" class="social-btn">E-mail</a>
    </div>
  </div>
</section>

<div class="embed-grid">
   <iframe data-testid="embed-iframe" style="border-radius:12px" src="https://open.spotify.com/embed/playlist/7xSSloL88IlBSkIxlYoFZc?utm_source=generator" width="100%" height="352" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>

  <iframe src="https://discord.com/widget?id=1048595712868372531&theme=dark" width="100%" height="352" allowtransparency="true" frameborder="0" sandbox="allow-popups allow-popups-to-escape-sandbox allow-same-origin allow-scripts"></iframe>

<h2 class="section-title">Recent Dumps</h2>

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
