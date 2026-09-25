# Functional Architecture of European Electricity Trading Markets

This repository contains the publication artifacts for:

> Walter Kurz and Wojtek Stricker. “Functional Architecture of European Electricity Trading Markets: Requirements for AI Supported Trading Systems under Regulatory Constraints.” *Swissi AI Journal*, Volume 2026, Article SAIJ-cwo7xrcdsaut.

- Journal record: https://journal.swissi-ai.institute/en/doi/cwo7xrcdsaut
- DOI: `10.5281/zenodo.21901249`
- arXiv: https://arxiv.org/abs/2609.29108
- Full paper: [`paper.pdf`](paper.pdf)
- arXiv source archive: [`arxiv-source.zip`](arxiv-source.zip)
- Extracted LaTeX source: [`source/`](source/)

## Research artifacts

The reproducible publication set comprises the complete LaTeX source, bibliography, included research figures, compiled PDF, and arXiv upload archive.

The manuscript presents its models through equations, tables, and formal analysis contained in the LaTeX source.

Bibliographic records are stored at [`source/4-bib/2-bib.bib`](source/4-bib/2-bib.bib).

## Build

A TeX installation with `pdflatex` is required. Run:

```sh
./build.sh
```

The script compiles the paper from the committed source and processed bibliography.

## License

The paper and repository contents are published under the [Creative Commons Attribution 4.0 International License](LICENSE).
