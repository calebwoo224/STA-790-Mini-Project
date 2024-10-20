# STA-790-String-Distance-Metrics

Below are the steps to reproduce `summary_experiment.pdf` from `summary_experiment.Rmd` and `presentation_slides.html` from `presentation_slides.Rmd`

### First Time

- Knit `summary_experiment.Rmd` to get `summary_experiment.pdf`
  - This will take a while to run the experiment the first time
  - Afterwards you will have the new pdf and a directory called `experiment_results` with files storing the results from the experiments
- Knit `presentation_slides.Rmd` to get `presentation_slides.html`
  - This will be much faster since it is using the files from `experiment_results`
  - Afterwards you will have the new html
  
### Second Time and Onwards
- In `summary_experiment.Rmd`, go to the **Experiment** section, go to the **Name Matching** section
  - Find the second longer code chunk
  - Change the code chunk to `{r, eval=FALSE}`
- Knit `summary_experiment.Rmd` to get `summary_experiment.pdf`
  - This will be fast since it is using the files from `experiment_results`
  - Afterwards you will have the new pdf
- Knit `presentation_slides.Rmd` to get `presentation_slides.html`
  - This will be fast since it is using the files from `experiment_results`
  - Afterwards you will have the new html