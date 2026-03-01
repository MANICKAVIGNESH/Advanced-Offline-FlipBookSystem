# Advanced-Offline-FlipBookSystem
Developed an Interactive 3D FlipBook Web Application using HTML, CSS, and JavaScript featuring smooth page animations, realistic page-turn sound effects, keyboard and mouse navigation, and fullscreen functionality for an enhanced digital reading experience.

📘 Project Setup Instructions
Interactive 3D FlipBook with Realistic Page Sound
📁 1. Folder Structure (Important)

All files must be inside the same folder.

Project Folder
│
├── Professional_FlipBook.html
├── flip.mp3
├── page_1.png
├── page_2.png
├── page_3.png
├── page_4.png
├── page_5.png
├── page_6.png
└── page_7.png

⚠ Do NOT rename files unless you update the HTML code.

🔊 2. Audio File Rules

The sound file must be named exactly:

flip.mp3

It must be placed in the same folder as the HTML file.

Make sure file extensions are visible in Windows.

Ensure it is not accidentally named:

flip.mp3.mp3

🖼 3. Page Image Rules

Images must be named:

page_1.png to page_7.png

If adding more pages:

Add new image file

Add corresponding <div class="page"> in HTML

Maintain reverse order inside the book container

🌐 4. How to Run the Project

Open the project folder.

Double-click Professional_FlipBook.html

Click once anywhere on the page (important for audio activation).

Use:

Next / Prev buttons

Left & Right arrow keys

Mouse scroll

Fullscreen button

⌨ Controls
Action	Control
Next Page	Right Arrow / Scroll Down / Next Button
Previous Page	Left Arrow / Scroll Up / Prev Button
Fullscreen	Full Screen Button
⚠ Browser Notes

Works best in:

Google Chrome

Microsoft Edge

Some browsers block sound until user interaction.

Always click once before flipping pages.

🔧 Customization

To change sound:

let flipSound = new Audio("flip.mp3");

Replace "flip.mp3" with your desired audio file name.

To adjust volume:

flipSound.volume = 0.7;  // 0.0 to 1.0
💻 Technical Details

Built using HTML, CSS (3D transforms), and JavaScript.

Fully offline project.

No external libraries required.

✅ Final Checklist Before Sharing

✔ All files in one folder
✔ Correct file names
✔ Sound working
✔ Images loading
✔ No console errors
