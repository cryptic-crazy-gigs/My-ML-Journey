What I learned ?

1. What is ML :
Traditional coding is where you lay set of rules, input and rules are provided to the machine and the machine generates you the output.
Whereas, in Machine Learning, machine is provided with input and output, and machine has to generate it's own rules and work them on new input data to generate the output.
In short, machine learning is learning from data.

2. AI vs ML vs DL
There are several kinds of intelligence. Emotional intelligence, Creative intelligence, pattern based intelligence. Currently, we thought, we can give pattern based intelligence to machines.  
AI is where you want the machine to have all kinds of intelligence, not possible curently.
ML makes it possible for machines to have pattern-based intelligence. ML uses mathematical/statistical models to incur in machines pattern-based learning.
At some point, when data is huge, the model still does not improve.
DL is for problems where ML methods fail. DL is inspired from the Human brain. It is where it can learn from humongous amounts of data.

3. Types of ML based on supervision
-> Supervised ML : Regression, Classification
   supervised ML is where you provide machine with both input and outputs.

-> Unsupervised ML : Clustering, Dimensionality Reduction, Anomaly Detection, Association Rule Learning
   Unsupervised ML is where you provide machine with only the inputs.

-> Semi-Supervised ML
   wherein things are like Unsupervised ML, but in each cluster you just label one thing, and all others are then labelled the same.

-> Reinforcemant Learning : You don't have initial data in such cases. put your machine in a learning environment. It learns based on points is loses or earns.

5. Types of ML based on Production.

-> Batch Learning : Herein, The model is trained on a good amount of data offline in development environment at once. Then, it is evaluated. And then model is loaded on server.
   No incremental Learning. After a period, when it needs to have learned on new data, the model is pulled down, trained over again with the updated data, and then put on server. This happens periodically.

-> Online Learning : Incremental Learning. Here, it solves the problem of availability in Batch Learning. Initially, same happens here as in batch learning. But, it is dynamic in learning.
   It predicts as well as learns on the continuous stream of incoming data which is actually in the form of small batches. Learning rate is important variable here.
   Advantages are 1. best for concept drift, faster learning, cost effective. Disadvantages are 1. Tricky to use and 2. Risky as it is based on learning from continuous streaming data which needs
   constant monitoring to ensure it is not bad and is relevant.


   Now, lets move ahead with the playlist to learn more.
