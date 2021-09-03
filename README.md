Repo with trained punctuation restoration models for https://github.com/sviperm/neuro-comma and https://github.com/xashru/punctuation-restoration 

Colab to prepare data for any language:
https://colab.research.google.com/drive/1-EUY-Do3vR_h3htyjjAMR-zVQyUsaH-t?usp=sharing  
Just set right language in LANG1 and LANG2 parameters. Also you have to set right UTF-8 characters for you language: https://www.periodni.com/unicode_utf-8_encoding.html.

Training Datasets in neuro-comma format:
|Dataset language|Google Drive Link|
|---|----|
|Portuguese|https://drive.google.com/file/d/1-0t7sskF3bKGeXiCOx4nL9R53-Z0f7ak/view?usp=sharing|
|Spanish|https://drive.google.com/file/d/1JHATFSu4amgz-cHcKXsSUyUs9T70kPa7/view?usp=sharing|  
|German|https://drive.google.com/file/d/1Us6mMtPjOxUi1Mu_M1PHWTB9pxuwyod7/view?usp=sharing|
  
  
Neuro-comma (puntuation-restoration) format: Oh, nun ja, dann wird sie es wohl gewesen sein. Wo sind die Karten geblieben?  

turns into:  
oh	COMMA  
nun	O  
ja	COMMA  
dann	O  
wird	O  
sie	O  
es	O  
wohl	O  
gewesen	O  
sein	PERIOD  
wo	O  
sind	O  
die	O  
karten	O  
geblieben	QUESTION  

Pretrained models:
|Model language|Base model|Google Drive Link|
|---|---|----|
|Portuguese|xlm-roberta-large|https://mega.nz/folder/LCBzga5A#_RonehX7eLF3sI95HNRzWQ|
|Spanish|xlm-roberta-large|https://mega.nz/folder/bOZThATD#hie5QHgPF7VxNEhWx3uxDA|
|German|slm-roberta-large|https://mega.nz/folder/vGR0RZRT#2w1zF9VRNApaBscnEdvv6A|

## How it works
https://github.com/sviperm/neuro-comma  
https://github.com/xashru/punctuation-restoration
