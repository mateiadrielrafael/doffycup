# 🚧 This repo has been moved to [prescientmoon/doffycup](https://github.com/prescientmoon/doffycup) 🚧

# Doffycup

Doffycup is a small game with the goal of introducing young children to basic programming concepts. An online version you can try for yourself is hosted on [github pages](https://mateiadrielrafael.github.io/doffycup/).

## Tech stack

Doffycup is built using preact and typescript. The project can be built reproducibly using nix. Moreover, we also provide a nix shell for development.

### Changing dependencies

The npm dependency hash needs to be recomputed when the npm lockfile changes:

```sh
nix run .#compute-npm-dep-hash
```

## Infoeducatie 2021

This project was made during the final hackathon phase of [infoeducatie 2021](https://infoeducatie.ro/). The scuffed presentation can be found [here](https://youtu.be/h536BEVIe1U?t=296). I worked on the project together with [vyc](https://github.com/vycdev).
