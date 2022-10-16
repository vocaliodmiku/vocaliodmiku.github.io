---
title: "Self-supervised pretraining technology for multi-model processing"

date: "2022-08-01"

width: "520x"
height: "320px"
image: "images/wav2vec.svg"
content: "In speech processing especially, we are urged to utlize large scale unlabeled acoustic data. [Wav2vec 2.0](https://ai.facebook.com/blog/wav2vec-20-learning-the-structure-of-speech-from-raw-audio/) is set tackle that. It is trained by predicting high-level contextualized speech representations which can describe many different speech audio recordings and non-speech (we have verified its outstanding performance on [VAD](https://en.wikipedia.org/wiki/Voice_activity_detection)). What's more, low-resource languages can improve significantly with cross-lingual training. After the huge success of Wav2vec 2.0, many new methods to apply self-supervised learning to acoustic data come out, e.g. UniSpeech, HuBERT, WavLM, etc. Another line of works are pay attention to multi-model processing. Data2vec aims to bridge the gap between different self-supervised learning algorithms for images, speech, text or other modalities function, and develops a unified way to generate representations in a common feature space."

contenta: "In practice, we have found that it's not easy to train an ASR model with a train-from-scratch decoder. Multi-model self-supervised learning can help the
text modality decoder generalize fast. Currently we are exploring these technology for more possibilties. "

contentb: "*[picture come from [here](https://ai.facebook.com/blog/wav2vec-20-learning-the-structure-of-speech-from-raw-audio/)]*"
---

