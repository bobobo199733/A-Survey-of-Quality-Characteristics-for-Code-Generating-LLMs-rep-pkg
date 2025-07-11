# Foundations for ExAEquo: A Review of Explainability, Accuracy, and Energy Consumption in LLMs
Replication Package for the "Foundations for ExAEquo: A Review of Explainability, Accuracy, and Energy Consumption in LLMs" paper

Abstract - The increasing adoption of Large Language Models (LLMs) for AI-assisted code generation in high-stakes domains, such as healthcare and legal applications, necessitates a structured approach to model selection. Key concerns include explainability, accuracy, and energy consumption, as these factors directly impact compliance, accountability, and sustainability. This research presents the findings of a systematic literature review and forms the foundational phase of ExAEquo, an actionable framework designed to support ICT professionals in making informed decisions when selecting LLMs for code generation tasks.

By adopting an integrated methodology combining automated search, snowballing, and qualitative thematic analysis, we: (i) establish definitions for explainability, accuracy, and energy consumption in the context of LLMs, (ii) identify the most prevalent dimensions of these factors in peer-reviewed studies published since 2023: \textit{actionability}, \textit{fidelity}, and \textit{interpretability} for explainability; \textit{benchmark performance} and \textit{correctness} for accuracy; and \textit{inference workload}, \textit{model size}, and \textit{optimization techniques} for energy consumption, and (iii) uncover key research gaps: explainability, accuracy, and energy consumption are often treated as unified concepts; the energy consumption concept is frequently misunderstood in the LLM literature; critical aspects such as \textit{trasparency} for explainability, \textit{security} for accuracy, and \textit{deployment environments} for energy consumption remain underexplored.

This literature review lays the conceptual groundwork for the design of ExAEquo by offering a structured map of the current research landscape and exposing the trade-offs that ICT professionals must consider when selecting LLMs for responsible and efficient deployment.


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
