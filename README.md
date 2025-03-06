# Care Plan Pre-Assessment

This repository contains a **single-file** HTML solution for a **multi-step care plan form**. Staff can:

1. Fill out resident data across multiple steps (Next/Previous).
2. Generate a summary of inputs.
3. Download a **styled PDF** with a header bar and bold section headings.

## How to Use

- **Clone or Download** the repository.
- Open **index.html** in your web browser.
- Fill in each step, then click **Next** to proceed.
- Once you reach the final step (Staff Sign-Off), click:
  - **Generate Summary** to preview text in the summary box.
  - **Download PDF** to save a formatted PDF with a teal header.

## Technologies

- Pure HTML/CSS/JS in a single file.
- [jsPDF](https://github.com/parallax/jsPDF) (loaded from a CDN) for PDF generation.

## Customization

- Adjust colours, fonts, or layout within the `<style>` tags in **index.html**.
- Modify the PDF generation code (in `<script>`) for advanced styling or logos.

## License

(Mention any license here, e.g. MIT or your preferred license.)
