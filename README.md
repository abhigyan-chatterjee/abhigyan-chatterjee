# Abhigyan Chatterjee

Backend and systems engineer. I like the parts of software that sit close to the machine: process
isolation, concurrency, and the failure paths nobody tests.

[nullbit.in](https://nullbit.in) · [abhi@nullbit.in](mailto:abhi@nullbit.in) · [X](https://x.com/Nullbit_in) · [LinkedIn](https://www.linkedin.com/in/abhigyan-chatterjee/) · [Résumé](https://nullbit.in/assets/resume.pdf)

---

### Merit — [live](https://merit.nullbit.in) · [source](https://github.com/abhigyan-chatterjee/merit)

Placement prep, mock interviews, and timed assessment. 274 verified problems (5,479 test cases) across
18 topics, 17 algorithm visualizers, 574 MCQs, 11 proctored mock exams, SM-2 spaced revision, a
live-judged AI mock-interview portal (in-memory PDF résumé parsing), and a 4-mode signed-in BYOK AI
tutor with zero server key storage. Untrusted submissions run in two Cloud Run judge services
(`judge-light` for Python/JS, `judge-heavy` for Java/C++), never inside the API: neither holds a
database credential or a signing key, and the FastAPI + Neon PostgreSQL stack runs in a 414MB
memory-capped deployment on a 1GB Oracle Cloud VPS.

### VPSPulse — [source](https://github.com/abhigyan-chatterjee/VPSPulse)

Self-hosted VPS-by-VPS resource and service monitor in pure Go (`~13 MB` hub binary with embedded
React 19 UI) paired with a `~6 MB` static Linux push agent (`amd64`/`arm64`) streaming outbound HTTPS
heartbeats behind NAT with zero open inbound ports. Collects `/proc` host telemetry, Docker container
health/CPU deltas, and watched/failed `systemd` units; runs SSRF-hardened HTTP/HTTPS/TLS, TCP, and
ICMP probes via custom `net.Dialer.Control`; stores metrics in SQLite (`WAL`) with tiered downsampling
(`10s` → `1m` → `5m`) and retention pruning; and dispatches real-time SSE plus hysteresis-guarded
alerts across Discord, Telegram, Slack, SMTP, and webhooks.

### Aurora — [live](https://aurora.nullbit.in) · [source](https://github.com/abhigyan-chatterjee/aurora)

Package workflow front-end for Arch Linux (`v0.6.0`). One command resolves official repositories and
the AUR concurrently via goroutines, then delegates to `pacman` and `makepkg` instead of
reimplementing either. AUR installs check for `-bin` variants (`prefer_bin`), PKGBUILDs are fetched
and shown before building (`--inspect` aborts on failed fetch, `--diff` shows rebuild changes), and
`doctor` runs 12 machine checks across 14 commands with `--json` output and SHA-256 verified self-updates.


---

**Stack.** Go, Python, TypeScript, SQL, C · FastAPI, PostgreSQL, SQLite, React · Linux, Docker, systemd, Cloud Run, Caddy

Finishing a B.Tech in Electronics and Communication Engineering at Techno Main Salt Lake (2027).
Looking for backend and systems roles.
