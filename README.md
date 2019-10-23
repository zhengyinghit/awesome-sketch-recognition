# awesome-sketch-recognition

This project aims at providing a comprehensive performance comparison of existing methods and collecting good papers for freehand sketch recognition.


## Datasets
- **TU-Berlin**

The [TU-Berlin dataset](http://cybertron.cg.tu-berlin.de/eitz/projects/classifysketch) has 20,000 freehand sketches collected by Amazon Mechanical Turk (AMT). All sketches are equally distributed in 250 object classes, i.e. each class has 80 sketches. After constructing the dataset, the authors conduct a human classification experiment. The result shows that human can only correctly recognize 73.1% of sketches, which demonstrates that freehand sketch recognition is a very challenging task.

## Results
- **TU-Berlin**

|Methods|split1|split2|split3|average|epochs|JPU|Mean IoU|pixAcc|
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
