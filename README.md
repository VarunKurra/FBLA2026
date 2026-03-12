# 🕵️ Project Retrace

hey! so this is **Retrace**, a lost and found app i built for FBLA 2026. basically, it's meant to help students find their lost stuff around campus without all the usual stress. 

i wanted to make it feel super modern and actually useful, so i added some pretty cool tech under the hood.

## 🚀 check it out
**Live Site:** [https://retrace-mo.vercel.app](https://retrace-mo.vercel.app)

## ✨ key features (the cool stuff)

*   **Neural Search 🧠:** okay, this is my favorite part. instead of just searching for keywords, you can actually describe what you lost in plain english (like "my crusty blue water bottle") and the AI (Groq + Llama 3) will try to find it. super helpful if you don't know the exact name of the item.
*   **Spatial Map 📍:** it's got a map view where you can see exactly where items were found. it even helps you navigate to them.
*   **Admin Console 🛡️:** i built a professional dashboard for school staff to manage all the reports, approve claims, and keep things organized.
*   **Premium UI ✨:** worked really hard on the design. it uses glassmorphism, smooth animations (thanks to framer-motion), and it's fully responsive so it looks great on a phone too.

## 🛠️ tech stack
*   **Frontend:** React + Vite (speed is key ⚡)
*   **Styling:** Vanilla CSS (custom designed from scratch)
*   **Animations:** Framer Motion
*   **Backend/DB:** Supabase
*   **AI:** Groq API (Llama-3-8b)

## 🏗️ how to run it locally
if you want to play around with the code, here's how to get it running:

1.  clone the repo: `git clone https://github.com/VarunKurra/FBLA2026.git`
2.  install dependencies: `npm install`
3.  create a `.env` file and add your `VITE_GROQ_API_KEY`
4.  start the dev server: `npm run dev`

hope you like it! let me know if you have any questions. ✌️
