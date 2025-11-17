## Lottie Animations in Figma

Lottie is a lightweight animation format that allows you to use high-quality, scalable vector animations in your designs—without heavy GIF files or large videos. Lottie files use the `.json` format, which stores animation data created in tools like After Effects (using the Bodymovin plugin).

Figma supports Lottie animations so you can preview, place, and prototype real motion in your designs. This makes your prototypes more realistic and closer to the final product.

---

## Why Lottie Is Useful
- **Lightweight:** Much smaller than GIFs or videos.
- **Scalable:** Stays sharp at any size (vector-based).
- **Editable:** Can change speed, loop behavior, direction, and playback triggers.
- **Interactive:** Works very well in mobile and web apps.
- **Developer friendly:** Developers can easily integrate Lottie in React, Flutter, Android, iOS, and more.

Lottie is perfect for loaders, success checkmarks, empty states, fun illustrations, onboarding screens, and micro-interactions.

---

## How to Use Lottie in Figma

### 1. Get a Lottie File
You can download Lottie files from:
- **LottieFiles.com**
- **Icons8 Lottie library**
- Custom exports from **After Effects (Bodymovin)**

Download the `.json` file or copy the Lottie URL.

### 2. Import into Figma
You have two ways:
- Drag the `.json` file into your Figma canvas  
- OR use the **LottieFiles Figma plugin** to browse and insert directly

Figma will display the animation as a Lottie element.

### 3. Adjust Playback Settings
In the right sidebar, you can control:
- **Loop On/Off**
- **Play automatically**
- **Play on interaction**
- **Playback speed**
- **Direction (for reverse animations)**

These controls help you prototype real UI flows.

---

## Creating an Animated Loader Using Lottie

A loader animation is one of the most common uses of Lottie. It gives your app or website a polished, professional feel.

### Step 1: Choose the Type of Loader
Loaders can be:
- Circular spinners  
- Dots bouncing  
- Progress rings  
- Pulse animations  
- Line loaders  
- Futuristic loops  

Pick one that matches your app’s brand and style.

### Step 2: Download a Lottie Loader
Go to **LottieFiles.com → Search “loader"**  
Pick a simple animation (looping is important).  
Download the `.json` file.

### Step 3: Import Into Figma
Drag the `.json` file into your canvas.  
Resize it to match your UI environment.

### Step 4: Set Up the Interaction (Prototype Mode)
1. Create two screens:
   - **Screen A:** User clicks or triggers loading  
   - **Screen B:** After loading finishes  

2. In **Prototype**:
   - Select the button on Screen A  
   - Add **On Click → Navigate To → Screen A (animation overlay)**  
   - Add the Lottie loader centered  
   - Set loader to **Loop**

3. Add a delay animation:
   - From the loader overlay → **After Delay (1000–2000ms)** → Navigate to Screen B  
   - Use **Smart Animate** or **Instant** transition

Your prototype now shows a real Lottie loading animation before the next screen appears.

### Step 5: Fine-Tune the Loader
You can adjust:
- Size (usually 48–80px)  
- Speed (1.0 or 1.2 feels smooth)  
- Opacity for softer visuals  
- Background overlay (blur or semi-transparent)

---

## Best Practices for Lottie in UI
- Keep animations **lightweight** (under 200KB if possible)
- Use **loop animations** for loaders  
- Use **short, non-looping animations** for success or error feedback  
- Match animation style with your brand (rounded shapes, soft curves, smooth timing)  
- Avoid overwhelming movement (clean, simple animations work best)

---

## Summary
Lottie animations bring real, high-quality motion into Figma prototypes. They help you design modern UI loading states, success animations, onboarding flows, and micro-interactions that feel realistic and ready for development. By using Lottie in Figma, you can create professional motion experiences without needing advanced animation tools.

**Lottie = small file size + smooth motion + real app-level animation.**
