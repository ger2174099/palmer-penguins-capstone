# Data source and ethics

Dr. Kristen Gorman and the Palmer Station Long-Term Ecological Research program collected penguin measurements in the Palmer Archipelago, Antarctica, from 2007 to 2009. Allison Horst, Alison Hill, and Kristen Gorman packaged the simplified dataset as part of [palmerpenguins](https://allisonhorst.github.io/palmerpenguins/articles/intro.html). The dataset is released under [CC0](https://creativecommons.org/publicdomain/zero/1.0/). The [original study](https://doi.org/10.1371/journal.pone.0090081) describes the research methods.

Accessed November 23, 2026. The included [CSV](https://raw.githubusercontent.com/allisonhorst/palmerpenguins/8957207b78d6ccd1b4654a9dd9c9041b657478ab/inst/extdata/penguins.csv) is the upstream file from the pinned commit, with no edits. Save it as `data/raw/penguins.csv` if you need a replacement. Its SHA-256 is `f204db2c753b0937caac3cb35258562c14f073e4bbc76be24b4c51ce22767a93`.

The file contains animal measurements and no human personal information, so human participant consent does not apply. CC0 covers data reuse. The study describes animal research approvals separately. The sample covers adult foraging penguins of three species at three islands. Chicks, other species, and colonies outside the study sites are absent. Species counts are uneven, and Chinstrap and Gentoo were each sampled on only one island in this file. The recorded sex field is missing for 11 rows. The measurements represent three historical field seasons, so they cannot tell us how populations look today.

Flipper and bill dimensions are measured in millimeters, body mass in grams, and year identifies the field season. Each row is an observation. The simplified file does not include individual IDs.
