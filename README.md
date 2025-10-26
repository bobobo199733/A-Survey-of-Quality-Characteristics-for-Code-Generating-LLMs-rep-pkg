# Explainability, Accuracy, and Energy Consumption in Large Language Models for Code Generation: A Systematic Literature Review
Replication Package for the "Explainability, Accuracy, and Energy Consumption in Large Language Models for Code Generation: A Systematic Literature Review" paper

The increasing adoption of Large Language Models (LLMs) for AI-assisted code generation in high-stakes domains, such as healthcare and legal applications, requires a structured approach to model selection. Key concerns include explainability, accuracy, and energy consumption, as these factors directly impact compliance, accountability, and sustainability. This research presents the findings of a systematic literature review.

By adopting an integrated methodology combining automated search, snowballing, and qualitative thematic analysis, we: (i) establish definitions for explainability, accuracy, and energy consumption in the context of LLMs, (ii) investigate the utilized explainability methods, (iii) explore the current frameworks that consider the relationship between at least one of the three factors, and (iv) identify the most prevalent dimensions of these factors in peer-reviewed studies published since 2023: \textit{actionability}, \textit{fidelity}, and \textit{interpretability} for explainability; \textit{benchmark performance} and \textit{correctness} for accuracy; and \textit{inference workload}, \textit{model size}, and \textit{optimization techniques} for energy consumption.

This literature review offers a structured map of the current research landscape concerning LLMs used exclusively for code generation tasks with respect to their explainability, accuracy, and energy consumption.


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
