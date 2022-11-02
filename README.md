# DSA4262-Project-2
*The following showcases 2 sets of instructions - 1 set of instruction showing how to train a model and use that model to predict the probabilities for test data, while the other set showing how to use a model (gradientboostingclassifier.sav) for prediction.*

**I. For coursemates to follow along - prediction using model**
1. Click on the green **Code** button and select the option *Download ZIP* to download the scripts and csv files into local environment.
2. Once the zip file has been downloaded, extract the files into the directory of your choice.
3. After the file has been dragged into the directory, click one level into the zip file and drag the folder that you see into the parent directory.
4. Start up an AWS ubuntu instance and follow the instructions from *https://www.digitalocean.com/community/tutorials/how-to-set-up-jupyter-notebook-with-python-3-on-ubuntu-18-04* to set up jupyter notebook in the ubuntu instance once the AWS instance has started. You can also follow the video demonstration if you are not sure how to install it on your own.
  <li> i. Start up your aws ubuntu instance before following the video/ instructions. 
5. Once jupyter notebook has been installed in the ubuntu instance, we can open Jupyter Notebook then upload the notebook (**Project 2 - Prediction Script for Github.ipynb**), csv file (**test_set_github.csv**) and model (**gradientboostingclassifier.sav**).
6. In order to do predictions using the model that has been trained, open up **Project 2 - Prediction Script for Github** and run all the codes. At the end of the script, the predictions for the test dataset (*test_set_github.csv*) will be outputted in the form of a csv file (*predictions.csv*).

**II. For training a model and using that model for predictions**
1. Click on the green **Code** button and select the option *Download ZIP* to download the scripts and csv files into local environment.
2. Once the zip file has been downloaded, extract the files into the directory of your choice.
3. After the file has been dragged into the directory, click one level into the zip file and drag the folder that you see into the parent directory.
4. Start up an AWS ubuntu instance and follow the instructions from *https://www.digitalocean.com/community/tutorials/how-to-set-up-jupyter-notebook-with-python-3-on-ubuntu-18-04* to set up jupyter notebook in the ubuntu instance once the AWS instance has started. You can also follow the video demonstration if you are not sure how to install it on your own.
5. Once jupyter notebook has been installed in the ubuntu instance, we can open Jupyter Notebook and upload the notebooks and csv files into jupyter notebook.
6. We will first be using **Project 2 - Training Script for Github.ipynb** to train a GradientBoostingClassifier. This script will be using *train_set_github.csv* as an input, and the output from this script will be a model (**gradientboostingclassfier.sav**).
7. Once the model has been outputted from **Project 2 - Training Script for Github.ipynb**, we move on to **Project 2 - Prediction Script for Github.ipynb**, where we will be using the model to predict the probabilities for the test data.
8. **Project 2 - Prediction Script for Github.ipynb** will be using *test_set_github.csv* as an input and through this script, we will be able to obtain the outputs for the test data in the form of a csv file (*predictions.csv*).
