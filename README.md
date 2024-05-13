# plot_rain

This repository contain codes to plot real time rainfall comparing to IDF curves.

For the example here, heavy rainfall of different durations at Lake Houston in late April and early May are plotted against Atlas 14 IDF curves.

![790_comparison](https://github.com/yuchenluv/plot_rain/assets/57869474/2f86acfd-38c3-4e28-b7b9-3fb7c84a5591)

Time series of gauge-wise rainfall observations in Harris County can be downloaded <https://www.harriscountyfws.org/?View=full>.
Atlas 14 IDF curves estimates can be downloaded <https://hdsc.nws.noaa.gov/pfds/pfds_map_cont.html?bkmrk=tx>.

## Reproducability

You will need the following software:

- Julia, specifically version 1.9.3 (recommended installation using [JuliaUp](https://github.com/JuliaLang/juliaup)) (you will see this setting in the `.vscode` folder, so it will work automatically if you use VS Code -- otherwise you may need to run the correct version explicitly)
- [Quarto](https://quarto.org/) for notebook rendering

For more background on using Julia and Quarto, see [here](https://ceve-421-521.github.io/labs/lab-01/).
You can then run the `plot_rain.qmd` notebook to generate the plots.
