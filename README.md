# EuroSAT-Classification
 EuroSAT is dataset which is captured from Stalite for different regions  , it contains 10 classes , the classes are 

[ 'River', 'SeaLake','AnnualCrop','Forest','HerbaceousVegetation','Highway','Industrial','Pasture','PermanentCrop','Residential']


>This serves as the assignment for the SatelliteImagery course taught to seniro students in CUFE for 2023.

## Technologies 📚

<br>

<div align='center'>

<img src="https://github.com/Iten-No-404/COVID-Vaccine-Stance-Detection/blob/main/pytorch.png"  width="25%">
</div>
<br>


# Pipeline 
### Data Preparation  & Preprocessing
I started spliting data into training and test data set with balancing every class without doing unbalanced distribution for classes then creating two transforms for train and test which applying in  random cropping for images , normalization and resizing for them
### Model 
I bulit ResNet-18 from scratch 
First , I buit NN CLass which contains the basic resnet-18 layers
Secondly , building ResNet-18 with 4 Layers of skip connections
### Results
I started training with 5 Epochs which gets 88% for both train & test
with 10 epochs I got 93.5 for training and 87.95 for testing

### Resource & References 
Meduim , Kaggle ,RestNet architecture Papers

