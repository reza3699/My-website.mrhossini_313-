<!DOCTYPE html>
<html lang="fa">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>| آگاهی و فضاهایmr_hossini313_369
کیهانی</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header class="header">
    <div class="logo">لیلا</div>
    <nav class="nav">
      <button class="nav-toggle" id="navToggle">☰</button>
      <ul class="nav-links" id="navLinks">
        <li><a href="#home">خانه</a></li>
        <li><a href="#about">درباره من</a></li>
        <li><a href="#projects">پروژه‌ها</a></li>
        <li><a href="#contact">ارتباط</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="home" class="hero">
      <div class="hero-content">
        <h1>آگاهی در مدار کیهان</h1>
        <p>
          اینجا جاییه که صدا، کلمات و فضاهای دیجیتال با هم ترکیب می‌شن؛
          از پادکست آگاهی تا بات‌های شخصی و سرورهای دیسکورد.
        </p>
        <a href="#projects" class="btn">دیدن پروژه‌ها</a>
      </div>
    </section>

    <section id="about" class="section">
      <h2>درباره من</h2>
      <p>
        من رضا هستم، اما اینجا می‌تونی من رو لیلا صدا بزنی؛
        عاشق فضاهای کیهانی، مدیتیشن صبحگاهی، ساخت بات‌های شخصی
        و خلق محتواهایی که آگاهی رو یه ذره بیشتر می‌کنن.
      </p>
    </section>

    <section id="projects" class="section">
      <h2>پروژه‌ها</h2>
      <div class="cards">
        <article class="card">
          <h3>پادکست آگاهی</h3>
          <p>اپیزودهایی درباره خودشناسی، کیهان، و تجربه‌های انسانی.</p>
          <a href="#" class="card-link">لینک پادکست</a>
        </article>
        <article class="card">
          <h3>بات مهتاب</h3>
          <p>یک بات شخصی با فضای خیال‌انگیز و گفت‌وگوهای نمادین.</p>
          <a href="#" class="card-link">لینک بات</a>
        </article>
        <article class="card">
          <h3>کانال تلگرام آگاهی</h3>
          <p>متن‌ها و پست‌هایی برای لمسِ آرامش و آگاهی روزمره.</p>
          <a href="#" class="card-link">لینک کانال</a>
        </article>
      </div>
    </section>

    <section id="contact" class="section">
      <h2>ارتباط</h2>
      <p>اگه دوست داشتی در مورد همکاری، ایده‌ها یا پروژه‌ها گپ بزنیم:</p>
      <ul class="contact-list">
        <li><strong>ایمیل:</strong> your-email@example.com</li>
        <li><strong>دیسکورد:</strong> Reza313_369</li>
        <li><strong>تلگرام:</strong> کانال «آگاهی»</li>
      </ul>
    </section>
  </main>

  <footer class="footer">
    <p>© 2026 لیلا – مدار آگاهی و کیهان</p>
  </footer>

  <script src="script.js"></script>
</body>
</html># My-website.mrhossini_313-@import url("https://fonts.googleapis.com/css2?family=Vazirmatn:wght@300;500;700&display=swap");

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  direction: rtl;
  font-family: "Vazirmatn", system-ui, sans-serif;
  background: radial-gradient(circle at top, #1f2a3b, #050814);
  color: #f5f5f5;
}

/* Header */
.header {
  position: sticky;
  top: 0;
  z-index: 10;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0.8rem 1.5rem;
  background: rgba(5, 8, 20, 0.9);
  backdrop-filter: blur(10px);
}

.logo {
  font-weight: 700;
  letter-spacing: 0.1em;
}

.nav {
  display: flex;
  align-items: center;
}

.nav-toggle {
  display: none;
  background: none;
  border: 1px solid #888;
  color: #f5f5f5;
  padding: 0.3rem 0.6rem;
  border-radius: 4px;
  cursor: pointer;
}

.nav-links {
  list-style: none;
  display: flex;
  gap: 1rem;
}

.nav-links a {
  color: #ddd;
  text-decoration: none;
  font-size: 0.9rem;
  transition: color 0.2s, transform 0.2s;
}

.nav-links a:hover {
  color: #fff;
  transform: translateY(-1px);
}

/* Hero */
.hero {
  min-height: 70vh;
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 2rem 1.5rem;
  background: linear-gradient(135deg, #101528, #1b2340);
}

.hero-content {
  max-width: 700px;
  text-align: center;
}

.hero h1 {
  font-size: 2.2rem;
  margin-bottom: 1rem;
}

.hero p {
  font-size: 1rem;
  line-height: 1.8;
  margin-bottom: 1.5rem;
  color: #d0d6e8;
}

.btn {
  display: inline-block;
  padding: 0.7rem 1.4rem;
  border-radius: 999px;
  background: #ff7ac4;
  color: #050814;
  text-decoration: none;
  font-weight: 500;
  box-shadow: 0 0 20px rgba(255, 122, 196, 0.4);
  transition: transform 0.2s, box-shadow 0.2s;
}

.btn:hover {
  transform: translateY(-2px);
  box-shadow: 0 0 30px rgba(255, 122, 196, 0.6);
}

/* Sections */
.section {
  padding: 3rem 1.5rem;
  max-width: 900px;
  margin: 0 auto;
}

.section h2 {
  font-size: 1.6rem;
  margin-bottom: 1rem;
  border-right: 3px solid #ff7ac4;
  padding-right: 0.5rem;
}

.section p {
  line-height: 1.9;
  color: #d0d6e8;
}

/* Cards */
.cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
  gap: 1.5rem;
  margin-top: 1.5rem;
}

.card {
  background: rgba(10, 14, 30, 0.9);
  border-radius: 12px;
  padding: 1.2rem;
  box-shadow: 0 10px 25px rgba(0, 0, 0, 0.4);
  border: 1px solid rgba(255, 255, 255, 0.05);
}

.card h3 {
  margin-bottom: 0.6rem;
}

.card p {
  font-size: 0.9rem;
  color: #c4cbe0;
  margin-bottom: 0.8rem;
}

.card-link {
  font-size: 0.85rem;
  color: #ff7ac4;
  text-decoration: none;
}

/* Contact */
.contact-list {
  list-style: none;
  margin-top: 1rem;
}

.contact-list li {
  margin-bottom: 0.4rem;
}

/* Footer */
.footer {
  text-align: center;
  padding: 1.5rem;
  font-size: 0.8rem;
  color: #a3aac5;
}

/* Responsive */
@media (max-width: 768px) {
  .nav-toggle {
    display: inline-block;
  }

  .nav-links {
    position: absolute;
    top: 3.2rem;
    right: 1.5rem;
    flex-direction: column;
    background: rgba(5, 8, 20, 0.95);
    padding: 0.8rem 1rem;
    border-radius: 8px;
    display: none;
  }

  .nav-links.show {
    display: flex;
  }

  .hero h1 {
    font-size: 1.8rem;
  }
}
const navToggle = document.getElementById("navToggle");
const navLinks = document.getElementById("navLinks");

navToggle.addEventListener("click", () => {
  navLinks.classList.toggle("show");
});

// اسکرول نرم
document.querySelectorAll('a[href^="#"]').forEach((link) => {
  link.addEventListener("click", (e) => {
    const targetId = link.getAttribute("href").substring(1);
    const target = document.getElementById(targetId);
    if (target) {
      e.preventDefault();
      target.scrollIntoView({ behavior: "smooth" });
      navLinks.classList.remove("show");
    }
  });
});
