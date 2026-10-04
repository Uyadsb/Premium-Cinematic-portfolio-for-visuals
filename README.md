# JAMIN — Cinematic Portfolio

A premium, film-style portfolio website for **JAMIN**: Video Editor, Filmmaker, Colorist and Content Creator.
Built as a single `index.html` file with no frameworks and no build step.

## Features

- Cinematic hero with showreel background and a DaVinci Resolve editing window
- Showreel section with a play state
- Selected work: six project cards with a full-screen project detail page and "Next project" navigation
- Reels and short-form grid (9:16) with category tabs and a vertical player
- Color grading section with interactive before/after sliders
- Behind-the-camera gallery with captions
- About, skills, services and a dramatic contact section
- Navigation that hides while scrolling, with a PLAY indicator for the showreel
- Responsive layout with scroll-reveal animations

## Getting started

1. Rename the HTML file to `index.html`.
2. Open it in a browser, or host it on GitHub Pages, Netlify or Vercel.

No install is needed.

## Replacing the placeholder media

Every placeholder frame is labeled with the filename it expects. Put your files in the same folder as `index.html`:

| Placeholder | Section |
|---|---|
| `SHOWREEL_VIDEO.mp4` | Hero background |
| `SHOWREEL_2026.mp4` | Showreel |
| `PROJECT_01_THE_LAST_LIGHT.mp4` … `PROJECT_06_CITY_FRAGMENTS.mp4` | Selected work |
| `PROJECT_STILL_01.jpg` … `03.jpg` | Project detail gallery |
| `GRADE_01_RAW.jpg` / `GRADE_01_FINAL.jpg` (01–03) | Color before/after |
| `REEL_01_NO_SIGNAL.mp4` … `REEL_06_RHYTHM_CUT.mp4` | Reels grid |
| `CAMERA_01–04.jpg`, `BTS_01–02.jpg` | Behind the camera |
| `JAMIN_PORTRAIT.jpg` | About |
| `DAVINCI_EDIT_SCREENSHOT.png` | Hero editing window |

Swap each placeholder `ph(...)` frame in the code for an `<img>` or `<video>` tag using the same filename.

## Editing content

- **Projects:** edit the `P` array in the script
- **Reels:** add one line to the `R` array: `[title, category, views, filename, hue]`
- **Color grades:** edit the `G` array
- **Colors and fonts:** CSS variables at the top of the `<style>` block (`--acc` is the accent color)

## Contact

Replace `hello@yourdomain.com` and the social links in the contact section.

## License

© 2026 JAMIN. All rights reserved.
