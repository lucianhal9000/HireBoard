<div align="center">

<h1>📋 HireBoard</h1>

<p><strong>A modern, full-featured job application tracker built with Next.js 14.</strong><br/>
Track every stage of your job search — from first click to final offer.</p>

[![Next.js](https://img.shields.io/badge/Next.js-14-black?logo=next.js&logoColor=white)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![MUI](https://img.shields.io/badge/MUI-v5-007FFF?logo=mui&logoColor=white)](https://mui.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)
[![CI](https://github.com/lucianhal9000/HireBoard/actions/workflows/ci.yml/badge.svg)](https://github.com/lucianhal9000/HireBoard/actions/workflows/ci.yml)

</div>

---

## ✨ Features

| Feature | Description |
|---|---|
| 🗂️ **Kanban Board** | Visual pipeline across Applied → Interview → Offer → Rejected |
| 🖱️ **Drag & Drop** | Reorder and move cards with `@hello-pangea/dnd` |
| ✏️ **Add / Edit Jobs** | Full form in an MUI Dialog — company, role, link, notes, date |
| 🔍 **Detail Drawer** | Side panel with all job info at a glance |
| 🌓 **Light / Dark Mode** | System-aware theme toggle via MUI `ThemeProvider` |
| 📊 **Table View** | `/list` route powered by MUI DataGrid with sorting & quick-filter |
| 💾 **Persistent Storage** | Saved to `localStorage` — no account or backend required |

---

## 🛠️ Tech Stack

- **Framework** — [Next.js 14](https://nextjs.org/) (App Router)
- **Language** — [TypeScript](https://www.typescriptlang.org/)
- **UI Library** — [MUI v5](https://mui.com/) (DataGrid, Dialog, Drawer, ThemeProvider)
- **Drag & Drop** — [@hello-pangea/dnd](https://github.com/hello-pangea/dnd)
- **Storage** — Browser `localStorage`

---

## 🚀 Getting Started

### Prerequisites

- Node.js ≥ 18
- npm ≥ 9

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/lucianhal9000/HireBoard.git
cd HireBoard

# 2. Install dependencies
npm install

# 3. Start the development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### Build for Production

```bash
npm run build
npm start
```

---

## 📁 Project Structure

```
HireBoard/
├── app/
│   ├── api/
│   │   └── jobs/
│   │       └── route.ts        # Placeholder for future REST backend
│   ├── list/
│   │   └── page.tsx            # Table view with MUI DataGrid
│   ├── layout.tsx
│   └── page.tsx                # Kanban board view
├── components/
│   ├── Board/                  # Kanban columns & cards
│   ├── JobDialog/              # Add / Edit job form
│   ├── JobDrawer/              # Job detail side panel
│   └── ThemeToggle/            # Light / dark mode switch
├── hooks/
│   └── useJobs.ts              # localStorage CRUD logic
├── types/
│   └── job.ts                  # Job interface / enums
└── theme/
    └── index.ts                # MUI theme configuration
```

---

## 🗺️ Roadmap

- [ ] Cloud sync (Supabase / Firebase backend)
- [ ] Export to CSV / PDF
- [ ] Deadline reminders & calendar integration
- [ ] Statistics dashboard (apply rate, response rate, stage funnel)
- [ ] Browser extension for one-click job capture

---

## 🤝 Contributing

Contributions are welcome! Please open an issue first to discuss what you'd like to change.

1. Fork the repo
2. Create a branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "feat: add your feature"`
4. Push and open a Pull Request

---

## 📄 License

Distributed under the [MIT License](./LICENSE).

---

<div align="center">
  Built by <a href="https://github.com/lucianhal9000">Likhith</a> · Give it a ⭐ if it helped!
</div>
