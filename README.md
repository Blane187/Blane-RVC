
# Blane RVC

[![Open In Collab](https://img.shields.io/badge/Open%20In%20Google%20Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=white)](https://colab.research.google.com/github/Blane187/Blane-RVC/blob/master/Advanced_RVC.ipynb)


### Information

Blane-RVC presents itself as a state-of-the-art web UI crafted to streamline rapid and effortless inference. This comprehensive toolset encompasses a model downloader, a voice splitter.

Please support the original RVC. This inference won't be possible to make without it.

[Original RVC Repository](https://github.com/RVC-Project/Retrieval-based-Voice-Conversion-WebUI)

#### Features

- Support V1 & V2 Model ✅
  
- Youtube Audio Downloader ✅
  
- Demucs (Voice Splitter) [Internet required for downloading model] ✅
  
- Microphone Support ✅
  
- TTS Support ✅
  
- Model Downloader ✅



### Installation

1. Install Dependencies <br />
```
pip install torch torchvision torchaudio
```
pip install -r requirements.txt
```
python tools/Download_models.py
```


2. Install [ffmpeg](https://ffmpeg.org/)


### Run WebUI <br />


```
python infer.py
```
