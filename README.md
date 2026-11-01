# Krishna Ramamoorthy's website

Source for [krishnaramamoorthy.com](https://krishnaramamoorthy.com), built with [Hugo](https://gohugo.io) and a modified [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme. Pushing to `main` publishes the site through the GitHub Action in `.github/workflows/hugo.yml`.

## How to update

Most updates are a few lines in one of the files in `data/`. The pages and the cards on the home page read from these files, so nothing else needs editing.

| To change | Edit | Notes |
|---|---|---|
| Lab members | `data/team.yaml` | `group` is `undergrad`, `grad`, `phd` or `alumni`. To graduate someone, change `group` to `alumni` and add `now` (where they went). Square photos go in `static/team/`. |
| Publications | `data/publications.yaml` | Add new papers at the top. Put `**double stars**` around the name to bold, and a `*` after a supervised student. |
| Senior design projects | `data/seniordesign.yaml` | Add a new year at the top. `image` (in `static/design/`), `full` (a bigger image to open on click), `imagepos`, `awards`, `link` and `links` (several text and url pairs) are optional. |
| Beyond Work photos | `data/photos.yaml` | Photos live in `static/beyond/`. |
| Courses | `content/courses/_index.md` | Copy an existing course card. The home card counts courses by their `CSEN` number. |
| Professional activities | `content/service/_index.md` | A plain list. The home card counts the items. |
| Bio, roles and contact | `content/_index.md` and `profileMode` in `config.yml` | |
| CV | `static/KrishnaRamamoorthyCV.pdf` | Replace the file and keep the name. |

## Run it locally

Install Hugo extended **0.128.0**, the version the deploy uses (newer versions can break this theme), then from this folder:

```
hugo server
```

and open http://localhost:1313. Changes show up as you save.

## Where things live

- `content/` holds one folder per page (WIN Lab, Publications, Senior Design, Courses, Professional Activities, Beyond Work). `content/_index.md` is the home page.
- `data/` holds the lists described above.
- `layouts/shortcodes/` renders those lists (`team`, `publications`, `seniordesign`, `photos`, `modules` for the home cards).
- `assets/css/extended/site.css` holds the site's own styles.
- `static/` holds files served as is, grouped by page: `team/`, `design/`, `beyond/`, `courses/`, `winlab/`, `home/`. Favicons and the CV stay at the top level so their links never change.

## Credits

Based on the [Hugo academic template](https://github.com/pmichaillat/hugo-website) by Pascal Michaillat, which builds on PaperMod. Licensed under the MIT License (see `LICENSE.md`).
