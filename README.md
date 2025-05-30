# Happy Anniversary Webapp

A simple, animated, and customizable anniversary greeting website with confetti, music, and a photo gallery.

---

## 🚀 How to Run

1. **Download or Clone the Repository**
   - Download the folder or use  
     `git clone <repo-url>`

2. **Add Your Assets**
   - Place your couple image in `assets/images/couple.png`
   - Add your gallery images as `photo1.png`, `photo2.png`, etc. in `assets/images/`
   - Add your music file as `assets/audio/romantic.mp3`

3. **Open the Project**
   - Open the folder in [Visual Studio Code](https://code.visualstudio.com/) or any code editor.

4. **Run the Webapp**

   **Option 1: Open Directly**
   - Open `index.html` in your browser (double-click or right-click > Open with browser).

   **Option 2: Run with Python HTTP Server (Recommended for full functionality)**
   - Open a terminal in the project folder.
   - Run the following command:
     - For Python 3:
       ```
       python -m http.server 8000
       ```
     - For Python 2:
       ```
       python -m SimpleHTTPServer 8000
       ```
   - Open your browser and go to: [http://localhost:8000](http://localhost:8000)

---

## 📝 How to Edit

### 1. **Change Names or Messages**
- Open `index.html`
- Edit the `<h1>`, `<h2>`, and `<p class="message">` tags as you like.

### 2. **Change Images**
- Replace `assets/images/couple.png` with your own image.
- Add or replace gallery images in `assets/images/` and update their filenames in `script.js` under `galleryImages`.

### 3. **Change Music**
- Replace `assets/audio/romantic.mp3` with your own audio file.

### 4. **Edit Gallery**
- In `script.js`, update the `galleryImages` array with your image filenames.

### 5. **Customize Styles**
- Edit `style.css` to change colors, fonts, animations, etc.

---

## 💡 Tips

- For best results, use images of similar size for the gallery.
- You can add more images to the gallery by adding their paths to the `galleryImages` array in `script.js`.
- To change the confetti effect, edit the confetti section in `script.js`.

---

## 🛠️ Troubleshooting

- If images or music do not load, check the file paths and extensions.
- If the gallery does not appear, make sure you have clicked the "Play Romantic Tune" button.

---

## 📁 Project Structure

```
happy_anniversary_website/
│
├── assets/
│   ├── images/
│   │   ├── couple.png
│   │   ├── photo1.png
│   │   ├── photo2.png
│   │   └── ...
│   └── audio/
│       └── romantic.mp3
├── index.html
├── style.css
├── script.js
└── README.md
```

---

Enjoy and Happy Anniversary! 🎉