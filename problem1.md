# Problem 1
In this experiment, we give a dataset of a store with thousands of transactions of customers buying
several items from the store. We will use the Apriori algorithm to find correlations between various
items in the store. Answer the following questions:

1. How many records are there in the dataset?

    

2. In a single transaction, what is the maximum number of items a customer has bought? We
assume that each record is a separate transaction



3. Write any five transactions a customer has done.
4. We use the wordcloud to generate a stunning visualization format to highlight crucial textual
data points and convey essential information. Generate and paste the wordcloud with max
words set to 25 and 50. Briefly describe your understanding of the plot.
5. What are the top 5 most frequent items in the dataset?
6. Suppose we have the following transaction data: [[’Apple’, ’Beer’, ’Rice’, ’Chicken’],
[’Apple’, ’Beer’, ’Rice’], [’Apple’, ’Beer’], [’Apple’, ’Bananas’],
[’Milk’, ’Beer’, ’Rice’, ’Chicken’], [’Milk’, ’Beer’, ’Rice’], [’Milk’, ’Beer’],
[’Apple’, ’Bananas’]]. Transform this input dataset into a one-hot encoded Boolean array.
Hint: In the Jupyter notebook, we use TransactionEncoder to do the same.
7. In the input dataset, how many unique items are present?
8. Run Apriori to generate frequent itemsets at support thresholds of 1%, 2%, 3%, 4%, 5%, 6%,
8%,10%,12%,16% and 20%. In a single figure, for each threshold (X-axis), plot the number
of itemsets (Y-axis). Comment on the general trends illustrated by the plots and the reason for
the trend.
9. At support threshold 1%, we see frequent itemset of size three along with size 2 and 1.
However, at the support threshold of 2%, we observe itemsets of size 1 and 2 only. Why do
you think this is so?
10. Run Apriori to generate frequent itemsets of length 2 at support thresholds of 1%, 2%, 3%,
4% and 5%. In a single figure, for each threshold (X-axis), plot the number of itemsets of
length 2 (Y-axis). Comment on the general trends illustrated by the plots and the reason for
the trend.
11. For the following itemset, write down its corresponding support value:
• Mineral Water
• Chocolate
• Eggs
• Eggs, Mineral Water
• Chocolate, Mineral Water