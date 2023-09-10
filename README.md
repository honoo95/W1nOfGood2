[![Open In Colab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252)](https://colab.research.google.com/drive/1r4IRL0UA7JEoZ0ZK8PKfMyTIBHKpyhcw)

# Installation

```bash
!git clone https://github.com/777gt/-EVC-
!cd -EVC-
!pip install -r requirements.txt
```
Now download the hubert base model into that folder too.

# Running it
On windows you can just open the go-web.bat file or navigate to the EasyGUI folder and manually type:
```bash
!python.exe GUI.py --pycmd python.exe --port 7897
```
On linux do:
```bash
!python3 GUI.py --pycmd python3
```

Latest updates:
6/18/23 : Automatically selects the index file when you select your model if it exists.
6/19/23: Added Elevenlabs API TTS and Google TTS.
6/20/23: Changed default values, removed resampling option. Optimized for local installation.
6/21/23: Added a Wav2Lip tab from wav2lip-HD https://github.com/indianajson/wav2lip-HD
