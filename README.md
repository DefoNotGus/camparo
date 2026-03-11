# camparo

A simple, lightweight web application that allows you to compare two pieces of code to easily spot the differences, similar to resolving a Git conflict.

What it does

Side-by-Side Comparison: Paste your original code on the left and your modified code on the right to see exactly what changed.

Multiple Languages: Supports syntax highlighting [coloring the text to make code easier to read] for JavaScript, Python, Java, C#, YAML, Markdown, HTML, CSS, JSON, C++, and SQL.

View Toggle: Switch between a side-by-side view and an inline view [showing changes in a single combined text block] with a simple toggle switch.

How it is built

This project is built to be entirely self-contained and requires no build tools or package managers (like npm).

HTML/CSS: Structure and layout.

Tailwind CSS (via CDN): Used for quick, modern styling.

Vue 3 (via CDN): Handles the application state [managing the data and updating the screen] without needing a complex setup.

Monaco Editor: The code editor engine (the same one used in Visual Studio Code) that powers the Git-style diff view.

How to use

Download or copy the index.html file.

Open it directly in any web browser.

Alternatively, host it on any basic static web server (like Coolify's Static Site option). No build steps are required.
