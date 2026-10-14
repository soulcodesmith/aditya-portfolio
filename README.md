# Aditya's Personal Portfolio & Digital Literacy Project

A minimalist, high-craft, single-page personal portfolio website designed for **Aditya**, 1st-Year B.Tech Student at **JECRC University**, submitted as part of the **Digital Literacy** college course and serving as a professional engineering hub.

Inspired by the design aesthetics of **Linear**, **Apple**, and **Vercel** — dark mode by default, hairline borders, subtle glassmorphism, responsive bento grids, and typography-first layouts.

---

## 🚀 Quick Start (Instant Preview)

No build tools, Node.js, or complex setups required!

1. **Direct Browser Open:**  
   Simply double-click the `index.html` file or drag & drop it into Google Chrome, Safari, Brave, or Firefox.
   
2. **Local Development Server (Optional):**
   ```bash
   # Python 3 built-in server
   python3 -m http.server 8000
   ```
   Then open `http://localhost:8000` in your browser.

---

## 🎨 Design System & Highlights

- **Theme:** Sophisticated zinc-950 dark mode with subtle radial ambient glow and hairline borders (`border-white/10`).
- **Typography:** Modern clean sans-serif (`Inter`) paired with code mono (`JetBrains Mono`).
- **Icons:** [Lucide Icons](https://lucide.dev/) loaded via CDN.
- **Glassmorphism:** `backdrop-blur-xl bg-white/[0.02]` with smooth 200ms scale/lift transitions.
- **Micro-Interactions:**
  - One-click copy email button (`adityajecrc@gmail.com`) with animated toast notification.
  - Interactive project detail modal.
  - Active navigation spy highlighting the current section on scroll.
  - Mobile responsive slide-down menu with smooth scroll anchors.

---

## 🧱 Sections Overview

1. **Floating Navigation Bar (Sticky Glass):**
   - Monogram logo (`A` & `JECRC UNI • '29`)
   - Smooth-scrolling links: *About, Skills, Projects, Coursework, Contact*
   - "Resume" action button

2. **Hero Section:**
   - Real-time status pill: `● 1st Year B.Tech Student • JECRC University • Open to Collaborations`
   - Editorial headline & bio highlighting computing fundamentals & digital literacy
   - Direct CTA buttons: "Explore Projects", "Get in Touch", and quick email copy pill
   - Social links bar (GitHub, LinkedIn, X, Mail)

3. **Digital Literacy & Core Skills (Bento Grid):**
   - **Programming & Scripting:** Python 3, C/C++ (Pointers, Structs), Semantic HTML5, Modern CSS3/Tailwind, ES6+ JavaScript.
   - **Foundational Computing:** Binary data representation, IEEE-754, Internet architecture (OSI, TCP/IP, DNS), algorithmic Big-O, and digital ethics.
   - **Productivity & Digital Literacy:** Git/GitHub workflows, Linux terminal commands, LaTeX/Overleaf technical documentation, Markdown/Obsidian PKM, Google Workspace collaboration, 2FA/cyber hygiene.

4. **Featured Projects & Coursework:**
   - **MicroGrad-Py:** First-principles scalar autograd engine & computation graph in Python.
   - **Digital Literacy Academic Web Portal:** Interactive peer study guide on digital hygiene and web protocols.
   - **SysPulse CLI:** High-efficiency C/POSIX system and memory process monitor.

5. **Academic Journey & Coursework Milestones:**
   - Chronological vertical timeline detailing 1st-year engineering subjects at JECRC University:
     - Digital Literacy & Information Systems
     - Computer Programming & Problem Solving (C / Python)
     - Engineering Mathematics & Computational Calculus
     - Digital Logic Design & Computer Architecture

6. **Footer & Contact:**
   - Large typography "Let's build something exceptional together."
   - One-click copy email pill and direct email launch.
   - Copyright line: `© 2026 Aditya. Built for Digital Literacy at JECRC University.`

---

## 🛠️ How to Customize Personal Details

Open `index.html` in any text editor (VS Code, Sublime Text, or Notepad) and search for the following comments:

- **GitHub Link:** Search for `https://github.com` and replace with your profile (e.g. `https://github.com/aditya-jecrc`).
- **LinkedIn Link:** Search for `https://linkedin.com` and replace with your LinkedIn URL.
- **X / Twitter Handle:** Search for `https://x.com` and replace with your handle.
- **Resume File:** Place your PDF resume (e.g., `Aditya_Resume.pdf`) in the same folder and update the `handleDownloadCV()` function in the script tag to open `Aditya_Resume.pdf`.

---

## 🌐 Free 1-Minute Deployment Options

### Option 1: GitHub Pages
1. Create a new GitHub repository named `portfolio` or `aditya-portfolio`.
2. Push or upload `index.html`.
3. In GitHub repo settings, go to **Pages** &rarr; select `main` branch &rarr; click **Save**.
4. Your site will be live at `https://<username>.github.io/<repo>/`!

### Option 2: Vercel (Drag & Drop)
1. Visit [vercel.com](https://vercel.com).
2. Drag and drop this folder directly into the Vercel dashboard.
3. Your site will be deployed instantly with a free HTTPS `.vercel.app` URL.
