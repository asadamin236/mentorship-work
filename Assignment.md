# Assignment: Mastering CSS Positioning

This practical exercise is designed to help you understand how different CSS positioning properties affect the placement and behavior of elements on a webpage.

## Task
Create an HTML file with a main container and 5 distinct boxes inside it. Style each box according to the specifications below.

### Requirements:
1. **Container:** Create a `main-container` (Width: 600px, Height: 1500px, Background: #f0f0f0). *Note: The large height is intentional to allow for page scrolling.*

2. **Box 1 (Static):**
   - Use default positioning.
   - Background: `red`.

3. **Box 2 (Relative):**
   - Position: `relative`.
   - Apply `top: 20px; left: 20px;` and observe how it moves relative to its original position.
   - Background: `blue`.

4. **Box 3 (Absolute):**
   - Position: `absolute`.
   - Place it inside the `main-container` (Ensure the parent has `position: relative`).
   - Apply `top: 50px; right: 50px;`.
   - Background: `green`.

5. **Box 4 (Fixed):**
   - Position: `fixed`.
   - Fix it to the bottom-right corner of the screen (`bottom: 20px; right: 20px;`).
   - Scroll the page and observe if it stays fixed to the viewport.
   - Background: `orange`.

6. **Box 5 (Sticky):**
   - Position: `sticky`.
   - Place it in the middle of a long paragraph.
   - Apply `top: 0;`.
   - Scroll the page and observe if it "sticks" to the top when it reaches that point.
   - Background: `purple`.

---

## Challenge Questions
After completing the code, answer the following:
*   What happens to the `Absolute` box if you remove `position: relative` from its parent container?
*   Between `Fixed` and `Sticky`, which one occupies space in the "Document Flow," and which one is removed from it?

---
