## Overview

Redux Batched Actions provides utilities to dispatch multiple Redux actions as a single batched action, triggering only one subscriber notification and potentially one re-render cycle.

## Features

- Batch multiple actions into one dispatch
- Reduces unnecessary re-renders
- Single subscriber notification
- Reducer-level batching
- Compatible with standard Redux middleware
- Lightweight wrapper around actions