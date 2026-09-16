# HiveFive — KVIC Beekeeping Intelligence Dashboard

A ready-to-run React + Vite + Tailwind project containing the HiveFive-themed
KVIC beekeeping dashboard prototype.

## Requirements

- Node.js 18 or newer (check with `node -v`)
- npm (comes with Node.js)

## Run it

1. Unzip this folder and open a terminal inside it.
2. Install dependencies:

   ```
   npm install
   ```

3. Start the dev server:

   ```
   npm run dev
   ```

4. Open the URL it prints (usually `http://localhost:5173`) in your browser.

That's it — the dashboard should load with live mock data, charts, tables,
CSV export, and the mobile-responsive HiveFive theme.

## Build for production

```
npm run build
npm run preview
```

`npm run build` outputs a static `dist/` folder you can deploy anywhere
(Netlify, Vercel, GitHub Pages, a plain static file host, etc.).

## Project structure

```
hivefive-dashboard/
├── index.html
├── package.json
├── postcss.config.js
├── tailwind.config.js
├── vite.config.js
└── src/
    ├── main.jsx              # React entry point
    ├── App.jsx                # Renders the dashboard
    ├── HiveFiveDashboard.jsx  # The dashboard itself (all logic + data)
    └── index.css              # Tailwind directives
```

All dashboard logic, mock data, and interactivity live in
`src/HiveFiveDashboard.jsx` — everything else here is just the
scaffolding needed to run it.
