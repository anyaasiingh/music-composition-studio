# 🎵 Scratch Music Composer Game

A simple interactive music composition game built using Scratch.

Users can record a sequence of musical instruments and replay the composition. The project demonstrates event-driven programming, broadcasting, variables, and user interaction in Scratch.

---

## ✨ Features

- 🎸 Play Guitar sound
- 🥁 Play Drum sound
- 🎹 Play Keyboard sound
- 🎙 Start Recording
- ▶ Replay recorded music
- 📢 Recording popup notification
- 🎵 Sequential playback with equal timing

---

## 🛠 Technologies Used

- Scratch 3.0
- Scratch Music Extension

---

## 🎮 How to Play

1. Click the Green Flag.
2. Press the **Record** button.
3. Click any instrument to record its sound.
4. Press the **Play** button.
5. Listen to your recorded composition.

---

## 🧠 Algorithm

1. Initialize all variables.
2. Wait for user input.
3. If Record button is clicked, enable recording.
4. If an instrument is clicked:
   - Play its sound.
   - Store it if recording is enabled.
5. When Play is clicked:
   - Read the stored sequence.
   - Play each instrument in order.
6. Repeat until the program stops.

---

## 🏗 Architecture Diagram

```text
                User
                  │
                  ▼
          Mouse Click Events
                  │
      ┌───────────┼───────────┐
      ▼           ▼           ▼
  Record      Instrument     Play
  Button        Sprites      Button
      │           │            │
      ▼           ▼            ▼
Recording     Play Sound   Read Sequence
 Status           │             │
      └───────────┼─────────────┘
                  ▼
          Music Sequence
                  │
                  ▼
         Sequential Playback
```

---

## 📂 Project Structure

```
Music Composer Game
│
├── Stage
├── Guitar Sprite
├── Drum Sprite
├── Keyboard Sprite
├── Record Button
├── Play Button
├── Variables
└── Music Extension

---


## 👨‍💻 Author

Made by **Anya**
