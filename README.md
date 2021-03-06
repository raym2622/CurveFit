[![Build Status](https://travis-ci.com/ihmeuw-msca/CurveFit.svg?branch=master)](https://travis-ci.com/ihmeuw-msca/CurveFit)

# Curve Fitting for the COVID-19 Project
## Institute for Health Metrics and Evaluation

## DOCUMENTATION SITE
https://ihmeuw-msca.github.io/CurveFit/

### Maintainers
- Aleksandr Aravkin (saravkin@uw.edu)
- Peng Zheng (zhengp@uw.edu)
- Marlena Bannick (mnorwood@uw.edu)
- Jize Zhang (jizez@uw.edu)
- Alexey Sholokhov (aksh@uw.edu)
- Bradley Bell (bradbell@seanet.com)

### Resources
- [Current forecasts](https://covid19.healthdata.org/projections)

- [FAQ](http://www.healthdata.org/covid/faqs)

- [Updates](http://www.healthdata.org/covid/updates)

- [Updated Paper](http://www.healthdata.org/sites/default/files/files/Projects/COVID/RA_COVID-forecasting-USA-EEA_042120.pdf)


### **For any inquiries, please contact covid19@healthdata.org.**


## Install

Clone or download the repository and then do:
```buildoutcfg
make install
```

If you want to install somewhere other than the defualt for your system:
```
make install prefix=install_prefix_directory
```

Required packages:
* `numpy`,
* `scipy`,
* `pandas`.
