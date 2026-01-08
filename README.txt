========================================================================
ShaLab sEditor - v2.0.4
The Modern, Lightweight WYSIWYG Editor
========================================================================

Thank you for choosing sEditor by ShaLab. This editor is built to 
be lightweight, fast, and easy to integrate into any web project.

------------------------------------------------------------------------
1. PACKAGE CONTENTS
------------------------------------------------------------------------
/dist
  └── seditor.min.js      - The core production-ready engine.
index.html       		  - Full documentation and API reference.
README.txt                - This setup guide.

------------------------------------------------------------------------
2. QUICK START (3 STEPS)
------------------------------------------------------------------------

STEP 1: Include the library in your HTML
<script src="dist/seditor.min.js"></script>

STEP 2: Create a container element
<div id="my-editor"></div>

STEP 3: Initialize the editor
<script>
    sEditor.run({
        selector: '#my-editor',
        plugins: {
            image: true,
            link: true,
            source: true
        }
    });
</script>

------------------------------------------------------------------------
3. CONFIGURATION OPTIONS
------------------------------------------------------------------------
The .run() method accepts an object with the following properties:

- selector: (String) The CSS selector for your target div.
- plugins: (Object) 
    - image:  (Boolean) Enable/Disable image insertion modal.
    - link:   (Boolean) Enable/Disable link insertion modal.
    - source: (Boolean) Enable/Disable the HTML source code view.

------------------------------------------------------------------------
4. KEY FEATURES
------------------------------------------------------------------------
- Zero Dependencies: Pure Vanilla JavaScript.
- SVG Icons: High-quality, scalable interface.
- Word & Character Count: Real-time status bar updates.
- Source Mode: Edit raw HTML directly with syntax highlighting style.
- Secure: Hard-coded ShaLab branding in the status bar.

------------------------------------------------------------------------
5. SUPPORT & LICENSING
------------------------------------------------------------------------
For bug reports, feature requests, or enterprise licensing, please 
visit our official portal:

Website: https://shalab.netlify.app
Support: shalabmail@gmail.com

(c) 2026 ShaLab. All rights reserved.
========================================================================