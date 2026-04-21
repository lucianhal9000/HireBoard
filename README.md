# HireBoard

A clean job application tracker built with **Next.js 14 (App Router)**, **TypeScript**, and **MUI v5**.

## Features

- Kanban board: Applied / Interview / Offer / Rejected
- Drag & drop with `@hello-pangea/dnd`
- Add/Edit via MUI Dialog, details via MUI Drawer
- Light/Dark mode toggle with MUI ThemeProvider
- Table view at `/list` using **MUI DataGrid** (sorting + quick filtering)
- Persistence via browser `localStorage` (no server DB yet)

## Getting started

Install dependencies:

```bash
npm install
```

Run the dev server:

```bash
npm run dev
```

Open `http://localhost:3000`.

## Notes

- Job data is stored in `localStorage` under the key `hireboard:jobs`.
- The API route at `app/api/jobs/route.ts` is a placeholder for a future persistent backend.

"# HireBoard" 
