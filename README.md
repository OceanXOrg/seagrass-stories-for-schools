# Seagrass Stories
A classroom learning experience from OceanX Education about restoring seagrass meadows.

The page is designed for educators working with learners aged 12-14 in a 60-minute session. Learners explore seagrass ecology, investigate the restoration process, reflect on what they experienced, and create an idea that communicates ocean restoration.

## Open locally

Serve the folder over HTTP so the YouTube embeds work correctly:

```bash
python3 -m http.server 8765
```

Then open:

```text
http://localhost:8765/
```

## Project structure

```text
index.html                       Classroom learning page
Activity Pack/                    Learner activity and educator guide PDFs
seagrass_stories_feedback_questions.txt
seagrass_stories_summit_educator_cta.pdf
```

## Publish with GitHub Pages

1. Create a public GitHub repository.
2. Upload the project files, including the `Activity Pack` folder.
3. In the repository, open **Settings > Pages**.
4. Select **Deploy from a branch**.
5. Choose the `main` branch and the `/ (root)` folder.
6. Open the generated Pages URL. Because the page is named `index.html`, it will load at the repository root.

The PDF links use repository-relative paths, and the YouTube embeds use a valid referrer policy for hosted pages.
