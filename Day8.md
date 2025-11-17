## Motion Basics in Figma

Motion in Figma helps bring your UI to life by showing how elements behave when users interact with them. Good motion design is not about making things “move,” but about guiding attention, improving clarity, and creating smoother interactions.

---

## Easing
Easing defines *how* an animation progresses over time. Instead of moving at one constant speed, easing makes animations feel more natural.

Common easing types:
- **Linear:** Moves at a constant speed; good for simple transitions.
- **Ease In:** Starts slow and speeds up; used for elements entering the screen.
- **Ease Out:** Starts fast and slows down; great for elements coming to rest.
- **Ease In & Out:** Smooth on both ends; ideal for most UI animations.
- **Custom Beziers:** Lets you adjust curves to create unique motion behavior.

Easing helps your animation feel more realistic and less robotic.

---

## Timing
Timing controls how long an animation takes. Picking the right timing makes the motion feel intentional.

- **100–150ms:** Micro-interactions (hover effects, button taps)
- **200–300ms:** Sliders, dropdowns, small component transitions
- **300–400ms:** Larger movements or layout changes
- **500ms+:** Big transitions or modals

Shorter timing feels snappy. Longer timing feels softer and more dramatic. The goal is to keep animations fast enough to feel responsive, but slow enough to be readable.

---

## How to Animate a Card Hover in Figma

### 1. Create Two States
Make two frames:
- **Default State:** Normal card (e.g., shadow 100, scale 100%)
- **Hover State:** Slightly elevated (e.g., deeper shadow, scale 102%, lifted position)

### 2. Turn Them Into Variants
- Select both frames → **Combine as Variants**
- Name them: `Default` and `Hover`

### 3. Add Interaction
- Go to **Prototype** panel  
- Select the default variant  
- Add interaction: **While Hovering → Change To → Hover**

### 4. Add Motion Settings
Choose animation style:
- **Smart Animate** for smooth transitions  
- Pick easing (e.g., Ease Out)  
- Set timing (120–180ms is perfect for hover)

### 5. Test the Animation
Play it in the prototype viewer.  
The card should lift smoothly, giving a soft, responsive hover effect.

---

## Why Motion Matters
- Makes interactions feel alive.
- Helps users understand what is interactive.
- Improves affordance and clarity.
- Adds personality and polish to the UI.

**Good motion = smooth, intentional, and fast enough to never slow the user down.**
