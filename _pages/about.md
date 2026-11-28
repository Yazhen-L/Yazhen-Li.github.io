---
layout: about
title: Home
permalink: /
subtitle: ""

profile:
  align: left
  image: prof_pic.jpg
  image_circular: false
  more_info: >
    <p>New York University</p>
    <p>College of Arts and Science</p>
    <p>New York, NY</p>

selected_papers: false
social: true

announcements:
  enabled: false
  scrollable: true
  limit: 5

latest_posts:
  enabled: false
  scrollable: true
  limit: 3
---

<style>

/* Widen only the Home page */
body:has(.profile) .container {
  max-width: 1200px !important;
}

/* Keep the profile image at exactly 300px */
body:has(.profile) .profile,
body:has(.profile) .profile.float-left {
  width: 300px !important;
  min-width: 300px !important;
  max-width: 300px !important;
  flex: 0 0 300px !important;
}

body:has(.profile) .profile img,
body:has(.profile) .profile.float-left img {
  width: 300px !important;
  max-width: 300px !important;
  height: auto !important;
}
  
.contact-section {
  display: block;
  clear: none !important;
  margin-left: 360px;
  width: calc(100% - 360px);
  margin-top: 2rem;
}

  /* Keep the name visible on the Home page */
body .navbar-brand {
  display: inline-block !important;
  visibility: visible !important;
  opacity: 1 !important;
  font-family: "Times New Roman", Times, serif !important;
}

  body:has(.profile) .navbar .container::before {
  content: "Yazhen Li";
  display: inline-block;
  margin-right: auto;
  font-family: "Times New Roman", Times, serif !important;
  font-size: 1.4rem;
}
  
.post-header {
  display: none;
}

.profile.float-left {
  margin-right: 200px !important;
}

.profile .more-info {
  font-family: "Times New Roman", Times, serif !important;
  font-size: 1rem !important;
}

body,
body .post,
body .post p,
body .post li,
body .post h1,
body .post h2,
body .post h3,
body .post h4,
body .post h5,
body .post h6,
body .post .clearfix,
body .post .more-info {
  font-family: "Times New Roman", Times, serif !important;
}

body .post {
  font-size: 18px !important;
}

.home-name {
  margin-top: 0 !important;
  padding-top: 100px;
  font-family: "Times New Roman", Times, serif !important;
  font-size: 2rem;
}

.home-subtitle {
  font-family: "Times New Roman", Times, serif !important;
  font-size: 1.15rem;
  margin-bottom: 1.5rem;
}

.contact-divider {
  margin: 2.5rem 0 1.5rem;
}

@media (max-width: 768px) {
  .profile.float-left {
    float: none !important;
    margin-right: 0 !important;
  }
}
</style>

<h1 class="home-name">Yazhen Li</h1>

<p>
I am an undergraduate student at New York University CAS studying Computer Science and Data Science.
</p>

<p>
My research interests lie at the intersection of reliable language models, adaptive AI systems, AI-assisted research, and data-driven modeling of complex real-world risks.
</p>

<p>
I am currently working on research on ambiguity clarification in large language models and climate–energy risk modeling using temperature and electricity-market data.
</p>

<div class="contact-section">
  <hr class="contact-divider">

  <h2>Contact</h2>

  <p>Email:</p>
</div>
