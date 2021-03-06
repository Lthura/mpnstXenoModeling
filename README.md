# mpnstXenoModeling
MPNST Xenograft Modeling Framework defined by the `MXM` R package inside.

The goals are to collect data from the NF1 MPNST pre-clinical modeling project and analyze. To use this package:

1. Get access to the [MXM synapse project](https://www.synapse.org/#!Synapse:syn21984813/wiki/602362) - currently under development. Contact sara.gosline@pnnl.gov if you are interested.
2. Clone this repository 
3. Install renv: ```
if (!requireNamespace("remotes"))
  install.packages("remotes")
remotes::install_github("rstudio/renv")```
4. Activate renv: ```renv::restore()```
5. Build and load `MXM` package. 
6. R CMD install .

Then you should be able to run the code in this repo.
