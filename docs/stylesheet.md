<!-- simple-header.html -->
<!doctype html>
<html lang="id">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Contoh Header Sederhana</title>
<style>
  /* RESET SEDERHANA */
  * { box-sizing: border-box; margin: 0; padding: 0; }

  /* STYLES HEADER */
  header {
    background: linear-gradient(90deg,#0b6fa8,#0b9bd6);
    color: #fff;
    padding: 18px 24px;
    text-align: center;
    font-family: "Segoe UI", Roboto, Arial, sans-serif;
    box-shadow: 0 2px 6px rgba(0,0,0,0.12);
  }

  header .brand {
    font-size: 1.25rem;
    font-weight: 700;
    letter-spacing: 0.4px;
  }

  header .subtitle {
    display: block;
    font-size: 0.85rem;
    opacity: 0.9;
    margin-top: 4px;
    font-weight: 500;
  }
</style>
</head>
<body>
  <header>
    <div class="brand">Nama Situs<span class="subtitle">Tagline / Deskripsi singkat</span></div>
  </header>

  <main style="padding:24px;">
    <p>Konten halaman di sini...</p>
  </main>
</body>
</html>


This constant will always be a round number of pixels (so a line defined by it can look crisp) and will try to match the standard width of a thin line on the underlying platform. However, you should not rely on it being a constant size, because on different platforms and screen densities its value may be calculated differently.

A line with hairline width may not be visible if your simulator is downscaled.
