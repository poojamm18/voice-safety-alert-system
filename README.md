# Voice Safety Alert System

A Python-based voice-activated emergency alert prototype developed during the HackAura 24-Hour Hackathon.

The system continuously listens for predefined emergency keywords and automatically triggers emergency voice messages and a siren sound when a potential distress situation is detected.

---

## Problem Statement

In emergency situations such as harassment, assault, abduction, or other unsafe circumstances, a person may not be able to access their phone and call for help immediately.

This project aims to provide a hands-free emergency alert mechanism using voice recognition and automated audio alerts.

---

## Features

- Real-time microphone monitoring
- Voice-triggered emergency alerts
- Multilingual trigger-word detection
- Automated playback of help messages
- Siren activation during emergencies
- Manual alert trigger support
- Background execution using multithreading

---

## Technologies Used

- Python
- SpeechRecognition
- Pygame
- Threading

---

## Supported Trigger Words

The system supports multiple emergency keywords across different languages.

### English

- help
- stop
- danger
- emergency
- rescue
- attack
- harassment
- abuse
- assault
- police
- save me

### Hindi

- bachao
- madad
- madad karo
- mujhe bachao
- bachaiye
- bacha lo

### Telugu

- naaku help
- naaku sahayam cheyyandi
- nannu baachandi

### Kannada

- sahayam
- sahaya
- nanna rakshisi
- dayavittu sahaya maadi

---

## Project Workflow

```text
Microphone Input
       ↓
Speech Recognition
       ↓
Trigger Word Detection
       ↓
Emergency Alert Activated
       ↓
Help Messages Played
       ↓
Siren Sound Played
```

---

## Project Structure

```text
voice-safety-alert-system
│
├── assets
│   └── audio_files_placeholder.txt
│
├── voice_safety_alert.py
│
└── README.md
```

---

## Team

Developed during HackAura 24-Hour Hackathon by:

- Pooja M M
- Rohini R K
- Rachana Nagaraju

---

## Limitations

The original hackathon audio assets are currently unavailable.

The project was designed to use:

- help1.mp3
- help2.mp3
- help3.mp3
- siren.mp3

These files can be replaced with custom emergency recordings and siren sounds.

---

## Future Enhancements

- Mobile application integration
- GPS location sharing
- SMS-based emergency alerts
- AI-powered distress detection
- Additional language support
- Cloud-based emergency notification system