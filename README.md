# AIcrowd Blitz 2
Solutions of the 5 problems in the [15 day challenge](https://www.aicrowd.com/challenges/aicrowd-blitz-2) conducted on AIcrowd <br>
Worked along with [@naveenggmu](https://github.com/naveenggmu) and [@nimishsantosh107](https://github.com/nimishsantosh107). Won 3rd place in the challenge.

## LABOR
The goal was to predict the labor conditions of a labor group. The best submission was made by [CatBoost.ipynb](https://github.com/RamKaushikR/AIcrowd-Blitz-2/blob/master/LABOR/CatBoost.ipynb), making use of Category Boosting Classifier on the whole dataset (binary classification)

## CHESS
The goal is to predict the number of moves it would take for the white king to win or lose, given the positions of white king, white rook and black king. The best submission was made by [XGBoost.ipynb](https://github.com/RamKaushikR/AIcrowd-Blitz-2/blob/master/CHESS/XGBoost.ipynb), which use an XGBoost Classifier on the whole dataset (multiclass classification)

## SCRBL
The goal is to predict whether a given piece of text is scrambled or not. The best submission was made by [SimpleTransformers.ipynb](https://github.com/RamKaushikR/AIcrowd-Blitz-2/blob/master/SCRBL/SimpleTransformers.ipynb), which used a pretrained DistilBERT model to classify the pieces of texts (binary classification)

## SKELY
The goal was to predict the orientation of a 3D skeleton from a single image. The best submission was made by [ResNet.ipynb](https://github.com/RamKaushikR/AIcrowd-Blitz-2/blob/master/SKELY/ResNet.ipynb), which used a ResNet base, and a fully connected layer that produced a regression output. The model was trained for 15 epochs, but the loss minimized around 14 epochs, so the weights of the 14th epoch were loaded in order to make predictions (regression)

## MASKD
The goal was to create an object detection model capable of detecting the locations of masked and unmasked faces in an image. The best submission was made by [Detectron2.ipynb](https://github.com/RamKaushikR/AIcrowd-Blitz-2/blob/master/MASKD/Detectron2.ipynb), which used a Detectron2 base in order to train the model (object detection)
