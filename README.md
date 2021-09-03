Repo with trained punctuation restoration models for https://github.com/sviperm/neuro-comma and https://github.com/xashru/punctuation-restoration 

Colab to prepare data for any language:
https://colab.research.google.com/drive/1-EUY-Do3vR_h3htyjjAMR-zVQyUsaH-t?usp=sharing
Just set right language in LANG1 and LANG2 parameters
And set the right UTF-8 characters for you language 

All trained models are based on xlm-roberta-large, set it when call inference like 
python inference.py --pretrained-model=roberta-large --weight-path=roberta-large-en.pt --language=en 
--in-file=data/test_en.txt --out-file=data/test_en_out.txt

Portuguese language punctuation restoration model:
https://mega.nz/folder/LCBzga5A#_RonehX7eLF3sI95HNRzWQ

Portuguese dataset in neuro-comma format: https://drive.google.com/file/d/1-0t7sskF3bKGeXiCOx4nL9R53-Z0f7ak/view?usp=sharing

Spanish language punctuation restoration model:
https://mega.nz/folder/bOZThATD#hie5QHgPF7VxNEhWx3uxDA

Spanish dataaset in neuro-comma format: https://drive.google.com/file/d/1JHATFSu4amgz-cHcKXsSUyUs9T70kPa7/view?usp=sharing

## How it works
https://github.com/sviperm/neuro-comma
