This is my Bachelor Thesis titeld: The performance of a robust Bayesian approach to the 20 questions game under different patterns of noise. <br>
Grade: 9/10 in the Dutch System <br>
University: VU Amsterdam<br>
Supervisor: B.B. Kruit<br>

For a general overview see the Conference Poster. This was used to give a presentation about the Thesis at the BNAIC 2023
The pdf file contains the thesis. <br>
The jupyter notebooks FullPy.ipynb and Experiment_20_Q_Prob.ipynb contain the code. The experiment is in a different file because it has been run using google colab for computing time reasons. The notebook results.ipynp contains the visualisations of the results.<br>
The file BayesWeightedEntropyRandomBranching.ipynb uses a previous approach connecting to GraphDB for Knowledge Graph interactions. The FullPy version was used to transfer the code into google colab, which could not be connected to graphDB. <br> 
The .tsv and .nt files contain the dataset that was used. <br>

In this thesis I developed a new, robust approach for playing the 20 Questions Game (also known as Guess Who?) with a Knowledge Graph.
This approach uses Naive Bayes in combination with the system entropy to ensure the questioneer can still guess the correct entity, even when the answerer gives wrong answers.
This is especially relevant when interacting with knowledge graphs because design decisions and the closed world assumption can lead to errors. 
The experiments investigate how well this approach performs under different patterns of wrong answers (comparing wrong answers at the start to wrong answers towards the end, etc) 
