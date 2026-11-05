# Men at Work

This repo holds the published figures and data for the American Institute for Boys and Men's dashboard on men's employment in the United States. The site is served at **https://aibmen.github.io/men_at_work/** and embedded on [aibm.org](https://aibm.org/).

**This repo is generated. Don't edit it by hand.** Every file is produced by AIBM's data pipeline and replaced on each monthly update. The commit history is a record of what was published and when.

## Sources

- U.S. Bureau of Labor Statistics: Current Population Survey (labor force statistics and weekly earnings) and Current Employment Statistics (payroll jobs).
- U.S. Bureau of Economic Analysis, via FRED: PCE price index (`PCEPI`), used to adjust earnings for inflation.
- IPUMS CPS, University of Minnesota (www.ipums.org): CPS basic monthly microdata, used for NEET rates and state estimates. Only aggregates are published here.

## Citation

American Institute for Boys and Men. "Men at work: Trends and metrics." Data through the month shown in `data/manifest.json`. https://aibm.org/research/dashboard-tracking-male-employment-in-the-us/

When using the NEET or state tables, also cite IPUMS CPS: Sarah Flood, Miriam King, Renae Rodgers, Steven Ruggles, J. Robert Warren, Daniel Backman, Etienne Breton, Grace Cooper, Julia A. Rivera Drew, Stephanie Richards, David Van Riper, and Kari C.W. Williams. IPUMS CPS: Version 13.0 [dataset]. Minneapolis, MN: IPUMS, 2025. https://doi.org/10.18128/D030.V13.0

Questions: comms@aibm.org
