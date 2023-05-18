# Question-Answering-Application
Question-Answering Application with Django, BeautifulSoup, cdQA (Deep Learning)

## Getting Started

This project works on **Python 3+** and Django 2+.

Install dependencies:

```
python3 -m pip3 install -r requirements.txt
```

Download pre-trained models from cdQA and include into your project:

```
from cdqa.utils.download import download_model
download_model(model='bert-squad_1.1', dir='./models')
```


