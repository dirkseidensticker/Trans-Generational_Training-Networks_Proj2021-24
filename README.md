
# Investigating Trans-Generational Training Networks in Central Africa: A Multi-Layered Analysis of Pottery Technology (2021-2024)

This repository contains information on the above named research project
at Ghent University, funded by the *Fonds voor Wetenschappelijk
Onderzoek – Vlaanderen* (grant number: **1287922N**) awarded to D.
Seidensticker.

<div class="figure" style="text-align: center">

<img src="README_files/figure-gfm/map-1.png" alt="Map of sampled sitese" width="100%" />
<p class="caption">
Map of sampled sitese
</p>

</div>

## Folder and File Structure

- `samples.csv` contains a list of all studied samples and their
  meta-data

## Main Dataset **samples.csv**

The list of studied samples contains the following fields:

| Datafield | Description |
|----|----|
| ID | running sampling number |
| nwCongoID | reference to DB ID’s in [nwCongo/data/nwCongoDB.sqlite](https://github.com/dirkseidensticker/nwCongo/blob/master/data/base/nwCongoDB.sqlite) |
| tsID | running number of the thin-section slide |
| SITE | name of the site |
| CODE | site code as used in other reports |
| FEAT | code of the feature |
| IND | code of the individual sample / sherd |
| POTTERY | pottery style in reference to [aSCAC/potterygroups.csv](https://github.com/dirkseidensticker/aSCAC/blob/master/potterygroups.csv) |
| PROV | `x` marks samples with known provenance (e.g. ethnographic vessels or clay samples) |
| Xray | `x` marks samples with pXRF data |
| TYPE | identifies type of sherd or other characteristics |
| BOX | storage location |
| FABRIC | macroscopic fabric |
| SUBGRP | detailed macroscopic fabric (cf. Seidensticker 2021) |
| SurfSponges | marks absence/presence of sponge spicules using reflective light microscope |
| NOTES | notes |
| RIVER | river system |
| GROUP | initial sampeling clusters |
| REFERENCE | reference to published sources |

## Paper based on this project

|  |  |
|----|----|
|  | D. Seidensticker, W. Hubau, F. Mees, G. Fiers & V. Cnudde (submitted) “On and Off the Rivers: Strategies for Clay Sourcing and Preparation in the Congo Basin.”. Data & code [OnOffRivers](https://github.com/dirkseidensticker/OnOffRivers) |
| ![](https://raw.githubusercontent.com/dirkseidensticker/PikundaMunda_DissapearingPotteryTraditions_AAR/refs/heads/main/cover.jpg) | D. Seidensticker (2025) [“Pikunda-Munda: Disappearance of Pottery Production in the Western Congo Basin at the End of the Early Iron Age.”](https://link.springer.com/article/10.1007/s10437-024-09610-8) African Archaeological Review. <doi:10.1007/s10437-024-09610-8>. Data & code: [PikundaMunda_DissapearingPotteryTraditions_AAR](https://github.com/dirkseidensticker/PikundaMunda_DissapearingPotteryTraditions_AAR) |

## Licenses

**Figures and Tables :**
[CC-BY-4.0](http://creativecommons.org/licenses/by/4.0/)

**Data :** [CC-0](http://creativecommons.org/publicdomain/zero/1.0/)
attribution requested in reuse

**Code :** [MIT License](https://opensource.org/licenses/MIT)
