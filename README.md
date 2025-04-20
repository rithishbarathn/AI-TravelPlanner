# 🌍 AI Travel Planner App

The **AI Travel Planner** is an intelligent mobile app that helps users effortlessly generate and manage personalized travel plans using Artificial Intelligence. Built with **React Native** and **Expo**, this project integrates modern cloud and AI capabilities through **Google Gemini**, **Firebase Authentication**, **Cloud Firestore**, and **Google Maps APIs** for places, photos, and geolocation. It offers features like trip generation, hotel recommendations, flight booking redirection, and itinerary visualizations. The app follows a clean and scalable codebase architecture powered by Git **submodules** for modular development and separation of concerns.

> ✨ Plan trips. Discover destinations. Book with ease. All from one intelligent platform.

---

## 📦 Git Submodule Setup

This project uses Git submodules for structured component organization:
- `/components` – Shared UI and screens
- `/firebase` – Firebase config, Firestore access, auth logic
- `/ai-engine` – Gemini Pro API logic for AI-generated trip suggestions

Clone the project along with submodules:

```bash
git clone --recurse-submodules https://github.com/your-username/ai-travel-planner.git
cd ai-travel-planner

