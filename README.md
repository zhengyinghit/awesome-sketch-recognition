# awesome-sketch-recognition

This project aims at providing a comprehensive performance comparison of existing methods and collecting good papers for freehand sketch recognition.


## Datasets



**TU-Berlin**

The [TU-Berlin dataset](http://cybertron.cg.tu-berlin.de/eitz/projects/classifysketch) has 20,000 freehand sketches collected by Amazon Mechanical Turk (AMT). All sketches are equally distributed in 250 object classes, i.e. each class has 80 sketches. After constructing the dataset, the authors conduct a human classification experiment. The result shows that human can only correctly recognize 73.1% of sketches, which demonstrates that freehand sketch recognition is a very challenging task.

**Sketchy-R**

The [Sketchy dataset](http://sketchy.eye.gatech.edu/) is published for the task of sketch-based image retrieval, which consists of 75,471 sketch images unevenly distributed in 125 object classes. Among the 125 classes, there are 100 categories which also exist in the TU-Berlin dataset. Because of the mistake in the process of human drawing, there are 918 sketches marked as erroneous. The ***Sketchy-R dataset*** abandons these completely wrong samples and saves the other 74,553 sketches.

## Results
- **TU-Berlin**

|Methods|split1|split2|split3|average|
|:-:|:-:|:-:|:-:|:-:|
|SqueezeNet1.0|61.32|54.06|60.30|58.56|

- **Sketchy-R**

|Methods|split1|split2|split3|average|
|:-:|:-:|:-:|:-:|:-:|
|ResNet-152|92.50|92.96|93.11|92.86|
|DenseNet-161|92.02|92.63|92.83|92.49|
|SSDA|95.39|95.74|95.57|95.57|

## Papers


## Todo
- [ ] add more papers
- [ ] add evaluation metrics
- [ ] add results on TU-Berlin and Sketchy dataset

## Contact

If you have any questions or suggestions, please contact zhengyinghit@outlook.com.
