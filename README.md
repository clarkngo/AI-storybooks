# Tiny TaleBots — AI Storytime Corner 📚

A single-page site of AI-generated children's storybooks — playful stories about friendship, curiosity, and technology, each with a cover image, a themed description, and a short YouTube read-aloud video.

Live at: **https://clarkngo.github.io/AI-storybooks/**

## What's in it

- [`index.html`](index.html) — the whole site: a card list of storybooks, each linking out to its full story (shared via Gemini) and opening a "Watch video" modal for its YouTube read-aloud.
- [`assets/`](assets/) — cover images for each story and the site favicon.

No build step, no dependencies, no backend — it's plain HTML/CSS/JS.

## Stories

| Story | Themes |
|---|---|
| The AI School Day | Friendship, Curiosity, Teamwork, Introduction to AI |
| The Tale of Two Bots | Friendship, Exploration, Learning from Mistakes, Cooperation |
| The Starlight Fox | Friendship, Learning, Technology as a Helper, Imagination |
| The Day Scrubby Went Wobbly | Helping Others, Teamwork, Technology in Daily Life, Problem-Solving |
| My Car Drives Itself! | Adventure, Travel, Smart Technology, Safety, AI Decision-Making (simplified) |
| Adventures in the Virtual Playground | Imagination, Exploration, Creativity, Digital Worlds, Play |
| The Girl Who Spoke to Animals | Animals, Communication, Empathy, Understanding Others, Nature & Technology |

Each story's cover links to its full text (shared via Gemini); the "▶️ Watch video" button opens a read-aloud on YouTube in a modal without leaving the page.

## Deploying it

### GitHub Pages

1. In the repo, go to **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
3. Set **Branch** to `main` and the folder to `/ (root)`.
4. Save. The site will publish at `https://clarkngo.github.io/AI-storybooks/`.

### Running it locally

Any static file server works:

```bash
python3 -m http.server 8123
```

Then open `http://localhost:8123`.

## License

Dual-licensed:

- **Code** (the HTML/CSS/JS in `index.html`) — [MIT](LICENSE).
- **Content** (story descriptions, themes, and cover images in `assets/`) — [CC BY 4.0](LICENSE-CONTENT). Use, adapt, and redistribute freely, with attribution.
