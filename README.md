<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/brand/brainlife-mark-on-dark.svg">
    <img src=".github/brand/brainlife-mark-on-light.svg" alt="brainlife.io" width="140">
  </picture>
</p>

<h1 align="center">ui-surfaceview</h1>

<p align="center">
  White-matter tract surface viewer for brainlife.io datasets.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-legacy-lightgrey.svg" alt="Status: legacy">
  <a href="https://brainlife.io"><img src="https://img.shields.io/badge/brainlife.io-site-3b9fd0.svg" alt="brainlife.io"></a>
  <a href="https://brainlife.io/docs"><img src="https://img.shields.io/badge/Docs-brainlife.io%2Fdocs-005981.svg" alt="Documentation"></a>
  <a href="https://doi.org/10.1038/s41592-024-02237-2"><img src="https://img.shields.io/badge/DOI-10.1038%2Fs41592--024--02237--2-e57536.svg" alt="Nature Methods paper"></a>
</p>

> [!WARNING]
> **Legacy / not maintained.** This viewer is no longer offered for any datatype on brainlife.io (checked 2026-11). For volumes and tracts use [ui-niivue](https://github.com/brainlife/ui-niivue); for tracts also [ui-tractview](https://github.com/brainlife/ui-tractview).

## 🧠 At a glance

| | |
|---|---|
| 🧭 **What** | Static web page (White-matter tract surface viewer) that brainlife.io opens for a dataset; it reads the dataset's files through the brainlife API |
| 🗂️ **Datatypes** | Not assigned to any datatype on brainlife.io (checked 2026-11) |
| 🕰️ **Last change** | 2020-08-07 |

## 💻 Run it locally

```bash
git clone https://github.com/brainlife/ui-surfaceview && cd ui-surfaceview
npm install            # if package.json lists dependencies
npx http-server .      # or any static server; open index.html
```

brainlife.io serves the built files under `/ui/` and passes the dataset location to the page.

## 📝 Notes

[doi:10.25663/brainlife.ui.4](https://doi.org/10.25663/brainlife.ui.4). Authors: Soichi Hayashi, Steven O'Riley.

## 🔗 Related

[ui-niivue](https://github.com/brainlife/ui-niivue) (current in-browser viewer) · [abcd-novnc](https://github.com/brainlife/abcd-novnc) (desktop viewer launcher) · [warehouse-next](https://github.com/brainlife/warehouse-next) (datatypes and their viewers)

<details>
<summary><b>📜 Previous README (technical details)</b></summary>

This is a unique visualizer that shows the surface of major white matter tracts.

[Demo on brainlife.io](https://brainlife.io/ui/surfaces/) | [brainlife.io DOI](https://doi.org/10.25663/brainlife.ui.4)

</details>

## 📚 Citing

If you use brainlife.io in your work, please cite:

> Hayashi S, Caron BA, Heinsfeld AS, et al. brainlife.io: a decentralized and open-source cloud platform to support neuroscience research. *Nature Methods* 21:809–813 (2024). [doi:10.1038/s41592-024-02237-2](https://doi.org/10.1038/s41592-024-02237-2)

## 🤝 Contributing

Issues and pull requests are welcome in this repository. For help using brainlife.io, see the [documentation](https://brainlife.io/docs).

## ⚖️ License

This repository does not include a license file yet.

<p align="center"><sub>brainlife.io · Brain data across scales. One place to analyze, share and publish it. · The University of Texas at Austin</sub></p>
