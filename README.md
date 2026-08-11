# ReBac &middot; NSF SaTC Awards 2555491 and 2555492

Project website for **Collaborative Research: SaTC 2.0: RES: Modeling and Mitigating
Reflective Backscatter Side-Channel Attacks (ReBac) in Everyday Devices**.

- PI Lina Pu, The University of Alabama (Award 2555491)
- PI Yu Luo, Mississippi State University (Award 2555492)
- Oct 2026 to Sep 2029, NSF CISE / CNS, Secure and Trustworthy Cyberspace

Live site: `https://<your-github-username>.github.io/rebac-nsf-satc/`

---

## What is in here

| Path | What it is |
|---|---|
| `index.html` | The entire website. One file, no build step, no dependencies. |
| `images/` | Figures and photos. See `images/README.md` for the list. |
| `.nojekyll` | Tells GitHub Pages to serve files as-is. Leave it alone. |
| `deploy.sh` | One-line publish helper: `./deploy.sh "what changed"` |

## One-time setup (about 5 minutes)

1. Sign in at <https://github.com>.
2. Click **+** &rarr; **New repository**. Name it `rebac-nsf-satc`. Set it **Public**.
   Do **not** add a README, .gitignore, or license.
3. On the empty repo page, click **uploading an existing file**, then drag in
   everything from this folder, including the `images` folder and the hidden
   `.nojekyll` file. Click **Commit changes**.
4. Go to **Settings** &rarr; **Pages**. Under *Source* choose **Deploy from a branch**,
   branch **main**, folder **/ (root)**. Click **Save**.
5. Wait about a minute, then reload. GitHub shows the live URL at the top of that page.

## What is deliberately not on this page

Following the same rule as the CAREER site: **published and completed work only.**
No proposed tasks, no research questions, no timeline, and no proposed education or
outreach programme. The three research objectives appear at the level of detail in
the public NSF award abstract and no further.

## Updating the site

Ask Claude: *"add this publication to the ReBac site"*, *"swap in the new figure"*,
*"add my new student to People"*. The whole site is one HTML file, so any change is a
single edit and a single push.

To publish by hand instead:

```bash
./deploy.sh "added first project publication"
```

Or edit `index.html` in the GitHub web editor and commit. Changes go live in under a minute.

## Acknowledgment

This material is based upon work supported by the National Science Foundation under
Grant Nos. 2555491 and 2555492. Any opinions, findings, and conclusions or
recommendations expressed in this material are those of the author(s) and do not
necessarily reflect the views of the National Science Foundation.
