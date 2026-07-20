# Pokémon Go evolutions

A key part of Pokémon Go is using evolutions to get stronger Pokémon, and a deeper understanding of evolutions is key to being the greatest Pokémon Go player of all time. This data set covers 75 Pokémon evolutions spread across four species. A wide set of variables are provided, allowing a deeper dive into what characteristics are important in predicting a Pokémon's final combat power (CP).
Can be viewed as a data frame with 75 rows and 27 variables.

+ name - A unique name given to the Pokémon
+ species - The Pokémon's type, e.g. Pidgey.
+ cp - Pre-evolution Combat Power, which is a summary of the Pokémon's strength for battling prior to the evolution of the Pokémon.
+ hp - Pre-evolution Hit Points, which is a summary of how difficult it is to weaken the Pokémon in a battle.
+ weight - Pre-evolution weight, in kilograms.
+ height - Pre-evolution height, in meters.
+ power_up_stardust - Pre-evolution stardust required to power up the Pokémon.
+ power_up_candy - Pre-evolution candy required to power up the Pokémon.
+ attack_weak - The name of the pre-evolution weaker attack of the Pokémon.
+ attack_weak_type - The type of the pre-evolution weaker attack.
+ attack_weak_value - The damage done by the pre-evolution weaker attack.
+ attack_strong - The name of the pre-evolution stronger attack.
+ attack_strong_type - The type of the pre-evolution stronger attack.
+ attack_strong_value - The damage done by the pre-evolution stronger attack.
+ cp_new - Post-evolution Combat Power.
+ hp_new - Post-evolution Hit Points.
+ weight_new - Post-evolution weight, in kilograms.
+ height_new - Post-evolution height, in meters.
+ power_up_stardust_new - Post-evolution stardust required to power up the Pokémon.
+ power_up_candy_new - Post-evolution candy required to power up the Pokémon.
+ attack_weak_new - The name of the post-evolution weaker attack.
+ attack_weak_type_new - The type of the post-evolution weaker attack.
+ attack_weak_value_new - The damage done by the post-evolution weaker attack.
+ attack_strong_new - The name of the post-evolution stronger attack.
+ attack_strong_type_new - The type of the post-evolution stronger attack.
+ attack_strong_value_new - The damage done by the post-evolution stronger attack.
+ notes - Any additional notes made while collecting the data.

A critical element of Pokémon Go is to "evolve" Pokémon into new, stronger Pokémon for battle. This data set examines evolutions of 75 Pokémon covering four species, and it offers a rich set of 27 variables. The data allow for a careful examination of critical questions related to Pokémon evolutions:

+ What characteristics are important in predicting a Pokémon's combat power (CP) following the evolution?
+ How reliable is the prediction? Note: an individual player would not simply care about the average CP after evolution but also how predictable the final Pokémon's CP is.
+ Is post-evolution CP linearly related to the Pokémon's pre-evolution CP?
+ Is the model the same across different Pokémon species?

When first diving into the data, consider focusing on the Pidgey species. Next expand to include the Caterpie and Weedle species, and eventually, the Eevee species. 

# References

This is an original data set by OpenIntro that was collected in 2016. 
