## Overview

An open-source demo project that showcases how to build a Kanban board using React Admin, shadcn/ui components, and @hello-pangea/dnd for drag-and-drop interactions.

## Features

- Three-column Kanban board layout (todo, in progress, done) with responsive design
- Drag-and-drop card movement between columns using @hello-pangea/dnd
- Optimistic UI updates for instant drag-and-drop feedback without flicker
- Automatic order recalculation when cards are moved or reordered
- Modal-based todo creation form with default values and status selection
- Modal-based todo editing form with pessimistic mutation mode
- Custom data provider with automatic order calculation on creation
- Local state management synced with React Admin backend data
- Styled cards using shadcn/ui components (Card, Badge, Button, Dialog)
- TypeScript support with typed components and hooks
- Custom hooks: useTodosByStatus for state management, useTodoKanban for drag-and-drop bridging
- Visual feedback during drag operations (shadow, rotation effects)
- Droppable column highlighting when dragging over

## Components

- **KanbanBoard**: Main board wrapper with DragDropContext
- **TodoCard**: Individual task card with drag handle and click-to-edit
- **TodoCreate**: Modal dialog for creating new todos
- **TodoEdit**: Modal dialog for editing existing todos
- **TodoInputs**: Reusable form inputs component
- **TodoListActions**: Toolbar with create button

## Tech Stack

- React Admin (ra-core)
- shadcn/ui components
- @hello-pangea/dnd for drag-and-drop
- Vite + TypeScript
- Tailwind CSS
- ra-data-fakerest for mock data