# Explainability, Accuracy, and Energy Consumption in Large Language Models for Code Generation: A Systematic Literature Review
Replication Package for the "Explainability, Accuracy, and Energy Consumption in Large Language Models for Code Generation: A Systematic Literature Review" paper

The increasing adoption of Large Language Models (LLMs) for AI-assisted code generation in high-stakes domains, such as healthcare and legal applications, requires a structured approach to model selection. Key concerns include explainability, accuracy, and energy consumption, as these factors directly impact compliance, accountability, and sustainability. This research presents the findings of a systematic literature review.

By adopting an integrated methodology combining automated search, snowballing, and qualitative thematic analysis, we: (i) establish definitions for explainability, accuracy, and energy consumption in the context of LLMs, (ii) explore the current frameworks that consider the relationship between at least two of the three factors: explainability, accuracy, and energy consumption, and (iii) identify the most prevalent dimensions of these factors in peer-reviewed studies published since 2023: actionability, fidelity, and interpretability for explainability; benchmark performance and correctness for accuracy; and inference workload, model size, and optimization techniques for energy consumption.

This literature review offers a structured map of the current research landscape concerning LLMs used exclusively for code-generation tasks with respect to their explainability, accuracy, and energy consumption while highlighting the current gaps in the research: (i) there are no frameworks developed from 2023 onward that consider the relationships or trade-offs between at least two of the three factors, (ii) explainability, accuracy, and energy consumption are often treated as unified concepts, (iii) the energy consumption concept is frequently misunderstood in the LLM literature, and (iv) critical aspects such as trasparency for explainability, security for accuracy, and deployment environments for energy consumption remain underexplored.


## Overview of the replication package
This replication package is structured as follows:

    |--- Phase-1-Literature-Review/	                  The scripts utilized and the data extracted during Phase 1 of ExAEquo, which is represented by a Literature Review.
 
Each of the folders listed above is described in detail in the remainder of this readme.

### Phase-1-Literature-Review/Accuracy

    |--- CSVs                                          Contains additional CSV files outputted from the "jupyter_notebook_accuracy.ipynb" Python script, which was utilized at a later stage for this study. 
    |--- Figures                                       Contains the figures outputted from the "jupyter_notebook_accuracy.ipynb" Python script.
    |--- Papers                                        Contains XLSX and CSV files that are the initially gathered papers for Accuracy, the snowballing process, and the applied selection criteria.
    |--- jupyter_notebook_accuracy.ipynb               The Jupyter Notebook in Python utilized for generating the plots and the descriptive statistics that are required for answering RQ1, RQ2, and RQ3.
    

### Phase-1-Literature-Review/Energy Consumption

    |--- CSVs                                          Contains additional CSV files outputted from the "jupyter_notebook_energy_consumption.ipynb" Python script, which was utilized at a later stage for this study. 
    |--- Figures                                       Contains the figures outputted from the "jupyter_notebook_energy_consumption.ipynb" Python script.
    |--- Papers                                        Contains XLSX and CSV files that are the initially gathered papers for Energy Consumption, the snowballing process, and the applied selection criteria.
    |--- jupyter_notebook_energy_consumption.ipynb     The Jupyter Notebook in Python utilized for generating the plots and the descriptive statistics that are required for answering RQ1, RQ2, and RQ3.

### Phase-1-Literature-Review/Explainability

    |--- CSVs                                          Contains additional CSV files outputted from the "jupyter_notebook_explainability.ipynb" Python script, which was utilized at a later stage for this study. 
    |--- Figures                                       Contains the figures outputted from the "jupyter_notebook_explainability.ipynb" Python script.
    |--- Papers                                        Contains XLSX and CSV files that are the initially gathered papers for Explainability, the snowballing process, and the applied selection criteria.
    |--- jupyter_notebook_explainability.ipynb         The Jupyter Notebook in Python utilized for generating the plots and the descriptive statistics that are required for answering RQ1, RQ2, and RQ3.
    
### Phase-1-Literature-Review/
    |--- Frameworks.xlsx                               Contains the utilized frameworks across the papers that meet the selection criteria.
