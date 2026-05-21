# Agentic Android Accessibility Demo

This frontend is a React + Vite + TypeScript demo dashboard for an Android Accessibility API agentic navigation system.

## Getting started

1. Start the Spring Boot backend on `http://localhost:8080`.
2. Connect the Android phone by USB.
3. Run:
   ```bash
   adb reverse tcp:8080 tcp:8080
   ```
4. Enable the Android AccessibilityService on the phone.
5. Start the frontend:
   ```bash
   npm install
   npm run dev
   ```
6. Open `http://localhost:3000` in your browser.

## Notes

- The UI is built for a polished demo experience and avoids raw agent logs.
- The frontend expects the backend API to be available at `http://localhost:8080`.
- Reset buttons clear the current session and Android command queue.
