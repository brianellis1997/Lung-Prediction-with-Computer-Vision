# Lung-Prediction-with-Computer-Vision
Predicting Lung Diagnosis using X-Ray images with CNNs

Authors: Brian Ellis, Jamys Solosky
 
1.	INTRODUCTION

Our project focuses on lung prediction, specifically using Convolutional Neural Networks (CNNs) to analyze medical x-rays of lungs. The goal is to classify these x-rays into one of three categories: normal, virus, or bacteria. We anticipate several challenges along the way.
First, we have the advantage of pre-sorted data, which simplifies our preprocessing tasks. However, selecting the right model, especially for transfer learning, is crucial. The choice of our model base will impact both the accuracy of our predictions and the processing speed. Therefore, initial research on available models for transfer learning is essential.
Another potential challenge is the robustness of our dataset. If it falls short in providing a solid foundation for our model, we may need to perform data preprocessing, such as image alterations and generating additional training samples. This will help ensure that our model becomes more robust and capable of making accurate predictions.
Furthermore, we might encounter issues with our model's ability to generalize effectively across all classes. For instance, our model may excel at detecting normal lungs but struggle with virus classification. In such cases, we must adjust our training focus, possibly giving more emphasis to the virus category to achieve better balance.
Lastly, there is the possibility that our model might not produce remarkable results, making it challenging to justify documentation or presentation. If our model's performance falls short of expectations, and its image classification isn't sufficiently accurate, we might need to reevaluate our approach and experiment with different techniques.


2.	RELATED WORK

In 2018, Kadir and Gleeson explored lung cancer diagnosis using computer vision and machine learning. Prior research in 2015 employed Support Vector Machines, showing limited success due to pre-CNN era limitations (1).


3.	PROPOSED METHOD

We will use ResNet for transfer learning, known for low error rates and efficiency. We'll adjust depth and layers as needed and employ a softmax function for analysis.


4.	EXPERIMENTS

4.1	Dataset

Our instructor-provided lung prediction dataset consists of three classes: normal, virus, and bacteria.

4.2	Baselines

We created an initial SVM baseline model with 34% accuracy, indicating no significant improvement over random chance.

4.3	Expected Results 

We	aim	for	the	CNN	model	to	significantly outperform	the	baseline	and	exhibit	balanced performance across all classes.

5.	REFERENCES
   
[1]	Kadir T, Gleeson F. Lung cancer prediction using machine learning and advanced imaging techniques. Transl Lung Cancer Res. 2018 Jun;7(3):304-312. doi:
10.21037/tlcr.2018.05.15. PMID: 30050768; PMCID: PMC603796
