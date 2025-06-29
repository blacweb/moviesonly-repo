# Movies only is just a project!
Discription: well I made this project foe my coolege assigment and I made this wensite a fully functional with js. I also used html that is the skeleton of every web page
and I used plain CSS to make it's interface, It deos not have any kind of bakend,not yet but i am  going to add it if I am going to deploy this in the future.and we will modify it later!

# 📄 Overview
A simple, visually attractive movie showcase website built using:

# ✅ HTML (Structure)

# 🎨 CSS (Styling)

⭐ Font Awesome (Icons)

🖼️ Google Fonts (Custom typography)

🧱 HTML Structure
📌 1. <head> Section
🔡 Sets charset=UTF-8 and responsive viewport

🎨 Imports:

Font Awesome (<i class="fa">)

Google Font "Luckiest Guy"

style.css (local styling file)

🏷️ Title: https://www.moviesonly.com

📌 2. <body> Section
🧭 Header
html
Copy
Edit
<header>
  <button id="menu">...</button>
  <a id="logo">Movies Only</a>
  <a id="sign-up">Sign-in</a>
</header>
🍔 #menu: Hamburger icon for future menu toggle

🎞️ #logo: Brand name, styled large with a custom font

👤 #sign-up: Sign-in button with hover effect

📰 Ticker Notification
html
Copy
Edit
<div class="ticker-wrapper">
  <div class="ticker">...</div>
</div>
📢 Animated, scrolling client notice

🛑 Fully controlled via CSS @keyframes moveRight

⭐ Featured Movies Section
html
Copy
Edit
<article class="main-section">
  <a class="featured"> ... </a>
</article>
🎥 Displays 2025 movies in boxes with:

Poster image

Title

Quality (HD)

Year

🖱️ Hover changes text color for interactivity

🚀 Top Performing Movies
html
Copy
Edit
<article class="Top-performing">
  <a class="Top"> ... </a>
</article>
🏆 Showcases all-time great movies (1950s–2000s)

🎖️ Same structure as featured, but different class

🧾 Footer
html
Copy
Edit
<footer class="footer">
  <p>&copy; 2023 OnlyMovies</p>
</footer>
🔒 Copyright

❤️ Styled to match theme

🎨 CSS Highlights
🎨 Colors & Theme
Main theme: rgb(190, 5, 5) (deep red, Netflix-style)

Text: White (#fff) with hover black

Font: "Luckiest Guy" for logo, "Georgia" for titles

💠 Layouts
🎯 Flexbox-based for:

Header alignment

Movie cards layout (.main-section, .Top-performing)

🧱 Responsive base (but no media queries yet)

💡 Animations
css
Copy
Edit
@keyframes moveRight {
  0% { left: -100%; }
  100% { left: 100%; }
}
🏃 Scrolling ticker for client message

🔄 Infinite loop for dynamic UI

📂 Folder Structure Suggestion
cpp
Copy
Edit
📁 moviesonly/
├── 📄 index.html
├── 📄 style.css
├── 📁 assets/
│   └── 🎞️ images/
├── 📁 scripts/
│   └── 📜 app.js (optional future)
🔧 Suggested Improvements
✅ Fix broken image URL (Final Destination uses invalid Google image link)

📱 Add media queries for mobile responsiveness

🔐 Create actual sign-in form or user system

🧠 Add filtering/sorting by year/genre

🚀 Lazy-load images for better performance

💬 Optional JavaScript Features
Want me to add any of these?

🔐 Modal Sign-in Form

📱 Responsive Nav Toggle

🎯 Scroll to Top Button

🎞️ Search Bar


