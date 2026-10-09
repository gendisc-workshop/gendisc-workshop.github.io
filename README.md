# GenDisc · Proposed ICLR 2027 workshop

Website for **GenDisc: Principles of Generative Discovery in the Sciences**.
The workshop is proposed for ICLR 2027 and has not yet been accepted.

GenDisc aims to establish shared foundations for generative discovery, turning
insights from diverse experimental sciences into general principles for objectives,
algorithms, and validation.

## Website files

- `index.html`: workshop scope, draft call for papers, speakers, panel,
  organisers, dates, and programme.
- `styles.css`: layout, colours, typography, and mobile styles.
- `assets/`: discovery illustration and favicon (editable SVGs).
- `assets/people/`: public profile portraits, with their original image and page
  URLs recorded in `sources.json`. Each name and portrait links to that person's
  personal or lab website. Circular crops are applied in CSS.
- `.nojekyll`: tells GitHub Pages to serve the static files directly.

No build tools, packages, analytics, or external fonts are required.
The website works without JavaScript.

## Preview locally

Open `index.html` in a browser, or run:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Then visit <http://localhost:8000>.

## Publish on GitHub Pages

1. Commit the website files and push them to `main`.
2. Open [Settings → Pages](https://github.com/gendisc-workshop/gendisc-workshop.github.io/settings/pages).
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Choose **main** and **/ (root)**, then click **Save**.
5. Check the repository's [Actions](https://github.com/gendisc-workshop/gendisc-workshop.github.io/actions)
   for the Pages deployment, then visit <https://gendisc-workshop.github.io/>.

Publishing can take up to 10 minutes. Later commits pushed to `main` automatically
update the website. See [GitHub's publishing documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

## Update the content

Edit `index.html` locally or with GitHub's file editor and commit to `main`.
Section IDs: `about`, `participate` (draft call for papers), `speakers`, `panel`,
`programme`, `organisers`, and `contact`. The `themes` anchor points to the
topics of interest within the call for papers.

Content follows the supplied workshop proposal, preserving its scope qualifiers
and illustrative open problems. The PDF's filename mentions 2026, but the document
itself identifies the proposal as ICLR 2027. Speaker confirmations and methodology
labels follow the proposal; affiliations include the organisers’ requested updates.
The source PDF is not needed to serve the website and is not linked from the page.

Keep the acceptance-pending banner, metadata, footer, and provisional wording until
the workshop decision is known. Following acceptance, update the workshop date,
venue, time zone, submission requirements, deadlines, and OpenReview link together.
Add the public contact email to the `contact` section when selected.

Co-organisers can maintain the site with repository **Write** access; organisation
ownership can remain with the current owner.
