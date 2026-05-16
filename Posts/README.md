# Posts Intake Folder

This folder is where Keshav provides raw content for new posts.

## How it works

1. Create a subfolder for each post (e.g., `Classical Conditioning/`)
2. Add a `.md` file with the full post content
3. Add any images as `.webp`, `.png`, or `.jpg` files in the same subfolder
4. The agent will:
   - Read the MD file
   - Identify and optimize all images (PNG→WebP, compress)
   - Create the production MDX file in `src/content/posts/en/`
   - Create the Hindi version in `src/content/posts/hi/`
   - Move optimized images to `public/images/posts/<slug>/`
   - Update `src/content.config.ts` if needed
   - Build, commit, and push

## Image guidelines

- Provide high-quality PNG or WebP images
- Name them descriptively if possible (e.g., `pavlov-diagram.png`)
- The agent will optimize and rename them
- Images are placed in `public/images/posts/<slug>/` (not `src/assets/`) because Astro v6 content images work best from `public/`

## Content guidelines

- Write in-depth, well-structured posts for a general audience
- English is the primary language
- Hindi versions use Devanagari script with natural English terms
- Explain concepts with depth — not ELI5
- Include examples, context, nuance, common misunderstandings, applications
- Internal links between related posts are auto-generated
- Fact-check all claims before publishing
