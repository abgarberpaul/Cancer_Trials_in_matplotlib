# Mouse Cancer
## a matplotlib-challenge

**Repo Directory:**
- Solution code AND analysis in pymaceuticals_final.ipynb
- Source data file in "data" folder

## Observations on this sample dataset:

#1. The data demonstrates that the studies looked at roughly simliar sample sizes,
#and those sample sizes were distributed roughly evenly between male and female subjects. This
#suggests that the results of those studies can be directly compared to each other for analysis.

#2. If we can judge success by the diminishing size of a tumor, then regimen "Ramicane" 
#seems to have performed the most effectively. Mice on Ramicane had slightly more variation than
#mice on Capomulin (IQR of 9.10 to 7.78 respectively), though both were significantly tighter 
#than Ceftamin or Infubinol. However, Ramicane's lower bound and average decrease were both 
#lower than that of Capomulin, both suggesting that the Ramicane treatment is the best treatment
#for shrinking tumors over all.

#3. There is a significant correlation between heavier mice and heavier tumor sizes 
#(Pearson's of 0.84). However the data does not indicate that there is a strong correlation 
#between the size of the tumor and the number of Metastatic Sites (Pearson's of -0.31), suggesting
#that it may be a question of proportion rather than a sign that heavier mice have more 
#aggressive tumors.
