# Snuck It In

**Snuck It In** is a party game turned mobile app that challenges players to seamlessly insert random phrases into conversation without being detected. Built with React Native and Firebase, this app enables real-time multiplayer gameplay—no App Store or Play Store required. Simply install Expo Go on your device, scan the QR code below, and start playing.

---

## Table of Contents

1. [Overview](#overview)  
2. [Technologies Used](#technologies-used)  
3. [How to Play](#how-to-play)  
4. [Download and Installation](#download-and-installation)  
5. [QR Code](#qr-code)  
6. [Project Structure](#project-structure)  
7. [Contributing](#contributing)  
8. [License](#license)  

---

## Overview

In **Snuck It In**, each player receives five random phrase cards containing absurd phrases. The objective is to say those phrases naturally in conversation without other players noticing. If a player successfully slips a phrase for at least 30 seconds, they mark it as “snuck it in.” If someone catches them, the phrase is marked as “failed” and the slipping player draws a new card. The first player to clear all playable cards wins, while the last remaining player with cards loses. The app handles phrase distribution, real-time score tracking, and group management using Firebase Realtime Database.

---

## Technologies Used

- **React Native (Expo Router)**  
  Modern cross-platform framework for building native applications using JavaScript/TypeScript.

- **Expo Go & EAS (Expo Application Services)**  
  - **expo-updates**: Over-the-air (OTA) update functionality.  
  - **EAS Update**: Publish new JavaScript bundles without re-submitting to the App Store.

- **Firebase Realtime Database**  
  Real-time, cloud-hosted JSON database for keeping game state and player data in sync across devices.

- **TypeScript**  
  Typed superset of JavaScript for enhanced developer experience and early error detection.

- **Expo Vector Icons**  
  Cross-platform icon library for consistent UI icons.

- **React Hooks**  
  Custom hooks to manage context and theming.

- **Expo Splash Screen**  
  Native splash screen configuration to improve user experience at launch.

---

## How to Play

1. **Create or Join a Group**  
   - One player taps **Create Group** to generate a unique 4-character group code.  
   - Other players tap **Join Group**, enter the code and their display name.  

2. **Start the Game**  
   - Once all players are in, the group host taps **Start Game**.  
   - Each player is assigned five unique phrases from the pool.  

3. **Snuck It In**  
   - Players attempt to insert their phrases naturally into conversation.  
   - If a player completes slipping a phrase unnoticed for at least 30 seconds, they tap **Snuck It In**. The card remains visible but is marked complete.

4. **Getting Caught**  
   - If another player correctly catches a slip within 30 seconds, the slipping player taps **Failed**.  
   - A **Draw New Phrase** button appears for the slipping player. They may tap it anytime to add a new phrase to their hand.

5. **Tracking Scores**  
   - The **Scoreboard** shows each player’s “playable cards” count, calculated as:  
   - Players are ranked by the fewest playable cards.  

6. **Winning and Losing**  
   - The first player to reduce their playable cards to zero is the winner.  
   - When only one player remains with playable cards, that player is the loser.

---

## Download and Installation

To run **Snuck It In** on your device, follow these steps:

1. **Install Expo Go**  
   - **iOS**: Download from the App Store:  
     [https://apps.apple.com/app/expo-go/id982107779](https://apps.apple.com/app/expo-go/id982107779)  
   - **Android**: Download from Google Play:  
     [https://play.google.com/store/apps/details?id=host.exp.exponent](https://play.google.com/store/apps/details?id=host.exp.exponent)

2. **Scan the QR Code**  
   - Open **Expo Go** on your device.  
   - Tap “Scan QR Code” (Android) or use the iOS Camera app.  
   - Point at the QR code below. The app will download and launch automatically.

---

## QR Code

Scan this QR code in **Expo Go** to download and play **Snuck It In** immediately:

![Snuck It In QR Code](./downloads/snuckitinqrcode.png)



