# Brain Tumor Classification!

I have created the project on brain tumor classification. For this project three different models were used. Starting with supervised **CNN** model which identifies the image containing the tumor from brain mri scan images. Second model we have developed on **GAN** to generate more data (aka. Data Agumentation) of both classes of tumor and non-tumor. The last model created based on **VGG-16** one of the state-of-the-art model.

## Required Libraries

The following libraries are required to be installed in the machine to run the python scripts. Python version of 3.7.13 with pip.
```bash
	pip3 install tensorflow matplotlib scikit-learn Pillow pandas numpy keras seaborn missingno
```

## Required Dataset format
All the models are build using images in the folder named `'brain_tumor_dataset'` with sub folder called `'yes'` and `'no'`. It is recommended to keep the image type as `'.jpeg' / '.jpg'` for better performance and convenience. Image size should be at least `'224*224'`.  As I am not measuring performance on custom dataset I will take the test data from the dataset provided in this folder randomly. 

## Supervised Learning Model (CNN)

> Make sure all required files are installed before running the command along with the dataset required 

```bash
python3 group2_supervised_cnn.py
```
## Unsupervised Learning Model (GAN)

> Make sure all required files are installed before running the command along with the dataset required 

```bash
python3 group2_un_supervised_GAN.py
```
## State-of-the-art  Models (VGG-16)

> Make sure all required files are installed before running the command along with the dataset required 

```bash
python3 group2_vgg_16.py
```
