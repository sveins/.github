<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Collage — Fredrik, Ola & Ulf</title>
  <style>
    :root{--bg:#f6f7f9;--card:#fff;--accent:#0f1724}
    html,body{height:100%;margin:0;font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,'Helvetica Neue',Arial}
    body{background:var(--bg);display:flex;align-items:center;justify-content:center;padding:40px}
    .wrap{max-width:1100px;width:100%;}
    h1{text-align:center;color:var(--accent);margin:0 0 24px;font-size:20px}
    .grid{display:grid;gap:18px;grid-template-columns:repeat(3,1fr)}
    .card{background:linear-gradient(180deg, rgba(255,255,255,0.9), rgba(250,250,250,0.95));border-radius:12px;overflow:hidden;box-shadow:0 6px 24px rgba(16,24,40,0.08);display:flex;flex-direction:column}
    .card img{width:100%;height:320px;object-fit:cover;display:block;transition:transform .45s cubic-bezier(.2,.9,.2,1)}
    .card:hover img{transform:scale(1.04)}
    .caption{padding:14px 16px;font-weight:600;color:#111;background:transparent}
    .sub{padding:0 16px 16px 16px;color:#546179;font-size:13px}
    @media (max-width:900px){.grid{grid-template-columns:repeat(2,1fr)}.card img{height:260px}}
    @media (max-width:560px){.grid{grid-template-columns:1fr}.card img{height:220px}}
  </style>
</head>
<body>
  <div class="wrap">
    <h1>Collage — Fredrik Larsson · Ola Ericson · Ulf Grunbaum</h1>
    <div class="grid">
      <figure class="card">
        <img src="assets/fredrik_larsson-northern_lights-9656.jpg" alt="Fredrik Larsson"/>
        <figcaption class="caption">Fredrik Larsson</figcaption>
        <div class="sub">Photographer / Contributor</div>
      </figure>

      <figure class="card">
        <img src="assets/ola_ericson-skeppsbron_-1093.jpg" alt="Ola Ericson"/>
        <figcaption class="caption">Ola Ericson</figcaption>
        <div class="sub">Photographer / Contributor</div>
      </figure>

      <figure class="card">
        <img src="assets/ulf_gr%C3%BCnbaum-swedish_parliament_building-7623%20%283%29.jpg" alt="Ulf Grunbaum"/>
        <figcaption class="caption">Ulf Grunbaum</figcaption>
        <div class="sub">Photographer / Contributor</div>
      </figure>
    </div>
  </div>
</body>
</html>

<p align="center">
	<a href="https://github.com/sveins">
		<img src="https://img.shields.io/badge/GitHub-SI-363a4f?style=for-the-badge&logo=github" alt="SI GitHub" />
	</a>
</p>


## Index

- Official site: https://sweden.se
