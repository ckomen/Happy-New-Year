# Happy New Year Celebration Project

This project creates a festive **Happy New Year** greeting with animated text, colorful confetti, and dynamic fireworks using HTML, CSS, and JavaScript.

---

## **Features**
1. **Responsive Design**:
   - The layout adjusts dynamically for all screen sizes, ensuring a seamless user experience.

2. **Animated Text**:
   - The greeting message glows and pulses, adding a celebratory touch.

3. **Fireworks Effect**:
   - Randomly positioned fireworks burst with colorful sparks that expand and fade.

4. **Dynamic Confetti (Optional)**:
   - Colorful confetti can be added for a more festive atmosphere (commented out in the code for simplicity).

5. **Reusable Code**:
   - The JavaScript logic can be adapted for other occasions and animations.

---

## **Usage**
1. Save the code in an `.html` file (e.g., `new_year.html`).
2. Open the file in any web browser.
3. Enjoy the festive greeting with animations.

---

## **Code Structure**

### **HTML**
- Contains the main structure of the page, including:
  - A heading for the New Year greeting.

### **CSS**
- Styles the layout, text, and animations.
- Includes:
  - Radial gradient background for a festive feel.
  - Glowing text animation.
  - Styling for fireworks sparks.

### **JavaScript**
- Adds interactivity and dynamic animations:
  - Randomly generates fireworks positions.
  - Simulates spark movements and fades them out after animation.

---

## **Customization**

1. **Change the Greeting**:
   - Modify the text in the `<h1>` tag to personalize the message.

2. **Adjust Fireworks Behavior**:
   - Update the `setInterval` timing in the `createFirework` function to launch fireworks more or less frequently.
   - Modify the number of sparks or their spread by tweaking the loop and spark properties.

3. **Add Sound Effects**:
   - Enhance the experience by playing a sound when fireworks are launched. Use the Web Audio API or an `<audio>` tag.

4. **Enable Confetti**:
   - Uncomment or integrate confetti logic for additional flair.

---

## **Future Improvements**
1. Add background music with controls for users to toggle sound on/off.
2. Enhance animations using third-party libraries like **GSAP**.
3. Include a countdown timer leading up to the New Year.
4. Create a mobile-friendly version with optimized animations for smaller devices.

---

## **Credits**
Developed with vanilla HTML, CSS, and JavaScript. The project can be extended for other celebrations like birthdays, anniversaries, or holidays!

