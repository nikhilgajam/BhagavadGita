# Srimad Bhagavad Gita
The Ultimate Manual for Life

<div align="center">
  <img src="./Data/Pictures/BhagavadGita.png" alt="Bhagavad Gita Cosmic Form" width="100%" style="border-radius: 10px; box-shadow: 0 10px 30px rgba(0,0,0,0.5);">
  <br><br>
  
  [![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
  [![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
  [![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
</div>

## 🕉️ About The Project

This is a modern, immersive, and responsive web application designed to explore the timeless wisdom of the **Srimad Bhagavad Gita**. 

Unlike traditional text-heavy sites, this application focuses on a **visual and meditative experience**. It features a split-pane layout where the left side displays high-definition artwork representing the chapter, while the right side provides a distraction-free reading interface with intuitive controls.

## ✨ Key Features

* **Immersive Split-Screen UI:** A drag-adjustable split pane allowing you to balance the visual art and the text reading area.
* **Multilingual Support:** Seamlessly switch between **English**, **Hindi**, and **Telugu** translations.
* **Smart Navigation:**
    * Auto-transition between chapters when reaching the first/last verse.
    * Keyboard support (Arrow keys) for quick reading.
* **Customization:** Adjustable font size slider to suit your reading preference.
* **Progress Saving:** The app uses LocalStorage to remember your last read Chapter, Verse, Language, and layout settings automatically.
* **Rich Text Parsing:** Automatically formats verse text (headings and subheadings) for better readability.
* **Cosmic Aesthetics:** Beautiful CSS animations, glassmorphism effects, and a deep cosmic color palette.

## 🚀 Getting Started

### Prerequisites

You do not need any package managers (npm/yarn) or servers. This project runs directly in the browser using Vanilla JavaScript.

### Run with Python

To run project locally:
* On Windows: ```py -m http.server 8000```
* On Mac: ```python3 -m http.server 8000```
* On Linux: ```python3 -m http.server 8000```

### Folder Structure

**Crucial:** For the application to work, you must ensure your data files are organized exactly as shown below, as the JavaScript fetches these paths dynamically:

```text
/Project-Root
│
├── index.html                  # The main application file
├── README.md
│
└── Data/
    ├── Pictures/
    │   ├── favicon.png
    │   ├── Chapter 0.jpg       # Intro image
    │   ├── Chapter 1.jpg
    │   ├── ...
    │   └── Chapter 18.jpg
    │
    └── Bhagavad_Gita/
        ├── English/
        │   ├── Chapter_1/
        │   │   ├── Verse_0.txt
        │   │   └── ...
        │   └── ...
        ├── Hindi/
        │   └── ...
        └── Telugu/
            └── ...