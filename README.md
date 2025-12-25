# 🎄 Grand Luxury Tree


Hello! This is a small project I wrote to celebrate Christmas. ✨

Originally, I just wanted to draw a regular 3D Christmas tree, but I felt it wasn't cool enough, so I added **gesture recognition** and **particle effects**. Now you can control this tree "remotely" with your camera and even add your favorite photos.

Although it's only a few hundred lines of code, the visual effects are amazing (especially on a big screen).

Click the link below to access directly: Supports all platforms



## 🤔 What is this? (Intro)

This isn't a static web greeting card. It's a dynamic tree composed of **thousands of particles**.

I integrated it with Google's MediaPipe, so it understands your gestures.

* **Particle effects**: The tree breathes, rotates, and can even explode into a sky full of stars.

* **Grease control**: No mouse needed; just wave your hand at the camera to control it (feels like Doctor Strange).

* **Upload Memories:** Click the button in the upper right corner to upload photos, which will then transform into Polaroid photos with gold frames, floating around the tree.

* **Minimalist Aesthetics:** Only black and gold color scheme, no flashy decorations, emphasizing a sense of "high-end sophistication."


## 🛠️ What was used (Tech)

Pure front-end magic, without complex frameworks:

* **Three.js** - Handles 3D rendering and particle systems.

* **MediaPipe** - Handles gesture recognition (this is incredibly powerful).

* **Native JS (ES Modules)** - Hand-wrote the core logic. ## 🎮 How to Play? (Controls)

For first-timers, it's recommended to turn on your speakers (although background music isn't included yet, you can play Jingle Bells 🎵 yourself).

### 🖐️ Gesture Mode (Important!)
Make sure your browser allows camera access, then:

1. **Open your palm (🖐️)**: This is "Explosion Mode"! Trees will scatter and become nebulae, and you can rotate the view.

2. **Clench your fist (✊)**: Clench! The particles will recombine into a Christmas tree.

3. **Pinch your fingers (🤏)**: Like pinching something, it will randomly grab a photo and zoom in to show you.

### 🖱️ Mouse Users

* Left-click to drag and rotate, scroll wheel to zoom.

* **H key**: Pressing this hides all UI elements, great for screenshots or screen recordings as wallpaper.

## 🚀 Getting It Running (How to Run)

⚠️ **Note:** Because it uses ES Modules and camera permissions, **do not directly double-click `index.html` to open it**, your browser will report an error (CORS policy restriction). You need to set up a local server.

**If you have VS Code (recommended):** Install the `Live Server` plugin, right-click `index.html` -> "Open with Live Server". Done.

**If you are a Python expert:** Open a terminal in the directory:
```bash
python -m http.server 8000
````

Then access `localhost:8000` in your browser.

**If you prefer Node.js:**

```bash
npx http-server .

```

**Merry Christmas! 🎅**

If you find this project interesting, feel free to Star or Fork it and change the color to your liking!

Added mobile webpage support

## 🌐 Deployment (GitHub Pages)

To host this online for free:

1.  Rename your preferred HTML file (e.g., `christmas_tree_touch&gesture.html`) to `index.html`.
2.  Upload the files to a GitHub repository.
3.  Go to **Settings** -> **Pages**.
4.  Select `main` branch and save.
5.  Your tree will be live at `https://<username>.github.io/<repo-name>/`.

## Contributors ✨

Thanks to all the developers who contributed to this project:


## 📊 Star History

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=skygraphixxz-digitalproduct.github.io/christmas_tree_touch-gesture&type=date&legend=top-left)](https://www.star-history.com/#skygraphixxz-digitalproduct.github.io/christmas_tree_touch-gesture&type=date&legend=top-left)
