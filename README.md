# ISTP-SPASEValidation
This repository hosts the skeleton data files with ISTP metadata and the resulting SPASE records drafted from each example input. All ISTP-SPASE conversion implementations should use these inputs and outputs to check their mapping scripts against. For now, the special case where the ISTP field "REPRESENTATION_1" is excluded. All other prioritized mappings are covered by the full_input.* files.

Implementations of this mapping:
* ISTP Metadata Editor https://spdf.gsfc.nasa.gov/istp-metadata-editor/
* CDAWMeta https://github.com/rweigel/cdawmeta/blob/main/cdawmeta/generators/spase_auto.py
