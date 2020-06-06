# Palmer Station LTER Penguins (in progress)

Data are generously collected and made available by [Dr. Kristen Gorman](https://www.uaf.edu/cfos/people/faculty/detail/kristen-gorman.php) and the [Palmer Station, Antarctica LTER](https://pal.lternet.edu/), a member of the [Long Term Ecological Research Network](https://lternet.edu/). 

**Thank you** to Dr. Gorman, Palmer Station LTER and the LTER Network! Special thanks to Marty Downs (Director, LTER Network Office) for help regarding the data license & use.

## License & citation

- **Data are available by** [TODO: INSERT LICENSE INFO HERE].

- **Please cite this data using:** Gorman KB, Williams TD, Fraser WR (2014) Ecological Sexual Dimorphism and Environmental Variability within a Community of Antarctic Penguins (Genus *Pygoscelis*). PLoS ONE 9(3): e90081. doi:10.1371/journal.pone.0090081 [TODO: CHECK WITH KRISTEN & MARTY ON THIS]


## Summary:

The data folder contains two CSV files. For intro courses/examples, you probably want to use the first one (penguins_size.csv). 

- **penguins_size.csv**: Simplified data from original penguin data sets. Contains variables:

    - `species`: penguin species (Chinstrap, Adélie, or Gentoo)
    - `culmen_length_mm`: culmen length (mm) 
    - `culmen_depth_mm`: culmen depth (mm) 
    - `flipper_length_mm`: flipper length (mm) 
    - `body_mass_g`: body mass (g) 
    - `island`: island name (Dream, Torgerson, or Biscoe) in the Palmer Archipelago (Antarctica)
    - `sex`: penguin sex

- **penguins_lter.csv**: Original combined data 

See below for links and citations to original data. 

## Example graphs using the data:

#### Flipper length vs. body mass

<img src="figures/mass_flipper.png" width="600"/>

#### Flipper length vs. culmen length

<img src="figures/flipper_culmen.png" width="600"/>

#### Simpson's paradox example

Culmen length vs. culmen depth, omitting species: 

<img src="figures/culmen_no_species.png" width="600"/>

Culmen length vs. culmen depth, including species: 

<img src="figures/culmen_len_dep.png" width="600"/>

#### Opportunities for comparisons between groups

There are a number of questions you could ask about differences between groups. Here are a couple histograms to consider.

Flipper length histograms:

<img src="figures/flipper_hist.png" width="600"/>

Body mass histograms: 

<img src="figures/mass_hist.png" width="600"/>

## Supplemental artwork

You are invited to use this accompanying artwork (Artwork: @allison_horst):

#### Meet the penguins: 
<img src="figures/lter_penguins.png" width="600"/>

#### What is culmen length & depth? 
<img src="figures/culmen.png" width="400"/>

## Data: 

These data are published in: 

**Gorman KB, Williams TD, Fraser WR** (2014) Ecological Sexual Dimorphism and Environmental Variability within a Community of Antarctic Penguins (Genus *Pygoscelis*). PLoS ONE 9(3): e90081. doi:10.1371/journal.pone.0090081

See the full paper [HERE](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0090081). 

From Gorman et al. (2014): "Data reported here are publicly available within the PAL-LTER data system (datasets #219, 220, and 221): http://oceaninformatics.ucsd.edu/datazoo/data/pallter/datasets. These data are additionally archived within the United States (US) LTER Network’s Information System Data Portal: https://portal.lternet.edu/. Individuals interested in using these data are therefore expected to follow the US LTER Network’s Data Access Policy, Requirements and Use Agreement: https://lternet.edu/data-access-policy/."

Anyone interested in publishing the data should contact [Dr. Kristen Gorman](https://www.uaf.edu/cfos/people/faculty/detail/kristen-gorman.php) about analysis and working together on any final products.

## Links to data:

**Links to data from LTER Network Data Portal:** 

Original data accessed via the [LTER Data Portal](https://portal.lternet.edu/nis/home.jsp): 

- Chinstrap penguins: https://portal.lternet.edu/nis/mapbrowse?packageid=knb-lter-pal.220.3
- Adélie penguins: https://portal.lternet.edu/nis/mapbrowse?packageid=knb-lter-pal.219.3
- Gentoo penguins: https://portal.lternet.edu/nis/mapbrowse?packageid=knb-lter-pal.221.2
