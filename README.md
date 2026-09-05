# Portfolio site

Four files: `index.html`, `profile.jpg`, `Panimalar_Annadurai_Resume.pdf`, and this readme.
No build step, no dependencies. Every link on the page resolves.

## Publish it

1. Create a new **public** repo named exactly `PanimalarGA.github.io`.
2. Upload `index.html`, `profile.jpg` and `Panimalar_Annadurai_Resume.pdf` into the repo root. Commit.
3. Repo Settings, then Pages. Source: "Deploy from a branch", branch `main`, folder `/ (root)`. Save.
4. Live at `https://PanimalarGA.github.io` within a minute or two.

Keep all four files in the root. If you move the PDF or the photo into a subfolder,
update the two `href` values and the one `src` value in `index.html` to match.

## Two mismatches with your resume, worth deciding on

**Email.** Your resume header says `panimalarannadurai1998@gmail.com`. The site uses
`gapanimalar@gmail.com`, which is what you gave me. A recruiter who has both will see two
addresses. Pick one and make them agree.

**Phone.** Your resume carries `+1 (216) 255-4095`. I left it off the site on purpose. A phone
number on an indexed public page gets scraped and gets you spam calls. Add it if you want it,
but the resume download already covers anyone serious.

## What is deliberately not on the page

Per your instruction to keep CALM methods off public profiles while the paper is under review:

- No algorithm names (VARLiNGAM, CMA-ES) and no spectral-radius framing.
- No per-domain results table. The four domains are not named. Only the 27% to 76% range.
- The hero chart shows a single unnamed system rather than the lending case study.
- No link to `github.com/pxg399/CALM`.

Your resume is more explicit than this: it names the domains, names VARLiNGAM, and links the
repo. That is a defensible difference, since a resume goes to specific people and a github.io
page is indexed by Google and readable by reviewers. But it is a difference, so decide whether
you want the two aligned. Ask and I will restore the full version here once the paper is out.
