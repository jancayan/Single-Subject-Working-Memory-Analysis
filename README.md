# Single-Subject-Working-Memory-Analysis

Final Code Output stored in EDA.ipynb, the main subject data we have been working with is stored in the GitHub, but the normalized data is on a separate lab server currently only accessible to Jennifer. This is only used in one plotting images (denoted with "normalized brain imaging")

Dataset source from [**Dissociating the causal roles of frontal and parietal cortex in working memory capacity**](https://springernature.figshare.com/articles/journal_contribution/Dissociating_the_causal_roles_of_frontal_and_parietal_cortex_in_working_memory_capacity_Registered_Report_Stage_1*-_Protocol*/7145873/1?file=13370408) (Kiyonaga et al. 2018)

Theory:

- Model-free:(accuracy in the change detection task, recall error in the continuous report task)
  - PFC represents coarser, more abstract WM information (higher-level area)
  - IPS represents finer-grained, precise information (more low-level area of brain/ visual pathway)
- Model-based performance: (Mean mnemonic precision, variability in precision, and how precision scales with load, estimated for each task)
  - PFC → attentional control over WM primarily under high load
  - IPS → stimulus-specific WM representations regardless of load
  - PFC → encodes anticipated prospective action plans during the response phase
  - IPS → maintains retrospective mnemonic codes for stimulus information.
- Sub-theories:
  - Inferior IPS → binding stimulus features with the appropriate location (s
  - Superior IPS → encodes the stimulus features themselves
  - Should see false alarm rates (swap errors) if there is a problem with binding

Hypothesis Summaries:

1. TMS to PFC should have a larger effect on continuous report performance and when there is higher load, could be unnecessary for memory representation
2. TMS to IPS should more severely impair change detection performance at any load, and disrupt storage of mnemonic information (in this case maybe colors)

## Running Our Code
In order to reproduce the code to generate the data in our project, ensure that you create a conda environment using the environment.yml file. In this environment, run 
EDA.ipynb. Note that the code with stop at the "Plot with normalized data" section. This is because in order to run this section, you must be in a specific lab server. However, this section ended up being unused in the final report and is now irrelevant. All of the relevant code is completed prior to that section.