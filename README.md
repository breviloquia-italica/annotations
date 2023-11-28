# Breviloquia Italica: annotations

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10009942.svg)](https://doi.org/10.5281/zenodo.10009942)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

This resource contains all annotated candidates for innovative forms identified within the [Breviloquia Italica](https://github.com/breviloquia-italica) project.

## Description

The `data.csv` file is an UTF-8 CSV table of annotated candidates containing the following columns:

- `candidate`: the candidate form;
- `status`: an integer marking the candidate as either innovative (`1`) or not innovative (`-1`);
- `category`: a string containing the category for innovative candidates;
- `notes_category`: a string containing a colon separated list of categories considered for tagging innovative candidates;
- `notes_attestation`: a string containing free text with attestation information;
- `notes_general`: a string containing free text with general comments.

Please note that the `notes_category`, `notes_attestation` and `notes_general` columns were used as support during annotation, and as such were not translated from Italian.

Categories in the `category` column are values from the following list (translation to Italian is provided for comparison with `notes_category`):

- `acronym` (acronimo)
- `acronymic derivation` (deacronimico)
- `alteration` (alterazione)
- `compounding` (composizione)
- `deonymic derivation` (deonimico)
- `loanword adaptation` (prestito adattato)
- `loanword` (forestierismo)
- `orthographic variation` (variante grafica)
- `portmanteau` (macedonia)
- `prefixation` (prefissazione)
- `redefinition` (ridefinizione)
- `suffixation` (suffissazione)
- `tmesis` (tmesi)
- `transcategorisation` (transcategorizzazione)
- `univerbation` (univerbazione)

## Authors

Greta H. Franzini, Stefania Spina, Paolo Brasolin.

## License

This work is openly licensed via [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
