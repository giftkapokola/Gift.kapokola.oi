<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Site</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- Menu Section -->
  <nav class="navbar">
    <div class="logo">MySite</div>
    <ul class="menu">
      <li><a href="#">Home</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Services</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </nav>

  <!-- Main content -->
  <main>
    <h1>Welcome to My Website</h1>
    <p>This is a sample site with a navigation menu.</p>
  </main>

</body>
</html>
body {
  margin: 0;
  font-family: sans-serif;
}

.navbar {
  background-color: #333;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem;
}

.logo {
  color: white;
  font-size: 1.5rem;
  font-weight: bold;
}

.menu {
  list-style: none;
  display: flex;
  gap: 20px;
  margin: 0;
  padding: 0;
}

.menu li a {
  color: white;
  text-decoration: none;
  font-size: 1rem;
}

.menu li a:hover {
  text-decoration: underline;
}
