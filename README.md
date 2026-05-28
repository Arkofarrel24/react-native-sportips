<h1 align="center">🏃 SPORTIPS</h1>
<p align="center"><b>Sports tutorials for beginners</b></p>

<p align="center">
  <img src="https://img.shields.io/badge/Expo-000020?logo=expo&logoColor=white" />
  <img src="https://img.shields.io/badge/React_Native-61DAFB?logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white" />
</p>

A beginner-friendly mobile app that provides sports tutorials and guides, helping newcomers learn how to exercise and get started with various sports. Built with Expo (React Native) and TypeScript.

## Features

- 📋 Browse a list of sports with detailed tutorial pages
- 🔐 User authentication (login & register)
- 📱 Cross-platform — runs on Android, iOS, and web via Expo

## Tech Stack

- **Framework:** Expo (React Native)
- **Language:** TypeScript
- **Routing:** Expo Router (file-based)
- **Forms & Validation:** React Hook Form + Zod
- **HTTP Client:** Axios
- **Package Manager:** pnpm

## Project Structure

```
app/          screens & routes (file-based routing)
components/   reusable UI components (Button, Form, Header, etc.)
contexts/     React contexts (e.g. auth)
hooks/        custom hooks (e.g. useAuth)
libs/         utilities & helpers
assets/       images & static files
```

## Get Started

1. Install dependencies
   ```bash
   pnpm install
   ```

2. Set up environment variables — create a `.env` file:
   ```
   EXPO_PUBLIC_API_URL=http://<your-backend-host>:8000/api
   ```
   > Note: this app connects to a separate backend API for authentication and sports data. The frontend runs standalone, but login/data features require the backend to be running.

3. Start the app
   ```bash
   npx expo start
   ```
   Then open it in an Android emulator, iOS simulator, Expo Go, or the web.

## Contributors

This is a team project. See the [contributors page](https://github.com/Arkofarrel24/react-native-sportips/graphs/contributors) for everyone involved.

---

<p align="center">Built as a collaborative learning project.</p>
