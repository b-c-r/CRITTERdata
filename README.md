# Habitat *c*omplexity *r*educes feed*i*ng s*t*reng*t*h of fr*e*shwater p*r*edators (CRITTER, Data Repository)

## Summary

This data is a supplement to the upcoming publication of Aranbarri et al. (unpublished) investigating the effect of habitat complexity on the feeding functional response of two freshwater invertebrate predators. You will find details on the methodology in the cited publication. We will link to it after we make it publicly available.

## License

This data is published under a [**Creative Commons BY 4.0**](https://creativecommons.org/licenses/by/4.0/) license.

## Authors

-   Lorea Flores ([0000-0002-0082-4072](https://orcid.org/0000-0002-0082-4072))
    -   Data Collection, Experimental Design, Data Curation
    -   [lflorescompains@gmail.com](lflorescompains@gmail.com)
    -   Laboratory of Stream Ecology, Department of Plant Biology and Ecology, Faculty of Science and Technology, University of the Basque Country, UPV/EHU PO Box 644, 48080 Bilbao, Spain
-   Julia Reiss ([0000-0002-3740-0046](https://orcid.org/0000-0002-3740-0046))
    -   Experimental Design, Data Curation
    -   [julia.reiss@roehampton.ac.uk](julia.reiss@roehampton.ac.uk)
    -   Centre for Pollution Research and Policy, Brunel University of London, Uxbridge, UB8 3PH, UK
-   Aitor Larrañaga ([0000-0002-0185-9154](https://orcid.org/0000-0002-0185-9154))
    -   Experimental Design, Data Curation
    -   [aitor.larranagaa@ehu.eus](aitor.larranagaa@ehu.eus)
    -   Laboratory of Stream Ecology, Dept. of Plant Biology and Ecology, Faculty of Science and Technology, University of the Basque Country, UPV/EHU PO Box 644, 48080 Bilbao, Spain.
-   Björn C. Rall ([0000-0002-3191-8389](https://orcid.org/0000-0002-3191-8389))
    -   Experimental Design, Data Curation
    -   [bjoern.rall@uni-konstanz.de](bjoern.rall@uni-konstanz.de)
    -   Aquatic Ecology and Evolution Group, Limnological Institute, University of Konstanz, Mainaustraße 252, 78464 Konstanz/Egg, Germany
-   Mireia Aranbarri ([0009-0001-3506-0914](https://orcid.org/0009-0001-3506-0914))
    -   Data Curation
    -   [mireia.arambarri@ehu.eus](mireia.arambarri@ehu.eus)
    -   Laboratory of Stream Ecology, Dept. of Plant Biology and Ecology, Faculty of Science and Technology, University of the Basque Country, UPV/EHU PO Box 644, 48080 Bilbao, Spain.
-   Ioar de Guzmán ([0000-0001-8894-8477](https://orcid.org/0000-0001-8894-8477))
    -   Data Curation
    -   [mirenioar.deguzman@ehu.eus](mirenioar.deguzman@ehu.eus)
    -   Laboratory of Stream Ecology, Dept. of Plant Biology and Ecology, Faculty of Science and Technology, University of the Basque Country, UPV/EHU PO Box 644, 48080 Bilbao, Spain.

## Related Works

-   [Data on Zenodo](https://doi.org/10.5281/zenodo.14891980) [@FloresEtAl2025ComplexityReducesFeedingData]

-   [Data on GitHub](https://github.com/b-c-r/CRITTERdata)

-   [R-Code on Zenodo](https://doi.org/10.5281/zenodo.14894598) [@RallEtAl2025ComplexityReducesFeedingCode]

-   [R-Code on GitHub](https://github.com/b-c-r/CRITTERdata)

-   [Statistical Report on GitHub](https://github.com/b-c-r/CRITTERstatistics)

-   Statistical Report on Zenodo (link tba)

-   Scientific Preprint Paper (link tba)

## Data Location

The data is provided as "critter_data.csv" in the repositories main folder.

## Data Columns

-   **id**: *integer*; the unique identifier for every row or experimental trial.
-   **predator**: factor; the Latin binomial name of the predator in two levels: *Notonecta glauca* and *Ischnura elegans*.
-   **complexity_level**: *ordered factor*; the artificial habitat's level of complexity: levels 0-5.
-   **ring_count**: *integer*; the artificial habitat was made up of: 0, 2, or 3 rings.
-   **n_initial**: *integer*; the number of prey individuals at the start of the experiment: 1, 3, 5, 10, 30, 120, 80, 180.
-   **n_final**: *integer*; the remaining prey individuals at the end of the experiment.
-   **block_id**: *factor*; the temporal and design block of the experiments in two levels: 1, 2. Note that the blocks are at different times for each predator species. The second block was used to add higher prey densities.
-   **date**: *date*; date according to [ISO 8601](https://en.wikipedia.org/wiki/ISO_8601). Note that the dates for the experiments with *Ischnura elegans* are not given and marked as NA.

## Methods

Please see the methods section of the original publication (Aranbarri et al. unpublished, link tba) for details on how the data was collected.

## Funding Information

-   Mireia Aranbarri was funded by the **Investigo Programm funded by the NextGenerationEU initiative**.
-   Lorea Flores was funded by a grant by the **Spanish Ministry of Education and Culture**.
-   Ioar de Guzmán was funded by the **Spanish Ministry of Science, Innovation and Universities (TED2021-129966B-C31)**.
-   Julia Reiss was supported by a **Royal Society of London Starting Grant**.
-   Björn C. Rall gratefully acknowledges the funding by the **German Science Foundation (DFG) to the Research Unit DynaSym (FOR 5064)**.

## Acknowledgements

-   We thank the **WWT London** for the permission to sample damselflies and backswimmers on their grounds and **Szymon Szary** for his assistance in the field and laboratory.
