# Test Site

A simple static website for testing, hosted on GitHub Pages. The design is inspired by the [Momentum Design System](https://momentum.design/en/) by Webex/Cisco.

## Project Structure

```
site/
├── index.html      # Main landing page
├── style.css       # Momentum-inspired styles
├── README.md       # This file
└── scripts/       # (Future) Static JavaScript files
```

## Hosting on GitHub Pages

### Option 1: Deploy from a branch

1. Create a new repository on GitHub (or use an existing one)
2. Push this folder's contents to the repository
3. Go to **Settings** → **Pages**
4. Under **Source**, select your branch (e.g. `main`) and folder (e.g. `/` root)
5. Save — your site will be live at `https://<username>.github.io/<repo-name>/`

### Option 2: Deploy from a subfolder

If this site lives in a subfolder (e.g. `site/`) of your repo:

1. Go to **Settings** → **Pages**
2. Under **Source**, select the branch and set the folder to `/site` (or your folder name)

## Adding Static JavaScript Files

To host static `.js` files for use in other projects:

1. Create a `scripts/` directory in the repo root
2. Add your JavaScript files (e.g. `scripts/example.js`)
3. Reference them from your site or external projects:
   ```html
   <script src="https://<username>.github.io/<repo-name>/scripts/example.js"></script>
   ```

## Design Reference

This site uses styling inspired by Momentum:

- **Colors**: Webex brand blues (`#2E64F3`, `#1CC6FF`)
- **Typography**: System font stack with Momentum-style size/weight scale
- **Spacing & elevation**: Token-based spacing and subtle shadows

See [momentum.design](https://momentum.design/en/) for the full design system documentation.
