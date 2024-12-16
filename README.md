# GAT Based Models for Speech Spoofing in the Indonesian Language
- Vincent Suhardi
- Muh. Kemal Lathif Galih Putra
- Bryan Jeshua

With the advancement of artificial intelligence technology, the ability to produce synthetic voices that are almost indistinguishable from genuine human voices is increasing. This poses serious challenges in detecting spoofing, which refers to acts of mimicking or falsifying voice identity of someone for specific purposes. In the Indonesian language context, spoofing detection becomes crucial for maintaining security during conversations. Various Neural Network architectures have been used to detect spoofing, but their effectiveness can vary. Therefore, it is important to conduct a comparative study of different types of Neural Network models to determine the most optimal method for detecting spoofing in the Indonesian language and generating the spoofing dataset itself. This repository will serve as the collection of papers, journal, and codes that will be used to fulfill our goals.

For more details, come see our latest paper discussing this experiment in GAT Based Models for Speech Spoofing in the Indonesian Language.

We take deep inspiration and would like to shoutout the following links that helped us in developing this project:
- [The AASIST main repository](https://github.com/clovaai/aasist) used as our main source code reference and **we forked from this repository**. **Training and evaluation is the same as in this repository**. You could refer to the `config` directory for further configuration of the training/evaluation part.
- [INDspeech News LVSCR Dataset](https://huggingface.co/datasets/SEACrowd/indspeech_news_lvcsr) for bonafide audio data collection and spoofed generation through its text metadata.
- [Indonesian Coqui TTS configuration](https://github.com/Wikidepia/indonesian-tts/releases/) for spoofed audio data collection.
- [The AASIST paper](https://arxiv.org/abs/2110.01200) as the main paper for the modeling phase and data understanding.
- [The ASVspoofing2019 paper](https://arxiv.org/abs/1911.01601) for even deeper data understanding.

## Inference & Dataset
After we train our models from scratch, we take their inference in the `notebooks/spoofing-eval-inference.ipynb` notebook. The checkpoints as well as our training, validation, and testing dataset is kept in this [Google Drive](https://tinyurl.com/24l5da5z).