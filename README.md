# Pruning_efficienet_v2
Magnitude-based unstructured pruning to eliminate less valuable parameters from the network. I was able to prune 81% weights
![image](https://github.com/amitpant7/Pruning_efficienet_v2/assets/50907565/89190bb7-59a3-4a35-ade5-fd2d76401df8)

As this was unstructured pruning, it resulted in only a sparse model. There were no reductions in model size or MAC required. So I implemented channel pruning to effectively compress the model. Refer: https://github.com/amitpant7/Channel-Pruning-EfficientNetV2
