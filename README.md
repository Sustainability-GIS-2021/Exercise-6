# Zonation 5 Uusimaa-tutorial

*Version: 1.0 *

Simplified data and setups from UML (Uudenmaanliitto) analysis (Kuusterä et al. 2015).

The data and setups in this project are meant for training purposes only and do not represent a full real-life analysis.
Data are described in more detail in READMEs in each data subfolder.

*Distributed under Creative Commons BY-SA 4.0 Licence*
https://creativecommons.org/licenses/by/4.0/

You are allowed to:
- Share: copy and redistribute the material in any medium or format
- Adapt: remix, transform, and build upon the material for any purpose, even commercially

Under the following terms:
- Attribution: You must give appropriate credit, provide a link to the license, and indicate if changes were made.
You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
- ShareAlike: If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.

Cite the training set as:
Joel Jalkanen, Tuuli Toivonen, Joona Lehtomäki, Peter Kullberg, Heini Kujala & Atte Moilanen (2021) Zonation software training set with the Uusimaa data.

- No additional restrictions — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

## Variants

1. 01_abf_hab
2. 02_cazmax_hab
3. 03_abf_hab_spp
4. 04_abf_hab_spp_wghts
5. 05_abf_hab_spp_wghts_hmask
6. 06_abf_hab_spp_wghts_landuse

Codes in the names are interpreted as follows:

| Code    | Description                                    |
|---------|------------------------------------------------|
| abf     | Cell removal rule: additive benefit function   |
| cazmax  | Cell removal rule: core area zonation          |
| hab	  | Input features: habitats                       |
| spp	  | Input features: species                        |
| wghts	  | Varying weights                                |
| landuse | Planned landuse in Uusimaa region              |
| hmask	  | Protected areas as a hierarchic mask           |


## Contributors

- Joel Jalkanen <joel.jalkanen@helsinki.fi>
- Tuuli Toivonen <tuuli.toivonen@helsinki.fi>
- Joona Lehtomäki <joona.lehtomaki@gmail.com>
- Peter Kullberg <peter.kullberg@helsinki.fi>
- Atte Moilanen <atte.moilanen@helsinki.fi>


## References

Kuusterä, J., S. Aalto, A. Moilanen, T. Toivonen, and J. Lehtomäki. 2015. 
Uudenmaan viherrakenteen analysointi Zonation-menetelmällä. Helsinki. Available from 
http://www.uudenmaanliitto.fi/files/15491/Uudenmaan_viherrakenteen_analysointi_Zonation-menetelmalla_E145-2015.pdf.
