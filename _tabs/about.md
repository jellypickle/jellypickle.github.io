---
# the default layout is 'page'
icon: fas fa-info-circle
order: 2
title: About me
---

> Add your biographical information and background here to tell visitors about yourself.
{: .prompt-tip }

I'm a first-year undergraduate IT student in ADA university, currently interested in cybersecurity and machine learning. I'm also planning to get into electronics and learn how to work with arduino in the future.

I had a huge interest in art since childhood, and I started painting when I was 13. Unfortunately, due to my studies, I stopped painting, but whenever I have free time, I draw some sketches. Here, I would like to show some of my favorite paintings. :D
## My Paintings

<div class="paintings-gallery">
  <div class="painting-card">
    <img src="/assets/img/eternalheritage.jpg" alt="Eternal Heritage" class="painting-image" />
    <div class="painting-description">
      <h4>Eternal Heritage</h4>
      <p>This is my latest painting, and my most favorite work! At that time, I was preparing for an exhibition and exams at the same time, so it was a very exhausting process. Even though I hated it at first, as time passed, I slowly started to like it. My favorite part of the painting is the jewellery set. </p>
    </div>
  </div>

  <div class="painting-card">
    <img src="/assets/img/flowersbythesunset.jpg" alt="Flowers by the sunset" class="painting-image" />
    <div class="painting-description">
      <h4>Flowers by the sunset</h4>
      <p>I painted this because my mom showed me a reference of a photograph and seemed to really enjoy it, so I decided to paint it as a birthday gift as she loves floral pictures.</p>
    </div>
  </div>

  <div class="painting-card">
    <img src="/assets/img/pinkpetals.jpg" alt="Pink Petals" class="painting-image" />
    <div class="painting-description">
      <h4>Pink Petals</h4>
      <p>This is one of my favorite paintings after "Eternal Heritage". I specifically like the brush stroke techniques I used in this painting because it looks textured, and if you try to feel it with your hands, it feels bumpy, which is a characteristic that I like: it feels like the painting is three-dimensional. </p>
    </div>
  </div>

  <div class="painting-card">
    <img src="/assets/img/teatime.jpg" alt="Tea Time" class="painting-image" />
    <div class="painting-description">
      <h4>Tea Time</h4>
      <p> This was my second work in the beginning of my painting journey. The parts I enjoyed working on the most were the trees in the background and the pie. Sometimes this painting reminds me of spending summer break in Gakh.</p>
    </div>
  </div>
</div>

<style>
  .paintings-gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
    margin: 2rem 0;
  }

  .painting-card {
    border-radius: 8px;
    overflow: hidden;
    background: var(--card-bg);
    border: 1px solid var(--border-color);
    transition: all 0.3s ease;
    display: flex;
    flex-direction: column;
  }

  .painting-card:hover {
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
    transform: translateY(-4px);
  }

  .painting-image {
    width: 100%;
    height: 300px;
    object-fit: cover;
    display: block;
  }

  .painting-description {
    padding: 1.5rem;
    flex: 1;
    display: flex;
    flex-direction: column;
  }

  .painting-description h4 {
    margin: 0 0 0.5rem 0;
    font-size: 1.1rem;
    font-weight: 600;
  }

  .painting-description p {
    margin: 0;
    font-size: 0.9rem;
    line-height: 1.5;
    color: var(--text-secondary);
  }

  /* Fallback colors for light/dark mode */
  :root {
    --card-bg: #fff;
    --border-color: #e0e0e0;
    --text-secondary: #666;
  }

  html[data-mode="dark"] {
    --card-bg: #262d33;
    --border-color: #3a4048;
    --text-secondary: #999;
  }
</style>