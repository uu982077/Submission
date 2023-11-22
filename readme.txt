This directory contains the six sbjects used in the case study.
Each subject archive file has the models for each crn program used in the case study.
The archive also contain a TestMatrix.csv file which defines the abstract test properties and the inputs for each abstract test
and the InputMatrix.csv file contains what the initial values of the input species are for each input defined in TestMatrix.csv.

The RQ3-SummarizationFunctionTable.pdf contains the results from varying the summarization functions in the Traceback method defined in the paper.

RQ1-LocalizationValues.csv contains the localization ranks and normalized ranks for the 3 methods (Species, Reaction, traceack) in the case study. All subjects are evaluated, with each row being a crn program run. Each mutant is ran 5 times.

RQ2-LocalizationValues.csv contains the localization ranks and normalized ranks for the 3 methods (Species, Reaction, traceack) in the case study. All subjects are evaluated, with each row being a mutant run with a listed test suite (function (F), metamorphic (M), and invariant (I)).  The all test suite is the rows without a test suite label. Each crn program is ran 5 times.

RQ3-LocalizationValues.zip contains the localization ranks and normalized ranks for the 3 methods (Species, Reaction, traceack) in the case study. This file was archived due to its large size as it is over the paramter space of the Traceback method. Each row is a parameter selection, and was ran 5 times. We have the data for all subjects and crn programs in the study included.

KW-Subject-TestType.pdf are the per subject and per test suite RQ3 results for varying k and w using the Traceback method.

The k-parameter and w-parameter tables are Table 6 from the submission with the standard deviation included.
