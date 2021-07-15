# Bird distribution in Spain
![birds](https://cdna.artstation.com/p/assets/images/images/021/706/756/large/marina-lezcano-aves-firma.jpg?1572642446)

## <span style="color:green"> Context and objective </span>

***Birds are a miracle because they prove to us there is a finer, simpler state of being which we may strive to attain***

*Douglas Coupland*


They play a vital role in controlling pests, pollinating plants, spreading seeds, oxigenating the air and tranforming pollutants into nutrients.

They are not just creatures that beautify our planet but they also contribute to the balance and the operation of our ecosystem.     

**As humans, we are responsible for their endangerment and preservation.**


## <span style="color:green"> Aim </span>

Our aim is to study the distribution of birds in Spain, in search of inconsistencies in the patterns.

With more than 12 million of registers from observations in Spain, we study the distribution of 604 species, and their tendence over the past 20 years (low data volume prior to 2000)


## <span style="color:green"> Data & Technologies </span>

- Initial dataset: *EOD – eBird Observation Dataset* from GBIF, the Global Biodiversity Information Facility
    - EDA: Pandas, numpy, itertools
- Enrichment data: API call to the IUCN Red List *International Union for Conservation of Nature*
    - Request,json
- Visualizacion: Tableau
    -https://public.tableau.com/shared/RT8Q3CXJW?:display_count=n&:origin=viz_share_link


## <span style="color:green"> Conclusions </span>
- The record of bird sightings have grown exponentially in recent years, proportionally in the different spanish regions
- Despite the natural stability of birds in their geographical distribution, we found species with an unstable distribution over the years
- Through the study of these "unstable distribution species" and their category in the Red List, we find that those with a **decreasing population volume are aquatic birds**
        - Marmaronetta angustirostris - *Vulnerable (VU)*
        - Phoeniconaias minor - *Near threatened (NT)*
        - Calidris canutus - *Near threatened (NT)*
        - Podiceps grisegena
        - Fulica cristata
        - Alopochen aegyptiaca
        - Sterna paradisaea
        - Tringa flavipes
        - Alle alle
        - Aix galericulata
        - Anser fabalis
   

As a result of these conclusions, we suggest a deeper line of research focused on the threats to acquatic birds caused by humans:

- Marine waters: pollution, bycatch,  overbuilding and traffic in nearby areas
- Wetlands and fresh waters: use of pesticides in agriculture, transformation of humid areas into crops and overexploitation of groundwaters
