Taking my Amazon purchase history for the past 8 years and applying the CRISP-DM methodology for statistical analysis and predictive modeling. 

My <b>main motivation</b> for this project was to get ahold of data that would be 1) unique and 2) interesting to explore, and then practice applying the above mentioned framework as well as making predictions with sklearn and statsmodels.

Below is a set of questions that were answered during the analysis:
- How much did I spend by year? What year did I go on a shopping spree and spend the most? (<i>answered with seaborn catplot & relplot</i>)
- What was purchased during that binge-shopping year? (<i>barplot</i>)
- Which categories do most of my expenses fall into? (<i>countpot by qty and barplot by amount</i>)
- If we pick top 6 categories, do I tend to spend the same amount every year? (<i>two-level relplot</i>)
- What is the maximum amount I’ve ever spent on the most common expense categories? (<i>boxplot</i>)
- Lastly, what is my predicted purchase total for 2021? (<i>basic sklearn as well as statsmodel</i>)

<b>Libraries used</b>:
- pandas <i>for dataframe manipulations</i>
- numpy <i> for analysis </i>
- matplotlib.pyplot <i> for data visualizations</i>
- seaborn<i> for data visualizations</i>
</br><i>for predictive modeling:</i>
- scikit-learn
- statsmodels.api

<b>Files in the repository</b>: ipynb workbook (Amazon_Purchase_History_Analysis_Workbook.ipynb) and its html copy (Amazon_Purchase_History_Analysis_Workbook.html)
</br>

<b>Acknowledgments</b>: my personal Amazon purchase history used as the dataset.

<b>Summary of the analysis</b>
Year when most purchases were made was 2018. Most of the merchandise acquired that year were pet-related goods as well as electronic devises. Categories in which most of the purchases fall into throughout the analyzed period are: Beauty, Pet Products, Shoes & Clothes, Sporting Goods, and electronic devices. The purchase frequency varies YoY. The maximum amount spent in those categories does not exceed $450.

<b>Blog post</b> featured in Medium's <a href="https://towardsdatascience.com/the-beast-of-your-amazon-spendings-and-the-best-way-to-face-it-cebf428178f2">Towards Data Science rubric</a>
