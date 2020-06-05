# Utility Scripts

This folder contains framework-agnostic utility scripts for ATT&CK Control Framework Mappings. 

| Script | Purpose |
|:-------|:--------|
| mappingsToHeatmaps.py | Enables visualization of the control mappings in the ATT&CK Matrix. Builds [ATT&CK Navigator](https://github.com/mitre-attack/attack-navigator) heatmap layers. These layers can also be found in the `layers` folder of each control framework. |
| substitute.py | Enables construction of the ATT&CK Website and ATT&CK Navigator with controls taking the place of mitigations. Uses the ATT&CK STIX content from [MITRE/CTI](https://github.com/mitre/cti) and substitutes the controls and mappings for the ATT&CK mitigations. The output STIX bundle can be used as input to the [ATT&CK Navigator](https://github.com/mitre-attack/attack-navigator) or [ATT&CK website](https://github.com/mitre-attack/attack-website). The output of this script can also be found in the `data` folder of each control framework. |