# dummy-gtm-site
Test site for Google Tag Manager
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Dummy Blog</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  /* General Styles */
body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  margin: 0;
  padding: 0;
  background-color: #f4f4f4;
  color: #333;
}

/* Header */
header {
  background-color: #0077cc;
  color: white;
  padding: 20px;
  text-align: center;
}

/* Main Content */
main {
  max-width: 800px;
  margin: 20px auto;
  padding: 0 15px;
}

/* Blog Post */
.post {
  background: white;
  padding: 20px;
  margin-bottom: 20px;
  border-radius: 8px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.post h2 {
  color: #0077cc;
}

.post .date {
  font-size: 0.9em;
  color: #888;
}

/* Footer */
footer {
  text-align: center;
  padding: 20px;
  background: #222;
  color: white;
}

  <header>
    <h1>My Dummy Blog</h1>
    <p>A simple blog to test layout, styling, and GTM</p>
  </header>

  <main>
    <article class="post">
      <h2>First Blog Post</h2>
      <p class="date">June 20, 2025</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam lacinia, purus non facilisis malesuada, justo lorem ultrices ligula, at fermentum magna arcu at sapien.</p>
    </article>

    <article class="post">
      <h2>Second Blog Post</h2>
      <p class="date">June 18, 2025</p>
      <p>Aliquam erat volutpat. Suspendisse potenti. Cras volutpat, sapien a rhoncus fermentum, enim nisi dapibus purus, nec facilisis turpis nunc eget massa.</p>
    </article>
  </main>

  <footer>
    <p>&copy; 2025 My Dummy Blog</p>
  </footer>
</body>
</html>
