# NeuroSkinning: Automatic Skin Binding for Production Characters with Deep Graph Networks

Siggraph 2019,  [[pdf]](https://nos.netease.com/mg-file/mg/neteasegamecampus/art_works/20190624/201906242016238583.pdf) [[data]](http://fuxi.163.com/en/thesis/NeuroSkinning.html)

by Lijuan Liu, Youyi Zheng, Di Tang, Yi Yuan, Changjie Fan, Kun Zhou

This paper presents a deep-learning-based method to automatically compute skin weights for skeleton-based deformation of production characters.

![Automatically predicting skin weights.](https://github.com/yiyuan1991/NeuroSkinning/blob/master/imgs/skin.jpg)

We first construct a graph for the input character mesh with its associate skeleton hierarchy. Each graph node encodes the mesh-skeleton attributes. The graph and node attributes are fed into our graph convolution net to predict the skin weight map.

![The pipeline of our method.](https://github.com/yiyuan1991/NeuroSkinning/blob/master/imgs/pipeline.jpg)

Our method can be applied for different games.

![Example production characters.](https://github.com/yiyuan1991/NeuroSkinning/blob/master/imgs/examples.jpg)

![Deformations of characters in Game A.](https://github.com/yiyuan1991/NeuroSkinning/blob/master/imgs/gameA.jpg)

![Deformations of characters in Game B.](https://github.com/yiyuan1991/NeuroSkinning/blob/master/imgs/gameB.jpg)
