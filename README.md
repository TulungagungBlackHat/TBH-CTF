# TBH-CTF

<p align="center">
  <a href="https://github.com/TulungagungBlackHat/TBH-CTF/actions/workflows/ci.yml"><img src="https://img.shields.io/badge/license-MIT-red.svg" alt="License">
  <img src="https://img.shields.io/badge/level-beginner-blue.svg" alt="Beginner">
  <img src="https://img.shields.io/badge/challenges-3-green.svg" alt="Challenges"></a>
</p>

A tiny CTF for people taking their first capture-the-flag. Three challenges — crypto, web, forensics — all solvable with basic tools and careful reading.

Part of the [Tulungagung Black Hat](https://github.com/TulungagungBlackHat) toolset.

## Challenges

| # | Category | Difficulty | Skill practiced |
|---|----------|------------|-----------------|
| 1 | Crypto | Easy | Caesar cipher decoding |
| 2 | Web | Easy | Reading HTML source, hidden comments |
| 3 | Forensics | Easy | Base64 hidden in plain sight |

Flags use the format `TBH{...}`.

## How to Play

```bash
git clone https://github.com/TulungagungBlackHat/TBH-CTF
cd TBH-CTF
cat challenges/ch1/cipher.txt
cat challenges/ch2/index.html
cat challenges/ch3/readme.txt
```

No servers to attack, no installation needed — every challenge is a local file.

## Submitting Solutions

Open an Issue with the title `[SOLVED] Ch1` and include your **write-up** (how you solved it, not just the flag). Good write-ups teach the next beginner; flag-only posts get closed.

## Rules

- Share write-ups, not raw flags
- Educational only — the same skills used against systems you don't own are a crime, not a CTF
- Stuck? Re-read the file byte by byte. That's the point.

## Related Tools

- [awesome-tulungagung](https://github.com/TulungagungBlackHat/awesome-tulungagung) — curated learning resources for after the CTF
- [TBH-Toolkit](https://github.com/TulungagungBlackHat/TBH-Toolkit) — the real-world toolset these skills lead to

## License

[MIT](LICENSE) — Tulungagung Black Hat, East Java, Indonesia. Always Smile :)
