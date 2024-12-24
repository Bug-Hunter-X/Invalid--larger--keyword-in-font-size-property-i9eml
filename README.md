# Invalid 'larger' keyword in CSS font-size

This repository demonstrates an uncommon CSS error involving the misuse of the `larger` keyword within the `font-size` property. The `larger` keyword is intended for relative sizing, not as a standalone font size value.  This can lead to unexpected behavior where the font size remains unchanged or defaults to the browser's default settings.

The `bug.css` file contains the erroneous code. The `bugSolution.css` file shows the corrected version, using valid font size units (like `em`, `rem`, `px`, etc.).