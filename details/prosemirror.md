## Overview

ProseMirror is a well-designed, modular toolkit for building rich text editors on the web. It provides the core functionality and document model that many higher-level editors (like TipTap) are built upon.

## Core Concepts

- Document model - structured, schema-based
- Transforms - atomic document changes
- Plugin system - extend functionality
- Collaborative editing - built-in support
- History - undo/redo system
- Commands - composable operations
- Input rules - convert text patterns
- Keymaps - keyboard shortcuts

## Architecture

- Modular design (12 separate modules)
- Schema-driven
- Immutable documents
- Predictable updates
- Reversible transformations
- Conflict resolution for collaboration

## Core Modules

- prosemirror-model - document model
- prosemirror-state - editor state
- prosemirror-view - UI component
- prosemirror-transform - document transformations
- prosemirror-commands - basic editing commands
- prosemirror-keymap - key bindings
- prosemirror-history - undo/redo
- prosemirror-inputrules - text pattern handling
- prosemirror-schema-basic - basic document schema
- prosemirror-schema-list - list functionality
- prosemirror-collab - collaborative editing
- prosemirror-gapcursor - cursor in non-text positions

## Features

- Real-time collaborative editing
- Custom document schemas
- Marks (inline formatting)
- Nodes (block elements)
- Decorations (non-permanent styling)
- Node views (custom rendering)
- Plugin system
- Transaction-based updates
- Change tracking
- Position mapping

## Collaborative Editing

- Operational transformation
- Conflict resolution
- Position mapping
- Version tracking
- Rebase support
- Authority model

## Use Cases

- Rich text editors
- Collaborative document editors
- Code editors
- Documentation platforms
- Note-taking applications
- Content management systems

## Higher-Level Editors Built on ProseMirror

- TipTap - Modern React/Vue editor
- Atlassian Editor - Used in Confluence, Jira
- Remirror - React-focused
- Guardian's Prosemirror setup
- New York Times editor

## React Integration

- Use directly with React
- Or use TipTap for better React integration
- Community React wrappers available
- Ref-based integration

## Developer Experience

- Steep learning curve
- Powerful and flexible
- Well-documented
- Active community
- Stable API

## Pricing

Free and open-source under the MIT license.