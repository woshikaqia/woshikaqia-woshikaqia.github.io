# About Me

I am a psychometrician and social scientist specialized in measuremnt and statistics. I strive to deliver reliable and impactful educational and psychological assessments. 

I believe not a whole lot of people in my field use GitHub. I've recently started using GitHub and found it is a fun to be able to share ideas with a broader community. 

Below are a couple of projects I have been working on. Hopefully there are many more to come in the near future.

## The MIRTutils package
### Summary
The MIRTutils package is an R package that contains a set of utilty functions to help people conduct Item Reponse Theory (IRT) analyses. Other than dealing with traditional items, it is especailly designed to deal with new item types such as **item bundles** that are modeled by the Testlet Model (Bradlow, Wainer & Wang, 1999). Thing it does includes:
* Simulate item/testlet response data 
* Compute the probablity of getting a specific raw score, expected scores and score residuals, at both the item level and testlet level. 
* Compute item/testlet infomation 
* Evaluate item fit and item drift
* Evaluate person fit (such as the detection of cheating behaviours)

For more details, use the help function in R to retrieve R documentations after installation.
* use `help(MIRTutils-package)` for an overview of the package and modelling details.
* use `help(<function_name>)` for details about a specific function.

### Install
```r
devtools::install_github("woshikaqia/MIRTutils")
```
### GitHub Repo
[https://github.com/woshikaqia/MIRTutils/](https://github.com/woshikaqia/MIRTutils/)

<hr style="border:2px solid gray">

## The NGSS psychometrics toolkit
### Summary
The NGSS psychometrics toolkit is an Shiny app I built to visualize data and results from psychometrics analyses related to my work project. It serves as a customized tool to facilitate the operational year recap presentations towards stakeholders and assessment expertises. The "NGSS" in the name came from the assessment I have been working on at work, which is a novel assessment designed around the Next Generation Science Standards and calibrated using a multi-group multi-diemensional IRT model. 

A few things the app does are, for items in a specific client's item bank in a given year:
* Retrival and summary of IRT item parameters.
* Retrival and summary of the classical statistcs at both the item level and testlet level
* Cross-client comparsion of the clssical stattistcs for items shared between any of the two clients 
* Display study results comparing calibration results among differnt software

### Run a demo
Although this is a highly project-specific app, a demo can be run to get a flavor of what exactly it does if you are interested. The most part of it should be self-explanatory.
To run the app on your computer, install the `shiny` package in R and run
```r
shiny::runGitHub( "woshikaqia", "NGSSapp")
```
### GitHub Repo
[https://github.com/woshikaqia/NGSSapp/](https://github.com/woshikaqia/NGSSapp/)
