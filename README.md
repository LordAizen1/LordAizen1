### md kaif (sussybaka)
cs graduate from iiit delhi. class of 2026.

***

#### now
- open to work
- shipping side projects
- building small weird things that are hopefully useful

#### things i've made
- **[git-newspaper](https://github.com/LordAizen1/git-newspaper)** — your repo history, as a victorian-era newspaper. `npm`, 100★
- **[scamp](https://github.com/LordAizen1/scamp-cat)** — a pixel-art cat for your terminal. `rust`, 21★
- **[sys-gazette](https://github.com/LordAizen1/sys-gazette)** — system stats, in print
- **[opencode-evermemos-plugin](https://github.com/LordAizen1/opencode-evermemos-plugin)** — persistent memory for opencode. `typescript`

#### stack
`python` `c++` `typescript` `javascript` · `react` `next` `node` · `linux` `docker` · `pandas` `numpy` `sklearn` when the mood strikes

#### find me
[portfolio](https://www.mohammadkaif.me/) · [linkedin](https://linkedin.com/in/mohammadkaif007)

***

<p align="center">
  <img src="https://streak-stats.demolab.com?user=LordAizen1&hide_border=true&background=00000000&ring=FFD33D&fire=FFD33D&currStreakLabel=8B949E&sideLabels=8B949E&dates=8B949E&currStreakNum=C9D1D9&sideNums=C9D1D9" height="160" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/LordAizen1/LordAizen1/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/LordAizen1/LordAizen1/output/github-contribution-grid-snake.svg" />
    <img alt="github contribution snake" src="https://raw.githubusercontent.com/LordAizen1/LordAizen1/output/github-contribution-grid-snake.svg" />
  </picture>
</p>

***

<details>
  <summary>snake setup</summary>

Create `.github/workflows/snake.yml` in your profile repo with:

```yml
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

permissions:
  contents: write

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4

      - uses: Platane/snk@v3
        with:
          github_user_name: LordAizen1
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

Then enable GitHub Actions for the profile repo and let it create the `output` branch.

</details>
