<!doctype html>
<html lang="en-GB">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <meta name="theme-color" content="#0b1220" />

  <title>Simple Mechanic Ltd | Mobile Mechanic in Uxbridge, Hayes & Slough</title>
  <meta name="description" content="Simple Mechanic Ltd — trusted mobile mechanic in Uxbridge, Hayes & Slough (England). Diagnostics, servicing, brakes, batteries, alternators, starters, suspension and more. We come to your home or workplace. Call or WhatsApp for a fast quote." />

  <!-- Basic SEO -->
  <meta name="robots" content="index,follow" />
  <meta name="author" content="Simple Mechanic Ltd" />
  <meta name="geo.region" content="GB-ENG" />
  <meta name="geo.placename" content="Uxbridge, Hayes, Slough" />

  <!-- Open Graph / Social -->
  <meta property="og:site_name" content="Simple Mechanic Ltd" />
  <meta property="og:title" content="Simple Mechanic Ltd | Mobile Mechanic in Uxbridge, Hayes & Slough" />
  <meta property="og:description" content="Mobile mechanic in Uxbridge, Hayes & Slough (England). On-site repairs, servicing and diagnostics. Call or WhatsApp for a fast quote." />
  <meta property="og:type" content="website" />

  <!-- LocalBusiness / AutoRepair schema (edit address later if you want) -->
  <script type="application/ld+json">
  {
    "@context":"https://schema.org",
    "@type":"AutoRepair",
    "name":"Simple Mechanic Ltd",
    "description":"Mobile mechanic offering on-site repairs, servicing and diagnostics in Uxbridge, Hayes and Slough (England).",
    "telephone":"+447474352570",
    "areaServed":[
      {"@type":"City","name":"Uxbridge"},
      {"@type":"City","name":"Hayes"},
      {"@type":"City","name":"Slough"}
    ],
    "address":{
      "@type":"PostalAddress",
      "addressCountry":"GB",
      "addressRegion":"England"
    },
    "openingHoursSpecification":[
      {"@type":"OpeningHoursSpecification","dayOfWeek":["Monday","Tuesday","Wednesday","Thursday","Friday","Saturday","Sunday"],"opens":"08:00","closes":"20:00"}
    ],
    "paymentAccepted":"Cash, Card, Bank Transfer",
    "priceRange":"££"
  }
  </script>

  <style>
    :root{
      --bg:#0b1220; --card:#0f1a33; --muted:#a8b3cf; --text:#e9eeff;
      --accent:#5eead4; --accent2:#60a5fa; --danger:#fb7185;
      --line:rgba(255,255,255,.12); --shadow:0 12px 40px rgba(0,0,0,.35);
      --r:16px; --max:1120px;
      --font: ui-sans-serif,system-ui,-apple-system,Segoe UI,Roboto,Helvetica,Arial;
    }
    *{box-sizing:border-box}
    html{scroll-behavior:smooth}
    body{
      margin:0; font-family:var(--font); color:var(--text);
      background:
        radial-gradient(900px 500px at 15% -10%, rgba(96,165,250,.25), transparent 60%),
        radial-gradient(900px 500px at 90% 10%, rgba(94,234,212,.18), transparent 65%),
        linear-gradient(180deg, var(--bg), #070b14 75%);
    }
    a{color:inherit;text-decoration:none}
    .wrap{max-width:var(--max);margin:0 auto;padding:0 18px}
    .bar{
      position:sticky;top:0;z-index:50;
      backdrop-filter: blur(10px);
      background: rgba(11,18,32,.78);
      border-bottom:1px solid var(--line);
    }
    .nav{display:flex;align-items:center;justify-content:space-between;gap:12px;padding:14px 0}
    .brand{display:flex;gap:10px;align-items:center;font-weight:950;letter-spacing:.2px}
    .logo{
      width:38px;height:38px;border-radius:12px;
      background: linear-gradient(135deg, var(--accent2), var(--accent));
      position:relative; box-shadow:0 10px 28px rgba(96,165,250,.22);
      flex:0 0 auto;
    }
    .logo:after{content:"";position:absolute;inset:10px;border-radius:8px;background:rgba(11,18,32,.86)}
    .links{display:flex;gap:10px;flex-wrap:wrap}
    .links a{color:var(--muted);font-size:14px;padding:8px 10px;border-radius:10px}
    .links a:hover{background:rgba(255,255,255,.06);color:var(--text)}
    .cta{display:flex;gap:10px;flex-wrap:wrap;justify-content:flex-end}
    .btn{
      border:1px solid var(--line);
      background: rgba(255,255,255,.04);
      color:var(--text);
      padding:10px 12px;border-radius:12px;
      font-weight:800;font-size:14px;
      display:inline-flex;align-items:center;gap:8px;
      transition: transform .05s ease, background .15s ease, border-color .15s ease;
    }
    .btn:hover{background:rgba(255,255,255,.07);border-color:rgba(255,255,255,.18)}
    .btn:active{transform:translateY(1px)}
    .btn.primary{border-color:rgba(94,234,212,.35);background:linear-gradient(135deg, rgba(96,165,250,.18), rgba(94,234,212,.14))}
    .btn.danger{border-color:rgba(251,113,133,.35);background:linear-gradient(135deg, rgba(251,113,133,.16), rgba(96,165,250,.10))}
    .card{background: rgba(15,26,51,.74); border:1px solid var(--line); border-radius:var(--r); box-shadow:var(--shadow)}
    .hero{padding:46px 0 18px}
    .grid{display:grid;grid-template-columns:1.15fr .85fr;gap:18px;align-items:stretch}
    @media (max-width: 980px){.grid{grid-template-columns:1fr}.cta{justify-content:flex-start}}
    .heroCard{padding:26px}
    .kicker{color:var(--accent);font-weight:950;letter-spacing:.22em;font-size:12px;text-transform:uppercase;margin-bottom:10px}
    h1{margin:0 0 12px;font-size:42px;line-height:1.08;letter-spacing:-.02em}
    @media (max-width:520px){h1{font-size:34px}}
    .sub{margin:0 0 16px;color:var(--muted);font-size:16px;line-height:1.55}
    .badges{display:flex;flex-wrap:wrap;gap:10px;margin-top:16px}
    .badge{border:1px solid var(--line);background:rgba(255,255,255,.04);padding:8px 10px;border-radius:999px;color:var(--muted);font-size:13px}
    .badge b{color:var(--text)}
    .split{display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-top:14px}
    @media (max-width:520px){.split{grid-template-columns:1fr}}
    .book{padding:22px}
    .book h2{margin:0 0 8px;font-size:18px}
    .hint{margin:0 0 14px;color:var(--muted);font-size:13px}
    form{display:grid;gap:10px}
    .row{display:grid;grid-template-columns:1fr 1fr;gap:10px}
    @media (max-width:520px){.row{grid-template-columns:1fr}}
    label{font-size:12px;color:var(--muted)}
    input,select,textarea{
      width:100%;padding:11px 12px;border-radius:12px;
      border:1px solid var(--line); background: rgba(7,11,20,.55);
      color:var(--text);outline:none
    }
    textarea{min-height:92px;resize:vertical}
    input:focus,select:focus,textarea:focus{
      border-color:rgba(94,234,212,.45);
      box-shadow:0 0 0 4px rgba(94,234,212,.08)
    }
    .hr{height:1px;background:var(--line);margin:16px 0}
    section{padding:18px 0}
    .title{display:flex;align-items:flex-end;justify-content:space-between;gap:14px;flex-wrap:wrap;margin-bottom:12px}
    .title h2{margin:0;font-size:22px}
    .title p{margin:0;color:var(--muted);max-width:780px}
    .g3{display:grid;grid-template-columns:repeat(3,1fr);gap:12px}
    @media (max-width:980px){.g3{grid-template-columns:1fr}}
    .tile{padding:16px}
    .tile h3{margin:6px 0 8px;font-size:16px}
    .tile p{margin:0;color:var(--muted);line-height:1.5;font-size:14px}
    .icon{
      width:36px;height:36px;border-radius:12px;
      background:rgba(96,165,250,.16);border:1px solid rgba(96,165,250,.25);
      display:grid;place-items:center;font-weight:950;color:var(--accent2)
    }
    .pricing{padding:16px;overflow:auto}
    table{width:100%;border-collapse:collapse;min-width:760px}
    th,td{padding:12px;border-bottom:1px solid var(--line);text-align:left;vertical-align:top;font-size:14px}
    th{color:var(--muted);font-weight:950}
    .pill{display:inline-block;padding:5px 9px;border-radius:999px;border:1px solid var(--line);background:rgba(255,255,255,.04);color:var(--muted);font-size:12px;white-space:nowrap}
    .quote{padding:16px}
    .quote p{margin:0;line-height:1.55}
    .quote footer{margin-top:10px;color:var(--muted);font-size:13px}
    details{border:1px solid var(--line);background:rgba(255,255,255,.03);border-radius:14px;padding:12px}
    details+details{margin-top:10px}
    summary{cursor:pointer;font-weight:950;list-style:none}
    summary::-webkit-details-marker{display:none}
    details p{margin:10px 0 0;color:var(--muted);line-height:1.55}
    footer.site{margin-top:18px;border-top:1px solid var(--line);background:rgba(7,11,20,.40)}
    .foot{padding:18px 0;display:grid;grid-template-columns:1.2fr .8fr .8fr;gap:14px}
    @media (max-width:980px){.foot{grid-template-columns:1fr}}
    .small{color:var(--muted);font-size:13px;line-height:1.55}
    .list a{display:block;padding:6px 0;color:var(--muted)}
    .list a:hover{color:var(--text)}
    .copy{padding:12px 0 18px;color:var(--muted);font-size:12px;display:flex;justify-content:space-between;flex-wrap:wrap;gap:10px}
    .stickyActions{
      position:fixed;left:12px;right:12px;bottom:12px;
      max-width:var(--max);margin:0 auto;
      display:flex;gap:10px;z-index:60;
    }
    .stickyActions a{flex:1;justify-content:center}
    .note{border:1px dashed rgba(255,255,255,.22); background:rgba(255,255,255,.03); border-radius:14px; padding:12px; color:var(--muted); font-size:13px; line-height:1.5}
  </style>
</head>

<body>
  <div class="bar">
    <div class="wrap">
      <div class="nav">
        <a class="brand" href="#top"><span class="logo" aria-hidden="true"></span><span>Simple Mechanic Ltd</span></a>
        <nav class="links" aria-label="Primary">
          <a href="#services">Services</a>
          <a href="#pricing">Pricing</a>
          <a href="#areas">Areas</a>
          <a href="#reviews">Reviews</a>
          <a href="#faqs">FAQs</a>
          <a href="#contact">Contact</a>
        </nav>
        <div class="cta">
          <a class="btn danger" href="tel:+447474352570">📞 Call</a>
          <a class="btn primary" href="#booking">⚡ Get a Quote</a>
        </div>
      </div>
    </div>
  </div>

  <main id="top" class="wrap">
    <div class="hero">
      <div class="grid">
        <div class="card heroCard">
          <div class="kicker">MOBILE MECHANIC • ENGLAND</div>
          <h1>Mobile mechanic in <span style="color:var(--accent)">Uxbridge • Hayes • Slough</span> — we come to you.</h1>
          <p class="sub">
            Diagnostics, servicing, brakes, batteries, alternators, starters, suspension and more.
            Transparent quotes, fast response, and warranty-backed labour.
          </p>

          <div class="split">
            <a class="btn primary" href="#booking">✅ Book a Visit</a>
            <a class="btn" href="#services">🔧 View Services</a>
          </div>

          <div class="badges" aria-label="Key benefits">
            <span class="badge">⏱️ <b>Same-day</b> slots</span>
            <span class="badge">💷 <b>Clear</b> quotes</span>
            <span class="badge">🧾 <b>Invoice</b> provided</span>
            <span class="badge">🛡️ <b>Warranty</b> on labour</span>
            <span class="badge">🚐 <b>Fully equipped</b> van</span>
          </div>

          <div class="hr"></div>

          <div class="note">
            <b>Quick contact:</b> Call <b>07474 352570</b> or WhatsApp us with your postcode + vehicle + issue for a fast quote.
          </div>
        </div>

        <aside id="booking" class="card book">
          <h2>Get a quick quote</h2>
          <p class="hint">Fill in the form — we’ll reply with price & availability.</p>

          <form id="quoteForm">
            <div class="row">
              <div>
                <label for="name">Full name</label>
                <input id="name" name="name" placeholder="John Smith" required />
              </div>
              <div>
                <label for="phone">Phone / WhatsApp</label>
                <input id="phone" name="phone" placeholder="+44..." required />
              </div>
            </div>

            <div class="row">
              <div>
                <label for="postcode">Postcode</label>
                <input id="postcode" name="postcode" placeholder="e.g., UB8 1XX" required />
              </div>
              <div>
                <label for="when">Preferred time</label>
                <select id="when" name="when" required>
                  <option value="" disabled selected>Select…</option>
                  <option>Today</option>
                  <option>Tomorrow</option>
                  <option>This week</option>
                  <option>Weekend</option>
                </select>
              </div>
            </div>

            <div class="row">
              <div>
                <label for="vehicle">Vehicle</label>
                <input id="vehicle" name="vehicle" placeholder="BMW 320d 2018" required />
              </div>
              <div>
                <label for="reg">Registration (optional)</label>
                <input id="reg" name="reg" placeholder="AB12 CDE" />
              </div>
            </div>

            <div>
              <label for="issue">What’s the issue?</label>
              <textarea id="issue" name="issue" placeholder="Describe symptoms, warning lights, noises, etc." required></textarea>
            </div>

            <button class="btn primary" type="submit">Send request</button>

            <p class="small" style="margin:10px 0 0">
              Prefer WhatsApp? Tap below — it will open a ready-made message to send.
            </p>

            <div class="split">
              <a class="btn" id="waBtn" href="https://wa.me/447474352570" target="_blank" rel="noopener">💬 WhatsApp</a>
              <a class="btn danger" href="tel:+447474352570">📞 Call now</a>
            </div>

            <p class="small" style="margin:10px 0 0">
              <b>Email form:</b> this opens your email app. Replace <b>hello@example.com</b> with your email in the code when ready.
            </p>
          </form>
        </aside>
      </div>
    </div>

    <section id="services">
      <div class="title">
        <h2>Services</h2>
        <p>Most repairs can be done on your driveway. If a ramp is required, we’ll advise upfront.</p>
      </div>

      <div class="g3">
        <div class="card tile"><div class="icon">🧠</div><h3>Diagnostics & fault finding</h3><p>OBD scan, live data, practical checks, clear explanation and next steps.</p></div>
        <div class="card tile"><div class="icon">🛢️</div><h3>Servicing</h3><p>Interim / full service, oil & filter, air/cabin filters, spark plugs, fluids.</p></div>
        <div class="card tile"><div class="icon">🛑</div><h3>Brakes</h3><p>Discs & pads, calipers, brake fluid, inspections for noise/vibration.</p></div>
        <div class="card tile"><div class="icon">🔋</div><h3>Batteries</h3><p>Battery testing & replacement, start/stop support where required.</p></div>
        <div class="card tile"><div class="icon">⚡</div><h3>Starter & alternator</h3><p>Charging system tests, replacements, belt and pulley checks.</p></div>
        <div class="card tile"><div class="icon">🚗</div><h3>Suspension & steering</h3><p>Drop links, arms, ball joints, track rod ends, knocking/noise fixes.</p></div>
        <div class="card tile"><div class="icon">🌡️</div><h3>Cooling system</h3><p>Leaks, hoses, thermostats, coolant flush (where suitable).</p></div>
        <div class="card tile"><div class="icon">💡</div><h3>Electrical</h3><p>Bulbs, sensors, fuses/relays, battery drain tests.</p></div>
        <div class="card tile"><div class="icon">✅</div><h3>Pre-purchase inspection</h3><p>On-site check before you buy: scan + road test + report.</p></div>
      </div>
    </section>

    <section id="pricing">
      <div class="title">
        <h2>Pricing</h2>
        <p>Transparent “from” prices. Final quote depends on vehicle, access and parts required.</p>
      </div>

      <div class="card pricing" role="region" aria-label="Pricing table">
        <table>
          <thead>
            <tr><th>Service</th><th>From</th><th>Includes</th><th>Typical time</th></tr>
          </thead>
          <tbody>
            <tr><td>Diagnostics</td><td>£49</td><td>Scan + basic checks + advice (repair extra)</td><td><span class="pill">30–60 mins</span></td></tr>
            <tr><td>Interim service</td><td>£119</td><td>Oil + filter + checks (parts/grade vary)</td><td><span class="pill">60–90 mins</span></td></tr>
            <tr><td>Full service</td><td>£179</td><td>Oil + filters + inspections</td><td><span class="pill">90–120 mins</span></td></tr>
            <tr><td>Front brake pads (labour)</td><td>£89</td><td>Labour only (pads/discs extra)</td><td><span class="pill">60–90 mins</span></td></tr>
            <tr><td>Battery replacement (labour)</td><td>£39</td><td>Labour + testing (battery extra)</td><td><span class="pill">30–45 mins</span></td></tr>
            <tr><td>Pre-purchase inspection</td><td>£129</td><td>Scan + road test + summary</td><td><span class="pill">60–90 mins</span></td></tr>
          </tbody>
        </table>
      </div>

      <p class="small" style="margin-top:10px">
        <b>No surprises:</b> we confirm the final price before starting work. Invoice provided.
      </p>
    </section>

    <section id="areas">
      <div class="title">
        <h2>Areas covered (England)</h2>
        <p>We cover Uxbridge, Hayes and Slough, plus nearby postcodes. If you’re slightly outside, ask anyway.</p>
      </div>

      <div class="g3">
        <div class="card tile"><div class="icon">📍</div><h3>Uxbridge</h3><p>UB postcodes and nearby areas.</p></div>
        <div class="card tile"><div class="icon">📍</div><h3>Hayes</h3><p>UB3 and surrounding neighbourhoods.</p></div>
        <div class="card tile"><div class="icon">📍</div><h3>Slough</h3><p>SL postcodes and nearby areas.</p></div>
      </div>
    </section>

    <section id="reviews">
      <div class="title">
        <h2>Reviews</h2>
        <p>Add your real Google/Facebook reviews when ready.</p>
      </div>

      <div class="g3">
        <div class="card quote">
          <p>“Quick diagnosis, explained everything clearly and fixed it the same day.”</p>
          <footer>— Local customer</footer>
        </div>
        <div class="card quote">
          <p>“Fair price, on time, and very professional. Will use again.”</p>
          <footer>— Workplace visit</footer>
        </div>
        <div class="card quote">
          <p>“Saved me towing costs. Great communication via WhatsApp.”</p>
          <footer>— Emergency call-out</footer>
        </div>
      </div>
    </section>

    <section id="faqs">
      <div class="title">
        <h2>FAQs</h2>
        <p>Common questions about mobile repairs, parts, and warranty.</p>
      </div>

      <details><summary>Do you supply parts?</summary><p>Yes. We can quote OEM or quality aftermarket parts. If you supply your own parts, labour-only warranty may apply.</p></details>
      <details><summary>How do I pay?</summary><p>Cash, card, or bank transfer. Payment is usually after completion (or after parts confirmation for bigger jobs).</p></details>
      <details><summary>Can you do every job mobile?</summary><p>Many repairs are possible at your home. Some jobs need a ramp or special equipment — we’ll tell you upfront.</p></details>
      <details><summary>Is your work guaranteed?</summary><p>Labour warranty is included. Parts warranty depends on supplier terms and correct fitment/usage.</p></details>
    </section>

    <section id="contact">
      <div class="title">
        <h2>Contact</h2>
        <p>Fastest response: call or WhatsApp. Serving Uxbridge, Hayes & Slough (England).</p>
      </div>

      <div class="g3">
        <div class="card tile">
          <div class="icon">📞</div>
          <h3>Phone</h3>
          <p><a class="btn danger" href="tel:+447474352570" style="margin-top:10px">Call 07474 352570</a></p>
        </div>
        <div class="card tile">
          <div class="icon">💬</div>
          <h3>WhatsApp</h3>
          <p><a class="btn primary" href="https://wa.me/447474352570" target="_blank" rel="noopener" style="margin-top:10px">Message on WhatsApp</a></p>
        </div>
        <div class="card tile">
          <div class="icon">⏰</div>
          <h3>Hours</h3>
          <p>Mon–Sun 08:00–20:00<br><span class="small">Same-day slots subject to availability.</span></p>
        </div>
      </div>
    </section>
  </main>

  <footer class="site">
    <div class="wrap">
      <div class="foot">
        <div>
          <div class="brand" style="margin-bottom:8px"><span class="logo" aria-hidden="true"></span><span>Simple Mechanic Ltd</span></div>
          <p class="small">Mobile mechanic in England — Uxbridge, Hayes & Slough. Transparent quotes • Fast response.</p>
          <p class="small"><b>Phone:</b> +44 7474 352570 • <b>WhatsApp:</b> +44 7474 352570</p>
          <p class="small"><b>Email form:</b> currently set to <b>hello@example.com</b> (change it in the script below).</p>
        </div>

        <div class="list">
          <b style="display:block;margin-bottom:6px">Pages</b>
          <a href="#services">Services</a>
          <a href="#pricing">Pricing</a>
          <a href="#areas">Areas</a>
          <a href="#faqs">FAQs</a>
          <a href="#contact">Contact</a>
        </div>

        <div class="list">
          <b style="display:block;margin-bottom:6px">Quick actions</b>
          <a href="tel:+447474352570">Call now</a>
          <a href="https://wa.me/447474352570" target="_blank" rel="noopener">WhatsApp</a>
        </div>
      </div>

      <div class="copy">
        <span>© <span id="y"></span> Simple Mechanic Ltd. All rights reserved.</span>
        <span>Mobile-first • Local SEO ready</span>
      </div>
    </div>
  </footer>

  <!-- Sticky bottom buttons (mobile-friendly) -->
  <div class="stickyActions" aria-label="Quick contact buttons">
    <a class="btn danger" href="tel:+447474352570">📞 Call</a>
    <a class="btn primary" id="waSticky" href="https://wa.me/447474352570" target="_blank" rel="noopener">💬 WhatsApp</a>
  </div>

  <script>
    document.getElementById("y").textContent = new Date().getFullYear();

    // WhatsApp: build a ready-made message from the form fields (professional + fast).
    function buildWhatsAppMessage(data){
      return `Hello Simple Mechanic Ltd,%0A%0A` +
        `I’d like a quote/booking:%0A` +
        `Name: ${encodeURIComponent(data.name)}%0A` +
        `Phone: ${encodeURIComponent(data.phone)}%0A` +
        `Postcode: ${encodeURIComponent(data.postcode)}%0A` +
        `Preferred time: ${encodeURIComponent(data.when)}%0A` +
        `Vehicle: ${encodeURIComponent(data.vehicle)}%0A` +
        `Reg: ${encodeURIComponent(data.reg || "-")}%0A` +
        `Issue: ${encodeURIComponent(data.issue)}%0A%0A` +
        `Thanks.`;
    }

    const form = document.getElementById("quoteForm");
    const waBtn = document.getElementById("waBtn");
    const waSticky = document.getElementById("waSticky");

    form.addEventListener("submit", (e) => {
      e.preventDefault();
      const data = Object.fromEntries(new FormData(form).entries());

      // 1) Open email app (works instantly on iPhone) — change this email when you have it:
      const email = "hello@example.com"; // <-- PUT YOUR EMAIL HERE
      const subject = encodeURIComponent("Quote Request - Simple Mechanic Ltd");
      const body = encodeURIComponent(
        `New quote request (Simple Mechanic Ltd)\n` +
        `Name: ${data.name}\nPhone/WhatsApp: ${data.phone}\nPostcode: ${data.postcode}\n` +
        `Preferred time: ${data.when}\nVehicle: ${data.vehicle}\nReg: ${data.reg || "-"}\n` +
        `Issue: ${data.issue}\n`
      );
      window.location.href = `mailto:${email}?subject=${subject}&body=${body}`;
    });

    // Update WhatsApp links live as the user types, so message is ready.
    function refreshWhatsAppLinks(){
      const data = Object.fromEntries(new FormData(form).entries());
      const text = buildWhatsAppMessage({
        name: data.name || "",
        phone: data.phone || "",
        postcode: data.postcode || "",
        when: data.when || "",
        vehicle: data.vehicle || "",
        reg: data.reg || "",
        issue: data.issue || ""
      });
      const url = `https://wa.me/447474352570?text=${text}`;
      waBtn.href = url;
      waSticky.href = url;
    }
    ["input","change"].forEach(evt => form.addEventListener(evt, refreshWhatsAppLinks));
    refreshWhatsAppLinks();
  </script>
</body>
</html>