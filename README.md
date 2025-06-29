# Movies only is just a project!
Discription: well I made this project foe my coolege assigment and I made this wensite a fully functional with js. I also used html that is the skeleton of every web page
and I used plain CSS to make it's interface, It deos not have any kind of bakend,not yet but i am  going to add it if I am going to deploy this in the future.and we will modify it later!
 # The html is this
 <!DOCTYPE html>
<html lang="en">
  <head>
    <!-- Meta and External Styles -->
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />

    <!-- Font Awesome for icons -->
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css"
      crossorigin="anonymous"
    />

    <!-- Google Font: Luckiest Guy -->
    <style>
      @import url("https://fonts.googleapis.com/css2?family=Luckiest+Guy&display=swap");
    </style>

    <!-- Website Title -->
    <title>https://www.moviesonly.com</title>

    <!-- Local CSS -->
    <link rel="stylesheet" href="style.css" />
  </head>

  <body>
    <!-- Header Section -->
    <header>
      <!-- Hamburger menu icon (can be used to toggle nav later) -->
      <button id="menu"><i class="fa-solid fa-bars"></i></button>

      <!-- Website Logo -->
      <a id="logo" href="Index.html">Movies Only</a>

      <!-- Sign-in Link -->
      <a href="" id="sign-up"><i class="fa-solid fa-user"></i>Sign-in</a>
    </header>

    <!-- Main Content Area -->
    <main>
      <section>

        <!-- Scrolling Notification Banner -->
        <article class="line">
          <div class="ticker-wrapper">
            <div class="ticker">
              <span>This is just a demo for clients and links are not live, Thank you!</span>
            </div>
          </div>
        </article>

        <!-- Featured Movies Section -->
        <p class="feature">Featured</p>
        <article class="main-section">
          <!-- Repeatable Movie Item -->
          <a href="link.html" class="featured">
            <img src="..." height="250px" width="230px" alt="img" />
            <p>Final destination: Bloodlines</p>
            <p>HD</p>
            <p>2025</p>
          </a>
          <!-- Add more movies here -->
        </article>

        <!-- Top Performing Movies Section -->
        <p class="top">Top Performing</p>
        <article class="Top-performing">
          <a href="link.html" class="Top">
            <img src="download (1).jpeg" height="250px" width="230px" alt="img" />
            <p>Gladiators</p>
            <p>HD</p>
            <p>2000</p>
          </a>
          <!-- More top movies here -->
        </article>
      </section>
    </main>

    <!-- Footer -->
    <footer class="footer">
      <p>&copy; 2023 OnlyMovies. All rights reserved.</p>
    </footer>
  </body>
</html>

# The CSS for this html
<!DOCTYPE html>
<html lang="en">
  <head>
    <!-- Meta and External Styles -->
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />

    <!-- Font Awesome for icons -->
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css"
      crossorigin="anonymous"
    />

    <!-- Google Font: Luckiest Guy -->
    <style>
      @import url("https://fonts.googleapis.com/css2?family=Luckiest+Guy&display=swap");
    </style>

    <!-- Website Title -->
    <title>https://www.moviesonly.com</title>

    <!-- Local CSS -->
    <link rel="stylesheet" href="style.css" />
  </head>

  <body>
    <!-- Header Section -->
    <header>
      <!-- Hamburger menu icon (can be used to toggle nav later) -->
      <button id="menu"><i class="fa-solid fa-bars"></i></button>

      <!-- Website Logo -->
      <a id="logo" href="Index.html">Movies Only</a>

      <!-- Sign-in Link -->
      <a href="" id="sign-up"><i class="fa-solid fa-user"></i>Sign-in</a>
    </header>

    <!-- Main Content Area -->
    <main>
      <section>

        <!-- Scrolling Notification Banner -->
        <article class="line">
          <div class="ticker-wrapper">
            <div class="ticker">
              <span>This is just a demo for clients and links are not live, Thank you!</span>
            </div>
          </div>
        </article>

        <!-- Featured Movies Section -->
        <p class="feature">Featured</p>
        <article class="main-section">
          <!-- Repeatable Movie Item -->
          <a href="link.html" class="featured">
            <img src="..." height="250px" width="230px" alt="img" />
            <p>Final destination: Bloodlines</p>
            <p>HD</p>
            <p>2025</p>
          </a>
          <!-- Add more movies here -->
        </article>

        <!-- Top Performing Movies Section -->
        <p class="top">Top Performing</p>
        <article class="Top-performing">
          <a href="link.html" class="Top">
            <img src="download (1).jpeg" height="250px" width="230px" alt="img" />
            <p>Gladiators</p>
            <p>HD</p>
            <p>2000</p>
          </a>
          <!-- More top movies here -->
        </article>
      </section>
    </main>

    <!-- Footer -->
    <footer class="footer">
      <p>&copy; 2023 OnlyMovies. All rights reserved.</p>
    </footer>
  </body>
</html>
