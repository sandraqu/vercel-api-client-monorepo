# Studio Silverica

For your pleasure, a sample monorepo setup with /client and /server living in separate folders and deploying to vercel. The client is a sample Vite React app, and the server is a Node.js server using Express.js

```
your-project/
├── client/
│ ├── src/
│ │ ├── main.tsx (or main.jsx)
│ │ ├── App.tsx (or App.jsx)
│ │ └── ... (other client components, assets, etc.)
│ ├── public/
│ │ ├── vite.svg
│ │ └── ... (other public assets)
│ ├── vite.config.ts (or vite.config.js)
│ ├── tsconfig.json (if using TypeScript)
│ ├── package.json
│ ├── index.html
│ └── ... (other static files)
├── server/
│ ├── server.mjs (Your Node.js/Express server code)
│ └── package.json
├── vercel.json (Vercel deployment configuration)
├── .gitignore
└── README.md
```
