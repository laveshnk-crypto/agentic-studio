# Agentic Studio

Agentic Studio is a visual workflow builder for creating chatbot conversations as connected flow nodes. It helps you design conversation logic quickly with drag-and-drop editing, test behavior in a built-in simulation mode, and export your work for sharing or reuse.

## Project Description

This project is a React + Vite web application focused on low-friction chatbot flow design. Users can add message nodes, condition nodes, and custom nodes, connect them in a canvas, and iterate rapidly on conversational logic. The app includes validation and simulation so that flows can be tested before export.

## What You Can Do

- Build chatbot flows visually using node-based editing.
- Add and connect multiple node types (text, condition, custom).
- Simulate step-by-step conversation execution from the start node.
- Test conditional routing using dynamic input during simulation.
- Save and auto-save flows locally in the browser.
- Export flows as JSON data or PNG flow diagrams.
- Use desktop and mobile-friendly layouts with theme toggle support.

## Tech Stack

- React 19
- Vite 7
- React Flow
- Tailwind CSS
- Radix UI primitives

## Quick Start

1. Install dependencies:
	 npm install
2. Start the development server:
	 npm run dev
3. Open the local URL shown in your terminal (Vite default is usually http://localhost:5173).

## Build For Production

- Create production build:
	npm run build
- Preview production build locally:
	npm run preview