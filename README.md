# Metrics

Repository traffic and star history, saved weekly by `tools/archive_traffic.py` because GitHub keeps only 14 days. Written by a workflow; do not edit by hand.

| File | Columns |
|------|---------|
| `traffic/views.csv`, `traffic/clones.csv` | `date`, `count`, `uniques` (one row per day) |
| `traffic/referrers.csv`, `traffic/paths.csv` | `collected`, `name`, `count`, `uniques` (top 10 of the 14 days before `collected`) |
| `traffic/repo.csv` | `date`, `stars`, `forks`, `watchers`, `open_issues` |
