Predator

A single-page character website with a dark, mafia-inspired look. A full-screen background image sits under a black gradient, with cursive title text on top and four buttons that open pop-up boxes with details about the character.

Status: Work in progress. The layout and styling work, but the content is still being written.

Features
Full-screen hero section with a background image and a dark gradient overlay
Cursive title and button text (Great Vibes) with Cinzel for body text
Four buttons on the left side of the screen, stacked from bottom to top:
About
His Family
His Personality
What I Like About Him
Clicking a button opens a pop-up box over the page, so nothing on the screen shifts
The pop-up closes with the × button, by clicking outside the box, or by pressing Escape
Responsive: the title scales with the screen size
Built with
HTML
CSS (written inside index.html)
Vanilla JavaScript (no libraries or frameworks)
Google Fonts: Great Vibes and Cinzel
Project structure
predator/
├── index.html                              # page structure, styles and script
├── eddd9fbf109693169d6a19f7ce57b959.jpg    # background image
└── README.md
Getting started
Clone the repository:
bash
   git clone https://github.com/your-username/your-repo-name.git
Open the folder.
Double-click index.html to open it in your browser.

There is nothing to install or build. You need an internet connection so the fonts can load.

Customizing
Change the background image: replace the file name inside url("...") in the .hottie style in index.html.
Make the picture lighter or darker: edit the two rgba(0, 0, 0, ...) values in the gradient. Higher numbers are darker.
Change the title size: edit the clamp(...) value in .hottie h1.
Edit the pop-up text: change the text inside each <div class="content"> in the HTML.
