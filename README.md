# MIARFID-VPC-2019-20

## Computer Vision Class
## Denis Yurii
In this practice we were more concentrated on articles to build as much topologies as we can. All the topologies have one or several realizations. They are presented in network contense table and visual representation. The last one is especially interesting for complex not streight foreward nets like residual, google, etc. Some of topologies solve tasks, some are present only like a building function and plot visualisaion. We tried to achieve good implementations. For example, constructor of any net allows a very wide possibilities in topology structure. If the paper gave several options almost always all of those options are implemented in a automized way through inception parameters of net building function. Which is usually demonstrated right away with several examples. All the descriptions are given in code comments.

Lets see the plan. Families are grouped by functionality not structure. The exaption is resnet family.
### Google net family
Here we made
- google net
- exception net
* [GitHub](https://github.com/LokiAndere/MIARFID-VPC-2019-20/blob/master/GoogleNet_family.ipynb)

### Mobile net family
Here are done some nets who save computational expanses in one way or another
- mobile net
- mini cnn
Also both of them were used for gender recognition task
They achived 90% with small number of parameters and 95% with big
* [GitHub](https://github.com/LokiAndere/MIARFID-VPC-2019-20/blob/master/MobileNet_family.ipynb)

### VGG family
As was said before any topology structure is awaylable. For example, when we write vgg - we mean all of them and even new ones that you are going to make up.
- alex net
- vgg cnn
They were used for CIFAR10 task to achive as the task said above 70% and a good net builder. The good builder is a credo for all families in this practice. As was said "there are a lot vggs but good ones...". So check our topologies for all the net families.
* [GitHub](https://github.com/LokiAndere/MIARFID-VPC-2019-20/blob/master/VGG_family.ipynb)

### Archivator family
It was supposed to be family, but we did not finish the V-net
- U net
* [GitHub](https://github.com/LokiAndere/MIARFID-VPC-2019-20/blob/master/archivador_family.ipynb)

### Residual net family
- res net
- wide net
- dense net
* [GitHub](https://github.com/LokiAndere/MIARFID-VPC-2019-20/blob/master/res_net_family.ipynb)

### Squeeze net family
Again it was supposed to be acompanied by some others. It is a task for future
- squeeze net
* [GitHub](https://github.com/LokiAndere/MIARFID-VPC-2019-20/blob/master/squeezenet.ipynb)
