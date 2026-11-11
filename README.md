# English Plus 5 — Magic 3D Pop-Up Book (prototype v0.1)

An original educational 3D React application aligned by topic to **English Plus Grade 5 Student's Book**, Units 5 (Values, pp.54–67) and 6 (World of Work, pp.68–81).

## Run

Requires Node.js 18+.

```bash
npm install
npm run dev
```

Open the URL shown in the terminal. For a production build:

```bash
npm run build
npm run preview
```

Deploy the `dist` folder to Netlify, Vercel, or GitHub Pages (configure the base path for project subpaths).

## Included
- React Three Fiber book with animated cover, orbit/zoom, basic procedural 3D dioramas.
- 10 original Unit 5 and 12 original Unit 6 multiple-choice practice items with answer checking.
- Browser English speech synthesis for question and model labels.
- Local progress saving, SEN display option, teacher answer display.
- Text-file progress certificate.

## Prototype limitations
This is **not** the completed 22-activity specification: there are 22 **question cards**, not 22 distinct activity engines. Book pages do not yet turn individually, the 3D objects are simplified, and there is no drag-and-drop, original listening dialogues, speaking recording, 20-point assessment, PDF certificate or teacher dashboard. No claim of production readiness or verified mobile performance. No textbook illustrations or long passages are copied.
