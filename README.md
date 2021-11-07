# Casting-Quality-Inspection
Automation is the new key to boost industries. Keeping track of quality is very crucial in automated processes. Here is a simple application of neural networks in automating quality inspection process of metal casting of an automobile engine part. 
## Machine Learning Model
* Binary image classifier built on Tensorflow to identify metal casting as 'DEFECTIVE' or 'OK'.
* Framework : TensorFlow( Version: 2.6.0 )
* Algorithm : Convolutional Neural Network 2D
* Validation Accuracy : 98.3%
* **Defective Sample**<br />
![Image](https://github.com/Ashish-Abraham/Casting-Quality-Inspection/blob/main/Casting%20Data/Defective%20Samples/cast_def_0_11.jpeg)
* **Non-Defective Sample**<br />
![Image](https://github.com/Ashish-Abraham/Casting-Quality-Inspection/blob/main/Casting%20Data/OK/cast_ok_0_12.jpeg)
### How to train
Upload the python notebook in the folder **'model'** to Google Colab and run each cell for training the model.
## How to use:
* Download ML model .h5 file from folder **'model'**
* model = load_model('model.h5')
* Use model for classification

## *Thanks for reading the Documentation. Open to suggestions if any.*
