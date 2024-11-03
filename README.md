# Single-Subject-Working-Memory-Analysis

All analysis so far done on Jupyter Notebook (design*matrices.ipynb and experimental_design.ipynb have similar code)
Dataset source from [**Dissociating the causal roles of frontal and parietal cortex in working memory capacity**](https://springernature.figshare.com/articles/journal_contribution/Dissociating_the_causal_roles_of_frontal_and_parietal_cortex_in_working_memory_capacity_Registered_Report_Stage_1*-_Protocol_/7145873/1?file=13370408) (Kiyonaga et al. 2018)

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
