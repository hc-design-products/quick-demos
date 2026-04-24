# Prototype Gallery

A static HTML gallery for design prototypes and interaction demos.

## Structure

```
index.html              ← gallery homepage
demos/
  badge.html            ← Badge Guideline
  timeline.html         ← Timeline Picker
  asset-cards.html      ← Asset Cards
  gift-card.html        ← Gift Card
  claw-game.html        ← Claw Game
```

## Adding a new demo

1. Drop your `.html` file into `/demos`
2. Open `index.html` and copy one of the existing `<a class="demo-card">` blocks
3. Update the title, description, tags, href, and preview illustration
4. Commit and push — Vercel redeploys automatically

## Deploy to Vercel

1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) → Add New Project → import this repo
3. Click Deploy (no settings needed)

Your gallery will be live at `your-project.vercel.app`
