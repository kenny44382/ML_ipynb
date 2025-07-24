# Unsupervised algorithm and Dimensionality Reduction
A series of notebooks on unsupervised machine learning algorithms and dimensionality reduction techniques.

Notebook 1 : K Means Clustering from scratch 

NOTE : This notebook includes a Plotly plot at the very end. Plotly plots are not supported by GitHub's default view. Click on the shrotcut to the Colab notebook to view the interactive plot.

Screenshot :
![Screenshot (264)](https://user-images.githubusercontent.com/49288068/89455248-9e9b0780-d77f-11ea-94db-014d782ba542.png)
________________________________________________________________________________________________________________________________________________________________________________

Notebook 2 : Principal Component Analysis(PCA) from scratch

Dataset : Randomly generated, shape = (40,3). Current notebook is a basic notebook working on a 3 dimensioned dataset, as plotting data with dimension > 3 is not known. So, I have worked with a 3D dataset, performed dimensionality reduction(PCA) to reduce to 2D.

Screenshots(stepwise):

Original data :

![Screenshot (266)](https://user-images.githubusercontent.com/49288068/89693458-1efe6b80-d92c-11ea-8d1a-597fcb67691a.png)

Eigen vectors :

![Screenshot (267)](https://user-images.githubusercontent.com/49288068/89693465-245bb600-d92c-11ea-9d31-5dd985b8400c.png)

Transformed :

![Screenshot (268)](https://user-images.githubusercontent.com/49288068/89693473-2887d380-d92c-11ea-95a2-b60ea7def8fb.png)
________________________________________________________________________________________________________________________________________________________________________________

Notebook 3 : Linear Discriminant Analysis(LDA) from scratch

Dataset : [BankNote Authentication](https://www.kaggle.com/ritesaluja/bank-note-authentication-uci-data)

About the dataset : Data were extracted from images that were taken from genuine and forged banknote-like specimens. For digitization, an industrial camera usually used for print inspection was used. The final images have 400x 400 pixels. Due to the object lens and distance to the investigated object gray-scale pictures with a resolution of about 660 dpi were gained. Wavelet Transform tool were used to extract features from images.

Dimensionality reduction --> 4D data to 2D data.

Upcoming updates : LDA class.
________________________________________________________________________________________________________________________________________________________________________________

Notebook 4 : Apriori for Association Rule Mining (ARM)

Dataset : Groceries Dataset

Applying apriori algorithm to find association rules for recommending supermarket items based on history of purchase per transaction.

View the [Kaggle Notebook](https://www.kaggle.com/balaka18/apriori-for-arm-association-rule-mining) and upvote if it helps you :)
