---
layout: page
title: Welcome to Yutong's tiny kitchen.
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
    overflow-x: auto;
    scroll-snap-type: x mandatory;
  }

  .dish-images img {
    width: 100%;
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
      <img src="/assets/kitchen_img/valentine1.jpg" alt="Dish 1 - image 1">
      <img src="/assets/kitchen_img/valentine2.jpg" alt="Dish 2 - image 1">
    </div>
    <div class="dish-description">
      <h2>Valentine's Day Bread</h2>
      <p>The rosy dough was made from dragon fruit. </p>
    </div>
  </div>


  </main>

</body>
</html>
