---
layout: post
title: About
permalink: /about/
comments: true
---

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>About Me</title>
<style>
  body {
    background-color: #ffb6c1; /* light pink */
    color: white;
    font-family: Arial, sans-serif;
    margin: 20px;
  }

  a {
    color: #fffacd; /* soft yellow links */
  }

  .about-me p {
    margin: 5px 0;
  }

  .family-row {
    display: flex;
    justify-content: center;
    gap: 40px;
    margin-top: 20px;
    flex-wrap: wrap; /* makes it responsive */
  }

  .family-row div {
    text-align: center;
  }

  .family-row img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    object-fit: cover;
    border: 4px solid white;
    transition: transform 0.3s; /* smooth hover effect */
  }

  .family-row img:hover {
    transform: scale(1.1); /* grow slightly on hover */
  }
</style>
</head>
<body>

<h1>About Me</h1>
<p>Hi, I'm Angie!</p>

<h3>My Background</h3>
<p>I am <strong>Russian</strong> but I was born in <strong>America</strong></p>
<img src="https://upload.wikimedia.org/wikipedia/en/f/f3/Flag_of_Russia.svg" alt="Russian flag" width="150" height="150">
<img src="https://upload.wikimedia.org/wikipedia/en/a/a4/Flag_of_the_United_states.svg" alt="American flag" width="150" height="150">

<hr>

<h2>My Travels</h2>
<div class="about-me">
   <p><strong>I traveled to Italy 🇮🇹</strong></p>
   <p><strong>I traveled to France 🇫🇷</strong></p>
   <p><strong>I traveled to Russia 🇷🇺</strong></p>
   <p><strong>I traveled to Finland 🇫🇮</strong></p>
   <p><strong>I traveled to Japan 🇯🇵</strong></p>
</div>

<h2>My Family</h2>
<p>I live with a family of 4. Here are some pictures of my family:</p>
<div class="family-row">
  <div>
    <img src="https://drive.google.com/uc?export=view&id=1-dtCd5oT8hAwUuCqDV0oKwE09DWvEIUx" alt="Me and my mom"/>
    <p><strong>Me and my mom, Leyla</strong></p>
  </div>
  <div>
    <img src="https://drive.google.com/uc?export=view&id=1-b4wJITB71ebceCPDgYNMfgoA-ZbVX-" alt="Me and my brother"/>
    <p><strong>Me and my brother, Mark</strong></p>
  </div>
</div>

<h2>Me</h2>
<div class="about-me">
   <p><strong>Age:</strong> 14</p>
   <p><strong>Birthday:</strong> Dec 6th</p>
   <p><strong>Favorite color:</strong> pink</p>
</div>

<h2>Interests</h2>
<div class="about-me">
   <p><strong>I love to draw</strong></p>
   <p><strong>I love to read</strong></p>
   <p><strong>I love Asian food</strong></p>
   <p><strong>I am a cat person</strong></p>
</div>

</body>
</html>
