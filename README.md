# Yarra Bowmen

The official website for Yarra Bowmen Inc.

## Getting Started

### Prerequisites

To run this project locally, you need to have [Hugo](https://gohugo.io/) installed.

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/yarrabowmen/yarrabowmen.github.io.git
   cd yarrabowmen
   ```

2. Run the development server:
   ```bash
   ./preview.sh
   ```
   This script runs `hugo server --buildDrafts --disableFastRender`.

3. Open your browser and navigate to `http://localhost:1313`.

## Project Structure

- `content/`: Markdown files for the website pages (Home, Membership, Visitors, etc.).
- `assets/images/`: Site images and logos.
- `layouts/`: Custom HTML templates and partials.
- `hugo.yaml`: Site configuration, menus, and metadata.
- `.github/workflows/hugo.yaml`: GitHub Actions workflow for automated deployment.

## Deployment

The site is automatically built and deployed to GitHub Pages via GitHub Actions whenever changes are pushed to the main branch.
