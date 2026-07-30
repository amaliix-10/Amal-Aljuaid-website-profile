# Amal-Aljuaid-website-profile
## Personal Profile Website Project

Welcome to my personal website repository! This document outlines the step-by-step process of building a clean, lightweight personal portfolio using standard **HTML5** and **Notepad++**.

---

##  Step-by-Step Implementation Workflow

### 1️⃣ Writing Code in Notepad++
* Opened **Notepad++** and created a new file document.
* Wrote the standard HTML5 skeleton structure set to English (`lang="en"`).
* Structured the web page into two primary functional sections:
  1. **Hero Section (`<section class="hero">`):** Contains a welcoming header `<h1>` and a concise intro paragraph `<p>`.
  2. **Skills Section (`<section id="skills">`):** Organizes technical and professional skill sets across four categorized `<h3>` headings using clean comma-separated values.
* HTML:
```html
  <!DOCTYPE html>
  <html lang="en">
  <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>Amal Aljuaid | Profile</title>
  </head>
  <body>

      <!-- Hero Section -->
      <section class="hero">
          <div class="hero-content">
              <h1>Welcome...</h1>
              <p>I'm Amal Aljuaid, a Computer Engineering student at Taif University and a Trainee at Smart Methods company.</p>
              <img src="smart methods.jpg" width="200" height="200" alt="Smart Methods Logo">
          </div>
      </section>

      <hr>

      <!-- Skills Section -->
      <section id="skills">
          <h2>Technical & Professional Skills</h2>

          <h3>Programming & Embedded Systems</h3>
          <p>C++, Python, SQL, Embedded C, Arduino, Hardware Protocols (I2C, SPI, UART), IoT</p>

          <h3>Simulation & Design</h3>
          <p>MATLAB / Simulink, Multisim, Proteus, Tinkercad Circuits, Onshape 3D CAD, Cisco Packet Tracer</p>

          <h3>AI & Developer Tools</h3>
          <p>Computer Vision Basics, Google Colab, Teachable Machine, Git & GitHub, HTML5 / CSS3, MIT App Inventor</p>

          <h3>Professional Skills</h3>
          <p>Technical Documentation, Troubleshooting & Problem Solving, Team Collaboration, Fast Learning</p>
      </section>

  </body>
  </html>
 ```
---

### 2️⃣ Saving the File with the Correct Extension (`index.html`)
To ensure web browsers interpret the code as a functional web page rather than plain text:
1. In Notepad++, navigated to **`File` $\rightarrow$ `Save As...`**.
2. Entered the filename: `index.html`.
3. Changed the **Save as type** dropdown to **`All types (*.*)`** (or `Hyper Text Markup Language file (*.html)`).
4. Saved the file directly into the root project folder.

---

### 3️⃣ Attaching and Sizing the Image Asset (`smart methods.jpg`)
To correctly display the company logo without broken image paths:
1. **Directory Placement:** Placed the image file named `smart methods.jpg` in the **exact same folder** as `index.html`.
2. **HTML Markup:** Utilized the `<img>` tag as follows:
   ```html
   <img src="smart methods.jpg" width="200" height="200" alt="Smart Methods Logo">
