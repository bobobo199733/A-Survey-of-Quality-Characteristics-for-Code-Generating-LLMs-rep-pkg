# A Survey of Quality Characteristics for Code-Generating Large Language Models
Replication Package for the "A Survey of Quality Characteristics for Code-Generating Large Language Models" paper submitted under review at Quality Evaluation of ML-based Software Systems 2026.

Code-generating Large Language Models (LLMs) raise new challenges for
quality evaluation in ML-based software. We survey 142 peer-reviewed studies
on explainability, accuracy, and energy consumption using structured database
searches and recursive snowballing.

We examine operational dimensions, evaluation methods, research facets, and
geographical coverage. The results show fragmented practices: explainability
emphasizes actionability and post-hoc methods, accuracy is benchmark oriented,
and energy research focuses on optimization and inference workload. Integrated
evaluation remains rare, and the United States and China account for 54.9%
of the corpus.

These findings support multidimensional and trade-off-aware quality evaluation
of code-generating LLM-based software.

## Overview of the replication package
This replication package is structured as follows:

    |--- Phase-1-Literature-Review/	                  The scripts utilized and the data extracted during Phase 1 of ExAEquo, which is represented by a Literature Review.
 
Each of the folders listed above is described in detail in the remainder of this readme.

### Phase-1-Literature-Review/Accuracy

    |--- CSVs                                          Contains additional CSV files outputted from the "jupyter_notebook_accuracy.ipynb" Python script, which was utilized at a later stage for this study. 
    |--- Figures                                       Contains the figures outputted from the "jupyter_notebook_accuracy.ipynb" Python script.
    |--- Papers                                        Contains XLSX and CSV files that are the initially gathered papers for Accuracy, the snowballing process, and the applied selection criteria.
    |--- jupyter_notebook_accuracy.ipynb               The Jupyter Notebook in Python utilized for generating the plots and the descriptive statistics that are required for answering RQ1 and RQ3.
    

### Phase-1-Literature-Review/Energy Consumption

    |--- CSVs                                          Contains additional CSV files outputted from the "jupyter_notebook_energy_consumption.ipynb" Python script, which was utilized at a later stage for this study. 
    |--- Figures                                       Contains the figures outputted from the "jupyter_notebook_energy_consumption.ipynb" Python script.
    |--- Papers                                        Contains XLSX and CSV files that are the initially gathered papers for Energy Consumption, the snowballing process, and the applied selection criteria.
    |--- jupyter_notebook_energy_consumption.ipynb     The Jupyter Notebook in Python utilized for generating the plots and the descriptive statistics that are required for answering RQ1 and RQ3.

### Phase-1-Literature-Review/Explainability

    |--- CSVs                                          Contains additional CSV files outputted from the "jupyter_notebook_explainability.ipynb" Python script, which was utilized at a later stage for this study. 
    |--- Figures                                       Contains the figures outputted from the "jupyter_notebook_explainability.ipynb" Python script.
    |--- Papers                                        Contains XLSX and CSV files that are the initially gathered papers for Explainability, the snowballing process, and the applied selection criteria.
    |--- jupyter_notebook_explainability.ipynb         The Jupyter Notebook in Python utilized for generating the plots and the descriptive statistics that are required for answering RQ1 and RQ3.
    |--- Explainability-Utilised-Methods.xlsx          Contains the utilized frameworks across the papers that meet the selection criteria, required for answering RQ2.

    
### Phase-1-Literature-Review/
    |--- Frameworks.xlsx                               Contains the utilized frameworks across the papers that meet the selection criteria, required for answering RQ3.
