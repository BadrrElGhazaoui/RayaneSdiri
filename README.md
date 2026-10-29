# Rayane Sdiri — Athlete Portfolio

The personal portfolio of **Rayane Sdiri**, a Moroccan national-team épée fencer, three-time national champion, Sports Technology student, volunteer, and content creator.

The site brings together Rayane's sporting profile, competition highlights, community involvement, education, media appearances, and contact links in a clean design inspired by Morocco's red, green, and white colors.

## Portfolio

- **Competition:** Moroccan national titles, African Championships, the Coupe du Trône, and World Cup results
- **Community:** Fencing workshops, tournament support, youth events, and volunteer activities
- **Media:** Fencing content, media appearances, and collaborations
- **Education:** Sports Technology studies, academic background, and current training

## Connect

- **Email:** [rayanesdiri20@gmail.com](mailto:rayanesdiri20@gmail.com)
- **Phone:** [+212 626 989 746](tel:+212626989746)
- **LinkedIn:** [Rayane Sdiri](https://www.linkedin.com/in/rayane-sdiri-8048593a9/)
- **Instagram:** [@_rayanesdirii](https://www.instagram.com/_rayanesdirii/)
- **TikTok:** [@fencing_with_rayane](https://www.tiktok.com/@fencing_with_rayane)
- **GitHub:** [BadrrElGhazaoui](https://github.com/BadrrElGhazaoui)

## Built with

- [Astro](https://astro.build/) for static site generation
- [Tailwind CSS v4](https://tailwindcss.com/) for styling
- TypeScript for the site configuration

## Run locally

**Requirements:** Node.js and npm.

```bash
git clone https://github.com/BadrrElGhazaoui/RayaneSdiri.git
cd RayaneSdiri
npm install
npm run dev
```

Astro prints the local preview URL after the development server starts.

## Build

Create the production site in `dist/`:

```bash
npm run build
```

To preview the production build locally:

```bash
npm run preview
```

## Project structure

```text
public/
  images/                 # Profile portrait and other static assets
src/
  components/             # Hero, About, Media, Community, Education, Footer
  pages/index.astro       # Main portfolio page
  styles/global.css       # Global styles
  config.ts               # Portfolio content, results, and social links
astro.config.mjs          # Astro and GitHub Pages configuration
```

Portfolio content and links are maintained in [`src/config.ts`](./src/config.ts). Page sections are implemented as independent Astro components in [`src/components/`](./src/components/).
