# 🥊 Royal_Duel – Real-Time Two-Player Fighting Game with Video Chat  
"Where strategy meets voice in real time."

Royal_Duel is a real-time browser-based fighting game where two 
remote players** connect to battle each other while communicating over
a live video call. Player 1 is assigned to the first user, and Player 2 to the next. 
The game synchronizes inputs instantly and streams peer-to-peer video to let players talk, taunt, and team up — all in one experience.


## 🚀 Project Overview

Royal_Duel was built as a multiplayer interactive browser game that fuses gaming and communication** using **WebRTC** and **Socket.IO**. Designed to enhance the experience of casual web games, it allows friends or strangers to fight competitively while chatting in real time, making the experience immersive and socially engaging.

---

## 🎯 The Problem

> Multiplayer browser games often lack **real-time communication**, making gameplay feel disconnected.  
Simultaneously, live video chat platforms are not built for **interactive real-time games**. This project bridges both worlds.

---

## 💡 Solution

BattleCall combines multiplayer gameplay with a built-in live video chat layer using modern web technologies:

- 🧍 **Player Assignment**: Automatic assignment as Player 1 or Player 2
- 🎥 **Live Peer-to-Peer Video Call** via WebRTC
- 🕹️ **Keyboard-Based Game Control** (Canvas-rendered)
- 🔄 **Real-time Game Sync** using Socket.IO
- 🗣️ **Voice Communication** during gameplay

---

## 🧠 Technology Stack

### 🧱 Frontend
- **HTML + CSS** – UI and game layout
- **JavaScript** – Game logic and event handling
- **Canvas** – Game rendering

### ⚙️ Backend
- **Node.js + Express.js** – Game server and signaling
- **Socket.IO** – Real-time bi-directional communication
- **WebRTC** – Peer-to-peer video and audio

---

## 🔁 How It Works

1. **Connect**: First user becomes Player 1, second becomes Player 2
2. **Sync**: Socket.IO syncs game controls in real-time
3. **Call**: WebRTC establishes a peer video call
4. **Play**: Players control their fighters and hear each other
5. **Battle**: Real-time fight and live reactions enhance the fun

---

## ⌨️ Controls

| Action       | Key  |
|--------------|------|
| Move Left    | `ArrowLeft`  |
| Move Right   | `ArrowRight`  |
| Jump         | `ArrowUp`  |
| Attack1       | `ArrowDown` |
| Attack2       | `Space` |

---
