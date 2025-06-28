PDFMaster.fun is a web-based tool that allows users to view, annotate, and manage PDF files directly in their browser. It integrates seamlessly with GitHub Pages, making deployment and hosting straightforward.

🚀 Features
Upload & View PDFs: Drag-and-drop or select a PDF to view instantly in the browser.

Annotate & Highlight: Add comments, highlights, and notes.

Download Modified PDFs: Save your annotations back to a PDF.

Clean UI: Minimalist, intuitive interface—works on desktop and mobile.

🛠️ How It Works
Built using HTML, CSS, and JavaScript.

Utilizes PDF.js for PDF rendering.

Annotation features implemented using HTML canvas overlays on PDF pages.

Allows downloading of annotated PDFs via canvas.toBlob() and jsPDF.

📁 Repository Structure
bash
Copy
Edit
/
├─ index.html         # Main user interface
├─ css/
│   └─ styles.css     # Styling for the UI
├─ js/
│   ├─ pdf.js         # PDF.js rendering library
│   ├─ app.js         # Core annotation/download logic
│   └─ utils.js       # Helper functions
├─ assets/            # Icons and visual assets
└─ README.md          # You are here!


🔗 Additional Link
We also refere https://iacsccenter.blogspot.com/ used this website
