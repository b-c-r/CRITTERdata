Habitat *c*omplexity *r*educes feed*i*ng s*t*reng*t*h of fr*e*shwater
p*r*edators (CRITTER) — Data
================

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15348769.svg)](https://doi.org/10.5281/zenodo.15348769)

## Summary

This data is supplementing our preprint article by Aranbarri et al.
(2025) investigating the effect of habitat complexity on the feeding
functional response of two freshwater invertebrate predators. Find below
information on related works.

## License

The data and the pictures are published under a [**Creative Commons BY
4.0**](https://creativecommons.org/licenses/by/4.0/) license.

## How to cite:

If you use our data, pictures or our habitat silhouettes, please cite
us:

Flores, L., Reiss, J., Larrañaga, A., Rall, B. C., Aranbarri, M., and de
Guzmán, I. (2025): Habitat complexity reduces feeding strength of
freshwater predators (CRITTER) — Data. Zenodo.
<https://doi.org/10.5281/zenodo.14891980>

Specific version(s):

Flores, L., Reiss, J., Larrañaga, A., Rall, B. C., Aranbarri, M., and de
Guzmán, I. (2025): Habitat complexity reduces feeding strength of
freshwater predators (CRITTER) — Data (v0.1.2). Zenodo.
<https://doi.org/10.5281/zenodo.15348769>

Flores, L., Reiss, J., Larrañaga, A., Rall, B. C., Aranbarri, M., and de
Guzmán, I. (2025): Complexity reduces feeding strength of freshwater
predators (CRITTER) - Data (v0.1.0). Zenodo.
<https://doi.org/10.5281/zenodo.14891981>

## Authors

- Lorea Flores
  ([0000-0002-0082-4072](https://orcid.org/0000-0002-0082-4072))
  - Data Collection, Experimental Design, Data Curation, Pictures
  - <lflorescompains@gmail.com>
  - Laboratory of Stream Ecology, Department of Plant Biology and
    Ecology, Faculty of Science and Technology, University of the Basque
    Country, UPV/EHU PO Box 644, 48080 Bilbao, Spain
- Julia Reiss
  ([0000-0002-3740-0046](https://orcid.org/0000-0002-3740-0046))
  - Experimental Design, Data Curation
  - <julia.reiss@brunel.ac.uk>
  - Centre for Pollution Research and Policy, Brunel University of
    London, Uxbridge, UB8 3PH, UK
- Aitor Larrañaga
  ([0000-0002-0185-9154](https://orcid.org/0000-0002-0185-9154))
  - Experimental Design, Data Curation
  - <aitor.larranagaa@ehu.eus>
  - Laboratory of Stream Ecology, Dept. of Plant Biology and Ecology,
    Faculty of Science and Technology, University of the Basque Country,
    UPV/EHU PO Box 644, 48080 Bilbao, Spain.
- Björn C. Rall
  ([0000-0002-3191-8389](https://orcid.org/0000-0002-3191-8389))
  - Experimental Design, Data Curation
  - <bjoern.rall@uni-konstanz.de>
  - Aquatic Ecology and Evolution Group, Limnological Institute,
    University of Konstanz, Mainaustraße 252, 78464 Konstanz/Egg,
    Germany
- Mireia Aranbarri
  ([0009-0001-3506-0914](https://orcid.org/0009-0001-3506-0914))
  - Data Curation
  - <mireia.arambarri@ehu.eus>
  - Laboratory of Stream Ecology, Dept. of Plant Biology and Ecology,
    Faculty of Science and Technology, University of the Basque Country,
    UPV/EHU PO Box 644, 48080 Bilbao, Spain.
- Ioar de Guzmán
  ([0000-0001-8894-8477](https://orcid.org/0000-0001-8894-8477))
  - Data Curation
  - <mirenioar.deguzman@ehu.eus>
  - Laboratory of Stream Ecology, Dept. of Plant Biology and Ecology,
    Faculty of Science and Technology, University of the Basque Country,
    UPV/EHU PO Box 644, 48080 Bilbao, Spain.
  - INRAE, UMR 1224, Ecologie Comportementale et Biologie des
    Populations de Poissons, Aquapôle, quartier Ibarron, 64310 Saint-Pée
    sur Nivelle, France.

## Related Works

- [Data on Zenodo](https://doi.org/10.5281/zenodo.14891980) (Flores et
  al., 2025)

- [Data on GitHub](https://github.com/b-c-r/CRITTERdata)

- [R-Code on Zenodo](https://doi.org/10.5281/zenodo.14894598) (Rall et
  al., 2025a)

- [R-Code on GitHub](https://github.com/b-c-r/CRITTERcode)

- [Supplemental Statistics Report on
  Zenodo](https://doi.org/10.5281/zenodo.14898819) (Rall et al., 2025b)

- [Supplemental Statistics Report on
  GitHub](https://github.com/b-c-r/CRITTERstatistics)

- [Scientific Preprint
  Article](https://doi.org/10.1101/2025.02.22.639633) (Aranbarri et al.,
  2025)

## Data Location

The data is provided as “critter_data.csv” in the repositories main
folder.

## Data Columns

- **id**: *integer*; the unique identifier for every row or experimental
  trial.
- **predator**: factor; the Latin binomial name of the predator in two
  levels: *Notonecta glauca* and *Ischnura elegans*.
- **complexity_level**: *ordered factor*; the artificial habitat’s level
  of complexity: levels 0-5.
- **ring_count**: *integer*; the artificial habitat was made up of: 0,
  2, or 3 rings.
- **n_initial**: *integer*; the number of prey individuals at the start
  of the experiment: 1, 3, 5, 10, 30, 120, 80, 180.
- **n_final**: *integer*; the remaining prey individuals at the end of
  the experiment.
- **block_id**: *factor*; the temporal and design block of the
  experiments in two levels: 1, 2. Note that the blocks are at different
  times for each predator species. The second block was used to add
  higher prey densities.
- **date**: *date*; date according to [ISO
  8601](https://en.wikipedia.org/wiki/ISO_8601). Note that the dates for
  the experiments with *Ischnura elegans* are not given and marked as
  NA.

## Habitat Pictures

Find pictures and silhouettes of the habitat complexity levels 1 to 4 as
published in the folder `pictures`. `all_habitat_levels_numbered.png`
was originally published in Flores et al. (2016), figure 1, under a
[**Creative Commons BY
4.0**](https://creativecommons.org/licenses/by/4.0/) license. Mireia
Aranbarri and Ioar de Guzmán created the silhouettes from these
pictures.

## Methods

Please see the methods section of our
[publication](https://doi.org/10.1101/2025.02.22.639633) (Aranbarri et
al., 2025) for details on how the data was collected.

## Funding Information

- Mireia Aranbarri was funded by the **Investigo Programm funded by the
  NextGenerationEU initiative**.
- Lorea Flores was funded by a grant by the **Spanish Ministry of
  Education and Culture**.
- Ioar de Guzmán was funded by the **Spanish Ministry of Science,
  Innovation and Universities (TED2021-129966B-C31)**.
- Julia Reiss was supported by a **Royal Society of London Starting
  Grant**.
- Björn C. Rall gratefully acknowledges the funding by the **German
  Science Foundation (DFG) to the Research Unit DynaSym (FOR 5064)**.

## Acknowledgements

- We thank the **WWT London** for the permission to sample damselflies
  and backswimmers on their grounds and **Szymon Szary** for his
  assistance in the field and laboratory.

## References

<div id="refs" class="references csl-bib-body hanging-indent"
entry-spacing="0" line-spacing="2">

<div id="ref-AranbarriEtAl2025ComplexityReducesFeeding"
class="csl-entry">

Aranbarri, M., Flores, L., de Guzmán, I., Larrañaga, A., Elosegi, A.,
Rall, B. C., & Reiss, J. (2025). *Habitat complexity reduces feeding
strength of freshwater predators* (2025.02.22.639633). bioRxiv.
<https://doi.org/10.1101/2025.02.22.639633>

</div>

<div id="ref-FloresEtAl2016HabitatComplexityAquatic" class="csl-entry">

Flores, L., Bailey, R. A., Elosegi, A., Larrañaga, A., & Reiss, J.
(2016). Habitat complexity in aquatic microcosms affects processes
driven by detritivores. *PLOS One*, *11*(11), e0165065.
<https://doi.org/10.1371/journal.pone.0165065>

</div>

<div id="ref-FloresEtAl2025ComplexityReducesFeedingData"
class="csl-entry">

Flores, L., Reiss, J., Larrañaga, A., Rall, B. C., Aranbarri, M., & de
Guzmán, I. (2025). *Habitat complexity reduces feeding strength of
freshwater predators (CRITTER) — Data (v0.1.2)*. Zenodo.
<https://doi.org/10.5281/zenodo.15348769>

</div>

<div id="ref-RallEtAl2025ComplexityReducesFeedingCode"
class="csl-entry">

Rall, B. C., Aranbarri, M., Flores, L., de Guzmán, I., Larrañaga, A., &
Reiss, J. (2025a). *Habitat complexity reduces feeding strength of
freshwater predators (CRITTER) — Code (v0.1.2)*. Zenodo.
<https://doi.org/10.5281/zenodo.15346225>

</div>

<div id="ref-RallEtAl2025ComplexityReducesFeedingStatistics"
class="csl-entry">

Rall, B. C., Aranbarri, M., Flores, L., de Guzmán, I., Larrañaga, A., &
Reiss, J. (2025b). *Habitat complexity reduces feeding strength of
freshwater predators (CRITTER) — Supplemental Statistics Report
(v.0.1.2)*. Zenodo. <https://doi.org/10.5281/zenodo.15348995>

</div>

</div>
