# Chicago Fine Payment Prediction

![Chicago](readonly/chicago.jpg)
Image by <a href="https://pixabay.com/users/pexels-2286921/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=1853632">Pexels</a> from <a href="https://pixabay.com/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=1853632">Pixabay</a>

The following projects covers the city of Chicago and its combat against unpaid fines. 

Process: 

1. Data filtration, remove all the nan variables from the csv file and ensuring data is clean. 

2. Transformation, transforming the string data into a matrix that will be recognized by a machine learning algorithm. 

3. Model construction and application, utilize `GridSearchCV` to find the best parameters for each model. 

4. Prediction, using the previously constructed model to perform 

---------------------------------------

`GridSearchCV` is saved into a pickle file. 

`best_params_` are saved into a seperate file with `confusion_matrix` results. 

---------------------------------------

The projects imports consolidated data from the following open sources: 

* [Building Permits
](https://data.detroitmi.gov/datasets/building-permits?geometry=-83.421%2C42.265%2C-82.778%2C42.442)

* [Trades Permits
](https://data.detroitmi.gov/datasets/trades-permits?geometry=-83.421%2C42.265%2C-82.778%2C42.443)

* [Improve Detroit Issues
](https://data.detroitmi.gov/datasets/improve-detroit-issues?geometry=-86.017%2C41.829%2C-83.444%2C42.541)

* [DPD Citizen Complaints
](https://data.detroitmi.gov/datasets/dpd-citizen-complaints)

* [Parcel Viewer](https://cityofdetroit.github.io/parcel-viewer/)

