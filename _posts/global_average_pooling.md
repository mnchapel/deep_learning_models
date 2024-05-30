## Global average pooling

The global average, used at the end of the network, averages each 7x7 feature map into 1x1. The difference between the global average and a fully connected layer is the number of weights. If a fully connected layer is used on a 1024x7x7 feature maps then there are 1024x7x7x1024 weights (cf. the figure below).

![Fully connected layer]({{site.baseurl}}/assets/img/fully_connected_layer.svg)

If a global average pooling is used on the same bloc, there is 0 weight (cf. the figure below).

![Global average pooling]({{site.baseurl}}/assets/img/global_average_pooling.svg)
