# Breviloquia Italica: annotations

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10009942.svg)](https://doi.org/10.5281/zenodo.10009942)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

This resource contains all annotated candidates for innovative forms identified within the [Breviloquia Italica](https://github.com/breviloquia-italica) project.

## Description

The `data.csv` file is an UTF-8 CSV table of annotated candidates containing the following columns:

- `candidate`: a string containing the candidate form;
- `subset_a`: a boolean flag (`1` for true, `0` for false) representing whether the candidate matches selection criteria for subset A[^1];
- `subset_b`: a boolean flag (`1` for true, `0` for false) representing whether the candidate matches selection criteria for subset B[^1];
- `status`: an integer marking the candidate as either innovative (`1`) or not innovative (`-1`);
- `category`: a string containing the category for innovative candidates; values can be any of the following items (italian translation is provided for comparison with `notes_category`)
  - `acronym` (acronimo)
  - `acronymic derivation` (deacronimico)
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
- `pos`: a string containing the POS for innovative candidates; values are colon separated lists of items among
  - `ADJ` (adjective)
  - `ADV` (adverb)
  - `CON` (conjunction)
  - `INT` (interjection)
  - `NOM` (noun)
  - `NPR` (name)
  - `PRE` (preposition)
  - `PRO` (pronoun)
  - `VER` (verb)
- `hashtag_type`: a string containing the type of hashtag for innovative candidates; values are colon separated of items among
  - `evaluative`
  - `informative`
- `notes_category`: a string containing free text[^2] with comments on categorization;
- `notes_attestation`: a string containing a free text[^2] with attestation information;
- `notes_general`: a string containing a free text[^2] with general comments.

[^1]: Details on the definition of subsets A and B can be found in the publications.
[^2]: Please note that the `notes_*` columns were used as support during annotation, and as such were not translated from Italian.

## Authors

Greta H. Franzini, Stefania Spina, Paolo Brasolin.

## License

This work is openly licensed via [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
