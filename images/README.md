# Images

```
images/
├── wireframes/     ← authored layout mocks, badged "WIREFRAME" (committed)
├── screenshots/    ← YOUR real console captures (you create these)
└── diagrams/       ← optional: exported Mermaid, if your blog can't render it inline
```

## wireframes/ — what these are and are not

| File | Screen | Referenced in |
|---|---|---|
| `01-enable-aws-transform.svg` | The Enable / Get started setup page | Part 1 |
| `02-settings-tab.svg` | Settings tab with the web app + IDE URLs | Part 1 |
| `03-workspace-job-types.svg` | Workspace with the five job-type cards | Part 1D |
| `04-campaign-dashboard.svg` | Campaign dashboard with per-repo status | Part 7B |

**These are layout mocks, not screenshots.** Each carries a visible `WIREFRAME — not a screenshot` badge. They exist to orient you on where things sit before you click, and to make the guide readable by someone who hasn't enabled the service yet.

The live AWS Transform console **will** look different, and AWS changes it regularly. Never present a wireframe as a capture.

They're hand-authored SVG, so you can edit them in any text editor or open them in Inkscape/Figma.

## screenshots/ — the real thing

Empty by design. You populate it as you work through the guide.

The full capture list, filenames, redaction checklist, and capture-hygiene notes live in **[Appendix A of the guide](../README.md#appendix-a--screenshot-capture-plan)**.

Quick version:

```bash
mkdir -p images/screenshots
# then save captures as 01-budget-created.png, 02-get-started.png, …
```

⚠️ **Before publishing any capture, redact:** AWS account ID, profile/tenant ID in URLs, email addresses, IAM principal names, private repo URLs, and any real hostnames or IPs.

## diagrams/ — optional

Only needed if your blog platform can't render Mermaid. Paste a diagram's code into [mermaid.live](https://mermaid.live), export, and save here. Prefer SVG.
