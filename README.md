# 🏙️ Broadway Design — Landing Page

A hands-on CSS **layout & positioning** exercise for a fictional design firm. Practiced **display** and **position** to build a fixed header, centered nav, full-bleed jumbotron, and a responsive three-column section (Design • Develop • Deploy).

---

## 📸 Preview
![Project Screenshot](https://content.codecademy.com/projects/broadway/bg.jpg)

---

## 🗂️ Project Structure
broadway-design/  
├─ index.html  
└─ style.css

---

## ▶️ Live Demo
[![Open in CodeSandbox](https://img.shields.io/badge/Open%20in-CodeSandbox-black?style=for-the-badge&logo=codesandbox)](https://codesandbox.io/p/sandbox/github/SunilKumarPeela/Broadway-Design)

---

## 🎯 Skills Practiced
- CSS **positioning** (fixed header, relative content offset)  
- **Display** patterns (inline-block columns)  
- Full-bleed hero with **background-size: cover**  
- **Navigation** layout & spacing  
- **Media queries** for small screens  

---

## 📄 `index.html`
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Broadway Design</title>
    <link href="https://fonts.googleapis.com/css?family=Raleway:400,600" rel="stylesheet" />
    <link href="style.css" rel="stylesheet" />
  </head>

  <body>
    <header>
      <nav aria-label="Primary">
        <ul>
          <li> About </li>
          <li> Work </li>
          <li> Team </li>
          <li> Contact </li>
        </ul>
      </nav>
    </header>

    <main>
      <div class="jumbotron">
        <div class="container">
          <h1>We are Broadway</h1>
          <a href="#" class="btn-main">Get Started</a>
        </div>
      </div>
    </main>

    <section class="supporting" aria-labelledby="supporting-heading">
      <div class="container">
        <h2 id="supporting-heading" class="sr-only">What We Do</h2>

        <div class="col">
          <img src="https://content.codecademy.com/projects/broadway/design.svg" alt="Design icon" />
          <h2>Design</h2>
          <p>Make your projects look great and interact beautifully.</p>
          <a href="#" class="btn-default">Learn More</a><br />
        </div>

        <div class="col">
          <img src="https://content.codecademy.com/projects/broadway/develop.svg" alt="Develop icon" />
          <h2>Develop</h2>
          <p>Use modern tools to turn your design into a website.</p>
          <a href="#" class="btn-default">Learn More</a><br />
        </div>

        <div class="col">
          <img src="https://content.codecademy.com/projects/broadway/deploy.svg" alt="Deploy icon" />
          <h2>Deploy</h2>
          <p>Ship fast, scale confidently, and iterate with ease.</p>
          <a href="#" class="btn-default">Learn More</a><br />
        </div>
      </div>
    </section>

    <footer>
      <div class="container">
        <p>&copy; Broadway 2017</p>
      </div>
    </footer>
  </body>
</html>
