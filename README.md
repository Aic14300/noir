


```html
<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Felicia Ann Kelley - People Card</title>

<style>
  :root {
    --bg-light: #ffffff;
    --text-dark: #0b1020;
    --muted: #667085;
    --border-color: #e6eef8;
    --primary-color: #00d1ff; /* Accent color */
    --code-bg: #f6f8fb;
  }

  body {
    margin: 0;
    font-family: Inter, Arial, sans-serif;
    background: var(--bg-light);
    color: var(--text-dark);
    line-height: 1.6;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    padding: 20px;
    box-sizing: border-box;
  }

  .people-card {
    background: #ffffff;
    border: 1px solid var(--border-color);
    border-radius: 12px;
    padding: 30px;
    max-width: 600px;
    width: 100%;
    box-shadow: 0 8px 24px rgba(16,24,40,0.08);
    text-align: center;
  }

  .people-card h1 {
    font-size: 32px;
    color: var(--text-dark);
    margin-bottom: 10px;
  }

  .people-card .role {
    font-size: 18px;
    color: var(--muted);
    margin-bottom: 25px;
  }

  .people-card h2 {
    font-size: 20px;
    color: var(--primary-color);
    margin-top: 30px;
    margin-bottom: 15px;
    border-bottom: 1px solid var(--border-color);
    padding-bottom: 10px;
  }

  .people-card p {
    font-size: 15px;
    color: var(--text-dark);
    margin-bottom: 10px;
    text-align: left;
  }

  .people-card code {
    background: var(--code-bg);
    padding: 6px 10px;
    border-radius: 6px;
    font-family: monospace;
    font-size: 14px;
    color: var(--text-dark);
    word-break: break-all;
    display: inline-block; /* Allow wrapping */
    text-align: left;
  }

  .project-item {
    margin-bottom: 15px;
    text-align: left;
  }

  .project-item strong {
    color: var(--text-dark);
  }

  footer {
    margin-top: 40px;
    color: var(--muted);
    font-size: 13px;
  }
</style>
</head>
<body>

<div class="people-card">
  <h1>Felicia Ann Kelley</h1>
  <p class="role">Designer & Cryptographic Map Creator</p>

  <h2>Research & Contributions</h2>

  <div class="project-item">
    <p><strong>Project:</strong> Complete Cryptographic Chain — Visual Overview</p>
    <p><strong>Description:</strong> Designed and created a visual map detailing a cryptographic chain with 70 nodes and a block height of 65535.</p>
    <p><strong>Key Artifacts:</strong></p>
    <ul>
      <li><p><strong>Genesis Key:</strong> <code>b6f6991d02d64f9f7f8b5d3c6c30f8b8e5f5d5f1e2c3c31d03c4f1cde9d9c5f1</code></p></li>
      <li><p><strong>Cryptographic Hashes (Examples from Extension nodes):</strong></p>
        <ul>
          <li><strong>OPP SHA-256:</strong> <code>e3690f12a3b4c5d6e7f8091234567890abcdef0123456789abcdef0123456789</code></li>
          <li><strong>IOU SHA-256:</strong> <code>f47a1b2c3d4e5f60718293a4b5c6d7e8f90123a4b5c6d7e8f90123456789abcd</code></li>
          <li><strong>QRST SHA-256:</strong> <code>0123456789abcdef0123456789abcdefabcdef0123456789abcdef0123456789</code></li>
        </ul>
      </li>
    </ul>
  </div>

  <footer>
    This card compiles information from the provided "Cryptographic Chain Overview" HTML.
  </footer>
</div>

</body>
</html>
```
