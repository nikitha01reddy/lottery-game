
# Dynamic Lottery Game
The Dynamic Lottery Game is an interactive web-based game where users can randomly pick a number and win exciting prizes. The game features 50 numbered lottery boxes, each containing a hidden reward. When the user clicks the "Pick A Number" button, the system randomly selects a winning number with an engaging animation and sound effects.

Designed with a luxurious gold and dark theme, the game provides a thrilling experience using smooth transitions, glowing effects, and audio cues. Built using HTML, CSS, and JavaScript, it ensures seamless functionality and a fun-filled gaming experience.

## Live Project

You can view the live project here: [Dynamic Lottery Game](https://dynamic-lottery-game.netlify.app/)

##  Features

✔️<b>Responsive Design</b> - Media queries ensure optimal viewing across devices.

✔️<b>50 Lottery Boxes</b> - Each box has a unique number and a prize.

✔️<b> Random Selection</b> - The game randomly picks a number when the user clicks the button.

✔️ <b>Exciting Prizes</b> - Win items like iPhones, Laptops, Gold Jewelry, and more!

✔️ <b>Stylish & Animated</b> UI - Elegant gold and royal blue theme for a premium look.

✔️ <b>Sound Effects</b> - Click and win sounds to enhance user engagement.

✔️ <b>Glow Effects for Winning Box</b> - The selected number and prize are highlighted with a royal effect.

✔️ <b>Smooth Transitions</b> - Animated selection process for a suspenseful experience.


## 🚀 Technology Stack
<b>HTML</b> → Structure of the webpage

<b>CSS</b> → Styling, animations, responsiveness and media queries for a seamless experience on all devices.

<b>JavaScript </b>→ Game logic, number selection, and DOM manipulation

<b>Audio Effects</b> → Sound effects for click and win events

## Code Explanation

1️⃣ <b>HTML (index.html)</b>

The HTML file defines the basic structure of the game, including:

Title (h1)

Lottery number grid (.lottery-sheet-container)

Result display (#result)

Button (#pickNumberBtn)

2️⃣<b> CSS (lotterygame.css)</b>

Handles styling and responsiveness with:

✨ <b>Visual Design:</b> Dark theme (#121212) with gold accents (#FFD700) and glowing animations.

📱 <b>Mobile-First Responsiveness:</b> Media queries (448px-1245px) for perfect phone/tablet adaptation.

🎮 <b>Interactive Elements:</b> Smooth button transitions, touch-friendly boxes, and winning state effects (golden glow + platinum highlights).

📏 <b>Dynamic Scaling:</b> Auto-adjusting box sizes (55px-180px) and fonts (5px-18px) across devices

3️⃣<b> JavaScript (lottery_game.js)</b>

Here's a concise JavaScript explanation for your README:

<b>JavaScript (lottery_game.js)</b>

Handles game logic with:  

🎲 <b>Random Selection: </b> 
Generates 50 unique lottery boxes with prizes using `gifts` array  
Implements 2-stage random draw (highlight animation + final winner)  

🎯 <b>Interactive Features:</b>  
6-second countdown with box highlighting animation  
Sound effects for selection (`tick`) and win celebration (`win`)  
Dynamic DOM updates for results display and box states  

⚙️ <b>Core Functions:</b>  
`click` event listener triggers lottery draw sequence  
Interval-based animation with sequential highlighting  
Final prize assignment with golden box effect    

<i>Works with CSS classes (`winningBox`, `highlightedBox`) for visual feedback<i>


## Color Reference

| Element            | Color       |                                                             
| ----------------- | ------------------------------------------------------------------ |
| Background | #121212 Dark Black  |
| Primary Text | #FFD700 Gold |
|Winning Box | #DAA520 Goldenrod |
| Winning Box Border | #FFD700 Gold |
| Highlighted Box | #E5E4E2 Platinum |
| Highlighted Box Text | #121212 Dark Grey |
| Button Background | #007bff Bright Blue |
| Button Hover | #00458f Deep Blue |
| Button Focus | rgba(21, 164, 21, 0.829) Green |
|Lottery Box | #3498db Light Blue |
| Lottery Box Text | rgb(229, 228, 228) Soft White |


