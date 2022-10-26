# Machine_Learning-Power_System_Fault_Detection
Developed multiple ML Classifiers using SVM, PCA, Decision Tree, Random Forest, GMM &amp; MLP Models for detecting Faults in Power Systems and comparing their accuracies &amp; performances.

- The voltages and currents of all three phases were entered into a variety of machine learning models, after which the models were fine-tuned and their respective performances were compared.
- Using an **SVM** with a ‘rbf’ kernel, a **Decision Tree** with a maximum depth of 14, and a **Random Forest** with 162 estimators, the model was finetuned and achieved the highest accuracy possible (99.8%).
- Applied **PCA** to the data set and got more than 95% of the variance with 50% fewer input axes.
- Performed outlier detection with **Gaussian Mixture Models (GMM)** & obtained 99.5% accuracy at segregating faulty & non-fault conditions.
- Trained **MLP** models using a variety of activation functions and optimizers, and attained the following levels of accuracy: 73% when using linear and SGD, 98% when using relu and Adam, and 99.25% when using LeakyRelU and RMSProp.

## Files containing Code & Outputs:
1) **SVM-Decision_Tree-Random_Forest.ipynb** - Training of **SVM**, **Decision Tree** & **Random Forest** & testing their accuracies.
2) **PCA-Random_Forest.ipynb** - Reducing dimensions of dataset via **PCA** & achiving similar accuracy using **Random Forest**.
3) **Gaussian_Mixture_Model.ipynb** - Training a **Gaussian Mixture Models (GMM)** & a performing **Grid Search** on no. of components & density threshold, to find the best parameters for the GMM accuracy.
4) **MLP_Models_Comparision.ipynb** - Training 4 different **MLP** models & comparing thier accuracies & performances.
