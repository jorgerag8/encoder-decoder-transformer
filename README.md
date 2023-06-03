# Abstract

In the era of rapid development of machine learning techniques, they are being applied in different tasks solving different problems, 
in- cluding in behavior science and neuroscience. The data used was obtained from a study investigating continuous decision-making in mice, 
recording both timestamped behavioral information and concurrent neuronal activity. Given the nature of both sequences, 
an encoder-decoder transformer model was implemented to explore the possibility of using the neural activity of mice to predict 
its lever-held-down duration. Three models were tested, each to perform binary classification, multi-class classification, 
and sequence-to-sequence translation on neural activity and behavioral data collected from mice performing lever-held-down tasks. 
The three models’ performances indeed exceed our expectations considering the input is noisy neural data. 
Indicating that this type of model can be used to predict mice activity given neural activity information.
