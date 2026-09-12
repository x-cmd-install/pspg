# pspg

[中文版本](./README.cn.md)

Unix pager (with very rich functionality) designed for work with tables. Designed for PostgreSQL, but MySQL is supported too. Works well with pgcli too. Can be used as CSV or TSV viewer too. It supports searching, selecting rows, columns, or block and export selected area to clipboard. 

![pspg](https://repo.x-cmd.io/pspg.svg)

## Install

```sh
x install pspg
```

## Code insight

Total: **25,617** lines of code across **47** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| C | 22,648 | 2,333 | 4,939 | 22 |
| CHeader | 1,489 | 155 | 179 | 11 |
| M4 | 1,000 | 722 | 99 | 8 |
| RPMSpecfile | 166 | 2 | 54 | 1 |
| Sh | 93 | 27 | 22 | 5 |

## OpenSSF Scorecard

Overall score: **3.6 / 10**

Lowest-scoring checks:

- **Code-Review** (0/10) — Found 1/24 approved changesets -- score normalized to 0
- **Packaging** (-1/10) — packaging workflow not detected
- **Security-Policy** (4/10) — security policy file detected

## Source

- **Upstream**: <https://github.com/okbob/pspg>
- **License**: BSD-2-Clause

## Release

- **Latest**: `5.8.16` (2026-02-18)
- **Last commit**: 2026-09-06

## Popularity

- **Stars**: 2,731 · **Forks**: 90 · **Open issues**: 202 · **Contributors**: 32

## Totals (cumulative)

- **Releases**: 142 · **Merged PRs**: 60 · **Open PRs**: 1 · **Closed issues**: 201 · **Open issues**: 1 · **Commits**: 1365

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-13 | 0 | 0 | 1 | 0 | 1 | 5 |
| last60d | 2026-07-14 | 0 | 0 | 1 | 0 | 1 | 5 |
| 90d | 2026-06-14 | 0 | 0 | 1 | 1 | 1 | 6 |
| last180d | 2026-03-16 | 0 | 2 | 1 | 2 | 1 | 16 |
| 360d | 2025-09-17 | 4 | 3 | 1 | 10 | 1 | 40 |
| last720d | 2024-09-22 | 10 | 4 | 1 | 17 | 1 | 77 |

## Distribution status

Reported by **103** distros on [repology.org](https://repology.org/project/pspg). **32** are ✅ on the latest upstream release, **53** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Debian unstable | `5.8.16` | ✅ latest |
| Debian 14 | `5.8.16` | ✅ latest |
| Debian 13 | `5.8.9` | ⚠️ outdated |
| Ubuntu 26.04 LTS | `5.8.16` | ✅ latest |
| Ubuntu 24.04 LTS | `5.8.1` | ⚠️ outdated |
| Homebrew | `5.8.16` | ✅ latest |
| Fedora rawhide | `5.8.16` | ✅ latest |
| Nix unstable | `5.8.16` | ✅ latest |
| Void | `5.8.16` | ✅ latest |
| Alpine edge | `5.8.16` | ✅ latest |
| openSUSE Tumbleweed | `5.8.16` | ✅ latest |

## Improve this data

Install metadata for pspg lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `pspg` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/pspg.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260912.yml` · 2026-09-12T05:08:17Z._
