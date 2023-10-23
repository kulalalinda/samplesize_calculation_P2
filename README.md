# samplesize_calculation_P2
Using SAS® to Determine Sample Sizes for Traditional 2-Stage and Adaptive 2-Stage Phase II Cancer Clinical Trial Designs 
In a Phase II clinical trial, the primary objective is to determine the efficaciousness of a drug, such that decisions to
proceed with further studies and development of the drug are warranted. To detect a measurable effect in an
investigation product, a two-stage design is often used, whereby an interim look at the data may result in the decision
to terminate the trial early, or proceed with the second stage of the study. The Simon’s two-stage design to determine
sample size is one that is widely used and accepted in Phase II cancer trials. A number of alternative methods that
implement adaptive aspects to the design have also been published and used in trials. This paper will look
specifically at Lin and Shih’s adaptive method, which include extensions to Simon’s optimal and minimax designs.
Currently, PROC POWER in SAS v9 does not produce sample size calculations for two-stage designs, which led to
the motivation behind this paper. The SAS codes for the traditional and adaptive designs have been separated into
two macros, %SIMON and %ADAPTIVE, designed to produce multiple sample size outputs which satisfy userspecified constraints. 
