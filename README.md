# BRO-S-BIRTHDAY
# 🎂 Happy Birthday Bro — Birthday Surprise Website

A modern, interactive, and responsive birthday surprise website created for a male friend.

The website features birthday animations, interactive surprises, friendship wishes, background music, and a birthday cake celebration.

## 🎉 Features

- 🎂 Birthday-themed design
- 🎁 Interactive birthday surprise cards
- 🎵 Background birthday music
- 🎊 Animated birthday confetti
- 💌 Friendship birthday letter
- 🎂 Interactive birthday cake
- ✨ Animated entrance screen
- 🌌 Modern dark purple design
- 📱 Fully responsive layout
- 💻 Single HTML file
- 🎨 Customizable birthday messages and name

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- Google Fonts

No frameworks or additional JavaScript libraries are required.

## 📂 Project Structure

```text
Birthday-Surprise/
│
├── index.html
└── README.md
```

## 🚀 How to Run

1. Download or copy the project code.
2. Create a folder named `Birthday-Surprise`.
3. Create a file named `index.html`.
4. Paste the complete birthday website code into the file.
5. Save the file.
6. Open `index.html` in Google Chrome or another modern browser.
7. Click **Open Your Birthday Surprise**.
8. Tap the music button to play the birthday music.
9. Explore the birthday gifts, letter, and cake celebration.

## 🎵 Background Music

The website includes an external MP3 birthday music link.

Music starts when the user clicks the music button because browsers may block automatic audio playback.

An internet connection is required to load the external music file.

## 🎁 Birthday Surprise Sections

### 1. Birthday Entrance

An animated birthday welcome screen with a birthday cake and surprise button.

### 2. Birthday Greeting

A personalized birthday greeting with a friendship-focused message.

### 3. Interactive Birthday Gifts

Three birthday cards containing:

- Birthday wishes
- Friendship appreciation
- Motivation and best wishes

### 4. Birthday Letter

A personal birthday message celebrating friendship and wishing happiness, success, and good memories.

### 5. Birthday Cake

An interactive cake section with a birthday wish and confetti celebration.

## 🎨 Customization

Open `index.html` and locate the JavaScript configuration:

```javascript
const CONFIG = {
  name: "Bro",
  gifts: [
    // Birthday messages
  ]
};
```

### Change the Birthday Name

Replace:

```javascript
name: "Bro",
```

with your friend's name.

### Change Birthday Messages

Edit the messages inside:

```javascript
CONFIG.gifts
```

You can customize the birthday wishes, friendship messages, and motivational messages.

### Change Background Music

Find the audio element in the HTML:

```html
<audio id="birthdayMusic" loop preload="none">
  <source
    src="YOUR_MP3_LINK"
    type="audio/mpeg">
</audio>
```

Replace `YOUR_MP3_LINK` with your preferred publicly accessible MP3 link.

## 📱 Compatibility

The website is designed for:

- Desktop computers
- Windows laptops
- Android smartphones
- Modern web browsers

## 🎂 Project Purpose

This project is a creative birthday surprise made to celebrate friendship through an interactive website.

It combines web development, animation, music, and personalized birthday messages into one experience.

## 👨‍💻 Credits

**Created by:** Biprajit Kar

**Project:** Birthday Surprise Website

**Purpose:** Birthday celebration for a friend

**Made with:** HTML, CSS, and JavaScript

## 🎉 Final Message

Happy Birthday, Bro!

May your birthday be filled with happiness, laughter, success, and unforgettable memories.

Have an amazing birthday! 🎂
