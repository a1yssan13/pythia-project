## Pythia: A Survey of Memory and Attention of LLMs across Training and Size

This repository contains the figures and code that is used to complete the 5220 project: Pythia - A survey of memory and attention of LLMs across training and size. The repository also contains our final paper, which is the pdf file in the main folder. 

The folders are organized as such: 

- **notebooks**: contains all of the notebooks and code for the paper 
- **results**: saved csv files that loads the scores of all the 
- **images**: graphics + figures that are part of our presentation 

The code is formatted as follows: 

- *Results-Memorization Notebook:* This notebook is primarily used to generate the tables and graphs after the evluation on different models has finished running. Load the csv files from results in order to run the notebook. 
- *Memorization-Analysis* This notebook includes all of the code used to run the memorization results. The first section of the notebook loads in the dataset and gives a couple of brief statistics, such as the length of the dataset, the number of tokens in an example, and also provides a few examples of what each document looks like. The result of the notebook includes the various evaluations on the memorization scoring function. 
- *Attention_Analysis* This is the notebook that is used in order to run the attention section of our project. We include the following: a visualization of attentio heads, plots to plot the distance of each attention + entropy analysis, and also induction circuit analysis. 
- *2-0Attention Anlaysis* This includes the second section of the code for the attention analysis: notably include gradient change across changing steps as well as ablation studies. 
