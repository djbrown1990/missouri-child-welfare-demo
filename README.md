# missouri-child-welfare-demo

Production-style static executive demo deck for:

**Missouri Child Welfare - Reconciliation & Compliance Gate**

This deck is designed for a video walkthrough targeting public-sector executives and technical evaluators. It covers:
- Business problem and use case
- Mock setup architecture
- Salesforce data fragmentation model
- Reconciliation + compliance workflow
- Live demo flow and AWS evidence path

## Run locally

1. Open `index.html` directly in your browser.
2. Or use a simple static server if preferred.

Example:

```powershell
cd missouri-child-welfare-demo
start index.html
```

## Recording tips

- Use fullscreen for clean framing: press `F`.
- Navigate with keyboard: `Left/Right`, `Home/End`.
- Press `Esc` to exit fullscreen.
- Hide browser bookmarks/address bar before recording.
- Keep browser zoom at 100% for consistent typography.

## Deploy to GitHub Pages

1. Create a new GitHub repo.
2. Push this folder to `main`.
3. In GitHub: `Settings` -> `Pages`.
4. Under "Build and deployment":
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/(root)**
5. Save and wait for Pages URL to publish.

## Notes

- Mermaid diagrams use CDN and gracefully fall back to plain-text diagram summaries if rendering fails.
- No metrics are fabricated; placeholders are used where measurements are required.
