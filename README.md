# 2024 San Jacinto Flooding Analysis

From late April to early May 2024, heavy rainfall to the Northeast of Houston caused severe flooding.
Jeff Lindner, a meteorologist with the Harris County Flood Control District, tweeted about [significant spillage at Lake Houston](https://twitter.com/JeffLindner1/status/1786805612774355312), [10.2 inches of rainfall in 6 hours](https://twitter.com/JeffLindner1/status/1785972354025148880) at one gauge, and [6 inches in one hour](https://twitter.com/JeffLindner1/status/1784787034705461691) at another.
This underscores the importance of understanding the likelihood of extreme rainfall, like this, for flood preparedness.

In this repository, we analyze the rainfall data from this event and compare it to the Intensity-Duration-Frequency (IDF) curves from Atlas 14.
Importantly, the Atlas 14 data is based on historical data, so it is not necessarily representative of future conditions in a warming climate -- an issue we are actively working to address.

![790_comparison](https://github.com/yuchenluv/plot_rain/assets/57869474/2f86acfd-38c3-4e28-b7b9-3fb7c84a5591)

## Data

The data needed to reproduce this analysis is included in the `data` folder.
You can download the full datasets from publicly available sources:

- Time series of gauge-wise rainfall observations in Harris County: <https://www.harriscountyfws.org/?View=full>
- Atlas 14 IDF curve estimates: <https://hdsc.nws.noaa.gov/pfds/pfds_map_cont.html?bkmrk=tx>

## Reproducing the analysis

You will need the following software:

- Julia, specifically version 1.9.3 (recommended installation using [JuliaUp](https://github.com/JuliaLang/juliaup)) (you will see this setting in the `.vscode` folder, so it will work automatically if you use VS Code -- otherwise you may need to run the correct version explicitly)
- [Quarto](https://quarto.org/) for notebook rendering

For more background on using Julia and Quarto, see [here](https://ceve-421-521.github.io/labs/lab-01/).
You can then run the `plot_rain.qmd` notebook to generate the plots.
