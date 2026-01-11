# Tile Slime — Photo-Food Slime Mold Simulation

*Nederlandse samenvatting: Interactieve slime-simulatie geïnspireerd door slime molds en Xenobots, waarbij een foto als voedselveld wordt gebruikt.*

---

**Tile Slime** is an interactive, visually mesmerizing simulation inspired by **slime molds** and **Xenobot-style behavior**. Agents (the “slime”) automatically follow a food field created from a photo you upload, resulting in an organic, pulsating network that seems alive on your screen.

---

## 🌟 Features

- **Photo as Food:** Upload an image and see how the slime organizes itself around it.
- **Organic Pulsing:** Agents pulse automatically via a sine wave, giving the slime a “breathing” effect.
- **Glow & Color:** Slime reacts to image intensity, lighting up with vibrant colors on higher values.
- **Mobile-Friendly:** Fullscreen canvas, works beautifully on mobile devices.
- **Customizable:** Adjust speed, number of agents, and pulse frequency in the JS file.

---

## 🖱️ Usage

1. Open `index.html` in your browser (Chrome / Firefox / Safari recommended).  
2. Click the **Upload Image** button.  
3. Select an image to create the food field for the slime.  
4. Watch the slime organically move and pulse across your screen.  

---

## ⚙️ Parameters (JS)

- `AGENTS` — number of slime agents (default: 2000)  
- `SPEED` — speed of agents  
- `TURN` — how sharply agents turn  
- `DECAY` — trail fading speed (0.975 works well)  
- `SINE_FREQ` — slime pulsing frequency in Hz (default 1.5)  

Adjust these in the script for different behaviors and effects.

---

## 📂 Optional

- Use `.gitignore` if you want to exclude temporary or editor-specific files.  
- For GitHub Pages: place `index.html` in the root and publish directly.

---

## 🔮 Future Ideas

- Music-reactive pulsing (sine wave tied to audio BPM)  
- Agents reacting to colors in the uploaded image  
- Enhanced glow effects with shaders or canvas filters  
- Export GIFs or video of the simulation  

---

**Have fun watching your slime come to life!** 🟢🟡🔴 
