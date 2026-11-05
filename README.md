# Abhigyan Chatterjee

Backend and systems engineer. I build tools people actually run: a placement platform that executes
untrusted code, a package workflow CLI for Arch Linux, and internal tooling I shipped solo at LTM.

[nullbit.in](https://nullbit.in) · [abhi@nullbit.in](mailto:abhi@nullbit.in) · [LinkedIn](https://www.linkedin.com/in/abhigyan-chatterjee/) · [Résumé](https://nullbit.in/assets/resume.pdf)

---

### Merit — [live](https://merit.nullbit.in) · [source](https://github.com/abhigyan-chatterjee/merit)

Placement prep and timed assessment. 274 problems across 18 topics, graded in Python, JavaScript,
Java and C++. Untrusted submissions run in two Cloud Run judge services chosen by language, never
inside the API: neither holds a database credential or a signing key, so a compromised submission
cannot reach the database or mint its own tokens.

### Aurora — [live](https://aurora.nullbit.in) · [source](https://github.com/abhigyan-chatterjee/aurora)

Package workflow front-end for Arch Linux. One command resolves official repositories and the AUR in
parallel, then delegates to `pacman` and `makepkg` instead of reimplementing either. AUR PKGBUILDs
are fetched and shown before the build runs, and a failed fetch aborts that package rather than
compiling code you never saw. v0.6.0.

### eSim Manager — [source](https://github.com/abhigyan-chatterjee/esim-manager)

One static Go binary that installs eSim's EDA dependencies across Debian, Arch and Fedora, detecting
the distribution at runtime and mapping each tool to its family's package manager.

### URL Checker — [source](https://github.com/abhigyan-chatterjee/URL-Checker)

A character-level LSTM combined with seven handcrafted features over 651k labelled URLs, built to
catch lookalike domains and obfuscated paths instead of hand-writing a rule for each one.

---

**Stack.** Go, Python, TypeScript, SQL, C · FastAPI, PostgreSQL, React · Linux, Docker, Cloud Run, Caddy

Finishing a B.Tech in Electronics and Communication Engineering at Techno Main Salt Lake (2027).
Looking for backend and systems roles.
