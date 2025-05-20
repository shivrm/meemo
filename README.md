# Multimodal Emotion Recognition from Audio and Transcript

Trying to classify emotions from an audio recordings by training a CNN on spectrograms and an RNN on transcripts.

All the models will be trained on the [RAVDESS Emotional Speech Audio](https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio) dataset, which has to be downloaded and placed in the `dataset/` directory.

Install dependencies with
```
pip install -r requirements.txt
```

For evaluation results of the models, see [report.pdf](report.pdf)