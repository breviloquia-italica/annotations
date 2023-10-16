# Breviloquia Italica: annotations

This resource contains all annotated candidates for innovative forms identified within the [Breviloquia Italica](https://github.com/breviloquia-italica) project.

## `data.csv`

The `data.csv` file is a CSV table of annotated candidates containing the following columns:

- `candidate`: the candidate form;
- `status`: an integer marking the candidate as either innovative (`1`) or not innovative (`-1`);
- `category`: a string containing the category for innovative candidates;
- `notes_category`: a string containing a colon separated list of categories considered for tagging innovative candidates;
- `notes_attestation`: a string containing a free text with attestation information;
- `notes_general`: a string containing a free text with general comments.

Please note that the `notes_category`, `notes_attestation` and `notes_general` columns were used as support during annotation, and as such were not translated from Italian.

Categories in the `category` column are values from the following list (translation to Italian is provided for comparison with `notes_category`):

- `orthographic variation` (variante grafica)
- `univerbation` (univerbazione)
- `suffixation` (suffissazione)
- `loanword` (forestierismo)
- `portmanteau` (macedonia)
- `loanword adaptation` (prestito adattato)
- `alteration` (alterazione)
- `prefixation` (prefissazione)
- `acronym` (acronimo)
- `transcategorisation` (transcategorizzazione)
- `compounding` (composizione)
- `deonymic derivation` (deonimico)
- `redefinition` (ridefinizione)
- `acronymic derivation` (deacronimico)
- `tmesis` (tmesi)
