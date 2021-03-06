# Examples for Bayesian atomtype sampler

## Manifest
* `convert_frosst/` - code to convert hand-coded SMIRKS in modified AMBER .frcmod files into SMIRNOFF XML format, as per https://github.com/openforcefield/smarty/issues/118. Includes example notebooks looking at parameter occurrences in the result.
* `SMIRNOFF_vs_frosst/` - code to take a specified SMIRNOFF FFXML file (such as, for example, generated by conversion via the above `convert_frosst` infrastructure) and do detailed energy comparison to energies arising for same molecules from parm@frosst parameters, as per https://github.com/openforcefield/smarty/issues/123.
* `filter_molecule_sets/` - code used to filter DrugBank database including some initial subsets that were not used in final smarty/smirky testing
