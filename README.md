# Face Recognition with OpenCV
In this project a tried to make a very basic, simple face recignition command-line tool. Huge thanks for Adrian from pyimagesearch [for his tutorial](https://github.com/Hordon13/ObjectDetection). This whole project is based on that, I basically just made some restructuring, and added my own models etc.

### Usage

* Clone the repository
* Add your files to the dataset folder
	* Create a subfolder for each class you want to separate
	* Add as many image as you can to each class, I recommend at least 10/class (1 face/image)
	* In the Unkown folder add as many non-target image as you can (1 face/image)
	* The folder name will be displayed during the recognition, except the Unknown
* Run the train.py script (this will create the trainedModel.pickle and the labels.pickle)
* Run the recognize.py (the target class(es) will be displayed in a green rectangle with label; the non-target faces will be displayed with red without a label)

_Note: add/remove files to the dataset, don't forget to re-run the train script_

### Dependencies

* OpenCV
* Numpy
* Sklearn
* Imutils