<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>AI Tools Hub</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>AI Tools Hub</h1>
    <p>Free Online AI Tools</p>
  </header>

  <section class="tools">
    <div class="card">
      <h2>AI Text Generator</h2>
      <p>Generate content instantly.</p>
      <button onclick="alert('Demo Only')">Use Tool</button>
    </div>

    <div class="card">
      <h2>AI Image Generator</h2>
      <p>Create HD images with prompts.</p>
      <button onclick="alert('Demo Only')">Use Tool</button>
    </div>

    <div class="card">
      <h2>AI Voice Generator</h2>
      <p>Convert text to natural voice.</p>
      <button onclick="alert('Demo Only')">Use Tool</button>
    </div>
  </section>

  <footer>
    <p>© 2025 AI Tools Hub</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>

style css
body {
  font-family: Arial;
  margin: 0;
  padding: 0;
  background: #f2f2f2;
}

header {
  background: #4a4aff;
  color: #fff;
  padding: 20px;
  text-align: center;
}

.tools {
  display: flex;
  gap: 20px;
  padding: 20px;
  justify-content: center;
  flex-wrap: wrap;
}

.card {
  background: #fff;
  padding: 20px;
  width: 260px;
  border-radius: 10px;
  box-shadow: 0 0 10px #0002;
}

button {
  padding: 10px 15px;
  border: none;
  background: #4a4aff;
  color: white;
  border-radius: 6px;
  cursor: pointer;
}

footer {
  text-align: center;
  padding: 20px;
  background: #ddd;
}
console.log("AI Tools Hub Loaded");
