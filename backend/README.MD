## Installation

### 1.1 Libraries
```bash
pip install git+https://github.com/ramsrigouthamg/Questgen.ai
pip install git+https://github.com/boudinfl/pke.git

python -m nltk.downloader universal_tagset
python -m spacy download en 
```

### 1.2 Download and extract zip of Sense2vec wordvectors that are used for generation of multiple choices.
```
wget https://github.com/explosion/sense2vec/releases/download/v1.0.0/s2v_reddit_2015_md.tar.gz
tar -xvf  s2v_reddit_2015_md.tar.gz
```

##  Credit

This project utilizes code from the MIT licensed project [Questgen.ai](https://github.com/ramsrigouthamg/Questgen.ai) by [Ramsri Goutham Golla](https://github.com/ramsrigouthamg).