# 🃏 Memory Card Game - Educational Tool

A web-based memory matching game designed specifically for teachers and students. Teachers can easily create custom word-matching games using Excel, and generate a unique link to send to their students. Students can play directly on their mobile phones without needing to download any apps or upload any files!

## ✨ Features

- **👨‍🏫 Teacher Mode (Custom Creation):** Upload an Excel file (`.xlsx`) with your terms (e.g., English words in Column A, Chinese translations in Column B).
- **🔗 Instant Share Links:** Automatically generates a unique, playable link containing your custom words. No backend database required!
- **📱 Student Mode (Mobile Friendly):** When opening the share link, students see a clean, distraction-free game interface perfectly scaled for mobile devices.
- **⏱️ Live Stats:** Built-in timer and score tracker to make learning competitive and fun.

## 🚀 How to Use

### For Teachers (Creating the Game)
1. Open the game in your desktop browser.
2. Create an Excel file with pairs of words in Column A and Column B.
3. Click **"Upload Excel File"** and select your file.
4. Click **"Generate & Create Link"**.
5. Copy the generated link and send it to your students via WeChat, email, or any messaging app!

### For Students (Playing the Game)
1. Simply tap the link provided by your teacher.
2. Click **"Deal Cards"** to study the positions briefly.
3. Click **"Start Game"** to flip the cards down and start the timer.
4. Find all the matching pairs as fast as you can!

## 🛠️ Technical Details
Built entirely with vanilla HTML, CSS, and JavaScript. 
It uses the `xlsx` library to parse Excel files purely on the front-end. The "Share Link" feature encodes the custom word data directly into the URL query parameters using Base64 encoding, ensuring zero server costs and maximum privacy.
