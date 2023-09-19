# matplotlib-challenge
Statistical analysis of a clinical study dataset using Matplotlib, SciPy, and Pandas

by Jason Estrada

### Analysis

- Ten drug treatments were studied and the dataset was analyzed.  A summary of tumor volume statistics is provided under the **Summary Statistics** section.
- The bar chart shows the total number of timepoints for all mice tested for each treatment.  Capomulin (230) and Ramicane (228) had the most timepoints, and Propiva (148) had the least.
- The mouse gender distribution was fairly even (51% male, 49% female).
- Four treatments were analyzed further, looking at their final tumor volume sizes:
  - Capomulin
  - Ramicane
  - Infubinol
  - Ceftamin
- A box plot was created to show the distribution of the final tumor volume for each treatment group (with outliers if any).
- Using Capomulin data, additional plots were created:
  - Line plot of mouse ID `l509` (tumor volume vs timepoint)
  - Scatter plot of average tumor volume vs. mouse weight
  - Linear regression model of scatter plot. A correlation of 0.84 indicates a positive correlation of between the average tumor volume and mouse weight.