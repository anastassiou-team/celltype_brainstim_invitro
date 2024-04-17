#### *Results and algorithms for in vitro data analysis presented in:*
# "Cell class-specific electric field entrainment of neural activity"

> Developed in **Windows 10** and **Python 2.7**<br />
> https://www.python.org/<br />
> For the versions of individual libraries see "Versions.txt"

### Contents

* Directory **notebooks** contains the codes (in jupyter notebooks) used for analysis and for plotting.<br />
> Sub_Sup_entrainment_core_V1.ipynb<br />
> Sub_Sup_entrainment_core_hippo.ipynb<br />
> Sub_Sup_entrainment_core_human.ipynb<br />

This is the core code that is assessing e-field entrainment. This covers most of the subthreshold analysis (e.g. Figs1b, c, Fig 3) This analyzes suprathreshold data: e.g. generating rose plots for Fig2 and getting the spike histograms for Fig 4b, etc. and extracts the circular statistics information.<br />
** Those notebooks require the raw pickle files to run. Available on **Dandi**. Link: **PENDING...**

> Plots_Rayleigh_logp.ipynb

These are line plots plotting the Rayleigh p-values (e.g. Fig 2)

> boxplots_and_lineplots.ipynb

This notebook is for making the boxplot data where data is plotted per-cell (e.g. Fig 2d, e). These codes make use of data (control and 200 nA stim) in excel sheets—the large pandas dataframe was analyzed on a per-cell basis using the core entrainment codes, and then the numbers were put into excel sheets for convenience. 

> Angle_SD.ipynb

This plots the standard dev. of spike-phase distribution for various amplitude/frequencies in V1 (Fig. S4).

> bootstrapping_meanVL.ipynb

This is the code for getting the bootstrapped mean VL values for doing the spike-ISIrate-ESfreq comparison. This is the code, and the extracted output is in excel files (to be used for plotting). 

> Barplots_Bootstrap_comparisons.ipynb

This code is for pyramidal cells (for V1 and human), where we bar-plotted out the bootstrapped mean VL values and plotted them by spike-freq-bins. (i.e. Figs 4c-d). It also plots the Welch’s test and cohen’s d values for the control vs. ES comparisons

* Directory **tables** contains the necessary excel files.
> HumanCells_8Hzbins_ES_Con.xlsx<br />
> HumanCells_8Hzbins_ES_Con_old.xlsx<br />
> Human_200_boxplot_lineplot_nums.xlsx<br />
> Pvalb_V1_200_boxplot_lineplot_nums.xlsx<br />
> Pyr_V1_200_boxplot_lineplot_nums.xlsx<br />
> SST_V1_200_boxplot_lineplot_nums.xlsx<br />
> V1Pyr_8Hzbins_ES_Con.xlsx<br />
> V1_200_boxplot_lineplot_allclasses_ttest.xlsx<br />
> bootstrap_output_template2.xlsx<br />
> hippo_200_boxplot_lineplot_Pvalb.xlsx<br />
> hippo_200_boxplot_lineplot_Pyr.xlsx<br />
***

For more information, see **Intro_to_files_notebooks_ES.docx**

