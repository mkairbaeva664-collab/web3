# Assignment 3: Responsive Web Design

**Author:** Madina Kairbayeva  
**Group:** IT-2504 

---

## Project Overview
This project demonstrates the implementation of responsive web design techniques using **HTML5**, **CSS3 (Media Queries, Flexbox, CSS Grid)**, and **Bootstrap 5 Framework**. The project is split into three main tasks/parts:

1. **Part 1: Pure CSS Responsive Layouts**
   - Media Query practice (Fluid Typography).
   - Flexbox vs. CSS Grid responsive card layouts.
2. **Part 2: Bootstrap 5 Responsive Components**
   - Responsive Navigation Bar with collapse toggler.
   - 12-column Grid System layout for content.
3. **Part 3: Combined Project (Responsive Portfolio Page)**
   - A complete responsive single-page portfolio integrating modern layout patterns and custom color schemes.

---

## Tasks & Implementation Details

### Part 1: Media Queries & Layouts
- **Fluid Typography:** Implemented responsive font sizes using `@media (min-width: 768px)` so that headers dynamically scale across mobile and desktop viewports.
- **Flexbox vs. Grid Comparison:** Created two responsive product/project card layouts to compare `flex-wrap` behavior with `grid-template-columns: repeat(auto-fit, minmax(...))`.

> **Screenshots (Part 1):**
> *Tablet View:*
> <img width="960" height="800" alt="image" src="https://github.com/user-attachments/assets/9d4d1ea9-3d8d-4bd1-8fcf-be6b6b80c233" />
> 
> *Desktop View:*  
> <img width="1917" height="898" alt="image" src="https://github.com/user-attachments/assets/fa3e6215-d9fa-4972-b7f2-93f2a54baed3" />
> 
> *Mobile View:*  
> <img width="400" height="797" alt="image" src="https://github.com/user-attachments/assets/685b9ed7-9c45-4fdf-b113-1278574d659a" />

<img width="872" height="576" alt="image" src="https://github.com/user-attachments/assets/b1d2cd18-8f6f-4d0e-839a-56f04d5ef819" />
<img width="532" height="800" alt="image" src="https://github.com/user-attachments/assets/a2c073bf-c006-4028-9e8b-5857169cf0f1" />
<img width="630" height="653" alt="image" src="https://github.com/user-attachments/assets/63c90e30-7afa-4f33-a0a8-fa0dc3ae08bd" />

---

### Part 2: Bootstrap Framework
- Built a responsive header navigation bar using Bootstrap's `navbar-expand-md` and `navbar-dark` classes.
- Leveraged Bootstrap's 12-column grid system (`col-12`, `col-md-6`, `col-lg-8`, `col-lg-4`) to build multi-column section layouts.
- Added interactive collapse navigation for mobile screens powered by `bootstrap.bundle.min.js`.

> **Screenshots (Part 2):**
> *Tablet Menu:*
> <img width="962" height="801" alt="image" src="https://github.com/user-attachments/assets/49347aaa-e548-4864-9cf6-756b47be2a28" />
> 
> *Bootstrap Grid Desktop:*  
> <img width="1172" height="797" alt="image" src="https://github.com/user-attachments/assets/7126ca38-7c0b-4a91-a601-b4a253e42e52" />
> 
> *Bootstrap Navbar Mobile Menu (Collapsed/Expanded):*  
> <img width="462" height="797" alt="image" src="https://github.com/user-attachments/assets/ebe06d79-7c71-4d5b-87fd-fac7ffaf10b6" />

<img width="1272" height="701" alt="image" src="https://github.com/user-attachments/assets/63c09390-d8bf-4680-9aca-4ae6f9ab1d09" />
<img width="1042" height="742" alt="image" src="https://github.com/user-attachments/assets/369bf51b-c6a4-43fb-8be9-21142fc4ce7e" />
<img width="566" height="572" alt="image" src="https://github.com/user-attachments/assets/5b0f842d-7944-42a7-a73b-4833fd304f2b" />

---

### Part 3: Combined Portfolio Project
The final responsive portfolio page combines all concepts into a unified theme:
- **Header:** Sticky responsive navbar with project and contact section anchor links.
- **Main Section:** 
  - **Left Side (`col-lg-8`):** Project showcase cards displaying recent projects (*Digit Recognition, DB for Hospital, Remote Control, Bank System*).
  - **Right Side (`col-lg-4`):** Sticky/Side panel featuring user bio and contact details.
- **Footer:** Full-width responsive footer.
- **Color Palette:** Custom dark-themed palette (`#0C0304` background with `#341114` card surface and `#7E5758` accents).

> **Screenshots (Part 3 - Portfolio):**
> 
> *Full Portfolio Desktop View:*  
> <img width="960" height="801" alt="image" src="https://github.com/user-attachments/assets/8234d53c-0ffa-4ec1-8740-75e37a72ae4d" />
> 
> *Portfolio Tablet View:*  
> <img width="960" height="802" alt="image" src="https://github.com/user-attachments/assets/66dcb277-430e-4d92-b077-2dd87e00bb76" />
> 
> *Portfolio Mobile View:*  
> <img width="465" height="801" alt="image" src="https://github.com/user-attachments/assets/cf32e6b3-db30-4e12-a14c-387345de77a1" />

<img width="1400" height="667" alt="image" src="https://github.com/user-attachments/assets/60dd680e-1b26-4034-b945-894ce2a4d662" />
<img width="1195" height="713" alt="image" src="https://github.com/user-attachments/assets/6f20564b-a9e1-46d6-979d-1ac62e6354fb" />
<img width="1388" height="632" alt="image" src="https://github.com/user-attachments/assets/2307d939-b2f6-4012-9945-54195c90eabc" />
<img width="1037" height="237" alt="image" src="https://github.com/user-attachments/assets/1a3ca980-d610-4705-9d48-a67fd0ef7257" />
<img width="552" height="796" alt="image" src="https://github.com/user-attachments/assets/5f056d17-4196-4a39-ad9f-f7afb2843a6c" />
<img width="450" height="820" alt="image" src="https://github.com/user-attachments/assets/5e8d25ca-af25-4012-9fe7-34b819750cb8" />
<img width="543" height="222" alt="image" src="https://github.com/user-attachments/assets/a8db3554-b11e-4eeb-bbbb-dde880c8f023" />

---

## SUMMARY

This project demonstrates the implementation of responsive web design principles for a personal developer portfolio page using HTML5, CSS3, and Bootstrap 5.3. The page features a fully fluid layout designed with Bootstrap's 12-column grid system (col-12, col-md-6, col-lg-8, col-lg-4) to ensure seamless rendering across mobile, tablet, and desktop viewports. It includes a responsive navigation bar with a collapsing mobile menu toggle, a project showcase grid displaying recent technical work including Digit Recognition, DB for Hospital, Remote Control, and Bank System, an interactive sidebar with personal details and contact information, and a custom dark color scheme (#0C0304 background, #341114 card surfaces, and #7E5758 accents) applied cleanly without overriding framework styles with !important. Overall, the project focuses on semantic HTML structure, clean separation of concerns, and cross-browser responsiveness.
