# Photonics Lab Calculators

Small, self-contained HTML tools for common free-space optics calculations.
No build step, no dependencies beyond a Google Fonts link — each tool is a
single `index.html` file.

## Tools

- **[Beam Coupling Calculator](./beam-coupling-calculator/)** — focused spot
  size, effective NA, and mode-match quality for free-space-to-fiber coupling
  and 4f pinhole spatial filtering (paraxial Gaussian beam optics).
- **[Photon Energy Calculator](./photon-energy-calculator/)** — converts
  between wavelength, frequency, photon energy (eV / J), and wavenumber.

## Using a calculator on your own site

Each folder contains one `index.html` file with everything inline (HTML,
CSS, JS). To use it elsewhere:

1. Download the `index.html` file from the tool's folder.
2. **Google Sites:** Insert → Embed → Embed code → paste the file's contents.
3. **Any other site / CMS:** upload the file and link to it, or paste its
   contents into an iframe/embed block.
4. **GitHub Pages:** fork or clone this repo, enable Pages in
   Settings → Pages, and each tool will be live at
   `https://<your-username>.github.io/<repo-name>/<tool-folder>/`.

## Live pages (this repo, once Pages is enabled)

- `https://<username>.github.io/<repo-name>/beam-coupling-calculator/`
- `https://<username>.github.io/<repo-name>/photon-energy-calculator/`

## License

Feel free to reuse, modify, and republish — attribution appreciated but not required.
