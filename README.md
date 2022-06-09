I spent a lot of time making cyanotypes during COVID-19. Cyanotypes are photographic images made by coating a paper with an iron mixture and exposing it to UV light. The paper is then bathed in water and turns a rich blue as it oxidizes. Any opaque material left on the paper will appear as a white outline. 

The cyanotypes used in this project were made with leaves from an orange tree.

![Cyanotype image of a leaf](./imgs/01.jpg)

Images are first loaded in from Google Drive and displayed.

![](./imgs/02.png)

Images are normalized. Then, using numpy, a mean image is calculated and displayed along with -3 and +3 standard deviations.

![](./imgs/03.png)

An InceptionV3 model is loaded from TensorFlow. Activations are obtained from this model. Predictions for these activations are then converted into a numpy array and printed.

![](./imgs/04.png)

Features are extracted from the activations and printed.

![](.imgs/05.png)

The extracted features are then reduced to two dimensions using PCA, t-SNE, and UMAP techniques. Then, the features are plotted.

![](.imgs/06.png)

Images for each point are visualized.

![](.imgs/07.png)

A grid is created spanning the range of values of the 2D projected features. The features are assigned to a position on the grid and visualized.

![](.imgs/08.png)

The resulting grid is displayed with the assigned images.

![](.imgs/09.png)

Lastly, seaborn is used to plot a bivariate distribution of the features.

![](.imgs/10.png)
