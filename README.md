# Eight Ways Mobile

Mobile app that helps people build healthy habits based on the **8 natural remedies of Ellen G. White**, in an accessible and intuitive way.

> Backend: [eight-ways-api](https://github.com/Joao-Adegas/eight-ways-api)

## Features

- Home screen with the 8 natural remedies
- Daily questionnaire to track progress
- "My Goals" section to follow and customize goals
- Recommendations with goal suggestions for each remedy
- **Lumin**, a chatbot that answers questions about the remedies and helps with habit change

The interface favors intuitiveness, with visible buttons and confirmation messages for key actions such as adding and deleting goals.

## Tech stack

React Native, Expo. Prototyped in Figma.

## Getting started

### Prerequisites

- Node.js and npm
- [Expo Go](https://expo.dev/go) installed on your phone
- [eight-ways-api](https://github.com/Joao-Adegas/eight-ways-api) running (chatbot and goals services)

### Run

```bash
npm install
npx expo start
```

Scan the QR code with Expo Go to open the app on your phone.

### Configure the API address

Replace the IP address in the app's API calls with your machine's IP, for example:

```
http://<YOUR_IP>:8000/usuarios/1/objetivos_personalizados/
```

Your phone and your computer must be on the same network.

## Team

- Gabriela Alejandra Bergamine dos Santos
- João Pedro dos Santos Adegas — [@Joao-Adegas](https://github.com/Joao-Adegas)
- Pedro Sérgio

Project developed for the Hackathon 2025 – Unasp Tech.
