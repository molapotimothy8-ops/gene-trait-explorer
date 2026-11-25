# Lesotho Trait Survey Explorer
**Live demo:** https://molapotimothy8-ops.github.io/gene-trait-explorer/

An interactive page for exploring visible inherited traits (earlobes, handedness, tongue rolling, dimples, freckles, cleft chin, widow's peak) reported by about 303 people in Lesotho in 2026.

- `index.html`: the explorer (open it in any browser, no install needed)
- `lesotho-trait-survey-anonymized.csv`: the data, with emails and timestamps removed

## Method

Respondents answered an online form. Responses were parsed from the form export, anonymized, and coded (see the CSV header).

## Limitations

- Convenience sample (friends, family, schools), not representative of Lesotho.
- Self-reported traits; some people misjudge them.
- Age was not collected for the earliest responses, and sex could not be recovered for some rows.
- These traits are often taught as simple Mendelian traits, but their genetics is more complex. This project reports frequencies, not inheritance.

## License

Code: MIT. Survey data: CC BY 4.0.

Author: Timothy Molapo
