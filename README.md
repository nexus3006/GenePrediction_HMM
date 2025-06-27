# GenePrediction_HMM

Checkpoint Summary:


**Week 1: Probability and Gene Regulation**

In the first week, I focused on building a strong foundation in probability and understanding gene regulation.
I learned how to calculate basic probabilities, interpret conditional probabilities, and apply Bayes' Theorem. 

Alongside this, I explored gene regulation mechanisms, i.e. how cells control gene expression at the transcriptional level. I understood the roles of promoters, repressors, and enhancers, and how environmental signals influence gene activity. This gave me insights into how probability and biology often intersect in modeling gene behavior.

**Week 2: Hidden Markov Models (HMMs)**

In the second week, I was introduced to Markov chains and Hidden Markov Models.
I learned that a Markov chain is a sequence of events where the next state depends only on the current one (memoryless property). Then, I explored how Hidden Markov Models extend this by assuming the actual state is hidden, but we can observe related outputs.

I studied how HMMs are used in tasks like speech recognition or gene sequence analysis and got a basic idea of the forward algorithm for calculating probabilities of observed sequences given a model.

I learned that the Viterbi algorithm is a technique used to find the most probable sequence of hidden states in problems modelled by Hidden Markov Models (HMMs), especially in NLP tasks like part-of-speech tagging. Instead of checking all possible state sequences (which would be computationally expensive), the algorithm uses dynamic programming to efficiently track the most likely path to each state at every step. At each word (observation), it calculates the probability of being in each possible state based on the best previous state, transition probabilities, and emission probabilities. By the end of the sequence, the Viterbi algorithm gives the most probable path of tags or states instead of just individual predictions, which is crucial in structured prediction tasks.

**Assignment: Bike Sharing Demand Analysis**

For the first assignment, I analyzed a bike sharing dataset to understand how weather impacts daily rentals.
I merged the training and test datasets, handled missing values, and performed exploratory data analysis. I looked at trends in rentals across different weather conditions, detected outliers using the IQR method, and visualised relationships between rentals, temperature, and humidity.

I also performed a correlation analysis and found that temperature positively affects rentals, while humidity has a negative impact. This project helped me apply statistical reasoning to real-world data and interpret patterns using both plots and metrics.

