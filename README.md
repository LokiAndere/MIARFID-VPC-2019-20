# MIARFID-VPC-2019-20

## Computer Vision Class
## Denis Yurii
In this practice we were more concentrated on articles to build as much topologies as we can. All the topologies have one or several realizations. They are presented in network contense table and visual representation. The last one is especially interesting for complex not streight foreward nets like residual, google, etc. Some of topologies solve tasks, some are present only like a building function and plot visualisaion. We tried to achieve good implementations. For example, constructor of any net allows a very wide possibilities in topology structure. If the paper gave several options almost always all of those options are implemented in a automized way through inception parameters of net building function. Which is usually demonstrated right away with several examples. All the descriptions are given in code comments.

Lets see the plan. Families are grouped by functionality not structure. The exaption is resnet family.
### Google net family
Here we made
- google net
- exception net

We looked at inception and exception approaches
* [GitHub](https://github.com/LokiAndere/MIARFID-VPC-2019-20/blob/master/GoogleNet_family.ipynb)

### Mobile net family
Here are done some nets who save computational expanses in one way or another
- mobile net
- mini cnn

Also both of them were used for gender recognition task

They achived 90% with small number of parameters (mobilenet) and 95% with big (minicnn)
* [GitHub](https://github.com/LokiAndere/MIARFID-VPC-2019-20/blob/master/MobileNet_family.ipynb)

### VGG family
As was said before any topology structure is awaylable. For example, when we write vgg - we mean all of them and even new ones that you are going to make up. The architecture is controlled with additional parameters
- alex net
- vgg cnn

They were used for CIFAR10 task to achive as the task said above 70% and a good net builder. The good builder is a credo for all families in this practice. As was said "there are a lot vggs but good ones...". So check our topologies for all the net families.
* [GitHub](https://github.com/LokiAndere/MIARFID-VPC-2019-20/blob/master/VGG_family.ipynb)

### Archivator family
It was supposed to be family, but we did not finish the V-net. This is a task for future
- U net
* [GitHub](https://github.com/LokiAndere/MIARFID-VPC-2019-20/blob/master/archivador_family.ipynb)

### Residual net family
As was asked we created constructors for these three nets with as much additional parameters as we decided to.
- res net
- wide net
- dense net
* [GitHub](https://github.com/LokiAndere/MIARFID-VPC-2019-20/blob/master/res_net_family.ipynb)

### Mobile net family
Again it is from mobile family. But we did experiments in the first part so we put others here. So that the file is not that huge. Nets for mobile devices. They save parameters.
- squeeze net
- shuffle net

As we mentioned in comments in code we had no place to play with permute. That is why here we've chosen shuffle.
* [GitHub](https://github.com/LokiAndere/MIARFID-VPC-2019-20/blob/master/squeezenet.ipynb)

### Car biliniar task
We uploaded two trained vgg16. Renamed layers. Connected them together. To do it we used given function.
* [GitHub]()

### Style swap
We used vgg16 and vgg19. We incremented the number of iterations
* [GitHub](https://github.com/LokiAndere/MIARFID-VPC-2019-20/blob/master/swap.ipynb)

In general we now know how and why to use such methods and approaches as permute, deep wise, separable, add, concatenate, permute, group convolution etc. and many many smaller parameters to construct nets. See code inside for more info, we tried to organize everything in lecture like story. Sorry for the images, they tend to be lost. We can provide those separately. But the main idea is if a paper has a clear table of net structure it is enjoyable to be implemented looking at the table. Which is exactly what we did.

With great regards and a smile, yours DYE&FSA
