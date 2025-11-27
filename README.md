📰 The News Times – Grid Layout Project

This project is a simple newspaper-style webpage layout built with HTML and CSS Grid.
It demonstrates how to structure a news site with multiple articles, editorial sections, and a responsive multi-column layout.

📌 Features
✔ Newspaper-style layout

The page mimics the structure of a classic newspaper with a large title, navigation menu, and multiple article sections.

✔ CSS Grid for layout

Uses grid-template-areas to place stories in a structured 3-column grid:
grid-template-areas:
  "header header header"
  "story1 story2 story3"
  "story4 story5 story5";

✔ Individual story sections

Each story has:
A title
Text content
Optional images
Clean spacing and padding for readability
✔ Internal grid borders
Each grid item uses:
.container > div {
  outline: 2px solid black;
}
This creates clean borders between grid tracks.

Technologies Used
HTML5
CSS3 (Grid, Flexbox, Typography)

📄 How It Works
🧱 Layout

The .container acts as the main grid:

.container {
  border: 2px solid black;
  display: grid;
  grid-template-columns: repeat(3, 1fr);
}


Each story is placed using grid area names (story1, story2, etc.).

🎨 Styling

outline is used to draw borders between grid tracks

Flexbox is used to space navigation links

Custom font styling for the newspaper title

🖼️ Preview
The page displays:
<img width="1242" height="717" alt="image" src="https://github.com/user-attachments/assets/d0c81cf7-c736-466f-9d98-23801eda3aab" />

A large elegant title: The News Times
A navigation bar with sections like Politics, Sports, etc.
5 article sections arranged in a newspaper-style grid

🚀 How to Run
Simply open index.html in your browser:
Right-click → Open With → Your Browser
No build tools or dependencies required.
