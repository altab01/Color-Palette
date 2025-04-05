<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Color Palette Generator</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <header>
    <h1>🎨 Color Palette Generator</h1>
    <p>Upload an image and get the dominant and complementary color palette</p>
  </header>

  <main>
    <section class="upload-section">
      <input type="file" id="imageUpload" accept="image/*" />
      <canvas id="imageCanvas" style="display:none;"></canvas>
    </section>

    <section class="image-preview">
      <h2>Uploaded Image</h2>
      <img id="uploadedImage" alt="Uploaded Preview" />
    </section>

    <section class="palette-section">
      <h2>Main Color Palette</h2>
      <div id="mainPalette" class="palette-container"></div>
      
      <h2>Complementary Colors</h2>
      <div id="complementaryPalette" class="palette-container"></div>
    </section>
  </main>

  <footer>
    <p>Built with ❤️ using HTML, CSS & JavaScript</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
