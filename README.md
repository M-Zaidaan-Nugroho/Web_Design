# Week 3: C.R.A.P. Design Principles in HTML

## 📌 Project Overview
This project is an assignment for the **Web Design** course (Week 3). The objective was to create a clean, readable article layout about **SIMD (Single Instruction, Multiple Data)** while strictly applying the **C.R.A.P.** design principles using HTML and inline CSS.

<img width="2977" height="1776" alt="image" src="https://github.com/user-attachments/assets/1e150ba1-decd-427e-ae7e-03ec54a0b506" />

## 🎨 Design Principles Applied (C.R.A.P.)
The layout focuses on four pillars of design to improve user experience:

*   **Contrast:** Used bold weights for metadata labels (e.g., **Penerbit**, **Terbit**) and distinct font weights to separate the article title from the body.
*   **Repetition:** Established a consistent visual language by using the **Montserrat** font for the header/footer and maintaining uniform **1:1 aspect ratios** for all images.
*   **Alignment:** Utilized `flexbox` for structured alignment. The header uses vertical stacking, while the content section uses centered alignment to create a balanced focal point.
*   **Proximity:** Related elements are grouped using the `gap` property. Publication info is tightly grouped at the top, while documentation images are placed together at the bottom to indicate they belong to the same context.

## 🛠️ Technical Implementation
*   **HTML5:** Semantic structure using `<section>`, `<h1>`, `<div>`, and `<img>` tags.
*   **CSS3 (Inline):** Extensive use of `display: flex` for layout control, `gap` for spacing, and `aspect-ratio` for image consistency.
*   **Typography:** 
    *   **Montserrat**: Integrated via Google Fonts for headings and UI elements.
    *   **SF Pro**: Used for the body text to ensure high readability.

## 📂 Project Structure
```text
├── index.html              # Main HTML source code
└── assets/
    └── images/
        ├── main-image.png   # Primary article thumbnail
        ├── second-image.png # Documentation image 1
        └── third-image.png  # Documentation image 2
