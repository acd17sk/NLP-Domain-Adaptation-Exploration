# NLP-Domain-Adaptation-Exploration

### Abstract:
Domain adaptation is widely acknowledged as a challenging endeavor in the field of Natural Language Processing (NLP), particularly due to the scarcity of large datasets and the potential for a domain’s distinct linguistic features to detrimentally impact model performance. Given the rapid advancements in NLP, new techniques are continually emerging, some of which have not undergone comprehensive testing. In our study, we conducted experiments using a small dataset to assess the effectiveness of three fine-tuning techniques in the task of sentiment analysis.

### Here are the following libraries needed to run the experiment:
- numpy
- pandas
- simpletransformers
- torch
- torcheval
- sklearn
- warnings

### Directory walkthrough:
- `Data`: This folder stores all the data used in the experiment
- `Reddit_data_1500 Results`:  This folder stores all the results from the experiments of using the Reddit dataset of size 1500
- `Reddit_data_3750 Results`:  This folder stores all the results from the experiments of using the Reddit dataset of size 3750
- `Twitter_data_1500 Results`:  This folder stores all the results from the experiments of using the Twitter dataset of size 1500
- `Twitter_data_3750 Results`:  This folder stores all the results from the experiments of using the Twitter dataset of size 3750

### File walkthrough
- `Averager-Twitter-Reddit.ipynb`: This is the notebook file with the code for averaging all the run results from each run configuration
- `NLP essentials Data split.ipynb`: This is the notebook file with the code for splitting data based on the dataset subset size asked and splitting to training and evaluaiton data accordingly
- `NLP essentials model trainings.ipynb`: This is the notebook file with the code for running trainings on the model for each configuration and saving the results
- `Results sheet.xlsx`: This is the spreadsheet file showing in a table all the averaged results from each run configuration