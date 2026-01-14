sEditor.js - Lightweight WYSIWYG Editor
Version: 3.0.0
Author: ShaLab
URL: https://shalab.netlify.app/

OVERVIEW
sEditor is a standalone, pure JavaScript rich text editor. It is designed to be 
lightweight, featuring zero dependencies and built-in SVG icons.

KEY FEATURES
- Rich Text Formatting (Bold, Italic, Lists, etc.)
- Dark Mode & Fullscreen Support
- Image and Link Modals with advanced attributes
- Live Word and Character count
- HTML Source Code view

INSTALLATION
1. Include sEditor.js in your HTML file.
2. Create a <div> with a specific ID.
3. Initialize using: const editor = new sEditor(); editor.run({selector: '#id'});

METHODS
- getContent(): Returns the editor's HTML.
- setContent(html): Injects HTML into the editor.
- toggleDarkMode(): Switches themes.

LICENSE
Copyright (c) 2026 ShaLab.