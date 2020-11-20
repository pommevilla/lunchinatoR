# LunchinatoRs: Map visualization basics

Materials for a talk given at the LunchinatoRs weekly meeting at ISU on 11/20/2020. In this presentation, we go over the basics of working with `sf` objects and work towards building a basic animation of the change in Iowa county populations over the last several years. The talk is intended for people with some basic understanding of `R` and working with `tidyverse` functions (specifically `%>%`, `dplyr` verbs, and `ggplot`. 

You can see the presentation [here](https://pommevilla.github.io/lunchinatoR/11202020#1). If you are having trouble viewing the presentation online, the same content is printed out in `prsentation.pdf`.

### Packages required

- `tidyverse`: data manipulation and visualization
- `sf`: working with shapefiles
- `gganimate`: animations
- `ggthemes`: we'll use `theme_map()` on all of our map plots
- `geofacet`: some bonus visualizations
