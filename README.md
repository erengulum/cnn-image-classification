# Image Classification with CNNs

This assignment has been prepared for the image classification by using CNNs. The whole code is written and executed in Google Colab. It has a single code file. It is
recommended to use notebook(.ipynb) file instead of python(.py) file. Py file is automatically created by Google Colab. 
Most of the code consists of functions. The functions are kept as simple as possible and tried to be made in accordance with the singleton principle.

## Usage
It is possible to access the outputs and the code via the following link : https://colab.research.google.com/drive/1pp-yaSXB7OTVHXeXgoBg35rUxACTdUHg?usp=sharing

The code consists of a single .ipynb file. I also included ".py" version of the code in the directory. However, it is highly recommended to open as notebook(.ipynb) and execute in Google Colab.

In order for the code to work properly in Colab, you need to organize path part in the following code line according to the path of your own dataset:
!unzip drive/MyDrive/assignment3/Dataset.zip -d a_dataset

If you are going to execute it as .py file, you should unzip the data set and change the path below:
data = glob.glob("a_dataset/**/*.*")

## License
[MIT](https://choosealicense.com/licenses/mit/)
