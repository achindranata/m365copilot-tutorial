# Microsoft Copilot — End-User Coursework

A self-paced course on Microsoft Copilot, published as a static site.

## Publish on GitHub Pages

1. Create a repository and copy everything in this folder into it (keep the folder structure).
2. Commit and push to the `main` branch.
3. In the repository, open **Settings > Pages**.
4. Under **Build and deployment**, set **Source** to *Deploy from a branch*, pick `main` and the `/ (root)` folder, then **Save**.
5. The site goes live at `https://<user>.github.io/<repository>/` within a minute or two.

To serve it from a `docs/` folder instead, put these files in `docs/` and choose that folder in step 4.

## Structure

| Path | Page |
|---|---|
| `index.html` | Course outline — the landing page |
| `module-1-meet-copilot/` | Module 1 — Meet Copilot & Where to Access It |
| `module-2-fundamentals/` | Module 2 — Copilot Fundamentals & Safe Use |
| `module-3-prompting/` | Module 3 — Prompting Like a Pro |
| `module-4-office-apps/` | Module 4 — Copilot in the Office Apps |
| `module-5-first-party-agents/` | Module 5 — First-Party Agents |
| `module-6-copilot-modes/` | Module 6 — Microsoft Copilot Modes: Cowork, Code, Autopilot |
| `module-7-build-your-dashboard/` | Module 7 — Build Your Dashboard with Microsoft Copilot |
| `module-8-build-your-agent/` | Module 8 — Build Your Agent in Microsoft Copilot |
| `module-9-copilot-studio-agents/` | Module 9 — Build Your Agent in Copilot Studio |
| `module-10-agentic-workflows/` | Module 10 — Build your Agentic Workflow in Copilot Studio |
| `module-11-build-your-app/` | Module 11 — Build Your App with Copilot |
| `beyond-the-basics/` | Appendix — Beyond the Basics |
| `assets/styles.css` | Shared stylesheet (all images inlined) |
| `M365CopilotTutorial.html` | The whole course as one printable file |

Every page carries the left-hand agenda, so any module is one click away.
The interactive mock-ups and the Work IQ toggle are CSS-only — no JavaScript, no build step,
no external requests.

## Local preview

```bash
python -m http.server 8000
```

Then open <http://localhost:8000>.
