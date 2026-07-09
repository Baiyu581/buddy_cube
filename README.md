# Companion Cube AI Robot

A hand-sized, modular AI companion cube inspired by the Portal series.

## Project Overview

An intelligent, voice-driven companion that adapts to your location and preferences. It can dock onto different bases to unlock new capabilities (car mount, robotic arm, etc.).

## Features

- Natural voice interaction with personality
- Location awareness (Home / Away / Driving modes)
- Long-term memory of user preferences
- Music control with mood detection
- Modular docking system for future expansion

## Current Status

- Phase 0: Planning (In Progress)
- Phase 1: Core Voice Assistant (Planned)

## Tech Stack

- **Hardware**: Raspberry Pi Zero 2 W, GPS module, pogo pins
- **Software**: Python, Whisper (ASR), SQLite, threading

## How to Run

```bash
git clone https://github.com/yourusername/companion-cube-ai.git
cd companion-cube-ai
pip install -r requirements.txt
python src/main.py
