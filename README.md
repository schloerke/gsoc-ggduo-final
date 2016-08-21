# gsoc ggduo final

# Main Code:
* added gglegend: https://github.com/ggobi/ggally/pull/169
* first pass to ggduo: https://github.com/ggobi/ggally/pull/173
* merge to master: https://github.com/ggobi/ggally/pull/182
* added ggpairs/ggduo binwidth example: https://github.com/ggobi/ggally/pull/190

[Total Contribution in GGally repo](https://github.com/ggobi/ggally/compare/40e248c4124f41d7ae8aa2f828687e84069a7692...79dc9ff278a5906c112a5b7e3230799a86e2f48e) (> 250 commits. < 10 commits from other authors.)

[Package Code coverage (as determined by tests) as of v1.2.0: 98%](https://codecov.io/gh/ggobi/ggally/tree/9b04b7b53d8ce61692fa9f21bc52241a6ec2af52/R)

[Code coverage of main ggduo function as of v1.2.0: 99.4%](https://codecov.io/gh/ggobi/ggally/src/9b04b7b53d8ce61692fa9f21bc52241a6ec2af52/R/ggpairs.R)

# Other Significant Code Improvements

* added more docs to wrap function: https://github.com/ggobi/ggally/pull/159
* ggcoef added: https://github.com/ggobi/ggally/pull/162
* ggsurv censor size: https://github.com/ggobi/ggally/pull/176
* plotly #1: https://github.com/ggobi/ggally/pull/180
* plotly #2: https://github.com/ggobi/ggally/pull/187
* correct testing issues: https://github.com/ggobi/ggally/pull/183
* ggcor robust color: https://github.com/ggobi/ggally/pull/189
* general bracket code robustness: https://github.com/ggobi/ggally/pull/191

# Presentation to UseR2016! - June 30, 2016

https://github.com/schloerke/ggduo-user-2016/

# Start of Paper for JCGS

https://github.com/schloerke/ggduo-paper

(Which is being continued after Google Summer of code ends)


# Work Complete

Major ggduo work is complete and currently on CRAN ([v1.2.0](https://github.com/ggobi/ggally/releases/tag/v1.2.0)).  

This project is being continued after google summer of code to submit a paper to the Journal of Computational and Graphical Statistics.  There are a few small remaining items left to complete that will happen with the completion of the ggduo paper.

* Make a single regression plot that receives a stat model
  * The vertical columns should contain up to: points, residuals, influence, and cooks distance
  * Should use the broom package
* Make an example with the time series pigs data from cranvas::pigs
* Make a single ggplot faceted plot if only using a continuous plot type
