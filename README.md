# Empirical Evidence on Explainability, Accuracy, and Energy Trade-offs in Code-Generating LLMs: A Structured Literature Review
Replication Package for the "Empirical Evidence on Explainability, Accuracy, and Energy Trade-offs in Code-Generating LLMs: A Structured Literature Review" paper

Background: The increasing adoption of Large Language Models (LLMs) for AI-assisted code generation in high-stakes domains, such as healthcare and legal applications, requires a structured approach to model selection. Key concerns include explainability, accuracy, and energy consumption, as these factors directly impact compliance, accountability, and sustainability. 

Aims: This study aims to investigate how explainability, accuracy, and energy consumption are defined, evaluated, and related in the context of code-generating LLMs. Specifically, we aim to: (i) establish definitions for explainability, accuracy, and energy consumption in the context of LLMs, (ii) investigate the utilized explainability methods, (iii) explore the current frameworks that consider the relationship between at least one of the three factors, and (iv) identify the most prevalent dimensions of these factors in peer-reviewed studies published since 2023

Method: We adopted an integrated methodology combining automated database searches, backward and forward snowballing, and qualitative thematic analysis. The review focused on peer-reviewed studies published since 2023 that investigate at least one of the three factors in the context of LLM-based code generation.

Results: The analysis reveals that explainability, accuracy, and energy consumption are predominantly investigated in isolation, with limited research examining their combined trade-offs. Existing evaluation frameworks rarely provide integrated support for balancing these three factors during model selection. Furthermore, definitions and operationalizations of the three factors vary considerably across studies, limiting comparability and reproducibility.

Conclusions: The lack of integrated evaluation approaches obstructs informed selection of code-generating LLMs for high-stakes domains. This study provides a structured synthesis of the current state of research, highlights inconsistencies in evaluation practices, and identifies concrete research gaps for future work on integrated and sustainable code-generating LLM assessment frameworks.

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
