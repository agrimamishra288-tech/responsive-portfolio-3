# Responsive-portfolio-3
#Agrima Mishra
#roll no:2501010207
#Lab title: Responsive Personal Portfolio Website (CSS Advanced)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Description:

A one-page responsive personal portfolio built using HTML and advanced CSS only. The site demonstrates Flexbox for header and hero layout, CSS Grid/flex for skills and projects, responsive media queries (mobile-first), relative units, hover effects, keyframe animation, transforms, and polished card shadows/interaction. The design includes a hero section with animated subtitle, skills “pills”, full-width project cards, a contact form card, sticky header with navigation (including GitHub & LinkedIn links), and a CSS-only back-to-top button.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## How to view the site 

## Option A — Open locally (file)

Place index.html, style.css, and your image in the same folder.

Double-click index.html (or right-click → Open with → your browser).

Note: Some browser features (file security) work differently when opened via file://. If animations or anchors behave oddly, use a local server (below).

## Option B — Run a simple local server 

From the project folder run either:

# Python 3

# macOS / Linux / Windows (PowerShell)

python -m http.server 5500

# then open http://localhost:5500 in your browser

or

# VS Code Live Server extension

Install Live Server and click Go Live (recommended for fast refresh while editing).

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


## Navigation

Use the top navigation to jump to sections (About, Skills, Projects, Contact) or use the back-to-top button in the bottom-right.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


## Steps to view responsive behavior (how to test):


Open the site in your browser and use one of the following:


Resize the browser window manually.


Open Developer Tools (F12) → Toggle device toolbar (mobile emulator) to quickly switch device sizes.


Use the following breakpoints that were designed & tested:


Breakpoints tested


320–639px — small/mobile (single-column layout; hero stacks vertically; portrait becomes smaller; skills stack/wrap).


640–899px — large mobile / small tablet (two-column elements begin to space; pills may wrap to multiple rows).


900–999px — tablet / small desktop (hero becomes side-by-side with image on right; fonts scale up).


1000–1099px — desktop (wider content width and increased image sizes).


1100px+ — large desktop (maximum layout width, large heading sizes, skills stretch into multiple columns, projects display full-width cards).

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Test steps


Start server (or open index.html).


Resize window (or use DevTools device emulator) to each breakpoint listed above.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


## Verify:


Hero text and portrait: stacked on mobile, side-by-side on desktop.


Skills: pills wrap on small screens, stretch across row on larger screens.


Projects: stacked and full-width with centered text.


Contact form: centered and responsive (card scales down on small screens).


Hover effects on skills, project cards and send button.


Hero subtitle animation is running (color pulse).


“Back to Top” button is visible and anchors to top.


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Features implemented:


 Flexbox header + hero layout


 CSS Grid / flexible layout for skills & projects (mobile-first)


 Animated hero subtitle (keyframes)


 Hover effects & smooth transitions on pills, cards, buttons


 Multi-layered card shadows for premium UI look


 Contact form card (centered, animated)


 CSS-only Back-to-Top anchor (fixed)


 Responsive at the breakpoints listed above


 External, internal and inline CSS examples included (per lab requirements)


 Navigation contains links to GitHub and LinkedIn (open in new tab)

 
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Notes for grading / instructor


This submission uses only HTML + CSS (no JavaScript)


The CSS is modular and uses variables for easy theme edits.


The hero subtitle animation and other visual effects are implemented with @keyframes and transition.


Accessibility considerations: semantic HTML (header, main, section, nav, footer), alt text on images, focus outlines preserved.


The assignment brief used for requirements is included at /mnt/data/Lab 3.docx.


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Troubleshooting


If fonts look different, ensure internet connection (Google Fonts are loaded via @import).


If the contact card or pills don’t center properly, clear browser cache or test via a local server as suggested.


If images do not show, confirm the image filename matches the src in index.html.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Conclusion

This lab helped me apply advanced CSS concepts to build a responsive portfolio webpage that works well on all screen sizes. I used Flexbox, custom animations, media queries, and modern UI styling to create a clean and interactive design. The final webpage includes a hero section, skills, projects, and a contact form—all properly aligned and styled.

By completing this assignment, I gained practical experience with responsive design and learned how to enhance a webpage using animations, transitions, and well-structured layouts. This project shows how HTML and CSS can be combined to create a polished and visually appealing website without using any JavaScript. It also prepares me for upcoming labs and more advanced web development work.
