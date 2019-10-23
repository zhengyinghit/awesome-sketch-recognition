# awesome-sketch-recognition

This project aims at providing a comprehensive performance comparison of existing methods and collecting good papers for freehand sketch recognition.


## Datasets

**TU-Berlin**

The [TU-Berlin dataset](http://cybertron.cg.tu-berlin.de/eitz/projects/classifysketch) has 20,000 freehand sketches collected by Amazon Mechanical Turk (AMT). All sketches are equally distributed in 250 object classes, i.e. each class has 80 sketches. After constructing the dataset, the authors conduct a human classification experiment. The result shows that human can only correctly recognize 73.1% of sketches, which demonstrates that freehand sketch recognition is a very challenging task.

**Sketchy-R**
The [Sketchy dataset](http://sketchy.eye.gatech.edu/) is published for the task of sketch-based image retrieval, which consists of 75,471 sketch images unevenly distributed in 125 object classes. Among the 125 classes, there are 100 categories which also exist in the TU-Berlin dataset. Because of the mistake in the process of human drawing, there are 918 sketches marked as erroneous. The ***Sketchy-R dataset*** abandons these completely wrong samples and saves the other 74,553 sketches.

## Results
- **TU-Berlin**

|Methods|split1|split2|split3|average|epochs|JPU|Mean IoU|pixAcc|
=======


## Results
- **PASCAL VOC 2012**

|Methods|Backbone|TrainSet|EvalSet|crops_size|epochs|JPU|Mean IoU|pixAcc|
>>>>>>> edb207f991e44d5373157409c1eed136af3c7bdf
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|FCN32s|vgg16|train|val|480|60|✘|47.50|85.39|
|FCN16s|vgg16|train|val|480|60|✘|49.16|85.98|
|FCN8s|vgg16|train|val|480|60|✘|48.87|85.02|
|FCN32s|resnet50|train|val|480|50|✘|54.60|88.57|
|PSPNet|resnet50|train|val|480|60|✘|63.44|89.78|
|DeepLabv3|resnet50|train|val|480|60|✘|60.15|88.36|

## Papers


## Todo
- [ ] add more papers
- [ ] add evaluation metrics
- [ ] add results on TU-Berlin and Sketchy dataset

## Contact

If you have any questions or suggestions, please contact zhengyinghit@outlook.com.
