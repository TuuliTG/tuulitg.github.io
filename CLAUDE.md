# CLAUDE.md

The public website of the MealFriends app: its home page, privacy policy and terms of use (see `README.md`). The app
lives in `TuuliTG/MealFriends`; its `AGENTS.md` rules (branches, Conventional Commits, PRs, no secrets) apply here too.

- **The pages must match the app.** `privacy.html` says in plain words what MealFriends' `docs/privacy.md` (the
  records of processing) and ADR 0003 say; `terms.html` follows ADR 0003 (accounts, minimum age) and ADR 0004 (content
  rules, reporting, moderation). A change here is made together with the MealFriends change that causes it, and the
  two PRs link to each other.
- **A new version gets a new effective date** at the top of the changed page. A change that matters to users (new
  data, a new service that handles data, new rules) is announced in the app before it takes effect; say in the PR
  whether that's needed.
- Never rename or move `index.html`, `privacy.html` or `terms.html`, and keep any `google*.html` verification file:
  the addresses are in Google's and the stores' settings and in the app.
- Plain, short sentences a non-lawyer understands. English only for now; translations go in their own files.
- Plain HTML and `style.css` only: no scripts, trackers, analytics, web fonts or third-party embeds. Colours are
  MealFriends' leaf greens (ADR 0002). Pages must read well on a ~390pt wide phone, without sideways scrolling.
- Not legal advice: a change to the policy or terms is reviewed by the owner, and by someone qualified when it
  changes rights or obligations.
