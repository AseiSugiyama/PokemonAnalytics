# Pokèdex

## Pokemon.csv

This data was originally sourced from Kaggle, specifically [The Complete Pokemon Dataset](https://www.kaggle.com/rounakbanik/pokemon#pokemon.csv) (refer to that page for data set description). The data was scraped from [Serebii.net](https://serebii.net/). It was licensed under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). 

### Content

- name: The English name of the Pokemon
- japanese_name: The Original Japanese name of the Pokemon
- pokedex_number: The entry number of the Pokemon in the National Pokedex
- percentage_male: The percentage of the species that are male. Blank if the Pokemon is genderless.
- type1: The Primary Type of the Pokemon
- type2: The Secondary Type of the Pokemon
- classification: The Classification of the Pokemon as described by the Sun and Moon Pokedex
- height_m: Height of the Pokemon in metres
- weight_kg: The Weight of the Pokemon in kilograms
- capture_rate: Capture Rate of the Pokemon
- base_egg_steps: The number of steps required to hatch an egg of the Pokemon
- abilities: A stringified list of abilities that the Pokemon is capable of having
- experience_growth: The Experience Growth of the Pokemon
- base_happiness: Base Happiness of the Pokemon
- against_?: Eighteen features that denote the amount of damage taken against an attack of a particular type
- hp: The Base HP of the Pokemon
- attack: The Base Attack of the Pokemon
- defense: The Base Defense of the Pokemon
- sp_attack: The Base Special Attack of the Pokemon
- sp_defense: The Base Special Defense of the Pokemon
- speed: The Base Speed of the Pokemon
- generation: The numbered generation which the Pokemon was first introduced
- is_legendary: Denotes if the Pokemon is legendary.

## weight_and_height.csv

This data was also from Kaggle, specifically [Pokemon with stats | Kaggle](https://www.kaggle.com/abcsds/pokemon#Pokemon.csv) (refer to that page for data set description). It was licensed under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). 

This data contains three columns, id, height and weight with SI units (meter and kilogram) transformed from the original data with yard-pond units.
