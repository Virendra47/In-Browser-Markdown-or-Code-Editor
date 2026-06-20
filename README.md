📝 Markdown & Code Editor
A powerful, browser-based dual-pane Markdown/HTML/CSS editor with real-time preview, dark/light theme toggle, and interactive JavaScript support.

✨ Features
Core Features
Dual-Pane Layout - Write on the left, preview on the right
Real-Time Preview - Updates instantly as you type
Dark/Light Theme Toggle - Switch themes with a click
Syntax Highlighting - Beautiful code highlighting for multiple languages
Responsive Design - Works on desktop and mobile devices
Supported Content
✅ Markdown - Headers, lists, tables, links, images, blockquotes
✅ HTML - Divs, spans, buttons, inputs, forms
✅ CSS - Inline styles, gradients, animations
✅ JavaScript - Interactive elements (counters, timers, to-do lists)
Interactive Demos
🖱️ Click Counter - Track button clicks
🎨 Color Changer - Change colors with buttons
📝 Greeting Input - Type your name for a personalized message
⏱️ Timer - Start, stop, and reset timer

✅ To-Do List - Add, complete, and delete tasks

🛠️ Technologies Used
Technology	Purpose
HTML5	Structure
CSS3	Styling, animations, responsive design
JavaScript (ES6)	Interactivity, logic
Marked.js	Markdown to HTML conversion
DOMPurify	HTML sanitization for security
Highlight.js	Code syntax highlighting
📦 Installation
Option 1: Clone the Repository
bash
git clone https://github.com/yourusername/markdown-editor.git
cd markdown-editor
Option 2: Download ZIP
Click the green "Code" button
Select "Download ZIP"
Extract the files
Open index.html in your browser

🎯 How to Use
Open index.html in any modern browser
Write content in the left panel using Markdown or HTML
See the preview update in real-time on the right
Toggle themes using the sun/moon switch
Try the interactive demos included in the default content

Example Markdown
markdown
# Heading 1
## Heading 2

**Bold text** and *italic text*

- List item 1
- List item 2

Example HTML
html
<div style="background: linear-gradient(135deg, #6C76E8, #76DAB2); padding: 20px; border-radius: 12px; color: white;">
  <h3>Styled Box</h3>
  <p>HTML with inline CSS</p>
</div>
📁 Project Structure
text
markdown-editor/
├── index.html          # Main application file
├── README.md           # Project documentation
└── LICENSE             # MIT License
🔒 Security Features
DOMPurify - Sanitizes HTML to prevent XSS attacks
No external scripts - All processing happens in your browser
Safe evaluation - Uses Function() instead of eval() for calculations

🎨 Customization
Changing the Theme Colors
Edit the CSS variables in the :root section:

css
:root {
  --bg-main: #f6f8fa;
  --bg-panel: #ffffff;
  --text: #1f2328;
  --accent: #6C76E8;
}
Adding Your Own Footer
Modify the footer section in index.html:

html
<footer class="app-footer">
  <p>
    Made with ❤️ by <span class="name">Your Name</span>
    <span class="year">© 2026</span>
  </p>
</footer>
📱 Responsive Design
Desktop - Full dual-pane layout
Tablet - Stacked panes with scroll
Mobile - Optimized touch interface

🤝 Contributing
Contributions are welcome! Here's how:

Fork the repository

Create your feature branch: git checkout -b feature/AmazingFeature
Commit your changes: git commit -m 'Add AmazingFeature'
Push to the branch: git push origin feature/AmazingFeature
Open a Pull Request

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

👨‍💻 Author
Virendra
Made with ❤️ and JavaScript

🙏 Acknowledgments
Marked.js - Markdown parser

DOMPurify - HTML sanitizer

Highlight.js - Syntax highlighting

🎯 Roadmap
Export to PDF
Auto-save to localStorage
Multiple file tabs
Drag-and-drop images
Keyboard shortcuts
Full-screen mode
Word/character counter
💬 Support
For support, email virendrapandule7070@gmail.com or create an issue on GitHub.
⭐ Star this repo if you found it useful!
