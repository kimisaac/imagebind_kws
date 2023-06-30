
# Zero Shot Keyword Spotting (KWS) using ImageBind

This project focuses on developing an algorithm using ImageBind for zero-shot classification of the KWS test dataset. The KWS dataset consists of 37 single-word utterances, including categories like "Yes," "No," "Left," "Right," and others. It also includes silence and unknown categories. You can download the dataset from the torchaudio datasets.

Random Audio Classification: The algorithm randomly selects an audio sample from the test split and performs classification. An audio player is provided in the user interface (UI) for listening to the selected audio.

Voice Recording: The UI allows users to record their own voice for testing purposes. An audio recorder is included to capture user recordings.

Summary Statistics: The algorithm provides summary statistics, including the number of data points in the test dataset and the accuracy of the classification results.

Comparison
Here is a comparison table showcasing the performance scores of state-of-the-art (SOTA) models for KWS. The table indicates whether each model was trained using supervised, self-supervised, or weakly supervised approaches. It also specifies whether the evaluation is zero-shot, few-shot, or not applicable.

   
SOTA Models Scores
| Model                 | Training Approach   | Evaluation     | Accuracy   |
|-----------------------|---------------------|----------------|------------|
| Imagebind-KWS         | Unsupervised        | Zero Shot      | 0.0225     |
| TripletLoss-res15     | Unsupervised        | Not zero or few| 0.9856     |

Note: Please refer to the GitHub repository below for access to the KWS dataset and additional information.

[Deep-Learning-Experiments: KWS Demo](https://github.com/roatienza/Deep-Learning-Experiments/blob/master/versions/2022/supervised/python/kws_demo.ipynb)

