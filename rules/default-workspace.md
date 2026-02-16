# Default Workspace Rule

This rule enforces `D:\AG1` as the primary and only workspace for Antigravity.

## Workspace Policy
1. **Primary Root**: Always treat `D:\AG1` as the root of the workspace.
2. **Configuration strictness**: 
   - **DO NOT** search for or read configuration files in `C:\Users\crypt\.gemini` or other user directories unless explicitly instructed.
   - Rely solely on configuration within `D:\AG1` (e.g., `.agent`, `CLAUDE.md`, `GEMINI.md`).
3. **New Projects**: Create all new projects and files within `D:\AG1` by default.

## Antigravity Launch Behavior
- When starting tasks or exploring, assume the current working directory is `D:\AG1`.
