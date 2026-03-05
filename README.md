# TaskBoard Pro

TaskBoard Pro is a high-performance, portfolio-ready Kanban board designed with a premium, modern aesthetic.

Instead of a standard, utilitarian dashboard, TaskBoard Pro features a stunning Glassmorphism UI. It uses a soft gradient background paired with frosted-glass translucent columns, and smooth interactive hover effects to deliver a highly tactile user experience.

Note: This project is built using a coordinated Multi-Agent AI framework (via Antigravity), where specific AI personas (e.g., Frontend Developer, Orchestrator) collaborate based on strict SKILL.md guidelines.

## Tech Stack

Built for speed and fluid interactions using:

Core Framework: Next.js 15+ (App Router, Server Components, Server Actions)

Styling: Tailwind CSS (for layout, typography, and advanced backdrop-blur glass effects)

Interactivity: @dnd-kit/core (for seamless drag-and-drop physics)

State Management: React 19 Hooks (leveraging useOptimistic for instantaneous UI feedback)

## Core Features

Interactive Pipeline: Four main columns to manage workflows: Backlog (Task Ready), In Progress, Needs Review, and Done.

Draggable Task Cards: Cards feature titles, descriptions, user avatars, and color-coded priority tags (🔴 Red for High, 🟠 Amber for Medium, 🔵 Blue for Low).

Fluid Drag & Drop: Smooth animations and physics when picking up, hovering, and dropping tasks across the board.

Add Task Modal: A sleek, matching glass-themed modal to easily inject new tasks into the workflow without breaking context.

Optimistic Updates: The UI reacts instantly to user interactions before waiting for server confirmations.

## Multi-Agent Development Structure

This repository is built and maintained by specialized AI agents. Check the skills/ directory for the strict behavioral boundaries of each agent:

skills/frontend-developer/SKILL.md: Manages the Next.js UI, dnd-kit logic, and Tailwind Glassmorphism.

(More agent skills to be added as the project expands)

🛠️ Getting Started

First, run the development server:

npm install
# then
npm run dev
# or
yarn dev
# or
pnpm dev


Open http://localhost:3000 with your browser to see the result.
