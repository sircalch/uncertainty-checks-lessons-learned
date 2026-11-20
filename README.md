# Uncertainty and consistency checks for molecular simulation [LiveCoMS Lessons Learned, Article v0.9]

Lessons learned from testing two automated uncertainty checks on processes with known answers and on real data:
**MDCheck** (equilibration, autocorrelation-corrected intervals and replica consistency for time-series averages) and
**FEPCert** (overlap, TI/BAR agreement, convergence and cycle closure for alchemical free-energy analyses).

- Article source: `main.tex` (LiveCoMS Lessons Learned template, `livecoms.cls`), references in `references.bib`.
- Current PDF: `releases/LiveCoMS_Article_v0.9.pdf`; Supporting Information: `si.tex` / `si.pdf`.
- Software and validation scripts: https://github.com/sircalch/mdcheck and https://github.com/sircalch/fepcert
  (MDCheck 1.1.0, doi:10.5281/zenodo.23719908; FEPCert 1.2.0, doi:10.5281/zenodo.23085662).

## Authors
Andrés Monreal-Hernández (Universidad Estatal de Sonora, corresponding author, andres.monreal@ues.mx),
Sara Lizbeth Franco Amaya and Carlos Ivanhoe Martínez Osorio (Universidad de Sonora).

## Contributing
Please use the issue tracker for questions, corrections, additional benchmarks or suggestions. Contributors whose comments are used will be acknowledged in the article.

## License
Creative Commons Attribution 4.0 International (CC BY 4.0), see `LICENSE`.

## Build
`latexmk -pdf main.tex` (pdfLaTeX; the template uses the OpenSans package).
