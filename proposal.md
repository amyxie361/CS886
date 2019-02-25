# CS886 proposal
1. *Introduction*: briefly introduce the name of the task and authors
2. *Problem definition*: We proposal to analyze the semi-supervised sequence learning method CVT and further try to improve it. We will use Cross-view learning to take care of the semi-supervised learning part  and use automatic rule extraction to analyze different views advantages and disadvantages. We intend to improve CVT by either fixing primary view or aggregating multi-views.
3. *Why interesting*? 
	1. Sequence labeling requires lot of resource
	2. Pre-trained models do not take advantage of the labels
	3. Supervised models based on pre-trained models do not take advantage of unlabeled data
	4. *Self-training is tautological.*[这个我其实没太明白- 不了解self-training]
4. *Related work* - *semi-supervised* sequence learning
	1. 和why interesting 连起来讲， 
	2. 加上其他related work
5. *CVT-model*: come from cross view in CV, two eye view can help human construct 3D feeling. Focusing on different view will help to understand data better
6. *CVT Model introduction*: labeled-data + unlabeled data / training / inference
7. Cross-View Training only use the *primary prediction modules* during inference. We want to analyze roles of different views and try to combine them.
*Related work* - automatic rule extraction
8. *Automatic rule extraction introduction*
9. *Initial attempt*: reproduction of both paper / initial combine result.
10. *Future plan*