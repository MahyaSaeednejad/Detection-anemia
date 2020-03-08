Tools and Infrastructure
You need to have:
•	python 3.8.0
•	TensorFlow 2.0
•	Keras
The codes are written in and tested in JupyterLabs software. 
The current project was built and tested in Windows and MAC laptops with 16 GB RAM.
 GPU's or virtual environments were not experimented or needed at this stage

Data set
Original data set consists of 299 samples are in X_HW_data.csv file.
Augmented data consists of 1197 samples are in Just_Augmented.csv file.
Original data and Augmented data with 1496 samples are in X_HW_data_Augmented.csv file.
In order to run the program, you need to have all the samples in one file. Program will split the samples into train and test set.

Programs
For Two labels classification run the files in the below:
SVM with two labels: SVM-2label.ipynb
CNN with two labels: CNN-2label.ipynb
CNN-SVM with two labels: CNN-SVM-2label.ipynb
Otherwise:
SVM with four labels: SVM.ipynb
CNN with four labels: CNN.ipynb
CNN-SVM with four labels: CNN-SVM.ipynb

Run the program
1.	Have dataset(csv) file and program(ipynb) in a same folder
2.	Change the name of dataset that you want in the program: 
df = pd.read_csv('X_HW_data.csv')
df = pd.read_csv('X_HW_data_Augmented.csv')
df = pd.read_csv(' Just_Augmented.csv ')

NOTE: codes for pre-processing are in the pre-process folder and those program are implemented for color paper data set.

         
         
   








