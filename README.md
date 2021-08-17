# Clustering EPL Midfielders in different groups accoding to their style of play

Midfielders are extremely important players on the field. In addition, there are many distinct types of midfielders, each of whom has a specific job to play for their side. However, we frequently hear people comparing two players with vastly different playing styles, which is incorrect. So I decided to do a project with the objective to divide these players into three or four groups using K-Means Clustering depending on 16 different parameters which are publicly available on fbref.com.

Tools used:

    Python
    Principal Component Analysis
    MinMax Scaling
    K-Means Clustering

First I reduced the dimensions to 2 using PCA. I checked the data distribtion using the reduced data set. You can use PCA notebook to and PCA image to check the same.
Then I scaled the data between 0 to 1 using MinMaxSCaling technique which is available in sklearn library.
Finally divided the data in 3 clusters (which was optimum as checked by using Elbow Evaluation technique).

You can check and implement by yourself using the data set and the zipped notebook which is attached to this repo.
