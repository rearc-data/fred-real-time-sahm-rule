<a href="https://www.rearc.io/data/">
    <img src="./rearc_logo_rgb.png" alt="Rearc Logo" title="Rearc Logo" height="52" />
</a>

Real-time Sahm Rule Recession Indicator | FRED
=========================

You can subscribe to the AWS Data Exchange product utilizing the automation featured in this repository by visiting [https://aws.amazon.com/marketplace/pp/prodview-vkbu2bcnuq72a](https://aws.amazon.com/marketplace/pp/prodview-vkbu2bcnuq72a).

## Main Overview

This release contains information on the Sahm Recession Indicator which signals the beginning of a recession based on the three-month moving average of the national unemployment rate (U3) in the U.S. The U3 rate shows signs of a recession when it rises by 0.50 percentage points or more relative to its low in the past 12 months.

The included data is provided by the Federal Reserve Bank of St. Louis' FRED (Federal Reserve Economic Data) platform, which contains information on over 700,000+ series related to historical economic data. If you are interested in learning more or want to explore other datasets maintained on FRED, visit the [FRED homepage](https://fred.stlouisfed.org/).


#### Data Source

This resource is presented in both the XLS and CSV formats. The included dataset contains the following columns:

`DATE, SAHMREALTIME`

The `SAHMREALTIME` column represents percentage points based on the three-month moving average of the national unemployment rate at the time of the corresponding `DATE`.  


## More Information
- Source: [Federal Reserve Economic Data (FRED)](https://fred.stlouisfed.org/series/SAHMREALTIME)
- [FRED | Federal Reserve Bank of St. Louis](https://fred.stlouisfed.org/)
- [Federal Reserve Bank of St. Louis | Homepage](https://www.stlouisfed.org/)
- [Terms of Use FAQ](https://fred.stlouisfed.org/legal/)
- Frequency: Monthly
- Formats: XLS, CSV

## Contact Details
- If you find any issues with or have enhancement ideas for this product, open up a GitHub [issue](https://github.com/rearc-data/fred-real-time-sahm-rule/issues) and we will gladly take a look at it. Better yet, submit a pull request. Any contributions you make are greatly appreciated :heart:.
- If you are looking for specific open datasets currently not available on ADX, please submit a request on our project board [here](https://github.com/rearc-data/covid-datasets-aws-data-exchange/projects/1).
- If you have questions about the source data, please contact [FRED](https://fred.stlouisfed.org/contactus/).
- If you have any other questions or feedback, send us an email at data@rearc.io.

## About Rearc
Rearc is a cloud, software and services company. We believe that empowering engineers drives innovation. Cloud-native architectures, modern software and data practices, and the ability to safely experiment can enable engineers to realize their full potential. We have partnered with several enterprises and startups to help them achieve agility. Our approach is simple — empower engineers with the best tools possible to make an impact within their industry.
