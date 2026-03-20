  font-size: 1.2rem;
  box-shadow: 0 2px 10px rgba(201,168,76,0.3);
}

.nav-logo-text {
  display: flex;
  flex-direction: column;
  line-height: 1.1;
}

.nav-logo-text strong {
  font-family: 'Playfair Display', serif;
  font-size: 0.92rem;
  color: white;
}

.nav-logo-text span {
  font-size: 0.58rem;
  color: var(--gold);
  letter-spacing: 2px;
  text-transform: uppercase;
}

.nav-links {
  display: flex;
  align-items: center;
  gap: 4px;
  list-style: none;
}

.nav-links a {
  text-decoration: none;
  color: var(--white70);
  font-size: 0.8rem;
  font-weight: 600;
  padding: 6px 12px;
  border-radius: 6px;
  transition: all 0.2s;
  letter-spacing: 0.3px;
}

.nav-links a:hover { color: var(--gold-light); background: var(--white10); }

.nav-right {
  display: flex;
  align-items: center;
  gap: 12px;
}

.lang-btn {
  background: var(--white10);
  border: 1px solid rgba(201,168,76,0.3);
  border-radius: 20px;
  padding: 5px 14px;
  font-size: 0.75rem;
  font-weight: 700;
  color: var(--gold-light);
  cursor: pointer;
  font-family: 'Raleway', sans-serif;
  transition: all 0.2s;
}

.lang-btn:hover { background: rgba(201,168,76,0.15); }

.nav-cta {
  background: linear-gradient(135deg, var(--gold), var(--gold-light));
  border: none;
  border-radius: 20px;
  padding: 7px 18px;
  font-size: 0.78rem;
  font-weight: 700;
  color: var(--navy);
  cursor: pointer;
  font-family: 'Raleway', sans-serif;
  text-decoration: none;
  transition: all 0.2s;
  box-shadow: 0 3px 12px rgba(201,168,76,0.3);
}

.nav-cta:hover { transform: translateY(-1px); box-shadow: 0 5px 18px rgba(201,168,76,0.4); }

/* ============ HERO ============ */
#accueil {
  min-height: 100vh;
  position: relative;
  display: flex;
  align-items: center;
  padding: 100px 8% 60px;
  overflow: hidden;
}

.hero-bg {
  position: absolute;
  inset: 0;
  background: linear-gradient(135deg, #060e1a 0%, #0a1e3d 50%, #0d2548 100%);
}

.hero-pattern {
  position: absolute;
  inset: 0;
  opacity: 0.03;
  background-image:
    repeating-linear-gradient(45deg, #c9a84c 0, #c9a84c 1px, transparent 0, transparent 50%),
    repeating-linear-gradient(-45deg, #c9a84c 0, #c9a84c 1px, transparent 0, transparent 50%);
  background-size: 50px 50px;
}

.hero-glow {
  position: absolute;
  right: -100px;
  top: 50%;
  transform: translateY(-50%);
  width: 600px; height: 600px;
  border-radius: 50%;
  background: radial-gradient(circle, rgba(201,168,76,0.08) 0%, transparent 70%);
}

.hero-glow2 {
  position: absolute;
  left: -100px;
  bottom: -100px;
  width: 400px; height: 400px;
  border-radius: 50%;
  background: radial-gradient(circle, rgba(15,48,90,0.6) 0%, transparent 70%);
}

.hero-content {
  position: relative;
  max-width: 700px;
  z-index: 2;
}

.hero-badge {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  background: rgba(201,168,76,0.12);
  border: 1px solid rgba(201,168,76,0.3);
  border-radius: 20px;
  padding: 6px 16px;
  font-size: 0.75rem;
  font-weight: 600;
  color: var(--gold-light);
  letter-spacing: 1px;
  text-transform: uppercase;
  margin-bottom: 24px;
  animation: fadeUp 0.8s ease forwards;
}

.hero-title {
  font-family: 'Playfair Display', serif;
  font-size: 3.2rem;
  font-weight: 900;
  line-height: 1.1;
  margin-bottom: 20px;
  animation: fadeUp 0.8s ease 0.1s forwards;
  opacity: 0;
}

.hero-title span { color: var(--gold-light); }

.hero-subtitle {
  font-size: 1rem;
  color: var(--white70);
  line-height: 1.7;
  margin-bottom: 36px;
  max-width: 560px;
  animation: fadeUp 0.8s ease 0.2s forwards;
  opacity: 0;
}

.hero-btns {
  display: flex;
  gap: 14px;
  flex-wrap: wrap;
  animation: fadeUp 0.8s ease 0.3s forwards;
  opacity: 0;
}

.btn-primary {
  background: linear-gradient(135deg, var(--gold), var(--gold-light));
  border: none;
  border-radius: 25px;
  padding: 13px 28px;
  font-size: 0.88rem;
  font-weight: 700;
  color: var(--navy);
  cursor: pointer;
  font-family: 'Raleway', sans-serif;
  text-decoration: none;
  transition: all 0.3s;
  box-shadow: 0 5px 20px rgba(201,168,76,0.35);
}

.btn-primary:hover { transform: translateY(-2px); box-shadow: 0 8px 25px rgba(201,168,76,0.5); }

.btn-secondary {
  background: transparent;
  border: 1.5px solid rgba(201,168,76,0.5);
  border-radius: 25px;
  padding: 13px 28px;
  font-size: 0.88rem;
  font-weight: 700;
  color: var(--gold-light);
  cursor: pointer;
  font-family: 'Raleway', sans-serif;
  text-decoration: none;
  transition: all 0.3s;
}

.btn-secondary:hover { background: rgba(201,168,76,0.1); border-color: var(--gold-light); }

.hero-stats {
  position: absolute;
  right: 8%;
  top: 50%;
  transform: translateY(-50%);
  display: flex;
  flex-direction: column;
  gap: 16px;
  z-index: 2;
  animation: fadeRight 0.8s ease 0.4s forwards;
  opacity: 0;
}

.stat-card {
  background: rgba(255,255,255,0.05);
  border: 1px solid rgba(201,168,76,0.2);
  border-radius: 12px;
  padding: 16px 20px;
  text-align: center;
  min-width: 120px;
  backdrop-filter: blur(10px);
}

.stat-card .num {
  font-family: 'Playfair Display', serif;
  font-size: 1.8rem;
  font-weight: 900;
  color: var(--gold-light);
  line-height: 1;
}

.stat-card .lbl {
  font-size: 0.65rem;
  color: var(--white70);
  text-transform: uppercase;
  letter-spacing: 1px;
  margin-top: 4px;
}

/* ============ SECTIONS COMMUNES ============ */
section {
  padding: 90px 8%;
  position: relative;
}

.section-header {
  text-align: center;
  margin-bottom: 60px;
}

.section-label {
  display: inline-block;
  background: rgba(201,168,76,0.12);
  border: 1px solid rgba(201,168,76,0.3);
  border-radius: 20px;
  padding: 5px 16px;
  font-size: 0.72rem;
  font-weight: 700;
  color: var(--gold);
  letter-spacing: 2px;
  text-transform: uppercase;
  margin-bottom: 14px;
}

.section-title {
  font-family: 'Playfair Display', serif;
  font-size: 2.2rem;
  font-weight: 900;
  color: white;
  line-height: 1.2;
  margin-bottom: 14px;
}

.section-title span { color: var(--gold-light); }

.section-desc {
  font-size: 0.92rem;
  color: var(--white70);
  max-width: 550px;
  margin: 0 auto;
  line-height: 1.7;
}

.gold-line {
  width: 60px; height: 3px;
  background: linear-gradient(90deg, var(--gold), var(--gold-light));
  border-radius: 2px;
  margin: 16px auto 0;
}

/* ============ SERVICES ============ */
#services {
  background: linear-gradient(180deg, var(--navy) 0%, #0a1e3d 100%);
}

.services-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 24px;
}

.service-card {
  background: rgba(255,255,255,0.04);
  border: 1px solid rgba(201,168,76,0.15);
  border-radius: 16px;
  padding: 30px 24px;
  transition: all 0.3s;
  cursor: default;
  position: relative;
  overflow: hidden;
}

.service-card::before {
  content: '';
  position: absolute;
  top: 0; left: 0; right: 0;
  height: 3px;
  background: linear-gradient(90deg, var(--gold), var(--gold-light));
  transform: scaleX(0);
  transition: transform 0.3s;
}

.service-card:hover {
  background: rgba(201,168,76,0.07);
  border-color: rgba(201,168,76,0.35);
  transform: translateY(-4px);
  box-shadow: 0 12px 35px rgba(0,0,0,0.3);
}

.service-card:hover::before { transform: scaleX(1); }

.service-icon {
  width: 55px; height: 55px;
  background: linear-gradient(135deg, rgba(201,168,76,0.15), rgba(201,168,76,0.08));
  border: 1px solid rgba(201,168,76,0.3);
  border-radius: 14px;
  display: flex; align-items: center; justify-content: center;
  font-size: 1.6rem;
  margin-bottom: 18px;
}

.service-card h3 {
  font-family: 'Playfair Display', serif;
  font-size: 1.05rem;
  color: white;
  margin-bottom: 10px;
}

.service-card p {
  font-size: 0.82rem;
  color: var(--white70);
  line-height: 1.6;
}

.service-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 5px;
  margin-top: 14px;
}

.stag {
  background: rgba(201,168,76,0.1);
  border-radius: 10px;
  padding: 3px 8px;
  font-size: 0.62rem;
  color: var(--gold);
  font-weight: 600;
}

/* ============ À PROPOS ============ */
#apropos {
  background: #060e1a;
}

.about-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 60px;
  align-items: center;
}

.about-left { display: flex; flex-direction: column; gap: 20px; }

.about-left h2 {
  font-family: 'Playfair Display', serif;
  font-size: 2rem;
  line-height: 1.2;
}

.about-left h2 span { color: var(--gold-light); }

.about-left p {
  font-size: 0.88rem;
  color: var(--white70);
  line-height: 1.8;
}

.about-highlight {
  background: rgba(201,168,76,0.08);
  border-left: 3px solid var(--gold);
  border-radius: 0 8px 8px 0;
  padding: 14px 18px;
  font-size: 0.85rem;
  color: var(--white90);
  font-style: italic;
  line-height: 1.6;
}

.about-right {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 16px;
}

.about-stat {
  background: rgba(255,255,255,0.04);
  border: 1px solid rgba(201,168,76,0.18);
  border-radius: 14px;
  padding: 22px 18px;
  text-align: center;
  transition: all 0.3s;
}

.about-stat:hover {
  background: rgba(201,168,76,0.08);
  border-color: rgba(201,168,76,0.35);
}

.about-stat .big {
  font-family: 'Playfair Display', serif;
  font-size: 2.2rem;
  font-weight: 900;
  color: var(--gold-light);
  line-height: 1;
}

.about-stat .lbl {
  font-size: 0.72rem;
  color: var(--white70);
  margin-top: 6px;
  line-height: 1.3;
}

.about-person {
  grid-column: 1 / -1;
  background: linear-gradient(135deg, rgba(201,168,76,0.1), rgba(201,168,76,0.05));
  border: 1px solid rgba(201,168,76,0.25);
  border-radius: 14px;
  padding: 20px;
  display: flex;
  align-items: center;
  gap: 16px;
}

.person-avatar {
  width: 54px; height: 54px;
  background: linear-gradient(135deg, var(--gold), var(--gold-light));
  border-radius: 50%;
  display: flex; align-items: center; justify-content: center;
  font-size: 1.4rem;
  flex-shrink: 0;
}

.person-info strong {
  display: block;
  font-size: 0.88rem;
  color: white;
  font-weight: 700;
}

.person-info span {
  font-size: 0.72rem;
  color: var(--gold);
}

/* ============ FORMATIONS ============ */
#formations {
  background: linear-gradient(180deg, #0a1e3d 0%, var(--navy) 100%);
}

.formations-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 24px;
}

.formation-card {
  background: rgba(255,255,255,0.04);
  border: 1px solid rgba(201,168,76,0.15);
  border-radius: 16px;
  overflow: hidden;
  transition: all 0.3s;
}

.formation-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 15px 40px rgba(0,0,0,0.35);
  border-color: rgba(201,168,76,0.35);
}

.formation-header {
  background: linear-gradient(135deg, rgba(201,168,76,0.15), rgba(201,168,76,0.05));
  padding: 22px 24px;
  display: flex;
  align-items: center;
  gap: 14px;
  border-bottom: 1px solid rgba(201,168,76,0.12);
}

.formation-emoji { font-size: 1.8rem; }

.formation-header h3 {
  font-family: 'Playfair Display', serif;
  font-size: 1rem;
  color: white;
}

.formation-header span {
  font-size: 0.68rem;
  color: var(--gold);
  font-weight: 600;
}

.formation-body {
  padding: 20px 24px;
  display: flex;
  flex-direction: column;
  gap: 10px;
}

.formation-body p {
  font-size: 0.8rem;
  color: var(--white70);
  line-height: 1.6;
}

.formation-modules {
  list-style: none;
  display: flex;
  flex-direction: column;
  gap: 6px;
}

.formation-modules li {
  font-size: 0.78rem;
  color: var(--white70);
  display: flex;
  align-items: flex-start;
  gap: 8px;
}

.formation-modules li::before {
  content: '▸';
  color: var(--gold);
  flex-shrink: 0;
  margin-top: 1px;
}

.formation-footer {
  padding: 14px 24px;
  border-top: 1px solid rgba(255,255,255,0.05);
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.duration-badge {
  background: rgba(201,168,76,0.12);
  border: 1px solid rgba(201,168,76,0.25);
  border-radius: 10px;
  padding: 4px 10px;
  font-size: 0.68rem;
  font-weight: 700;
  color: var(--gold-light);
}

/* ============ RÉALISATIONS ============ */
#realisations {
  background: #060e1a;
}

.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 24px;
}

.project-card {
  background: rgba(255,255,255,0.04);
  border: 1px solid rgba(201,168,76,0.15);
  border-radius: 16px;
  padding: 28px 24px;
  transition: all 0.3s;
  position: relative;
}

.project-card:hover {
  background: rgba(201,168,76,0.06);
  border-color: rgba(201,168,76,0.3);
  transform: translateY(-4px);
}

.project-num {
  position: absolute;
  top: 20px; right: 20px;
  font-family: 'Playfair Display', serif;
  font-size: 2.5rem;
  font-weight: 900;
  color: rgba(201,168,76,0.1);
  line-height: 1;
}

.project-icon {
  font-size: 2rem;
  margin-bottom: 14px;
}

.project-card h3 {
  font-family: 'Playfair Display', serif;
  font-size: 1rem;
  color: white;
  margin-bottom: 8px;
}

.project-card p {
  font-size: 0.8rem;
  color: var(--white70);
  line-height: 1.6;
  margin-bottom: 14px;
}

.project-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 5px;
}

.ptag {
  background: rgba(201,168,76,0.1);
  border-radius: 10px;
  padding: 3px 8px;
  font-size: 0.62rem;
  color: var(--gold);
  font-weight: 600;
}

.project-status {
  display: inline-flex;
  align-items: center;
  gap: 5px;
  font-size: 0.68rem;
  font-weight: 600;
  margin-top: 12px;
}

.project-status.done { color: #3fb950; }
.project-status.ongoing { color: var(--gold-light); }

/* ============ CONTACT ============ */
#contact {
  background: linear-gradient(180deg, var(--navy) 0%, #060e1a 100%);
}

.contact-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 50px;
  align-items: start;
}

.contact-left h2 {
  font-family: 'Playfair Display', serif;
  font-size: 1.8rem;
  margin-bottom: 12px;
}

.contact-left h2 span { color: var(--gold-light); }

.contact-left p {
  font-size: 0.85rem;
  color: var(--white70);
  line-height: 1.7;
  margin-bottom: 28px;
}

.contact-items {
  display: flex;
  flex-direction: column;
  gap: 14px;
}

.ci {
  display: flex;
  align-items: center;
  gap: 14px;
}

.ci-icon {
  width: 42px; height: 42px;
  background: rgba(201,168,76,0.12);
  border: 1px solid rgba(201,168,76,0.3);
  border-radius: 10px;
  display: flex; align-items: center; justify-content: center;
  font-size: 1.1rem;
  flex-shrink: 0;
}

.ci-text .ci-label {
  font-size: 0.65rem;
  color: var(--gold);
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 1px;
}

.ci-text .ci-value {
  font-size: 0.85rem;
  color: white;
  font-weight: 500;
}

.contact-form {
  background: rgba(255,255,255,0.04);
  border: 1px solid rgba(201,168,76,0.15);
  border-radius: 16px;
  padding: 30px;
  display: flex;
  flex-direction: column;
  gap: 16px;
}

.contact-form h3 {
  font-family: 'Playfair Display', serif;
  font-size: 1.1rem;
  color: white;
  margin-bottom: 4px;
}

.form-row {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 12px;
}

.form-group {
  display: flex;
  flex-direction: column;
  gap: 6px;
}

.form-group label {
  font-size: 0.72rem;
  font-weight: 600;
  color: var(--gold);
  text-transform: uppercase;
  letter-spacing: 0.5px;
}

.form-group input,
.form-group textarea,
.form-group select {
  background: rgba(255,255,255,0.05);
  border: 1px solid rgba(201,168,76,0.2);
  border-radius: 8px;
  padding: 10px 14px;
  color: white;
  font-family: 'Raleway', sans-serif;
  font-size: 0.82rem;
  transition: border-color 0.2s;
  outline: none;
}

.form-group input:focus,
.form-group textarea:focus,
.form-group select:focus {
  border-color: var(--gold);
  background: rgba(201,168,76,0.05);
}

.form-group input::placeholder,
.form-group textarea::placeholder { color: rgba(255,255,255,0.3); }

.form-group textarea { resize: vertical; min-height: 90px; }

.form-group select option { background: var(--navy2); }

.form-submit {
  background: linear-gradient(135deg, var(--gold), var(--gold-light));
  border: none;
  border-radius: 25px;
  padding: 12px;
  font-size: 0.88rem;
  font-weight: 700;
  color: var(--navy);
  cursor: pointer;
  font-family: 'Raleway', sans-serif;
  transition: all 0.3s;
  box-shadow: 0 4px 15px rgba(201,168,76,0.3);
  width: 100%;
}

.form-submit:hover { transform: translateY(-2px); box-shadow: 0 6px 20px rgba(201,168,76,0.4); }

/* ============ FOOTER ============ */
footer {
  background: #040b14;
  border-top: 1px solid rgba(201,168,76,0.15);
  padding: 40px 8% 24px;
}

.footer-top {
  display: grid;
  grid-template-columns: 2fr 1fr 1fr;
  gap: 40px;
  margin-bottom: 30px;
}

.footer-brand p {
  font-size: 0.8rem;
  color: var(--white70);
  line-height: 1.7;
  margin: 12px 0 18px;
  max-width: 280px;
}

.footer-col h4 {
  font-size: 0.82rem;
  font-weight: 700;
  color: var(--gold-light);
  text-transform: uppercase;
  letter-spacing: 1px;
  margin-bottom: 14px;
}

.footer-col ul { list-style: none; display: flex; flex-direction: column; gap: 8px; }

.footer-col ul li a {
  font-size: 0.78rem;
  color: var(--white70);
  text-decoration: none;
  transition: color 0.2s;
}

.footer-col ul li a:hover { color: var(--gold-light); }

.footer-bottom {
  border-top: 1px solid rgba(255,255,255,0.05);
  padding-top: 20px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  flex-wrap: wrap;
  gap: 10px;
}

.footer-bottom p {
  font-size: 0.72rem;
  color: rgba(255,255,255,0.4);
}

.footer-bottom span { color: var(--gold); }

/* ============ ANIMATIONS ============ */
@keyframes fadeUp {
  from { opacity: 0; transform: translateY(25px); }
  to { opacity: 1; transform: translateY(0); }
}

@keyframes fadeRight {
  from { opacity: 0; transform: translateX(30px); }
  to { opacity: 1; transform: translateX(0); }
}

/* ============ BILINGUAL ============ */
[data-en] { display: none; }
body.en [data-fr] { display: none; }
body.en [data-en] { display: initial; }
body.en [data-en].block { display: block; }
body.en [data-en].flex { display: flex; }
body.en [data-en].grid { display: grid; }

/* ============ SCROLL TOP ============ */
.scroll-top {
  position: fixed;
  bottom: 24px;
  right: 24px;
  width: 42px; height: 42px;
  background: linear-gradient(135deg, var(--gold), var(--gold-light));
  border-radius: 50%;
  display: flex; align-items: center; justify-content: center;
  font-size: 1rem;
  color: var(--navy);
  cursor: pointer;
  box-shadow: 0 4px 15px rgba(201,168,76,0.4);
  z-index: 999;
  text-decoration: none;
  transition: transform 0.2s;
}

.scroll-top:hover { transform: translateY(-3px); }

/* ============ RESPONSIVE ============ */
@media (max-width: 900px) {
  .hero-stats { display: none; }
  .hero-title { font-size: 2.2rem; }
  .about-grid, .contact-grid { grid-template-columns: 1fr; }
  .footer-top { grid-template-columns: 1fr; }
  .nav-links { display: none; }
  .form-row { grid-template-columns: 1fr; }
}
</style>
</head>
<body>

<!-- NAVBAR -->
<nav>
  <a href="#accueil" class="nav-logo">
    <div class="nav-logo-icon">🏛️</div>
    <div class="nav-logo-text">
      <strong>FINDEV CONSEIL NIGER</strong>
      <span data-fr>Cabinet de Conseil</span>
      <span data-en>Consulting Firm</span>
    </div>
  </a>
  <ul class="nav-links">
    <li><a href="#accueil" data-fr>Accueil</a><a href="#accueil" data-en>Home</a></li>
    <li><a href="#services" data-fr>Services</a><a href="#services" data-en>Services</a></li>
    <li><a href="#apropos" data-fr>À propos</a><a href="#apropos" data-en>About</a></li>
    <li><a href="#formations" data-fr>Formations</a><a href="#formations" data-en>Training</a></li>
    <li><a href="#realisations" data-fr>Réalisations</a><a href="#realisations" data-en>Projects</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
  <div class="nav-right">
    <button class="lang-btn" onclick="toggleLang()">🌐 EN / FR</button>
    <a href="#contact" class="nav-cta" data-fr>Nous contacter</a>
    <a href="#contact" class="nav-cta" data-en>Contact Us</a>
  </div>
</nav>

<!-- HERO -->
<section id="accueil">
  <div class="hero-bg"></div>
  <div class="hero-pattern"></div>
  <div class="hero-glow"></div>
  <div class="hero-glow2"></div>
  <div class="hero-content">
    <div class="hero-badge">🇳🇪 <span data-fr>Maradi, Niger — Cabinet Professionnel</span><span data-en>Maradi, Niger — Professional Firm</span></div>
    <h1 class="hero-title" data-fr>FINDEV <span>CONSEIL</span><br>NIGER</h1>
    <h1 class="hero-title" data-en>FINDEV <span>CONSEIL</span><br>NIGER</h1>
    <p class="hero-subtitle" data-fr>Votre partenaire de confiance en <strong style="color:#e8c96a">Finances Publiques</strong> et <strong style="color:#e8c96a">Développement Local</strong>. Expertise, rigueur et engagement au service de votre croissance à Maradi et dans toute la région.</p>
    <p class="hero-subtitle" data-en>Your trusted partner in <strong style="color:#e8c96a">Public Finance</strong> and <strong style="color:#e8c96a">Local Development</strong>. Expertise, rigor and commitment to support your growth in Maradi and across the region.</p>
    <div class="hero-btns">
      <a href="#services" class="btn-primary" data-fr>Découvrir nos services</a>
      <a href="#services" class="btn-primary" data-en>Discover our services</a>
      <a href="#contact" class="btn-secondary" data-fr>Nous contacter</a>
      <a href="#contact" class="btn-secondary" data-en>Contact us</a>
    </div>
  </div>
  <div class="hero-stats">
    <div class="stat-card">
      <div class="num">4+</div>
      <div class="lbl" data-fr>Domaines d'expertise</div>
      <div class="lbl" data-en>Areas of expertise</div>
    </div>
    <div class="stat-card">
      <div class="num">🏛️</div>
      <div class="lbl" data-fr>Cabinet agréé</div>
      <div class="lbl" data-en>Licensed firm</div>
    </div>
    <div class="stat-card">
      <div class="num">🇳🇪</div>
      <div class="lbl" data-fr>Maradi, Niger</div>
      <div class="lbl" data-en>Maradi, Niger</div>
    </div>
  </div>
</section>

<!-- SERVICES -->
<section id="services">
  <div class="section-header">
    <div class="section-label" data-fr>Nos Services</div>
    <div class="section-label" data-en>Our Services</div>
    <h2 class="section-title" data-fr>Ce que nous <span>offrons</span></h2>
    <h2 class="section-title" data-en>What we <span>offer</span></h2>
    <p class="section-desc" data-fr>Nous proposons des services de conseil adaptés aux réalités du Niger et de la zone UEMOA.</p>
    <p class="section-desc" data-en>We provide consulting services adapted to the realities of Niger and the UEMOA zone.</p>
    <div class="gold-line"></div>
  </div>
  <div class="services-grid">
    <div class="service-card">
      <div class="service-icon">📊</div>
      <h3 data-fr>Finances Publiques</h3>
      <h3 data-en>Public Finance</h3>
      <p data-fr>Audit, budgétisation, contrôle financier et conseil en gestion des ressources publiques selon les normes LOFIN, UEMOA et SYSCOHADA.</p>
      <p data-en>Audit, budgeting, financial control and public resource management consulting according to LOFIN, UEMOA and SYSCOHADA standards.</p>
      <div class="service-tags">
        <span class="stag">LOFIN</span><span class="stag">UEMOA</span><span class="stag">SYSCOHADA</span><span class="stag">Audit</span>
      </div>
    </div>
    <div class="service-card">
      <div class="service-icon">🏘️</div>
      <h3 data-fr>Développement Local</h3>
      <h3 data-en>Local Development</h3>
      <p data-fr>Appui aux communes et collectivités territoriales, élaboration de plans de développement local et accompagnement des projets ruraux.</p>
      <p data-en>Support to municipalities and local authorities, preparation of local development plans and rural project management.</p>
      <div class="service-tags">
        <span class="stag">Communes</span><span class="stag">PDL</span><span class="stag">Projets ruraux</span>
      </div>
    </div>
    <div class="service-card">
      <div class="service-icon">🎓</div>
      <h3 data-fr>Formation Professionnelle</h3>
      <h3 data-en>Professional Training</h3>
      <p data-fr>Programmes de formation en Gestion de projet (PMI-PMBOK), Suivi-Évaluation, Ressources Humaines et Comptabilité SYSCOHADA.</p>
      <p data-en>Training programs in Project Management (PMI-PMBOK), Monitoring & Evaluation, Human Resources and SYSCOHADA Accounting.</p>
      <div class="service-tags">
        <span class="stag">PMI-PMBOK</span><span class="stag">S&E</span><span class="stag">RH</span><span class="stag">Comptabilité</span>
      </div>
    </div>
    <div class="service-card">
      <div class="service-icon">📋</div>
      <h3>DataCollect Pro</h3>
      <p data-fr>Collecte de données terrain, analyse statistique, conception d'outils de collecte et production de rapports d'études personnalisés.</p>
      <p data-en>Field data collection, statistical analysis, design of collection tools and production of customized study reports.</p>
      <div class="service-tags">
        <span class="stag">Collecte terrain</span><span class="stag">Analyse</span><span class="stag">Rapports</span>
      </div>
    </div>
    <div class="service-card">
      <div class="service-icon">📝</div>
      <h3 data-fr>Élaboration de Projets</h3>
      <h3 data-en>Project Development</h3>
      <p data-fr>Conception et rédaction de projets de développement, mobilisation de financements auprès des bailleurs de fonds nationaux et internationaux.</p>
      <p data-en>Design and drafting of development projects, mobilization of funding from national and international donors.</p>
      <div class="service-tags">
        <span class="stag">Bailleurs</span><span class="stag">Financement</span><span class="stag">ONG</span>
      </div>
    </div>
    <div class="service-card">
      <div class="service-icon">🔍</div>
      <h3 data-fr>Suivi & Évaluation</h3>
      <h3 data-en>Monitoring & Evaluation</h3>
      <p data-fr>Mise en place de systèmes de suivi-évaluation, collecte d'indicateurs de performance et évaluation d'impact des projets.</p>
      <p data-en>Setting up monitoring and evaluation systems, performance indicator collection and project impact assessment.</p>
      <div class="service-tags">
        <span class="stag">Indicateurs</span><span class="stag">Impact</span><span class="stag">Performance</span>
      </div>
    </div>
  </div>
</section>

<!-- À PROPOS -->
<section id="apropos">
  <div class="about-grid">
    <div class="about-left">
      <div class="section-label" data-fr>À propos de nous</div>
      <div class="section-label" data-en>About us</div>
      <h2 data-fr>Un cabinet au service du <span>développement</span> du Niger</h2>
      <h2 data-en>A firm dedicated to <span>Niger's development</span></h2>
      <p data-fr>FINDEV CONSEIL NIGER est un cabinet de conseil indépendant basé à Maradi, spécialisé dans les finances publiques et le développement local. Nous accompagnons les institutions publiques, les ONG, les collectivités et les entreprises dans la gestion de leurs ressources et la réalisation de leurs projets.</p>
      <p data-en>FINDEV CONSEIL NIGER is an independent consulting firm based in Maradi, specialized in public finance and local development. We support public institutions, NGOs, communities and businesses in managing their resources and achieving their projects.</p>
      <div class="about-highlight" data-fr>
        "Le développement local commence par une bonne gestion des ressources publiques." — Lawali Ibrahim Mahaman Sanoussi, Fondateur
      </div>
      <div class="about-highlight" data-en>
        "Local development starts with good management of public resources." — Lawali Ibrahim Mahaman Sanoussi, Founder
      </div>
      <a href="#contact" class="btn-primary" style="align-self:flex-start;" data-fr>Travailler avec nous</a>
      <a href="#contact" class="btn-primary" style="align-self:flex-start;" data-en>Work with us</a>
    </div>
    <div class="about-right">
      <div class="about-stat">
        <div class="big">4+</div>
        <div class="lbl" data-fr>Domaines d'expertise</div>
        <div class="lbl" data-en>Areas of expertise</div>
      </div>
      <div class="about-stat">
        <div class="big">🇳🇪</div>
        <div class="lbl" data-fr>Basé au Niger</div>
        <div class="lbl" data-en>Based in Niger</div>
      </div>
      <div class="about-stat">
        <div class="big">UEMOA</div>
        <div class="lbl" data-fr>Zone d'intervention</div>
        <div class="lbl" data-en>Area of intervention</div>
      </div>
      <div class="about-stat">
        <div class="big">✅</div>
        <div class="lbl" data-fr>Cabinet actif</div>
        <div class="lbl" data-en>Active firm</div>
      </div>
      <div class="about-person">
        <div class="person-avatar">👤</div>
        <div class="person-info">
          <strong>Lawali Ibrahim Mahaman Sanoussi</strong>
          <span data-fr>Fondateur & Directeur — FINDEV CONSEIL NIGER</span>
          <span data-en>Founder & Director — FINDEV CONSEIL NIGER</span>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- FORMATIONS -->
<section id="formations">
  <div class="section-header">
    <div class="section-label" data-fr>Nos Formations</div>
    <div class="section-label" data-en>Our Training Programs</div>
    <h2 class="section-title" data-fr>Développez vos <span>compétences</span></h2>
    <h2 class="section-title" data-en>Develop your <span>skills</span></h2>
    <p class="section-desc" data-fr>Des programmes de formation professionnelle adaptés au contexte nigérien et de la zone UEMOA.</p>
    <p class="section-desc" data-en>Professional training programs adapted to the Nigerian context and the UEMOA zone.</p>
    <div class="gold-line"></div>
  </div>
  <div class="formations-grid">
    <div class="formation-card">
      <div class="formation-header">
        <span class="formation-emoji">📊</span>
        <div>
          <h3 data-fr>Gestion de Projet</h3>
          <h3 data-en>Project Management</h3>
          <span>PMI-PMBOK & PRINCE2</span>
        </div>
      </div>
      <div class="formation-body">
        <p data-fr>Formation complète en gestion de projet selon les standards internationaux PMI-PMBOK, PRINCE2 et Agile/Scrum.</p>
        <p data-en>Comprehensive project management training according to international PMI-PMBOK, PRINCE2 and Agile/Scrum standards.</p>
        <ul class="formation-modules">
          <li data-fr>Initiation et planification de projet</li>
          <li data-fr>Gestion des risques et des parties prenantes</li>
          <li data-fr>Méthodologies Agile & Scrum</li>
          <li data-fr>Clôture et évaluation de projet</li>
          <li data-en>Project initiation and planning</li>
          <li data-en>Risk and stakeholder management</li>
          <li data-en>Agile & Scrum methodologies</li>
          <li data-en>Project closure and evaluation</li>
        </ul>
      </div>
      <div class="formation-footer">
        <span class="duration-badge" data-fr>⏱️ 80 heures</span>
        <span class="duration-badge" data-en>⏱️ 80 hours</span>
        <a href="#contact" class="btn-primary" style="padding:6px 16px; font-size:0.75rem;" data-fr>S'inscrire</a>
        <a href="#contact" class="btn-primary" style="padding:6px 16px; font-size:0.75rem;" data-en>Register</a>
      </div>
    </div>
    <div class="formation-card">
      <div class="formation-header">
        <span class="formation-emoji">🔍</span>
        <div>
          <h3 data-fr>Suivi & Évaluation</h3>
          <h3 data-en>Monitoring & Evaluation</h3>
          <span data-fr>Cadre logique & Indicateurs</span>
          <span data-en>Logical framework & Indicators</span>
        </div>
      </div>
      <div class="formation-body">
        <p data-fr>Maîtrisez les outils et méthodes de suivi-évaluation des projets de développement dans le contexte africain.</p>
        <p data-en>Master the tools and methods for monitoring and evaluating development projects in the African context.</p>
        <ul class="formation-modules">
          <li data-fr>Cadre logique et théorie du changement</li>
          <li data-fr>Conception d'indicateurs SMART</li>
          <li data-fr>Collecte et analyse des données S&E</li>
          <li data-fr>Rédaction de rapports d'évaluation</li>
          <li data-en>Logical framework and theory of change</li>
          <li data-en>SMART indicator design</li>
          <li data-en>M&E data collection and analysis</li>
          <li data-en>Evaluation report writing</li>
        </ul>
      </div>
      <div class="formation-footer">
        <span class="duration-badge" data-fr>⏱️ 60 heures</span>
        <span class="duration-badge" data-en>⏱️ 60 hours</span>
        <a href="#contact" class="btn-primary" style="padding:6px 16px; font-size:0.75rem;" data-fr>S'inscrire</a>
        <a href="#contact" class="btn-primary" style="padding:6px 16px; font-size:0.75rem;" data-en>Register</a>
      </div>
    </div>
    <div class="formation-card">
      <div class="formation-header">
        <span class="formation-emoji">💰</span>
        <div>
          <h3 data-fr>Finances Publiques</h3>
          <h3 data-en>Public Finance</h3>
          <span>SYSCOHADA & UEMOA</span>
        </div>
      </div>
      <div class="formation-body">
        <p data-fr>Formation pratique sur la gestion des finances publiques selon les directives UEMOA et le référentiel SYSCOHADA.</p>
        <p data-en>Practical training on public finance management according to UEMOA guidelines and the SYSCOHADA framework.</p>
        <ul class="formation-modules">
          <li data-fr>Directives UEMOA et LOFIN Niger</li>
          <li data-fr>Comptabilité SYSCOHADA approfondie</li>
          <li data-fr>Gestion budgétaire et SIGFIP</li>
          <li data-fr>Contrôle interne et audit financier</li>
          <li data-en>UEMOA directives and LOFIN Niger</li>
          <li data-en>Advanced SYSCOHADA accounting</li>
          <li data-en>Budget management and SIGFIP</li>
          <li data-en>Internal control and financial audit</li>
        </ul>
      </div>
      <div class="formation-footer">
        <span class="duration-badge" data-fr>⏱️ 40 heures</span>
        <span class="duration-badge" data-en>⏱️ 40 hours</span>
        <a href="#contact" class="btn-primary" style="padding:6px 16px; font-size:0.75rem;" data-fr>S'inscrire</a>
        <a href="#contact" class="btn-primary" style="padding:6px 16px; font-size:0.75rem;" data-en>Register</a>
      </div>
    </div>
  </div>
</section>

<!-- RÉALISATIONS -->
<section id="realisations">
  <div class="section-header">
    <div class="section-label" data-fr>Nos Réalisations</div>
    <div class="section-label" data-en>Our Projects</div>
    <h2 class="section-title" data-fr>Ce que nous avons <span>accompli</span></h2>
    <h2 class="section-title" data-en>What we have <span>achieved</span></h2>
    <p class="section-desc" data-fr>Découvrez quelques-unes de nos réalisations et projets phares au Niger.</p>
    <p class="section-desc" data-en>Discover some of our flagship achievements and projects in Niger.</p>
    <div class="gold-line"></div>
  </div>
  <div class="projects-grid">
    <div class="project-card">
      <div class="project-num">01</div>
      <div class="project-icon">🏗️</div>
      <h3 data-fr>PRCGFB-Maradi</h3>
      <h3 data-en>PRCGFB-Maradi</h3>
      <p data-fr>Projet de Renforcement des Capacités en Gestion des Finances dans 20 communes rurales de la région de Maradi sur 36 mois.</p>
      <p data-en>Capacity Building Project in Finance Management in 20 rural communes of the Maradi region over 36 months.</p>
      <div class="project-tags">
        <span class="ptag">20 communes</span><span class="ptag">36 mois</span><span class="ptag">Finances</span>
      </div>
      <div class="project-status ongoing">⚡ <span data-fr>En cours</span><span data-en>Ongoing</span></div>
    </div>
    <div class="project-card">
      <div class="project-num">02</div>
      <div class="project-icon">📚</div>
      <h3 data-fr>Programme Pédagogique CFD AL-BAYANE</h3>
      <h3 data-en>CFD AL-BAYANE Educational Program</h3>
      <p data-fr>Élaboration d'un programme pédagogique complet de lecture coranique bilingue (français/arabe) — 13 manuels niveaux N1 à N10.</p>
      <p data-en>Development of a complete bilingual Quranic reading educational program (French/Arabic) — 13 manuals for levels N1 to N10.</p>
      <div class="project-tags">
        <span class="ptag">13 manuels</span><span class="ptag">Bilingue</span><span class="ptag">FR/AR</span>
      </div>
      <div class="project-status done">✅ <span data-fr>Réalisé</span><span data-en>Completed</span></div>
    </div>
    <div class="project-card">
      <div class="project-num">03</div>
      <div class="project-icon">📋</div>
      <h3>DataCollect Pro</h3>
      <p data-fr>Service professionnel de collecte et d'analyse de données terrain pour les ONG, institutions et entreprises opérant au Niger.</p>
      <p data-en>Professional field data collection and analysis service for NGOs, institutions and businesses operating in Niger.</p>
      <div class="project-tags">
        <span class="ptag">ONG</span><span class="ptag">Institutions</span><span class="ptag">Niger</span>
      </div>
      <div class="project-status ongoing">⚡ <span data-fr>En cours</span><span data-en>Active</span></div>
    </div>
    <div class="project-card">
      <div class="project-num">04</div>
      <div class="project-icon">📖</div>
      <h3 data-fr>Guide NGO — Gestion Budgétaire</h3>
      <h3 data-en>NGO Budget Management Guide</h3>
      <p data-fr>Production d'un guide complet de gestion budgétaire pour ONG avec classeur Excel fonctionnel (8 onglets, centaines de formules).</p>
      <p data-en>Production of a comprehensive budget management guide for NGOs with functional Excel workbook (8 tabs, hundreds of formulas).</p>
      <div class="project-tags">
        <span class="ptag">ONG</span><span class="ptag">Budget</span><span class="ptag">Excel</span>
      </div>
      <div class="project-status done">✅ <span data-fr>Réalisé</span><span data-en>Completed</span></div>
    </div>
    <div class="project-card">
      <div class="project-num">05</div>
      <div class="project-icon">🎓</div>
      <h3 data-fr>Formation Gestion de Projet — 80h</h3>
      <h3 data-en>Project Management Training — 80h</h3>
      <p data-fr>Programme de formation complet PMI-PMBOK, PRINCE2 et Agile/Scrum avec kits participants, certificats et supports de cours.</p>
      <p data-en>Complete PMI-PMBOK, PRINCE2 and Agile/Scrum training program with participant kits, certificates and course materials.</p>
      <div class="project-tags">
        <span class="ptag">PMI-PMBOK</span><span class="ptag">PRINCE2</span><span class="ptag">Agile</span>
      </div>
      <div class="project-status done">✅ <span data-fr>Réalisé</span><span data-en>Completed</span></div>
    </div>
    <div class="project-card">
      <div class="project-num">06</div>
      <div class="project-icon">🏛️</div>
      <h3 data-fr>Appui Hôtel de Ville de Maradi</h3>
      <h3 data-en>Maradi City Hall Support</h3>
      <p data-fr>Stage et mission d'appui à l'Hôtel de Ville de Maradi axé sur la motivation des agents et la performance des fonctionnaires.</p>
      <p data-en>Internship and support mission at Maradi City Hall focused on staff motivation and civil servant performance.</p>
      <div class="project-tags">
        <span class="ptag">RH</span><span class="ptag">Performance</span><span class="ptag">Maradi</span>
      </div>
      <div class="project-status done">✅ <span data-fr>Réalisé</span><span data-en>Completed</span></div>
    </div>
  </div>
</section>

<!-- CONTACT -->
<section id="contact">
  <div class="section-header">
    <div class="section-label" data-fr>Contactez-nous</div>
    <div class="section-label" data-en>Contact Us</div>
    <h2 class="section-title" data-fr>Parlons de votre <span>projet</span></h2>
    <h2 class="section-title" data-en>Let's talk about your <span>project</span></h2>
    <div class="gold-line"></div>
  </div>
  <div class="contact-grid">
    <div class="contact-left">
      <h2 data-fr>Nous sommes <span>disponibles</span></h2>
      <h2 data-en>We are <span>available</span></h2>
      <p data-fr>N'hésitez pas à nous contacter pour tout besoin en conseil, formation ou collecte de données. Nous répondons rapidement à toutes vos demandes.</p>
      <p data-en>Feel free to contact us for any consulting, training or data collection needs. We respond quickly to all your requests.</p>
      <div class="contact-items">
        <div class="ci">
          <div class="ci-icon">📱</div>
          <div class="ci-text">
            <div class="ci-label" data-fr>Téléphone</div>
            <div class="ci-label" data-en>Phone</div>
            <div class="ci-value">(+227) 89 34 97 61</div>
          </div>
        </div>
        <div class="ci">
          <div class="ci-icon">📧</div>
          <div class="ci-text">
            <div class="ci-label">Email</div>
            <div class="ci-value">sanoussilawali31@gmail.com</div>
          </div>
        </div>
        <div class="ci">
          <div class="ci-icon">📍</div>
          <div class="ci-text">
            <div class="ci-label" data-fr>Adresse</div>
            <div class="ci-label" data-en>Address</div>
            <div class="ci-value">Maradi, Niger 🇳🇪</div>
          </div>
        </div>
        <div class="ci">
          <div class="ci-icon">🌐</div>
          <div class="ci-text">
            <div class="ci-label">GitHub</div>
            <div class="ci-value">github.com/sanoussilawali31-cyber</div>
          </div>
        </div>
      </div>
    </div>
    <div class="contact-form">
      <h3 data-fr>✉️ Envoyer un message</h3>
      <h3 data-en>✉️ Send a message</h3>
      <div class="form-row">
        <div class="form-group">
          <label data-fr>Prénom</label>
          <label data-en>First name</label>
          <input type="text" placeholder="Votre prénom">
        </div>
        <div class="form-group">
          <label data-fr>Nom</label>
          <label data-en>Last name</label>
          <input type="text" placeholder="Votre nom">
        </div>
      </div>
      <div class="form-group">
        <label>Email</label>
        <input type="email" placeholder="votre@email.com">
      </div>
      <div class="form-group">
        <label data-fr>Service souhaité</label>
        <label data-en>Desired service</label>
        <select>
          <option data-fr>Finances Publiques</option>
          <option data-en>Public Finance</option>
          <option data-fr>Développement Local</option>
          <option data-en>Local Development</option>
          <option data-fr>Formation Professionnelle</option>
          <option data-en>Professional Training</option>
          <option>DataCollect Pro</option>
          <option data-fr>Autre</option>
          <option data-en>Other</option>
        </select>
      </div>
      <div class="form-group">
        <label data-fr>Message</label>
        <label data-en>Message</label>
        <textarea placeholder="Décrivez votre besoin..."></textarea>
      </div>
      <button class="form-submit" data-fr>📨 Envoyer le message</button>
      <button class="form-submit" data-en>📨 Send message</button>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <div class="footer-top">
    <div class="footer-brand">
      <div class="nav-logo" style="display:flex; margin-bottom:10px;">
        <div class="nav-logo-icon">🏛️</div>
        <div class="nav-logo-text" style="margin-left:10px;">
          <strong>FINDEV CONSEIL NIGER</strong>
          <span data-fr>Cabinet de Conseil</span>
          <span data-en>Consulting Firm</span>
        </div>
      </div>
      <p data-fr>Cabinet de Conseil en Finances Publiques et Développement Local basé à Maradi, Niger. Votre partenaire de confiance pour la gestion de vos ressources.</p>
      <p data-en>Public Finance and Local Development Consulting Firm based in Maradi, Niger. Your trusted partner for resource management.</p>
    </div>
    <div class="footer-col">
      <h4 data-fr>Navigation</h4>
      <h4 data-en>Navigation</h4>
      <ul>
        <li><a href="#accueil" data-fr>Accueil</a><a href="#accueil" data-en>Home</a></li>
        <li><a href="#services" data-fr>Services</a><a href="#services" data-en>Services</a></li>
        <li><a href="#apropos" data-fr>À propos</a><a href="#apropos" data-en>About</a></li>
        <li><a href="#formations" data-fr>Formations</a><a href="#formations" data-en>Training</a></li>
        <li><a href="#realisations" data-fr>Réalisations</a><a href="#realisations" data-en>Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </div>
    <div class="footer-col">
      <h4>Contact</h4>
      <ul>
        <li><a href="tel:+22789349761">📱 (+227) 89 34 97 61</a></li>
        <li><a href="mailto:sanoussilawali31@gmail.com">📧 sanoussilawali31@gmail.com</a></li>
        <li><a href="#">📍 Maradi, Niger 🇳🇪</a></li>
        <li><a href="https://github.com/sanoussilawali31-cyber">🌐 GitHub</a></li>
      </ul>
    </div>
  </div>
  <div class="footer-bottom">
    <p data-fr>© 2025 <span>FINDEV CONSEIL NIGER</span>. Tous droits réservés. — Maradi, Niger 🇳🇪</p>
    <p data-en>© 2025 <span>FINDEV CONSEIL NIGER</span>. All rights reserved. — Maradi, Niger 🇳🇪</p>
    <p data-fr>Développé pour <span>Lawali Ibrahim Mahaman Sanoussi</span></p>
    <p data-en>Developed for <span>Lawali Ibrahim Mahaman Sanoussi</span></p>
  </div>
</footer>

<!-- SCROLL TOP -->
<a href="#accueil" class="scroll-top">↑</a>

<script>
function toggleLang() {
  document.body.classList.toggle('en');
}

// Active nav link on scroll
const sections = document.querySelectorAll('section[id]');
const navLinks = document.querySelectorAll('.nav-links a');

window.addEventListener('scroll', () => {
  let current = '';
  sections.forEach(s => {
    if (window.scrollY >= s.offsetTop - 100) current = s.getAttribute('id');
  });
  navLinks.forEach(a => {
    a.style.color = a.getAttribute('href') === '#' + current ? '#e8c96a' : '';
  });
});
</script>
</body>
</html>
