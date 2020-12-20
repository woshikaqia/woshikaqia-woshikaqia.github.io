# Welcome to woshikaqia's homepage

I am a psychometrician and social scientist specialized in measuremnt and statistics. I strive to deliver reliable and impactful educational and psychological assessments. 

I believe not a whole lot of people in my field use GitHub. I've recently started using GitHub and found it is a fun to be able to share ideas with a broader community. Below are a couple of projects I have been working on. Hopefully there are many more to come in the near future.

## The MIRTutils package
### Summary
The MIRTutils package is an R package that contains a set of utilty functions to help people conduct Item Reponse Theory (IRT) analyses, especially when dealing with new item types such as item bundles. It can do things such as simulate response data, compute expected items score, item residuals and item infomation, as well as model-data fit evaluation. 

For more details about what it does and model details, use `help()` function after installation to retrieve R documentations.

### Install
```R
devtools::install_github("woshikaqia/MIRTutils")
```
### GitHub Repo
https://github.com/woshikaqia/MIRTutils/.

## The NGSS psychometrics toolkit
### Summary
The NGSS psychometrics toolkit is an Shiny app I built to visualize data and results from psychometrics analyses related to my work project. It serves as a customized tool to facilitate the operational year recap presentations towards stakeholders and assessment expertises. The "NGSS" in the name came from the assessment I have been working on at work, which is a novel assessment designed around the Next Generation Science Standards and calibrated using a multi-group multi-diemensional IRT model.

### Run a demo
Although this is a highly customized app for my work project, a demo can be run to get a flavor of what exactly the app does. The most part of it should be self-explanatory.
To run the app on your computer, install the `shiny` package and run
```R
shiny::runGitHub( "woshikaqia", "NGSSapp")
```
### GitHub Repo
https://github.com/woshikaqia/NGSSapp/.
