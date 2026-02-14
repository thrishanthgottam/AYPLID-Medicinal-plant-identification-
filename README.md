# HerbScan
Identification of Different Medicinal Plants/Raw materials through Image Processing Using Machine Learning Algorithms

## Download Dataset
https://www.kaggle.com/datasets/riteshranjansaroj/segmented-medicinal-leaf-images

## Zip in the Repository and extract it
1. Check for flask version else download it with this command
     $ pip install -U Flask.
2. Check for all the other packages. If any packages are missing use this command
     $ pip install -U <package-name>
3. Run the web application 
    $ python app.py
4. Select the photo which is to be tested.
5. The application will display the image predicted with confidence level using the MobileNetV2 model prediction.
## Orginal code contains:(93.0% AVG)
* zoom
* Rotation
* flip
* Brightness change
* MobileNet(Pretrained Classifier Model)
## Added.(94.3% AVG)
1. To increase the accuracy added the Randomcrop Zoomin feature in process of extraction of the image to analysis.
   (Because the patterns of every plant is unique).
2. Added a cache chunk of 8-8 size (for paral processing).
3. Randomcrop for extracting the peace of chunk for analysis.   
## Work to be done.
1. Develop a database with all the information of the dataset classes.
2. Upload the database into a REST API.(So far plan for local API).
3. Fetch the details and display.

Additional works.
1. Design for the frontend of the application.
2. Discussion about more features.
