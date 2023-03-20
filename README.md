# AI Tool for Blood Cell Detection

Blood cell detection, it is a crucial step in medical diagnostics, in figuring out the many blood cell varieties and any abnormalities they may include. This helps in better diagnosis of diseases and is often performed by experts at research labs. This task can be automated using artificial intelligence (AI) techniques with decent accuracy. In this project, we will go over how to detect blood cells using `MobileNetV2` with `Conv2D`, using Tensorflow and Keras.

**The model is compiled with the following parameters:**

```
'model.compile( optimizer="adam",
                loss="categorical_crossentropy",
                metrics=["accuracy"] )
```

## Requirements and Installation:

To use this tool, you will need to have Python 3 and the following libraries installed:
```
- Keras
- NumPy
- Matplotlib
```

You can install these libraries using pip:

```
$> pip install keras numpy matplotlib
```
## Usage

To use the blood cell detection tool, you will need to prepare your images and run the script. Follow these steps:

1.  Prepare your images by placing them in a directory called **images** in the root directory of the project.

2.  Run the ipynb by changing the directory path of test variable. If you want to train the model on custom data, change the train dir.

![image](https://user-images.githubusercontent.com/64140687/226269891-55f19fa5-d418-482d-9ec5-6561ab5c82a7.png)

## Output and Results

The model is trained on a dataset of blood cell images (~12000) and achieves an accuracy of over **93%**. The model can detect different types of blood
cells like: 
* EOSINOPHIL
* LYMPHOCYTE
- MONOCYTE'
- NEUTROPHIL

### Model prediction on Validating data:

![image](https://user-images.githubusercontent.com/64140687/226270630-542569ab-587c-42e8-acfd-6e8170a058f9.png)


## Conclusion

The blood cell detection tool is a powerful and accurate way to analyze blood cell images using deep learning. With its high accuracy and
easy-to-use interface, it is a valuable tool for medical researchers and professionals. With simple tools, we were able to create a model that can successfully classify the different types of blood cells.

## Furthur Improvements:

These are the possible improvements that can be made if someone wishes to continue with the project.

* Increase the number of `Epochs` to train the model better.
* Split the data in a random order between train, test and validate.
* Change the model: `MobileNetV2` to some other model like `VGG19` or `CNN` for better performance.
* Tuning the Hyper Parameters for better results.

