The objective of the code below is to use the RandAugment Technique for the purpose of auto augmentation to increase the size of the training data set artificially. The augmentation applied is shown to imporve the generalization of deep learning model in the vision tasks

**Task**: One shot learning


**Datasets** used: MNIST, Omniglot


**Model**: Siamese Network


**Objective function**: Pair loss function/contrastive loss function

Papers referred are:

    Cubuk, Ekin D., et al. "Randaugment: Practical automated data augmentation with a reduced search space." Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops. 2020. https://arxiv.org/abs/1902.03477
    
    Lake, Brenden M., Ruslan Salakhutdinov, and Joshua B. Tenenbaum. "The Omniglot challenge: a 3-year progress report." Current Opinion in Behavioral Sciences 29 (2019): 97-104. https://arxiv.org/abs/1902.03477
    
    
The unofficial code for augmentation is present here:

https://github.com/ildoonet/pytorch-randaugment/blob/master/RandAugment/augmentations.py


