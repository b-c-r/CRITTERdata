# *C*omplexity *r*educes feed*i*ng s*t*reng*t*h of fr*e*shwater p*r*edators (CRITTER, Data Repository)

## Summary

This data is a supplement to the upcoming publication of Aranbarri et al. (unpublished) investigating the effect of habitat complexity on the feeding functional response of two freshwater invertebrate predators. You will find details on the methodology in the cited publication. We will link to it after we make it publicly available.

## License

This data is published under a [**Creative Commons BY 4.0**](https://creativecommons.org/licenses/by/4.0/)**.**

## Authors

-   Lorea Flores ([0000-0002-0082-4072](https://orcid.org/0000-0002-0082-4072))
    -   Data Collection, Experimental Design, Data Curation
    -   INRA, UMR 1224, Ecologie Comportementale et Biologie des Populations de Poissons, Aquapôle, quartier Ibarron, 64310 Saint-Pée sur Nivelle, France
-   Julia Reiss ([0000-0002-3740-0046](https://orcid.org/0000-0002-3740-0046))
    -   Experimental Design, Data Curation
    -   Division of Environmental Sciences, College of Health, Medicine and Life Sciences, Brunel University of London, Uxbridge, UB8 3PH, UK.
-   Aitor Larrañaga ([0000-0002-0185-9154](https://orcid.org/0000-0002-0185-9154))
    -   Experimental Design, Data Curation
    -   Laboratory of Stream Ecology, Dept. of Plant Biology and Ecology, Faculty of Science and Technology, University of the Basque Country, UPV/EHU PO Box 644, 48080 Bilbao, Spain.
-   Björn C. Rall ([0000-0002-3191-8389](https://orcid.org/0000-0002-3191-8389))
    -   Experimental Design, Data Curation
    -   Aquatic Ecology and Evolution Group, Limnological Institute, University of Konstanz, Mainaustraße 252, 78464 Konstanz/Egg, Germany
-   Mireia Aranbarri ([0009-0001-3506-0914](https://orcid.org/0009-0001-3506-0914))
    -   Data Curation
    -   Laboratory of Stream Ecology, Dept. of Plant Biology and Ecology, Faculty of Science and Technology, University of the Basque Country, UPV/EHU PO Box 644, 48080 Bilbao, Spain.
-   Ioar de Guzmán ([0000-0001-8894-8477](https://orcid.org/0000-0001-8894-8477))
    -   Data Curation
    -   Laboratory of Stream Ecology, Dept. of Plant Biology and Ecology, Faculty of Science and Technology, University of the Basque Country, UPV/EHU PO Box 644, 48080 Bilbao, Spain.

## Related Works

-   Data on Zenodo (link TBA)

-   Scientific Preprint Paper (link tba)

-   R-Code (link tba)

-   Supplementary Statistical Report (link tba)

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
