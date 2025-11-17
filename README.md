# Asynchronous Events-based Panoptic Segmentation using Graph Mixer Neural Network

# Cite the article:


# Dataset:
[Download dataset link](https://springernature.figshare.com/collections/A_Neuromorphic_Dataset_for_Object_Segmentation_in_Indoor_Cluttered_Environment/6432548/1)
1. [ESD1 dataset](https://springernature.figshare.com/articles/dataset/ESD-2/22109120?backTo=%2Fcollections%2FA_Neuromorphic_Dataset_for_Object_Segmentation_in_Indoor_Cluttered_Environment%2F6432548&file=39281702)
2. [ESD2 dataset](https://springernature.figshare.com/articles/dataset/ESD-1/22109117?backTo=%2Fcollections%2FA_Neuromorphic_Dataset_for_Object_Segmentation_in_Indoor_Cluttered_Environment%2F6432548&file=39281594)

# Framework of GNN-Mixer
In the context of robotic grasping, object segmentation encounters several difficulties when faced with dynamic conditions such as real-time operation, occlusion, low lighting, motion blur, and object size variability. In response to these challenges, we propose the Graph Mixer Neural Network that includes a novel collaborative contextual mixing layer, applied to 3D event graphs formed on asynchronous events. The proposed layer is designed to spread spatiotemporal correlation within an event graph at four nearest neighbor levels parallelly. We evaluate the effectiveness of our proposed method on the Event-based Segmentation (ESD) Dataset, which includes five unique image degradation challenges, including occlusion, blur, brightness, trajectory, scale variance, and segmentation of known and unknown objects. The results show that our proposed approach outperforms state-of-the-art methods in terms of mean intersection over the union and pixel accuracy.

<img width="524" alt="image" src="https://user-images.githubusercontent.com/43345233/226508490-28877081-6544-49ac-92f6-4104209dadeb.png">



# Results
<img width="529" alt="image" src="https://user-images.githubusercontent.com/43345233/226508618-c3cba303-d432-4262-9573-ec7e2da534fe.png">

# Requirements:
 Python 3.7 
 Pytorch 1.0.1.post2
 pytorch_geometric 1.1.2
 
 Preparations:
