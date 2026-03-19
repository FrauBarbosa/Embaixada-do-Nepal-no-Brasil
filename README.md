<!DOCTYPE html>

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Embassy of Nepal in Brazil</title>

<style>
body {
  margin: 0;
  font-family: "Segoe UI", Arial, sans-serif;
  background: #f4f6f8;
  color: #222;
}

/* HEADER */
header {
  background: linear-gradient(90deg, #b22222, #8b0000);
  color: white;
  padding: 20px;
  display: flex;
  align-items: center;
  gap: 15px;
}

header img {
  width: 60px;
}

header h1 {
  margin: 0;
  font-size: 22px;
}

/* NAV */
nav {
  background: #003893;
  padding: 12px;
  text-align: center;
  position: sticky;
  top: 0;
}

nav a {
  color: white;
  margin: 0 15px;
  text-decoration: none;
  font-weight: 500;
}

/* HERO */
.hero {
  background: url('https://upload.wikimedia.org/wikipedia/commons/1/12/Mount_Everest_as_seen_from_Drukair2_PLW_edit.jpg') center/cover;
  color: white;
  padding: 100px 20px;
  text-align: center;
}

.hero h2 {
  font-size: 36px;
  margin-bottom: 10px;
}

/* CONTAINER */
.section {
  max-width: 1100px;
  margin: auto;
  padding: 40px 20px;
}

/* CARDS */
.card {
  background: white;
  padding: 25px;
  margin-bottom: 25px;
  border-radius: 15px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.08);
}

/* GRID */
.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}

/* NEWS CARD */
.news-card {
  background: #fff;
  padding: 20px;
  border-radius: 12px;
  transition: 0.2s;
}

.news-card:hover {
  transform: translateY(-5px);
}

/* BUTTON */
.btn {
  display: inline-block;
  padding: 10px 15px;
  background: #003893;
  color: white;
  text-decoration: none;
  border-radius: 6px;
  margin-top: 10px;
}

/* FOOTER */
footer {
  background: #111;
  color: white;
  padding: 20px;
  text-align: center;
}
</style>

</head>

<body>

<header>
  <img src="https://media.tenor.com/7cX2K7kQzJIAAAAd/nepal-flag.gif">
  <h1>Embassy of Nepal in Brazil</h1>
</header>

<nav>
  <a href="#services">Services</a>
  <a href="#mission">Mission</a>
  <a href="#news">News</a>
  <a href="#contact">Contact</a>
</nav>

<section class="hero">
  <h2>Welcome to the Embassy of Nepal</h2>
  <p>Promoting Nepal–Brazil relations</p>
</section>

<div class="section">

  <div class="card" id="services">
    <h2>Consular Services</h2>
    <div class="grid">
      <div class="news-card">
        <h3>Visa</h3>
        <p>Apply for travel authorization.</p>
      </div>
      <div class="news-card">
        <h3>Passport</h3>
        <p>Support for Nepali citizens.</p>
      </div>
      <div class="news-card">
        <h3>Authentication</h3>
        <p>Legal document services.</p>
      </div>
    </div>
  </div>

  <div class="card" id="mission">
    <h2>Diplomatic Mission</h2>
    <p>The Embassy promotes cooperation, diplomacy, and cultural exchange between Nepal and Brazil.</p>
  </div>

  <div class="card" id="news">
    <h2>Latest News</h2>
    <div class="grid">
      <div class="news-card">
        <h3>Embassy Event</h3>
        <p>Cultural event in Brasília.</p>
      </div>
      <div class="news-card">
        <h3>Meeting</h3>
        <p>Diplomatic meeting with Brazilian officials.</p>
      </div>
      <div class="news-card">
        <h3>Notice</h3>
        <p>Updates on consular services.</p>
      </div>
    </div>
  </div>

  <div class="card" id="contact">
    <h2>Contact</h2>
    <p><strong>Ambassador:</strong> Nirmal Raj Kafle</p>
    <p>Email: info@nepalembassy.gov.np</p>
    <p>Brasília, Brazil</p>
  </div>

</div>

<footer>
  <p>© 2026 Embassy of Nepal in Brazil</p>
</footer>

</body>
</html>
