---
layout: page
title: Welcome to my tiny kitchen.
---


<style>
  :root {
    --bg-color: #fff7f9;
    --card-bg: #fff;
    --accent: #f4c2c2;
    --font: 'Segoe UI', sans-serif;
    --text-color: #4a4a4a;
  }
  body {
    margin: 0;
    background-color: var(--bg-color);
    font-family: var(--font);
    color: var(--text-color);
  }
  header {
    text-align: center;
    padding: 2rem 1rem;
    background-color: var(--card-bg);
    box-shadow: 0 2px 5px rgba(0,0,0,0.05);
  }
  h1 {
    margin: 0;
    font-size: 2.5rem;
    color: #d2649a;
  }
  p.subtitle {
    font-size: 1.2rem;
    color: #888;
    margin-top: 0.5rem;
  }
  .gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 1.5rem;
    padding: 2rem;
    max-width: 1200px;
    margin: 0 auto;
  }
  .dish-card {
    background-color: var(--card-bg);
    border-radius: 16px;
    overflow: hidden;
    box-shadow: 0 4px 12px rgba(0,0,0,0.06);
    display: flex;
    flex-direction: column;
    transition: transform 0.2s ease;
  }

  .dish-card:hover {
    transform: translateY(-4px);
  }

  .dish-images {
    display: flex;
    flex-wrap: wrap;
    overflow-x: visible;
  }

  .dish-images img {
    width: 100%;
    height: auto;
    object-fit: cover;
    flex-shrink: 0;
    scroll-snap-align: start;
    border-bottom: 1px solid #eee;
  }

  .dish-images .imghalf {
    width: 50%;
    height: auto;
    object-fit: cover;
    flex-shrink: 0;
    scroll-snap-align: start;
    border-bottom: 1px solid #eee;
  }


  .dish-description {
    padding: 1rem 1.2rem;
  }

  .dish-description h2 {
    margin: 0 0 0.5rem;
    font-size: 1.3rem;
    color: #d2649a;
  }

  .dish-description p {
    margin: 0;
    font-size: 1rem;
    line-height: 1.5;
  }

  @media (max-width: 600px) {
    h1 {
      font-size: 2rem;
    }

    .dish-description h2 {
      font-size: 1.1rem;
    }
  }
</style>

<body>

  <main class="gallery">


  <div class="dish-card">
    <div class="dish-images">
<!--       <img class="imghalf" src="/assets/kitchen_img/valentine1.jpg" alt="Valentine's Day Bread - image 1">
      <img class="imghalf" src="/assets/kitchen_img/valentine2.jpg" alt="Valentine's Day Bread - image 2"> -->
      <img  src="/assets/kitchen_img/valentine1.jpg" alt="Valentine's Day Bread - image 1">
      <img  src="/assets/kitchen_img/valentine2.jpg" alt="Valentine's Day Bread - image 2">
    </div>
    <div class="dish-description">
      <h2>Valentine's day bread</h2>
      <p>The rosy dough was made from dragon fruit. </p>
    </div>
  </div>

  <div class="dish-card">
  <div class="dish-images">
      <img  src="/assets/kitchen_img/kale1.jpg" alt="kale - image 1">
      <img  src="/assets/kitchen_img/kale2.jpg" alt="kale - image 2">
  </div>
  <div class="dish-description">
    <h2>Kale Scrambled Egg.</h2>
    <p>Make kale juicy again. Don’t forget to drizzle some lemon-infused olive oil ~ </p>
    <p>Recipe from <a href="https://www.youtube.com/watch?v=aBdFe9rqoU8">曼食慢语 Amanda Tastes</a> </p>
  </div>
  </div>
  
  <div class="dish-card">
    <div class="dish-images">
      <img class="img" src="/assets/kitchen_img/tuotuomo.jpg" alt="tuotuomo - image 1">
    </div>
    <div class="dish-description">
      <h2>Pork Tuotuomo, Rucolas Salat mit Birnen und Ricotta</h2>
      <p>A fusion of Chinese and Swiss flavors. </p>
      <p>The tuotuomo was made from scratch following <a href="https://www.youtube.com/watch?v=fS7yzGb8q3g" target="_blank">小高姐的Magic Ingredients</a> </p>
      <p>The Rucolas Salat was inspired by a recipe from <a href="https://fooby.ch/de/rezepte/27196/rucola-salat-mit-birnen-und-ricotta">FOOBY.</a> </p>
    </div>
  </div>

  <div class="dish-card">
    <div class="dish-images">
      <img class="imghalf" src="/assets/kitchen_img/quiche1.jpg" alt="Quiche - image 1">
      <img class="imghalf" src="/assets/kitchen_img/quiche2.jpg" alt="Quiche - image 2">
    </div>
    <div class="dish-description">
      <h2>Zucchini and Mozzarella Quiche</h2>
      <p>My first home-cooked Quiche. My Italian colleagues gave it a thumbs up. </p>
    </div>
  </div>

  <div class="dish-card">
    <div class="dish-images">
      <img class="img" src="/assets/kitchen_img/teriyakisalmon.jpg" alt="salmon - image 1">
    </div>
    <div class="dish-description">
      <h2>Chinese-style Teriyaki Salmon Rice Bowl.</h2>
      <p>Another great idea to cook Salmon!</p>
      <p>Recipe from <a href="https://www.bilibili.com/video/BV1nJ411y7iT/?spm_id_from=333.999.0.0">喃猫小厨房.</a> </p>
    </div>
  </div>


  <div class="dish-card">
    <div class="dish-images">
      <img class="img" src="/assets/kitchen_img/morelrisotto.jpg" alt="morel - image 1">
    </div>
    <div class="dish-description">
      <h2>Chinese-style Morel Risotto.</h2>
      <p>Morel mushrooms from Yunnan, China, seasoned with some cream and soy sauce.</p>
    </div>
  </div>

  

  <div class="dish-card">
    <div class="dish-images">
      <img class="img" src="/assets/kitchen_img/seefood.jpg" alt="seafood - image 1">
    </div>
    <div class="dish-description">
      <h2>Tropical Experience.</h2>
      <p>Eat local seafood and fruits in Sanya, China.</p>
    </div>
  </div>

  <div class="dish-card">
    <div class="dish-images">
      <img class="img" src="/assets/kitchen_img/asparagus.jpg" alt="asparagus - image 1">
    </div>
    <div class="dish-description">
      <h2>The Prelude to Spring</h2>
      <p>Have you had asparagus this season?</p>
    </div>
  </div>


  <div class="dish-card">
    <div class="dish-images">
      <img class="img" src="/assets/kitchen_img/crawfish.jpg" alt="crawfish - image 1">
    </div>
    <div class="dish-description">
      <h2>Chinese-style Crawfish Pasta</h2>
      <p>It’s fun to practice twirling pasta!</p>
    </div>
  </div>


  <div class="dish-card">
    <div class="dish-images">
      <img class="img" src="/assets/kitchen_img/crepecake.jpg" alt="crepecake - image 1">
    </div>
    <div class="dish-description">
      <h2>Mango Crepe Cake</h2>
      <p>Remember to buy more cream next time :) </p>
    </div>
  </div>


  <div class="dish-card">
    <div class="dish-images">
      <img  src="/assets/kitchen_img/toast1.jpg" alt="toast1 - image 1">
      <img  src="/assets/kitchen_img/toast2.jpg" alt="toast2- image 2">
    </div>
    <div class="dish-description">
      <h2>Tangzhong Milk Toast</h2>
      <p><a href="https://en.wikipedia.org/wiki/Tangzhong">Tangzhong (汤种)</a>, originated in Asia, is a technique where a portion of the flour is cooked with water or milk to create a roux, which helps make the bread extra soft and moist.  </p>
      <p>These were the only two times I successfully made wonderfully soft, cloud-like toast.</p>
    </div>
  </div>



  </main>

</body>

