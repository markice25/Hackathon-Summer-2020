# University of Rochester Biomedical Data Science Hackathon Summer 2020



# Data

*  Training data are [here](train_data/).  These data include [the labels](train_data/severity_score_train.txt) that you need to predict
*  Test data are [here](test_data/).  Your predictions should be in the order of the `subject_id`s [listed here](prediction/prediction.csv) -- no join is performed on the `subject_id` column.

# Data Description
These data are from a prospective multi-year clinical translational study including three cohorts of term infants experiencing their first Respiratory Syncytial Virus (RSV) season. All infants are less than or equal to nine months of age at study entry. The three subject cohorts represent the full spectrum of RSV disease severity and include a birth cohort, a cohort of infants hospitalized for RSV disease and infants evaluated at ambulatory settings for RSV infection. All infants are followed longitudinally and evaluated at recognition of acute RSV infection and twice during convalescence. Genome-wide expression is assessed in the nasal airways (nasal_gene_expr), and in sorted peripheral blood lymphocytes(cd4_gene_expr, cd8_gene_expr, and cd19_gene_expr). Additionally, the microbiome of the nasal airway was measured (nasal_microbiome). All five of these data modalities are hypothesized to contribute to the severity of the disease, measured by a Global Respiratory Severity Score (GRSS), which is the prediction target for this challenge. 
