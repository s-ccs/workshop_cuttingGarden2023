# LMM+EEG Workshop @ CuttingGardens2023

For a non-interactive, rendered view, [follow this link](lmm_slides.html)

The main workshop content are Pluto.jl notebook files. To start them 

1) install Julia
   
2) run: `using Pkg;Pkg.add("Pluto")`
   
3) `using Pluto; Pluto.run()`

A browser should pop up in which you can paste either the link to the notebook, or download it and select it from your computer.

## Abstract
This is the abstract I used to advertise for the workshop:

Linear mixed models are versatile and increasingly popular in cognitive psychology to analyze behavioural datasets with within-subject trial-repetitions. Some brave researchers have already applied these hierarchical models to EEG data, typically on averaged space/time region of interest.  In this 2 h tutorial, I will revisit some of the basics and intuitions behind mixed models and extend them to the mass-univariate EEG case: fitting mixed models to all time-point and channels using the Unfold.jl & MixedModels.jl toolboxes in JuliaLang. You will be provided with interactive notebooks that run in your browser.  We  will  explore  together  some  implications  and  challenges  of  running  such  mass  univariate  LMMs:  baseline  periods,  identifiability  of  random  and  item  effects, and "usefulness".  I want to warn you though, I cannot provide a satisfactory answer to many of the issues that we will discuss in the workshop. My goal is rather to leave you with  a  sense  of  scientific  curiosity,  and  the  simulation-  and  analysis-tools  to explore some of those issues yourself


## License
Code is under MIT, slide content under CC-By.
