# Web Playground: HTML & CSS Interactive Designs

Welcome to this interactive collection of frontend web experiments. This repository showcases a variety of modern UI components, glassmorphic forms, smooth CSS keyframe animations, and dynamic JavaScript interactions. Each page is self-contained, making it easy to study, experiment with, and integrate into larger projects.

---

## 🚀 Projects Overview

Here is a detailed breakdown of the interactive pages included in this workspace:

### 1. 🏀 Bouncing Ball Animation (`ball.html`)
An infinite, physics-inspired 2D bouncing ball animation.
* **Key Features:**
  * Uses CSS `@keyframes` to animate positions along a simulated parabolic trajectory.
  * Squash-and-stretch effect (`transform: scaleY(...)`) on bounce impact.
  * Clean layout styling with a container frame and shadow effects.
* **How to preview:** Open [ball.html](file:///d:/My%20Apps/project/html/ball.html) directly in any browser.

### 2. 🔋 Battery Charging Indicator (`battery.html`)
A battery charging simulator that visually represents battery level transitions.
* **Key Features:**
  * Animated fluid filling effect utilizing height transitions.
  * Dynamic color shifting: transitions from critical battery (**Red** 🔴) to charging warning (**Orange** 🟠), medium charge (**Yellow** 🟡), optimal charge (**Light Green** 🟢), and fully charged (**Green** 💚).
  * Sleek silver battery body border with rounded caps.
* **How to preview:** Open [battery.html](file:///d:/My%20Apps/project/html/battery.html) in your browser.

### 3. 🎂 Interactive Birthday Greeting (`birthday.html`)
An elegant digital greeting card with custom typography and delightful animations.
* **Key Features:**
  * Uses Google Fonts (*Dancing Script* and *Alumni Sans SC*) for sophisticated typography.
  * Enticing spin-scale animations (`spinText`) and rotation entries (`rotate`) on load.
  * Responsive layout with dedicated media query styling for mobile screen optimization.
  * Interactive call-to-action that links out to custom celebratory media.
* **How to preview:** Open [birthday.html](file:///d:/My%20Apps/project/html/birthday.html) in your browser.

### 4. 📝 Glassmorphic Login & Profile Forms (`form.html` & `form2.html`)
A multi-step form flow featuring contemporary web design trends.
* **`form.html` (Login Screen):**
  * Modern glassmorphic panel style with `backdrop-filter: blur(...)` and glowing box shadows.
  * Animated background-clipped text header.
  * Client-side validation for emails, dates, and passwords.
* **`form2.html` (Detailed Profile Creator):**
  * Full-scale dashboard-like form flow.
  * Includes inputs for personal details, age constraints, selective dropdowns (Day/Month/Year/Country), gender radios, interactive color pickers, hobby checkboxes, file uploads, and address text areas.
  * Dynamic button hover states with dual-tone gradient glows (`#eb00ff` and `#00f0ff`).
  * Fully responsive mobile layout adjustments.
* **How to preview:** Open [form.html](file:///d:/My%20Apps/project/html/form.html) in your browser to experience the submission flow, which routes to [form2.html](file:///d:/My%20Apps/project/html/form2.html).

### 5. 🎨 Gradient Text & Random Color Switcher (`gradient.html`)
A playground focusing on CSS text effects and JavaScript DOM manipulation.
* **Key Features:**
  * **Gradient Heading:** Animated text clipping effect using background position shifts.
  * **Color Switcher:** A lightweight, inline JavaScript function that randomly cycles the background color among a premium, pre-selected color palette (`black`, `yellow`, `pink`, `skyblue`, `wheat`).
* **How to preview:** Open [gradient.html](file:///d:/My%20Apps/project/html/gradient.html) in your browser.

---

## 🛠️ Technical Highlights & Concepts Used

* **CSS Keyframes & Transformations:** Leveraged for advanced animations, squash-and-stretch effects, and smooth layout entry transitions.
* **Glassmorphism & Shadows:** Utilized `backdrop-filter` and complex multi-layered shadow overlays to create modern, floating UI cards.
* **Typography:** Integrates custom web fonts dynamically from Google Fonts API.
* **Form Validation & Semantics:** HTML5 semantic form controls ensure valid input formatting (dates, emails, passwords, phone numbers).
* **Responsive Layouts:** Handcrafted CSS media queries (`@media only screen and (max-width: ...)`) to guarantee adaptability across desktop, tablet, and mobile displays.
* **DOM Interactions:** Clean JavaScript DOM style injections for user action responses.

---

## 💻 Getting Started

Since these pages are built entirely using pure HTML, CSS, and Vanilla JavaScript, there are no complicated installation steps or build pipelines.

1. **Locally opening files:** Double-click any of the HTML files in your project directory (or right-click and open in a web browser of choice).
2. **With VS Code Live Server (Recommended):**
   * If you are using VS Code, install the **Live Server** extension.
   * Right-click any file (e.g. `form.html`) and select **"Open with Live Server"** to view changes in real-time.
