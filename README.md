# Memos topic analysis
Code for the topic modeling analysis done on the memos containing text.

In the file, 'Memos_Topic_Analysis.ipynb', add the name of your datafile in .csv format in the line: df = pd.read_csv(" ", sep=",") before running the code.

The column containing the memos is named as 'content'.

The code:
(a) Identifies the topics presesnt in the memos through topic modeling using Latent Dirichlet Allocation (LDA) technique

(b) Generate word cloud for documents belonging to each topic

(c) Find words that provide significant differentiation between the topics selected based on the multinomial logistic regression model using the forward entry method

(d) Find the percentage of memos within each topic that contained each distinguishing word
