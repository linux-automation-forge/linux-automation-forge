linux-automation-forge 🔨
I forge Linux tools that automate real problems — 9 shipped and counting.

Every tool in this forge was born from a friction I personally hit, built inpure Bash, and shipped with self-tests, docs, and a no-crash philosophy:missing dependencies degrade gracefully — they never explode.

🧰 The Toolkit — 9 tools, one philosophy
Scan it. Monitor it. Convert it. Verify it. Never retype it.

#	Tool	What it does	Highlight
1	netrecon-suite	Automated network recon & diagnostics — 4 modules, 70+ evidence files per run	Consolidated FINAL_REPORT + full audit trail
2	healthdash	Live terminal dashboard: CPU, RAM, disks, network, top processes	Zero dependencies, read-only, WSL-friendly
3	gitsafe	Beginner-proof git uploader — blocks secrets, oversize files, force-push accidents	Secret-scanning + guided error recovery
4	filekit	Compress, decompress & compare files/directories	Tar-bomb guard + integrity verification
5	weather-search	Worldwide weather station: NOW, 12h, 7-day, last-month archive	Pin codes & any city on Earth — no API key
6	vid-grab	Video/audio downloader menu for 1000+ sites	Wraps yt-dlp with a friendly quality menu
7	Docvert	Image + document converter with PDF merge/split/remove	Never overwrites; strict page-range parsing
8	shellquiz	Terminal drill game — 130+ questions across 21 Linux categories	Spaced repetition: misses come back until you own them
9	snippet	Personal snippet brain — store, find, run, share your commands	Your private Stack Overflow that never forgets
🔧 How I work
Problem first — every tool started as friction I personally hit
Tests from birth — every tool ships with --selftest
Graceful degradation — missing deps = clean skip with a reason, never a crash
Audit trails — important operations log everything, timestamped
Safety gates — destructive actions need confirmation, never silent
🛠️ Skills
BashLinuxGitNetworkingSecurityREST APIs

Also exploring: Python (Flask) · CI/CD · Docker

📈 Currently
🔨 Forging the next tool
📚 Deepening: Linux internals · automation patterns
🎯 Open to internships — Linux · DevOps · automation · backend
📫 Contact : manumanepalli999@gmail.com
LinkedInEmail

If you read this far: yes, all tools are real. Pick one and try to break it.

Verification — run with YOUR exact repo names:
bash

for repo in netrecon-suite healthdash gitsafe filekit weather-search vid-grab Docvert shellquiz snippet; do
  code=$(curl -s -o /dev/null -w "%{http_code}" "https://github.com/linux-automation-forge/$repo")
  echo "$code  $repo"
done
All 200 = paste the README, commit, done. Any 404 = tell me which one.

