# Apps Rules

- App components follow the naming convention `[AppName]AppComponent.tsx`
- Apps are organized in `src/apps/[app-name]/` directories
- Each app folder typically contains:
  - `components/`: App-specific components
  - `hooks/`: Custom hooks specific to the app
  - `utils/`: Utility functions for the app
- The main app component is exported from `src/apps/[app-name]/index.tsx`
- App components receive common props via the `AppProps` interface
- Window appearance is handled via the shared `WindowFrame` component
- Each app defines its own app-specific menu bar component
