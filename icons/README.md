# Icons

Shared image assets for every [@willtheorangeguy](https://github.com/willtheorangeguy) repository. Images live here once and are referenced by absolute URL, so a logo is updated in one place instead of in each repository.

## URL Pattern

```text
https://raw.githubusercontent.com/willtheorangeguy/.github/main/icons/<repository>/<file>
```

For example, PyWorkout's logo:

```markdown
<img src="https://raw.githubusercontent.com/willtheorangeguy/.github/main/icons/PyWorkout/logo.png" alt="PyWorkout">
```

Use `raw.githubusercontent.com`, never `github.com/.../blob/...` — the latter serves an HTML page, so the image will not render.

## Conventions

* One folder per repository, named exactly as the repository is.
* Filenames are lowercase, as are extensions. These are public URLs.
* `logo.png` is the repository's mark, used in the README header.
* `welcome.png` (or `.gif`, `.jpg`) is the hero screenshot below the navigation block.
* Any other name is a supporting screenshot referenced from that repository's `docs/`.
* Keep hero animations under a few megabytes. GIFs are downscaled to 600–800px and 8–12 fps; GitHub does not allow `<video>` in Markdown, so an animation has to stay a GIF.

## This Repository Must Stay Public

Every image in all 125 repositories resolves through this one repository. If it is renamed, made private, or force-pushed badly, every logo and screenshot breaks at once. Treat `main` as protected.
