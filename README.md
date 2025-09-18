This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
# 🎥 AI-Powered Interview Proctoring App

A React + TensorFlow.js powered **proctoring system** that runs entirely in the browser.  
It monitors whether a candidate is **looking at the screen** and detects **mobile phones** in real-time, raising alerts and generating session reports.

---

## ✨ Features

- 🌗 **Dark/Light Mode Toggle** – switch between dark mode and system theme.
- ↔️ **Horizontal Flip** – mirror the webcam feed.
- 📸 **Screenshots** – capture snapshots from the live camera.
- 📽️ **Manual Video Recording** – record short clips with session logs.
- 🤖 **Auto Recording** – automatically start recording when a person is detected.
- 🔊 **Volume Control** – adjust notification sound level.
- 🎨 **Canvas Highlighting** –  
  - 🔴 Person detection → Red box  
  - 🟡 Mobile phone detection → Yellow box  
  - 🟢 Other objects → Green box
- 🚨 **Real-time Alerts**  
  - Beeps + toast notification when candidate looks away for **5+ seconds**  
  - Alerts if a **mobile phone** is detected
- 📝 **Session Report**  
  - Automatically saves a JSON file when recording stops  
  - Each log entry includes:
    ```json
    
    ```

---

## 🛠️ Tech Stack

- **Frontend:** React + Next.js (Client Components)
- **UI:** [shadcn/ui](https://ui.shadcn.com/), TailwindCSS, [lucide-react](https://lucide.dev)
- **ML Model:** [TensorFlow.js](https://www.tensorflow.org/js) + [coco-ssd](https://github.com/tensorflow/tfjs-models/tree/master/coco-ssd)
- **Notifications:** [Sonner](https://sonner.emilkowal.ski/)
- **Media:** `react-webcam`, `MediaRecorder API`

---
2️⃣ Install Dependencies
npm install
# or
yarn install

3️⃣ Run Development Server
npm run dev





