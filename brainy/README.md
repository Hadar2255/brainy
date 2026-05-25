# 🦉 Brainy – אפליקציית זיכרון | Memory Training App

> אפליקציית מובייל בסגנון Duolingo ללימוד 7 שיטות זיכרון מוכחות.
> A Duolingo-style mobile app for learning 7 proven memory techniques.

---

## ⚡ התחלה מהירה / Quick Start

### לראות את האפליקציה עכשיו / See it now
לאחר הפעלת GitHub Pages לריפו זה:
```
https://hadar2255.github.io/brainy/preview/
```

### הרצה מקומית / Run locally
```bash
# מוקאפים HTML (אין צורך בהתקנה)
cd mockups && python3 -m http.server 8000
# → http://localhost:8000

# Preview אינטראקטיבי עם הטלפון
cd preview && python3 -m http.server 8000

# אפליקציית React Native אמיתית
cd app
npm install
npx expo start  # סרוק QR ב-Expo Go
```

---

## 📁 מבנה הפרויקט

```
brainy/
├── mockups/          # שלב 1: 14 מוקאפי HTML/CSS/JS אינטראקטיביים
├── app/              # שלב 2: אפליקציית React Native + Expo
├── preview/          # Preview אינטראקטיבי לדפדפן (מסגרת טלפון)
└── docs/             # תיעוד 7 שיטות הזיכרון
```

---

## ✨ פיצ'רים / Features

- 🦉 דמות תנשמת חמודה (Hoot) - סגנון ג'יבלי גיאומטרי
- 🎨 עיצוב גימיפיקציה עם gradients, glassmorphism, ואנימציות
- 🌐 דו-לשוני: עברית (RTL) + אנגלית (LTR)
- 🎮 5 סוגי תרגילים: Teach, Multiple Choice, Match, Recall, Order
- 🔥 רצפים יומיים, XP, hearts, הישגים
- 💾 שמירת התקדמות אוטומטית (AsyncStorage)
- 📱 קוד אחד שרץ ב-iOS, Android, ובדפדפן

---

## 🧠 7 שיטות הזיכרון

| # | שם | אייקון |
|---|-----|--------|
| 1 | MOM (Motivation, Observation, Mechanism) | 🧠 |
| 2 | PIE - ארמון הזיכרון | 🏰 |
| 3 | Chain Linking - שרשור | 🔗 |
| 4 | Body List - רשימת גוף | 🧍 |
| 5 | Peg System - עוגנים | ⚓ |
| 6 | Substitution - המרה | 🎨 |
| 7 | FAST - למידה מהירה | ⚡ |

תיעוד מלא: [docs/memory-methods.md](docs/memory-methods.md)

---

## 🛠 Tech Stack

| Layer | Tech |
|-------|------|
| App | React Native 0.74 + Expo SDK 51 |
| Routing | Expo Router (file-based) |
| State | Zustand + AsyncStorage |
| i18n | i18next + react-i18next |
| UI | react-native-svg + expo-linear-gradient + reanimated |
| Language | TypeScript |

---

## 📜 רישיון

פרויקט פרטי ללימוד אישי. לא לשימוש מסחרי.

Personal learning project. Not for commercial use.
