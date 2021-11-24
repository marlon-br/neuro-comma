Repo with trained punctuation restoration models for https://github.com/sviperm/neuro-comma and https://github.com/xashru/punctuation-restoration 

Colab to prepare data for any language:
https://colab.research.google.com/drive/1-EUY-Do3vR_h3htyjjAMR-zVQyUsaH-t?usp=sharing  
Just set right language in LANG1 and LANG2 parameters. Also you have to set right UTF-8 characters for you language: https://www.periodni.com/unicode_utf-8_encoding.html.

Training Datasets in neuro-comma format:
|Dataset language|Google Drive Link|Zipped Size|
|---|----|---|
|Portuguese|https://drive.google.com/file/d/1-0t7sskF3bKGeXiCOx4nL9R53-Z0f7ak/view?usp=sharing|358.2 MB|
|Spanish|https://drive.google.com/file/d/1JHATFSu4amgz-cHcKXsSUyUs9T70kPa7/view?usp=sharing|476.7 MB|
|German|https://drive.google.com/file/d/1Us6mMtPjOxUi1Mu_M1PHWTB9pxuwyod7/view?usp=sharing|721.9 MB|
|Russian|https://drive.google.com/file/d/1-0MBsnGfId6AGxgPhnkO2gAxaDn1DWGQ/view?usp=sharing|584.7 MB|
|French|https://drive.google.com/file/d/1--ocXMVscsIKghB9xzEUUeIVvJqY0qUX/view?usp=sharing|971.8 MB|  
  
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
|Portuguese|xlm-roberta-large|https://drive.google.com/file/d/1tjXmDSMgwF0iJsXw8sAGZop5CnMB16iM/view?usp=sharing|
|Spanish|xlm-roberta-large|https://drive.google.com/file/d/1YGHFOdr4wJCHjNpwBBy7KQ6a0-jqpYzO/view?usp=sharing|
|German (qunatized|xlm-roberta-large|https://drive.google.com/file/d/1Tw4ISUVMPqMXIwEU0IFy5ldSLa9z7Zjt/view?usp=sharing|
|Russian (quantized)|xlm-roberta-large|https://drive.google.com/file/d/1VgmF4wHbpftyWxZQrY7BJHOYdKYjZSBH/view?usp=sharing|
|French|xlm-roberta-large|https://drive.google.com/file/d/1wg6GeRi5EKE_60bni3PWsDQM_IdpXIn_/view?usp=sharing|
|English (from punctuation-restoration)|roberta-large|https://drive.google.com/file/d/17BPcnHVhpQlsOTC8LEayIFFJ7WkL00cr/view?usp=sharing|

## How it works
https://github.com/sviperm/neuro-comma  
https://github.com/xashru/punctuation-restoration
