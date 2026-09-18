<div align="center">

# ⚡ Spark Assistant

**A voice-first, always-on AI assistant for Android that executes real-world actions through natural language.**

Built with Gemini Live API · Hybrid Architecture (Capacitor + Kotlin) · Zero-latency WebSocket streaming

[![Android](https://img.shields.io/badge/Android-8.0%2B-green?logo=android)](https://developer.android.com)
[![Gemini](https://img.shields.io/badge/Gemini-3.5%20Flash--Lite-blue?logo=google)](https://ai.google.dev)
[![Capacitor](https://img.shields.io/badge/Capacitor-6.x-119EFF?logo=capacitor)](https://capacitorjs.com)
[![Kotlin](https://img.shields.io/badge/Kotlin-1.9-purple?logo=kotlin)](https://kotlinlang.org)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

</div>

---

## 📖 Overview

**Spark Assistant** is a background-resident Android AI assistant that listens for the wake word **"Hey Spark"** and executes real actions on your device — calling contacts, sending WhatsApp messages, reading notifications, controlling media, toggling hardware, and more.

Unlike traditional voice assistants that only *chat*, Spark is a **doer**. It uses Gemini's function calling to translate natural speech into concrete Android system operations within milliseconds.

### ✨ Key Highlights

- 🎙️ **Real-time bidirectional audio** via Gemini Live WebSocket API
- ⚡ **Sub-second latency** using `gemini-3.5-flash-lite`
- 🔄 **Never-idle connection** — auto-connects on launch, auto-reconnects on network drops
- 🎯 **17+ native Android tools** — calls, SMS, WhatsApp, media, calendar, hardware
- 🧠 **Persistent memory** — remembers facts across sessions
- 🎨 **Floating overlay** — always accessible, even when the screen is off
- 🔐 **100% BYOK** — your API key never leaves your device

---

## 🏗️ Architecture

Spark uses a **Hybrid Architecture** that combines the speed of web tooling with the raw power of native Android:
