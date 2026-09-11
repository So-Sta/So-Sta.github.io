# So.Sta. — Social Statistics website

This repository contains a **Quarto website** designed to be edited comfortably in **RStudio** and published with **GitHub Pages**.

## Structure

- `index.qmd` — home page
- `people.qmd` — group members
- `projects.qmd` — active and past projects
- `events.qmd` — conferences and group presence
- `materials.qmd` — apps, programmes, slides and teaching material
- `publications.qmd` — selected publications
- `news.qmd` — news
- `styles.css` — visual style
- `images/people/` — member images
- `assets/materials/` — downloadable files
- `.github/workflows/publish.yml` — automatic GitHub Pages deployment
- `preview/` — static preview of the current version

## Edit in RStudio

1. Install **Quarto** if it is not already available: <https://quarto.org/docs/get-started/>.
2. Open `sosta-website.Rproj` in RStudio.
3. Edit any `.qmd` file.
4. Use **Render Website** in RStudio, or run `quarto preview` in the Terminal for a live preview.

## Replace placeholder portraits

The current package uses neutral image placeholders because approved headshots were not supplied. Replace the corresponding PNG file in `images/people/` while keeping the same filename and dimensions close to square. No page code needs to change.

## Publish on GitHub Pages

1. Create a GitHub repository, for example `sosta-website`.
2. Push this folder to the repository.
3. In GitHub, open **Settings → Pages** and select **GitHub Actions** as the source.
4. Every push to `main` will render and publish the site automatically.

If you want the URL to be `https://<organisation>.github.io/`, name the repository `<organisation>.github.io`. Otherwise GitHub Pages will use a project URL such as `https://<organisation>.github.io/sosta-website/`.

## Notes on content

The initial content uses the team list supplied for the site, official university profile pages, official project websites, and the conference/programme files included in this package. Before public launch, check member biographies, approved photos, and whether all downloadable slides/materials should be public.

## Ca’ Foscari logo

The home page currently displays a linked Ca’ Foscari logo for the draft preview. Before public launch, replace it with the official approved logo file supplied by Ca’ Foscari and follow the University's current brand-use rules.
