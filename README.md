# ECG-neural-network
 
Used the time series data from the dataset <a href="https://physionet.org/content/ptb-xl/1.0.1/"> PTB-XL </a> (a large publicly available electrocardiography dataset) to classify ECG signals into the respective classes (diagnostic superclasses). The classes are mentioned in the link. I used an LSTM, multi-label classification, and combined tabular with time series data. The highest performing model had an ROC AUC score of 83%. More info is in the ECG.ipynb <br> <br>

<br>
<br>
Instructions:
<br>
You will need to download the dataset from the website above. I used version 1.0.1 from 2020. The data should be stored in folders "records100" and "records500", just like they do in the folder from the dataset. Place the folders in the same map as the notebook.

<br>
Installation with Anaconda/conda: <br>
open Anaconda Powershell Prompt <br>
conda create --name ECG <br>
conda activate ECG <br>
conda install --file requirements.txt <br>
Open notebook (ECG.ipynb) through your IDE of choice (Anaconda/VSC etc)


<br> <br>


Citation: <br>

Wagner, P., Strodthoff, N., Bousseljot, R., Samek, W., and Schaeffter, T. (2020) 'PTB-XL, a large publicly available electrocardiography dataset' (version 1.0.1), PhysioNet. Available at: https://doi.org/10.13026/x4td-x982.

Wagner, P., Strodthoff, N., Bousseljot, R.-D., Kreiseler, D., Lunze, F.I., Samek, W., Schaeffter, T. (2020), PTB-XL: A Large Publicly Available ECG Dataset. Scientific Data. https://doi.org/10.1038/s41597-020-0495-6

Goldberger, A., Amaral, L., Glass, L., Hausdorff, J., Ivanov, P.C., Mark, R., Mietus, J.E., Moody, G.B., Peng, C.K. and Stanley, H.E., 2000. PhysioBank, PhysioToolkit, and PhysioNet: Components of a new research resource for complex physiologic signals. Circulation [Online]. 101 (23), pp. e215–e220.
