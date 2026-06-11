---
name: component-scaffolder
description: Generates standardized React components. Triggered when the user asks to "scaffold a component", "create a React component", or "build a UI element".
---

# Core Mandates
- Always initialize new components using TypeScript (`.tsx`).
- Style the component exclusively using Tailwind CSS utility classes.
- Include a standard, exported interface for `Props`.
- Ensure the output is a functional component utilizing arrow syntax.
- If state is required, default to React hooks (`useState`, `useEffect`).
- Output only the clean code block; suppress introductory text or follow-up suggestions.