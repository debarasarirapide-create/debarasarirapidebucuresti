<!doctype html>
<html lang="ro">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Debarāsări Rapide București & Ilfov | Bogdan</title>
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    :root{
      --blue:#0B7CE3;
      --dark:#0f1720;
      --muted:#6b7280;
      --card-bg:#ffffff;
      --radius:14px;
      --container:1100px;
      font-family: 'Inter', system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    html,body{height:100%;margin:0;background:#f6f8fb;color:var(--dark);}
    a{color:inherit;text-decoration:none}
    .wrap{max-width:var(--container);margin:32px auto;padding:28px;}
    header{display:flex;align-items:center;justify-content:space-between;gap:16px;margin-bottom:24px}
    .brand{display:flex;gap:12px;align-items:center}
    .logo{
      width:56px;height:56px;border-radius:10px;display:flex;align-items:center;justify-content:center;
      background:linear-gradient(135deg,var(--blue),#146dd9);color:white;font-weight:700;font-size:18px;
    }
    .brand h1{font-size:18px;margin:0}
    .contact-mini{font-size:14px;text-align:right}
    .hero{
      display:grid;grid-template-columns:1fr 420px;gap:28px;align-items:center;
      background:linear-gradient(180deg,white,white);
      padding:36px;border-radius:18px;box-shadow:0 6px 24px rgba(12,24,48,0.06);
    }
    .hero-left h2{font-size:32px;margin:0 0 12px 0;line-height:1.05}
    .hero-left p{color:var(--muted);margin:0 0 20px 0}
    .btn{
      display:inline-block;background:var(--blue);color:white;padding:12px 18px;border-radius:10px;font-weight:600;
      box-shadow:0 6px 18px rgba(11,124,227,0.18)
    }
    .btn.secondary{background:white;border:1px solid #e6eefc;color:var(--blue)}
    .hero-right img{width:100%;height:auto;border-radius:12px;display:block;object-fit:cover}
    main{margin-top:28px;display:grid;gap:28px}
    .card{background:var(--card-bg);padding:28px;border-radius:16px;box-shadow:0 8px 30px rgba(12,24,48,0.04)}
    .services{display:grid;grid-template-columns:1fr 360px;gap:24px;align-items:start}
    .services ul{padding-left:16px;margin:12px 0 0 0;color:var(--muted)}
    .services li{margin:10px 0;line-height:1.4}
    .section-title{font-size:20px;margin:0 0 6px 0;font-weight:700}
    .section-sub{height:4px;width:44px;background:var(--blue);border-radius:6px;margin:8px 0 16px 0}
    .zones{display:flex;gap:20px;flex-wrap:wrap}
    .zone-box{flex:1;min-width:280px}
    .contact-grid{display:grid;grid-template-columns:1fr 360px;gap:24px;align-items:center}
    .contact-card p{margin:6px 0;color:var(--muted)}
    .phone{font-weight:700;color:var(--dark);font-size:20px;margin-top:6px}
    footer{margin-top:18px;text-align:center;color:var(--muted);font-size:13px;padding:18px 0}
    /* Responsive */
    @media (max-width:900px){
      .hero{grid-template-columns:1fr; text-align:center}
      .hero-right{order:-1}
      .services{grid-template-columns:1fr}
      .contact-grid{grid-template-columns:1fr}
    }
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <div class="brand">
        <div class="logo">DB</div>
        <div>
          <h1 style="margin:0">Debarāsări Rapide</h1>
          <div style="color:var(--muted);font-size:13px">București &amp; Ilfov — intervenim azi</div>
        </div>
      </div>
      <div class="contact-mini" aria-hidden="false">
        <div style="font-weight:600">Bogdan</div>
        <div style="color:var(--muted)">📞 <a href="tel:+40725175776">0725 175 776</a></div>
        <div style="color:var(--muted)"><a href="mailto:Debarasarirapide@gmail.com">Debarasarirapide@gmail.com</a></div>
      </div>
    </header>

    <!-- HERO -->
    <section class="hero" aria-labelledby="hero-title">
      <div class="hero-left">
        <h2 id="hero-title">Debarāsări rapide în București și Ilfov — intervenim chiar azi!</h2>
        <p>Scăpați de mobilă veche, electrocasnice, moloz și orice obiecte inutile în doar câteva ore. Prețuri corecte, echipă serioasă și transport inclus.</p>
        <div style="display:flex;gap:12px;flex-wrap:wrap">
          <a class="btn" href="tel:+40725175776" aria-label="Sună pe Bogdan">Sună acum • 0725 175 776</a>
          <a class="btn secondary" href="mailto:Debarasarirapide@gmail.com" aria-label="Cere ofertă prin email">Cere ofertă</a>
        </div>
      </div>

      <div class="hero-right">
        <!-- înlocuiește images/hero.jpg cu fotografia ta -->
        <img src="images/hero.jpg" alt="Camion de debarasare incarcat cu mobila si resturi">
      </div>
    </section>

    <main>
      <!-- Servicii -->
      <section class="card services" aria-labelledby="servicii">
        <div>
          <h3 id="servicii" class="section-title">Serviciile Noastre</h3>
          <div class="section-sub" aria-hidden="true"></div>
          <ul>
            <li>Debarasări garsoniere, apartamente, subsoluri și case</li>
            <li>Evacuare mobilă: canapele, dulapuri, rafturi, biblioteci</li>
            <li>Ridicare electrocasnice: frigidere, TV, mașini de spălat</li>
            <li>Debarasări birouri, hale și spații comerciale</li>
            <li>Evacuare moloz și resturi după renovări</li>
            <li>Curățenie după debarasare</li>
            <li>Transport obiecte grele și materiale voluminoase</li>
          </ul>
        </div>

        <div style="display:flex;align-items:center;justify-content:center">
          <!-- înlocuiește images/canapea.jpg -->
          <img src="images/canapea.jpg" alt="Canapea portocalie scoasă afară" style="width:100%;border-radius:12px;max-width:360px;object-fit:cover">
        </div>
      </section>

      <!-- Zone acoperite -->
      <section class="card" aria-labelledby="zone">
        <h3 id="zone" class="section-title">Zone Acoperite — București &amp; Ilfov</h3>
        <div class="section-sub" aria-hidden="true"></div>

        <div class="zones">
          <div class="zone-box">
            <strong>București:</strong>
            <p style="margin:6px 0;color:var(--muted)">Toate sectoarele: 1, 2, 3, 4, 5, 6 (intervenim rapid în orice zonă a orașului)</p>
          </div>

          <div class="zone-box">
            <strong>Ilfov (exemple):</strong>
            <p style="margin:6px 0;color:var(--muted)">
              Voluntari, Popești-Leordeni, Pantelimon, Chiajna, Bragadiru, Otopeni, Mogoșoaia, Buftea, 
              Atunci, Dărăști, Tunari, Chitila și localități învecinate.
            </p>
          </div>

          <div style="flex-basis:100%;height:12px"></div>

          <div style="display:flex;gap:18px;align-items:center">
            <div style="flex:1">
              <p style="color:var(--muted);margin:0 0 8px 0">Exemple de intervenții: evacuare mobilă completă, moloz din renovări, ridicare electrocasnice.</p>
            </div>
            <div style="width:160px">
              <!-- înlocuiește images/truck.jpg -->
              <img src="images/truck.jpg" alt="Autoutilitara pentru debarasari" style="width:100%;border-radius:10px;object-fit:cover">
            </div>
          </div>
        </div>
      </section>

      <!-- Contact -->
      <section class="card contact-grid" aria-labelledby="contact">
        <div class="contact-card">
          <h3 id="contact" class="section-title">Contact</h3>
          <div class="section-sub" aria-hidden="true"></div>
          <p>Sună direct pentru programare rapidă sau cere ofertă prin email. Intervenții în aceeași zi, echipă dedicată.</p>

          <div class="phone">📞 <a href="tel:+40725175776">0725 175 776</a></div>
          <div style="margin-top:8px;color:var(--muted)"><strong>Email:</strong> <a href="mailto:Debarasarirapide@gmail.com">Debarasarirapide@gmail.com</a></div>

          <div style="margin-top:18px">
            <a class="btn" href="tel:+40725175776">Sună acum</a>
            <a class="btn secondary" href="mailto:Debarasarirapide@gmail.com" style="margin-left:10px">Trimite email</a>
          </div>

          <p style="margin-top:16px;color:var(--muted);font-size:13px">Program: Luni-Duminică 07:00–22:00</p>
        </div>

        <div style="display:flex;align-items:center;justify-content:center">
          <!-- imagine reprezentativă; înlocuiește images/work.jpg -->
          <img src="images/work.jpg" alt="Echipă care mută saci și mobilă" style="width:100%;max-width:360px;border-radius:12px;object-fit:cover">
        </div>
      </section>
    </main>

    <footer>
      © <span id="year"></span> Debarāsări Rapide — București &amp; Ilfov • Bogdan • <a href="tel:+40725175776">0725 175 776</a>
    </footer>
  </div>

  <script>
    // setăm anul curent
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
