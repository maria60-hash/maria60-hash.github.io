<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1"> 
  <title>Hawaiian Brunch</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Hawaiian Brunch</h1>
    <p>Simple, tasty island recipes you can make at home.</p>
  </header>
  <nav>
    <ul>
      <li><a href="index.html">Home</a></li>
      <li><a href="#">Recipes</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </nav>

  <main>

    <!-- IMAGE (Ch. 2: images) -->
    <figure>
      <img src= <img width="500" height="750" alt="image" src="https://github.com/user-attachments/assets/bde4f335-c932-4ca5-b161-b7e4f60cbb9f" />
" alt="A colorful Hawaiian brunch spread">
      <figcaption>Welcome to the islands—breakfast style!</figcaption>
    </figure>

    <section>
      <h2>What You’ll Find</h2>
      <p>This site shares easy brunch ideas with local flavors. Start simple, learn a few techniques, and enjoy fresh, happy food.</p>
      <ul>
        <li>Beginner-friendly instructions</li>
        <li>Short ingredient lists</li>
        <li>Quick tips for better flavor</li>
      </ul>
    </section>

    <section>
      <h2>Featured Recipe: Pineapple Fried Rice</h2>
      <p>A sweet and savory favorite—great for brunch!</p>

      <h3>Ingredients</h3>
      <ul>
        <li>3 cups day-old cooked rice</li>
        <li>1 cup pineapple chunks</li>
        <li>1/2 cup peas and carrots</li>
        <li>2 eggs</li>
        <li>2 tbsp shoyu (soy sauce)</li>
        <li>You can also add chicken or shrimp to your preference</li>
      </ul>

      <h3>Steps</h3>
      <ol>
        <li>Scramble eggs in a pan and set aside.</li>
        <li>Stir-fry rice; add veggies and pineapple.</li>
        <li>Stir in shoyu and fold in eggs. Serve hot.</li>
      </ol>

      <h3>Quick Facts</h3>
      <table>
        <tr>
          <th>Prep Time</th>
          <th>Cook Time</th>
          <th>Servings</th>
        </tr>
        <tr>
          <td>10 min</td>
          <td>10 min</td>
          <td>3</td>
        </tr>
      </table>
    </section>

    <section>
      <h2>Quick Video Tip</h2>
      <p>Watch a short cooking tip video:</p>
      <div class="video">
        <iframe 
          src="https://www.youtube.com/watch?v=KTegZ6XARzU" 
          title="Cooking tip video"
          allowfullscreen>
        </iframe>
      </div>
    </section>

  </main>

  <footer>
    <p>© 2025 Hawaiian Brunch</p>
    <p><a href="#top">Back to top</a></p>
  </footer>

</body>
</html>

html, body {
  margin: 0;
  padding: 0;
  font-family: Arial, Helvetica, sans-serif;
}
img { max-width: 100%; height: auto; }

header, nav, main, footer {
  max-width: 1000px;
  margin: 0 auto;
  padding: 12px;
}

header {
  background: #f0f8ff;
  text-align: center;
}
header h1 {
  margin-bottom: 6px;
}

nav ul {
  list-style: none;
  margin: 0;
  padding: 0;
}
nav li { 
  display: inline-block; 
  margin-right: 12px; 
}
nav a {
  text-decoration: none;
  color: #004b57;
}
nav a:hover {
  text-decoration: underline;
}

section {
  margin: 18px 0;
}
figure {
  margin: 0;
  text-align: center;
}
figcaption {
  font-size: 0.9rem;
  color: #555;
  margin-top: 6px;
}

ul, ol {
  padding-left: 18px;
}
table {
  width: 100%;
  border-collapse: collapse;
  margin-top: 8px;
}
th, td {
  border: 1px solid #ccc;
  padding: 8px;
  text-align: left;
}
th {
  background: #f5f5f5;
}

.video {
  position: relative;
  padding-bottom: 56.25%;
  height: 0;
  overflow: hidden;
  background: #000;
}
.video iframe {
  position: absolute;
  top: 0; left: 0; width: 100%; height: 100%;
  border: 0;
}

footer {
  background: #f0f8ff;
  text-align: center;
  margin-top: 24px;
}

@media (min-width: 700px) {
  header p { font-size: 1.1rem; }
}

