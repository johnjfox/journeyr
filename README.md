## Introduction

TBD

### Applications

TBD

### Specific Application

TBD

## Installation

You'll need to install ``rstan`` first. Go to [http://mc-stan.org](http://mc-stan.org) and follow the instructions for your platform. The biggest challenge is getting a C++ compiler configured to work with your installation of R. The instructions at [https://github.com/stan-dev/rstan/wiki/RStan-Getting-Started](https://github.com/stan-dev/rstan/wiki/RStan-Getting-Started) are thorough, but there are several steps to take. If you're wondering why you need rstan, it's because most of the models have been implemented in stan code. 

Once you're convinced that stan / rstan has been installed corectly, you can install ``customr`` from within R using:

```
install.packages(c("devtools"))
library(devtools)
devtools::install_github("johnjfox/journeyr")
```

This installation will probably take longer than expected. That's because the stan models are being compiled. This should only happen once though.

More than likely, if there are problems during the installation it will be related to your stan/rstan installation. See the manual linked above for some hints about getting ``rstan`` installed and check the RStan section of the website at ``mc-stan.org`` for the latest information on RStan.

## Contributing

TBD

## Documentation and tutorials

TBD

## Questions? Comments? Requests?

TBD

## Main Articles

TBD

## References

### Journey Analytics
Both of the HBR articles are free with registration:
1. [ES15](https://hbr.org/2015/11/competing-on-customer-journeys)
1. [Swe16](https://hbr.org/2016/08/how-one-company-used-data-to-rethink-the-customer-journey)

### Bayesian Analysis
1. A great set of resources tied to Bayesian analysis, including a very nice package, is at 
[rethinking](https://github.com/rmcelreath/rethinking)
1. [STAN](http://mc-stan.org)