<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>How an Apple Gets to You</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <!-- Font -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;800&display=swap" rel="stylesheet">

  <style>
    :root {
      --red: #ff595e;
      --orange: #ff924c;
      --yellow: #ffca3a;
      --green: #8ac926;
      --teal: #2ec4b6;
      --blue: #1982c4;
      --purple: #6a4c93;
      --pink: #f15bb5;
      --dark: #1e1e2f;
    }

    * { box-sizing: border-box; }

    body {
      margin: 0;
      font-family: "Poppins", sans-serif;
      background: linear-gradient(135deg, #fdfcdc, #e0fbfc);
      color: var(--dark);
    }

    header {
      background: linear-gradient(135deg, var(--red), var(--orange), var(--pink));
      color: white;
      text-align: center;
      padding: 4.5rem 1rem;
      clip-path: polygon(0 0, 100% 0, 100% 85%, 0 100%);
    }

    header h1 {
      font-size: 3.2rem;
      margin: 0;
      font-weight: 800;
    }

    header p {
      font-size: 1.4rem;
      margin-top: 1rem;
      opacity: 0.95;
    }

    main {
      max-width: 1200px;
      margin: -3.5rem auto 3rem;
      padding: 0 1.5rem;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 1.75rem;
    }

    section {
      background: white;
      border-radius: 22px;
      padding: 1.75rem;
      box-shadow: 0 14px 35px rgba(0,0,0,0.12);
      transition: transform 0.35s ease, box-shadow 0.35s ease;
    }

    section:hover {
      transform: translateY(-10px) scale(1.03);
      box-shadow: 0 22px 50px rgba(0,0,0,0.18);
    }

    section h2 {
      margin-top: 0;
      font-size: 1.25rem;
      font-weight: 700;
    }

    section p {
      font-size: 0.95rem;
      line-height: 1.65;
    }

    .step1  { border-top: 8px solid var(--red); }
    .step2  { border-top: 8px solid var(--orange); }
    .step3  { border-top: 8px solid var(--yellow); }
    .step4  { border-top: 8px solid var(--pink); }
    .step5  { border-top: 8px solid var(--purple); }
    .step6  { border-top: 8px solid var(--green); }
    .step7  { border-top: 8px solid var(--teal); }
    .step8  { border-top: 8px solid var(--blue); }
    .step9  { border-top: 8px solid var(--red); }
    .step10 { border-top: 8px solid var(--orange); }
    .step11 { border-top: 8px solid var(--yellow); }
    .step12 { border-top: 8px solid var(--green); }
    .step13 { border-top: 8px solid var(--purple); }
    .step14 { border-top: 8px solid var(--pink); }
    .step15 { border-top: 8px solid var(--blue); }
    .step16 { border-top: 8px solid var(--orange); }
    .step17 { border-top: 8px solid var(--green); }

    footer {
      background: linear-gradient(135deg, var(--dark), #2b2b44);
      color: white;
      text-align: center;
      padding: 3.5rem 1rem;
    }

    footer h3 {
      margin-top: 0;
      font-weight: 600;
      font-size: 1.4rem;
    }

    footer ul {
      list-style: none;
      padding: 0;
      margin: 1.25rem 0;
    }

    footer li {
      margin: 0.6rem 0;
    }

    footer a {
      color: #ffd166;
      text-decoration: none;
      font-weight: 500;
    }

    footer a:hover {
      text-decoration: underline;
    }

    footer p {
      font-size: 0.85rem;
      opacity: 0.7;
    }
  </style>
</head>
<body>

<header>
  <h1>How an Apple Gets to You</h1>
  <p>The journey from orchard to table</p>
</header>

<main>
  <section class="step1"><h2>1. Choosing the Orchard Site</h2><p>Farmers select land with healthy soil, good drainage, sufficient sunlight, and cold winters.</p></section>
  <section class="step2"><h2>2. Planting Saplings</h2><p>Young apple trees are planted in rows with space for growth and airflow.</p></section>
  <section class="step3"><h2>3. Caring for the Trees</h2><p>Trees are watered, fertilized, pruned, and protected from pests and disease.</p></section>
  <section class="step4"><h2>4. Blossoming</h2><p>In spring, apple trees produce blossoms that allow fruit to develop.</p></section>
  <section class="step5"><h2>5. Pollination</h2><p>Bees transfer pollen between flowers, enabling apples to form.</p></section>
  <section class="step6"><h2>6. Apples Begin to Grow</h2><p>Small apples develop where blossoms once grew.</p></section>
  <section class="step7"><h2>7. Thinning the Fruit</h2><p>Extra apples are removed to improve size and quality.</p></section>
  <section class="step8"><h2>8. Ripening</h2><p>Apples grow, change color, and increase in sweetness.</p></section>
  <section class="step9"><h2>9. Harvesting</h2><p>Ripe apples are carefully picked to avoid damage.</p></section>
  <section class="step10"><h2>10. Transport to Packing House</h2><p>Apples are moved from orchards to packing facilities.</p></section>
  <section class="step11"><h2>11. Washing and Cleaning</h2><p>Apples are washed to remove dirt and debris.</p></section>
  <section class="step12"><h2>12. Sorting and Inspecting</h2><p>Apples are sorted by size and quality.</p></section>
  <section class="step13"><h2>13. Cold Storage</h2><p>Cold storage slows ripening and preserves freshness.</p></section>
  <section class="step14"><h2>14. Packaging and Labeling</h2><p>Apples are packaged and labeled for sale.</p></section>
  <section class="step15"><h2>15. Shipping to Stores</h2><p>Apples are transported to grocery stores.</p></section>
  <section class="step16"><h2>16. Buying the Apples</h2><p>Customers purchase apples at stores.</p></section>
  <section class="step17"><h2>17. Washing and Eating</h2><p>Apples are washed at home and eaten.</p></section>
</main>

<footer>
  <h3>Sources</h3>
  <ul>
    <li>
      <a href="https://www.britannica.com/topic/fruit-farming/Harvesting-and-packing" target="_blank" rel="noopener">
        Encyclopaedia Britannica – Fruit Farming
      </a>
    </li>
    <li>
      <a href="https://usapple.org/news-resources/apple-stages-from-the-tree-to-the-grocery-store" target="_blank" rel="noopener">
        U.S. Apple Association – Apple Stages
      </a>
    </li>
    <li>
      <a href="https://teara.govt.nz/en/apples-and-pears/page-6" target="_blank" rel="noopener">
        Te Ara Encyclopedia of New Zealand – Apples and Pears
      </a>
    </li>
  </ul>
  <p>Educational webpage</p>
</footer>

</body>
</html>
