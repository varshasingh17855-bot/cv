<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8"/>
  <meta name="viewport" content="width=device-width, initial-scale=1"/>
  <title>Varsha • Portfolio</title>

  <!-- Bootstrap + Icons -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.css" rel="stylesheet">

  <!-- Inline CSS (single-file) -->
  <style>
    :root{ --brand:#5b7fff; }
    html,body{ scroll-behavior:smooth; }
    body{ background:#f7f8fb; }
    .navbar{ background:#fff !important; }
    .hero-section{ padding-top:7rem; }
    .section-title{ font-weight:800; letter-spacing:.3px; }
    .info-card{ background:#fff; border:1px solid #eceef4; border-radius:16px; }
    .progress{ height:.6rem; background:#e9edf8; }
    .progress-bar{ background:var(--brand); }
    .card{ border:1px solid #eceef4; border-radius:16px; }
    .card-img-top{ border-top-left-radius:16px; border-top-right-radius:16px; }
    .product-card, .project-card .card{ transition:.2s ease; }
    .product-card:hover, .project-card .card:hover{ transform:translateY(-4px); box-shadow:0 10px 28px rgba(0,0,0,.08); }
    .filters .btn{ border-radius:999px; }
    .filters .btn.active{ background:var(--brand); color:#fff; }
    .badge-cat{ background:rgba(91,127,255,.08); color:#2c49d8; }
    footer{ background:#0b1020; color:#cbd3ff; }
    /* remove any accidental thin lines */
    hr, .border-bottom, .border-top{ border:0 !important; height:0 !important; }
    a:focus{ box-shadow:none !important; }
  </style>
</head>
<body data-bs-spy="scroll" data-bs-target="#mainNav" data-bs-offset="80" tabindex="0">

  <!-- NAV -->
  <nav id="mainNav" class="navbar navbar-expand-lg shadow-sm fixed-top">
    <div class="container">
      <a class="navbar-brand fw-bold" href="#home">Varsha</a>
      <button class="navbar-toggler" data-bs-toggle="collapse" data-bs-target="#nav"><span class="navbar-toggler-icon"></span></button>
      <div id="nav" class="collapse navbar-collapse">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
          <li class="nav-item"><a class="nav-link" href="#skills">Skills</a></li>
          <li class="nav-item"><a class="nav-link" href="#projects">Projects</a></li>
          <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- HERO -->
  <header id="home" class="hero-section">
    <div class="container py-5">
      <div class="row align-items-center g-4">
        <div class="col-lg-6">
          <h1 class="display-5 fw-bold">Hi, I’m <span class="text-primary">Varsha</span> — Web Developer &Designer </h1>
          <p class="lead text-secondary mt-2">HTML • CSS • Bootstrap • JavaScript • jQuery • SQL • Photoshop</p>
          <div class="d-flex gap-3 mt-3">
            <a href="#projects" class="btn btn-primary btn-lg"><i class="bi bi-rocket-takeoff"></i> View Projects</a>
            <a href="#contact" class="btn btn-outline-primary btn-lg"><i class="bi bi-envelope"></i> Contact</a>
          </div>
        </div>
        <div class="col-lg-6 text-center">
          <!-- apni image rakh sakte ho -->
          <img src="profil pic (1).jpg" alt="Varsha" class="img-fluid rounded-3 shadow" style="max-width:300px;">
        </div>
      </div>
    </div>
  </header>

  <!-- ABOUT -->
  <section id="about" class="py-5 bg-light">
    <div class="container">
      <h2 class="section-title mb-4">About</h2>
      <div class="row g-3">
        <div class="col-md-4">
          <div class="info-card p-3">
            <div class="d-flex align-items-center gap-2"><i class="bi bi-code-slash fs-4"></i><strong>Frontend</strong></div>
            <small class="text-secondary d-block mt-2">HTML5, CSS3, Bootstrap, JS, jQuery</small>
          </div>
        </div>
        <div class="col-md-4">
          <div class="info-card p-3">
            <div class="d-flex align-items-center gap-2"><i class="bi bi-palette fs-4"></i><strong>UI/UX</strong></div>
            <small class="text-secondary d-block mt-2">Responsive layouts, wireframes, micro-interactions</small>
          </div>
        </div>
        <div class="col-md-4">
          <div class="info-card p-3">
            <div class="d-flex align-items-center gap-2"><i class="bi bi-database fs-4"></i><strong>Basic Backend</strong></div>
            <small class="text-secondary d-block mt-2">PHP/SQLite for forms & data (demo)</small>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- SKILLS -->
  <section id="skills" class="py-5">
    <div class="container">
      <h2 class="section-title mb-4">Skills</h2>
      <div class="row g-4">
        <div class="col-md-6">
          <div class="d-flex justify-content-between"><span>HTML</span><span>90%</span></div>
          <div class="progress mb-3"><div class="progress-bar" style="width:90%"></div></div>
          <div class="d-flex justify-content-between"><span>CSS / Bootstrap</span><span>85%</span></div>
          <div class="progress mb-3"><div class="progress-bar" style="width:85%"></div></div>
          <div class="d-flex justify-content-between"><span>JavaScript</span><span>70%</span></div>
          <div class="progress mb-3"><div class="progress-bar" style="width:70%"></div></div>
        </div>
        <div class="col-md-6">
          <div class="d-flex justify-content-between"><span>jQuery</span><span>70%</span></div>
          <div class="progress mb-3"><div class="progress-bar" style="width:70%"></div></div>
          <div class="d-flex justify-content-between"><span>UI/UX</span><span>70%</span></div>
          <div class="progress mb-3"><div class="progress-bar" style="width:70%"></div></div>
          <div class="d-flex justify-content-between"><span>Photoshop</span><span>75%</span></div>
          <div class="progress mb-3"><div class="progress-bar" style="width:75%"></div></div>
        </div>
      </div>
    </div>
  </section>

  <!-- PROJECTS -->
  <section id="projects" class="py-5 bg-light">
    <div class="container">
      <div class="d-flex flex-wrap align-items-center justify-content-between">
        <h2 class="section-title mb-3">Projects</h2>
        <div class="filters btn-group mb-3" role="group" aria-label="Project filters">
          <button class="btn btn-outline-primary active" data-filter="*">All</button>
          <button class="btn btn-outline-primary" data-filter="web">Web</button>
          <button class="btn btn-outline-primary" data-filter="uiux">UI/UX</button>
          <button class="btn btn-outline-primary" data-filter="tools">Tools</button>
        </div>
      </div>

      <div class="row g-4" id="projectGrid">
        <!-- Project 1 -->
        <div class="col-md-6 col-lg-4 project-card" data-category="web">
          <div class="card h-100 shadow-sm">
            <img src="ui.png" class="card-img-top" alt="Mini E-commerce thumbnail">
            <div class="card-body d-flex flex-column">
              <h5 class="card-title">Mini E-commerce UI</h5>
              <p class="card-text small text-secondary">Responsive product grid with filters, cart UI mock, and smooth interactions.</p>
              <div class="mt-auto d-flex gap-2">
                <a href="ui.html" target="_blank" class="btn btn-sm btn-primary"><i class="bi bi-box-arrow-up-right"></i> Live</a>
                <a href="ui.html" target="_blank" class="btn btn-sm btn-outline-secondary"><i class="bi bi-github"></i> Code</a>
              </div>
            </div>
          </div>
        </div>

        <!-- Project 2 -->
        <div class="col-md-6 col-lg-4 project-card" data-category="uiux">
          <div class="card h-100 shadow-sm">
            <img src="Food Delivery.jpg" class="card-img-top" alt="Food Delivery Landing thumbnail">
            <div class="card-body d-flex flex-column">
              <h5 class="card-title">Food Delivery Landing</h5>
              <p class="card-text small text-secondary">Hero, menu showcase, and CTA flow focused on conversion with bold imagery.</p>
              <div class="mt-auto d-flex gap-2">
                <a href="food.html" target="_blank" class="btn btn-sm btn-primary"><i class="bi bi-box-arrow-up-right"></i> Live</a>
                <a href="food.html" target="_blank" class="btn btn-sm btn-outline-secondary"><i class="bi bi-github"></i> Code</a>
              </div>
            </div>
          </div>
        </div>

        <!-- Project 3 -->
        <div class="col-md-6 col-lg-4 project-card" data-category="tools">
          <div class="card h-100 shadow-sm">
            <img src="dashbord.png" class="card-img-top" alt="Admin Dashboard thumbnail">
            <div class="card-body d-flex flex-column">
              <h5 class="card-title">Admin Dashboard UI</h5>
              <p class="card-text small text-secondary">Cards, tables, and charts ready layout. Clean typography and spacing.</p>
              <div class="mt-auto d-flex gap-2">
                <a href="admin.html" target="_blank" class="btn btn-sm btn-primary"><i class="bi bi-box-arrow-up-right"></i> Live</a>
                <a href="admin.html" target="_blank" class="btn btn-sm btn-outline-secondary"><i class="bi bi-github"></i> Code</a>
              </div>
            </div>
          </div>
        </div>
      </div> <!-- /row -->
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact" class="py-5">
    <div class="container">
      <h2 class="section-title mb-4">Contact</h2>
      <div class="row g-4">
        <div class="col-lg-6">
          <form id="contactForm" class="needs-validation" novalidate>
            <div class="mb-3">
              <label class="form-label">Name</label>
              <input type="text" class="form-control" name="name" required>
              <div class="invalid-feedback">Please enter your name.</div>
            </div>
            <div class="mb-3">
              <label class="form-label">Email</label>
              <input type="email" class="form-control" name="email" required>
              <div class="invalid-feedback">Please enter a valid email.</div>
            </div>
            <div class="mb-3">
              <label class="form-label">Message</label>
              <textarea class="form-control" rows="4" name="message" required></textarea>
              <div class="invalid-feedback">Please write a message.</div>
            </div>
            <button class="btn btn-primary" type="submit"><i class="bi bi-send"></i> Send</button>
            <div id="formAlert" class="alert mt-3 d-none" role="alert"></div>
          </form>
        </div>
        <div class="col-lg-6">
          <div class="p-4 bg-light rounded-4 shadow-sm h-100">
            <h5 class="fw-semibold mb-3">Let’s work together</h5>
            <p class="text-secondary mb-2">I’m open to freelance work, internships, and full-time roles.</p>
            <p class="mb-0"><i class="bi bi-geo-alt"></i> India • Remote friendly</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="py-4">
    <div class="container text-center small">
      © <span id="year"></span> Varsha • Built with HTML, CSS, Bootstrap & JS
    </div>
  </footer>

  <!-- JS -->
  <script src="https://code.jquery.com/jquery-3.7.1.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

  <!-- Inline JS (single-file) -->
  <script>
    // Year
    document.getElementById("year").textContent = new Date().getFullYear();

    // Project Filters
    (function(){
      const buttons = document.querySelectorAll("[data-filter]");
      const cards = document.querySelectorAll(".project-card");
      buttons.forEach(btn=>{
        btn.addEventListener("click", ()=>{
          buttons.forEach(b=>b.classList.remove("active"));
          btn.classList.add("active");
          const f = btn.getAttribute("data-filter");
          cards.forEach(card=>{
            const cat = card.getAttribute("data-category");
            card.style.display = (f==="*" || f===cat) ? "" : "none";
          });
        });
      });
    })();

    // Contact form (front-end only)
    (function () {
      const form = document.getElementById("contactForm");
      const alertBox = document.getElementById("formAlert");
      form.addEventListener("submit", function (e) {
        e.preventDefault();
        if (!form.checkValidity()) { form.classList.add("was-validated"); return; }
        const data = Object.fromEntries(new FormData(form).entries());
        alertBox.className = "alert alert-success mt-3";
        alertBox.textContent = `Thanks ${data.name}! I will contact you at ${data.email}.`;
        form.reset(); form.classList.remove("was-validated");
      }, false);
    })();
  </script>
</body>
</html>
