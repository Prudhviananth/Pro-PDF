# Pro-PDF
Pdf editor 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>PDF Pro+</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>PDF Pro+</h1>
    <p>Edit PDFs and Create Resumes for Free</p>
  </header>

  <main>
    <!-- PDF Editor Section -->
    <section id="pdf-editor">
      <h2>PDF Editor</h2>
      <div class="tools">
        <button id="upload-pdf">Upload PDF</button>
        <button id="merge-pdf">Merge PDFs</button>
        <button id="split-pdf">Split PDF</button>
        <button id="add-text">Add Text</button>
        <button id="add-image">Add Image</button>
        <button id="download-pdf">Download PDF</button>
      </div>
      <div class="pdf-preview">
        <iframe id="pdf-preview-frame" src="" width="100%" height="500px"></iframe>
      </div>
    </section>

    <!-- Resume Builder Section -->
    <section id="resume-builder">
      <h2>Resume Builder</h2>
      <div class="resume-form">
        <label for="name">Full Name:</label>
        <input type="text" id="name" placeholder="Enter your name">

        <label for="email">Email:</label>
        <input type="email" id="email" placeholder="Enter your email">

        <label for="skills">Skills:</label>
        <textarea id="skills" placeholder="List your skills"></textarea>

        <label for="experience">Experience:</label>
        <textarea id="experience" placeholder="Describe your experience"></textarea>

        <button id="generate-resume">Generate Resume</button>
      </div>
      <div class="resume-preview">
        <iframe id="resume-preview-frame" src="" width="100%" height="500px"></iframe>
      </div>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 PDF Pro+. All rights reserved.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>