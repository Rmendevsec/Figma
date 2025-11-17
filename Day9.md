## Smart Animate, Page Transitions & Micro-interactions in Figma

Motion in Figma becomes powerful when you use **Smart Animate**, because it creates natural transitions by moving, resizing, fading, or reshaping elements between two frames. Instead of hard cuts, Smart Animate compares both frames and animates the differences automatically.

This helps you create realistic UI behavior—just like modern apps and websites.

---

# 1. Smart Animate (How It Works)

Smart Animate looks for matching layers in two frames:
- Same **layer name**
- Same **layer structure**
- Same **type** (shape/text/frame/component)

If Figma finds a match, it animates the change:
- Position  
- Opacity  
- Size (width/height)  
- Colors  
- Corner radius  
- Rotation  
- Auto layout changes  

Smart Animate is best for smooth, natural motion: cards expanding, buttons changing state, modals sliding in, tabs switching, etc.

---

# 2. Page Transitions with Smart Animate

Page transitions show how the UI moves from one screen to another. This is essential for prototyping apps or websites because it demonstrates the *flow*.

### How to Create a Smart Animate Page Transition
1. Design **Screen A** and **Screen B**
2. Keep shared elements (e.g., navbar, card, header) **named the same**
3. Switch to **Prototype** panel
4. From Screen A, add:
   - **On Click → Navigate To → Screen B**
5. Set animation:
   - **Smart Animate**
   - Choose easing (Ease Out, Ease In & Out, etc.)
   - Timing 300–450ms for pages

### Examples of Page Transitions
- Tapping a card expands it into a full-page detail view  
- A list item slides into a new page  
- Navigation bar fades and resizes between screens  
- A modal smoothly scales into view  

Smart Animate makes these feel real and fluid.

---

# 3. Micro-Interactions (Button → Success)

Micro-interactions are small animated moments that happen in response to a user action. They improve feedback and create a sense of delight.

### Example: Button → Success Animation

#### Step 1: Create 3 States
Create a component set with:
- **Default Button** (normal)
- **Loading Button** (spinner)
- **Success Button** (checkmark)

Make them variants in one component set.

#### Step 2: Add Interactions
- Default variant → **On Click → Change To → Loading**
- Loading variant → **After Delay (300–600ms) → Change To → Success**

#### Step 3: Add Motion Settings
Use:
- **Smart Animate**
- Easing **Ease Out** or **Ease In & Out**
- Timing between **150–300ms**

#### Step 4: Add Visual Motion
To make it feel real:
- Slightly shrink the button on click (scale 98%)
- Fade out text + fade in spinner
- Spinner rotates using the “Smart Animate Rotation” trick
- Success checkmark appears with a pop or fade-in

This creates a smooth, believable micro-interaction.

---

# 4. More Micro-Interactions You Can Create

### 1. Toggle Switch Animation  
- Circle sliding left → right  
- Background color change  
- Uses Smart Animate for smooth movement  

### 2. Accordion Open/Close  
- Chevron rotates  
- Content expands with Auto Layout  
- Smooth height animation with Smart Animate  

### 3. Tab Switch  
- Indicator bar slides  
- Tab text color changes  
- Content reflows underneath  

### 4. Floating Action Button (FAB) → Menu  
- FAB morphs into a close icon  
- Menu items fade + slide out  
- Corner radius + size smoothly animate  

### 5. Card Hover or Press  
- Elevation change  
- Scale up slightly  
- Shadow deepens  
- Text or image shifts position  

---

# 5. Tips for Better Motion in Figma

### 1. Keep Layer Names Consistent  
Smart Animate works best when frames have the same structure.

### 2. Use Realistic Timing  
- Micro interactions: **100–200ms**
- Buttons & cards: **150–250ms**
- Large page transitions: **300–450ms**
- Modals: **250–350ms**

### 3. Use Easing Correctly  
- **Ease Out:** Ending softly  
- **Ease In:** Starting softly  
- **Ease In & Out:** Smooth at both ends (best for UI)  
- **Custom Easing:** Advanced, for more personality  

### 4. Don't Over-Animate  
Motion should help the user, not distract them.

---

# Summary
Smart Animate helps transform static designs into dynamic, interactive prototypes.  
You can use it to:
- Build smooth page transitions  
- Create realistic app flows  
- Design polished micro-interactions  
- Animate components like buttons, cards, toggles, and menus  

The key is understanding easing, timing, structure, and consistent layer names.

**Good motion = clarity + feedback + personality.**
