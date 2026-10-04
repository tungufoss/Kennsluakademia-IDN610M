# Endurskoðun á námskeiði í Viðskiptagreind: Hagnýt hæfni í brennidepli

**Helga Ingimundardóttir** ([ORCID 0000-0002-2780-3546](https://orcid.org/0000-0002-2780-3546))
Iðnaðarverkfræðideild, Háskóli Íslands

Ráðstefna Kennsluakademíu opinberu háskólanna, Veröld Háskóla Íslands, 22. nóvember 2024

- **Web version:** <https://tungufoss.github.io/Kennsluakademia-IDN610M/>
- **PDF:** [article.pdf](article.pdf)
- **Slides:** [slides.pdf](slides.pdf)

## Útdráttur
Námskeiðið *Viðskiptagreind* var endurskipulagt með það að markmiði að tengja betur við hæfniþarfir atvinnulífsins. Námskeiðið var byggt á nálguninni *„Understanding by Design“* og *verkefnamiðaðri kennslu*. Verkefni í samstarfi við atvinnulífið voru tekin upp með markmiði að efla praktíska færni nemenda. Niðurstöður sýna aukna ánægju nemenda og betri árangur í tengslum við raunveruleg verkefni.

**Lykilorð:** Samantektarverkefni, Raunhæf verkefni, Skilningsmiðað námsmat, Hópavinna

## Vinsamlega vitnið í þetta verk sem
Ingimundardóttir, H. (2024). Endurskoðun á námskeiði í Viðskiptagreind: Hagnýt hæfni í brennidepli. *Ráðstefna Kennsluakademíu opinberu háskólanna*, Veröld Háskóla Íslands, Reykjavík. <https://tungufoss.github.io/Kennsluakademia-IDN610M/>

```bibtex
@inproceedings{Ingimundardottir2024Kennsluakademia,
  author    = {Ingimundardóttir, Helga},
  title     = {Endurskoðun á námskeiði í Viðskiptagreind: Hagnýt hæfni í brennidepli},
  booktitle = {Ráðstefna Kennsluakademíu opinberu háskólanna},
  address   = {Veröld Háskóla Íslands, Reykjavík},
  month     = nov,
  year      = {2024},
  url       = {https://tungufoss.github.io/Kennsluakademia-IDN610M/}
}
```

## Building
The paper is written once, in [article.qmd](article.qmd). [Quarto](https://quarto.org/) turns it into both the PDF and the web version:

```bash
quarto render article.qmd
```

This regenerates `article.tex`, `article.pdf` and `article.html`. Edit `article.qmd`, not `article.tex`, because every render overwrites it. Pushing to `main` publishes the web version (with the PDF and slides) to GitHub Pages.

The slides are a separate LaTeX Beamer deck: [slides.tex](slides.tex), using the HÍ theme in [HI-LaTeX/](HI-LaTeX/).

The layout comes from the [Kennsluakademía conference template](https://github.com/HI-IDN/Conf-Kennsluakademia), which explains the setup in more detail.

## License
MIT, see [LICENCE](LICENCE).
