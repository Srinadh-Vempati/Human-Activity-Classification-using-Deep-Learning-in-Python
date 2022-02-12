# Human-Activity-Classification-using-Deep-Learning-in-Python
Classification between 2 human activities namely normal walking and impaired walking from the accelerometer and gyroscopic measurements data collected and created a Deep Learning model.

**Project details:**

Collection of accelerormeter and gyroscopic sensor measurements from 4 persons in 2 action scenarios namely
-  Normal walking
-  Impaired walking ( with a little disability )

at various human limb locations with Smartphones. Later created a Deep Learning Classification model to predict the test set under the right class.

**Project Objective:**

Create and compare the DL models trained on measurement data obtained from Smartphone 1 & Smartphone 2 (2 distinct locations on human limb) and cheack which location proves to be a better feature for classification.

**Tools:**

Python /  pandas / numpy / scipy / matplotlib / scikit-learn / Tensorflow / keras 

**Project Steps:**

**1. Capturing Acclerometer and Gyroscopic sensor data using Smartphones**

- Data from various limb locations captures using multiple Smartphones simultaneously.

**2. Loading & Preprocessing measurement data**

- Subject wise data sort

- Filtering through a LowPass FIR filter

- Extraction and Resampling the corresponding data points of the useful action sequences

**3. Test-CrossValidation-Test sets genereation**

- Splitting the whole data into Test / Cross-Validation & Test sets

- Perform a 5-fold subjectwise Cross validation

**4. Neural Net**

-  4 layer architecture about 40k parameters including a Dropout layer to reduce overfitting.

-  Optimizing the NN parameters through Hyper-parameter tuning with GridSearch CV method.


**Conclusion:**

With help of F1 scores and the binary cross-entropy loss of each model, the best model was chosen between the 2
