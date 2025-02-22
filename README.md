## Text Sentiment Analysis Using Caikit and Hugging Face (IBMSkillNetwork GPXX0PYAEN)

---

### Material by Cognitive Class AI
### Task by CognitiveClass.ai

---

### My Name : _Silviana Anggellica_
### My Program : _IBM Advance AI_ at Infinite Learning

---
### Tools :
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)

![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)


### Language :
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)


### Model :
- pipeline
- analysis_sentiment
- Caikit
- Hugging Face

---

### Caikit is an open source AI toolkit that enables users to manage models through a set of developer friendly APIs.

### This technology was used to develop APIs in Caikit for text sentiment. Like :
- Create the project
- Create the data model specification
- Create the model wrapper
- Include the module and package dependencies
- Start the Caikit runtime
- Test the sentiment analysis
---

### Documentation

0. Install Caikit runtime
##### 1st in the terminal :
```
pip install --user virtualenv
```
---

1. Create the project
##### 1st in the terminal :
```
mkdir -p /home/project/text-sentiment text_sentiment
cd /home/project/text-sentiment/text_sentiment
```
---
2. Create the data model specification
##### 1st in the terminal :
```
mkdir data_model
cd data_model
```

##### 2nd :
#### add code in the `classification.py`

##### 3rd :
#### add code in the `__init__.py`
---
3. Create the model wrapper
##### 1st in the terminal :
```
cd /home/project/text-sentiment mkdir -p models/text_sentiment
cd models/text_sentiment
```

##### 2nd : 
#### add code in the `config.yml`

##### 3rd in the terminal :
```
cd /home/project/text-sentiment text_sentiment
mkdir runtime_model
cd runtime_model
```

##### 4th :
#### add code in the `hf_module.py`

##### 5th :
#### add code in the `__init__.py`

##### 6th :
#### add code in the `config.yml`

##### 7th :
#### add code in the `__init__.py`
---
4. Include the module and package dependencies
##### 1st in the terminal :
```
cd /home/project/text-sentiment
```

##### 2nd : 
#### add code in the `requirements.txt`

##### 3rd  in the terminal: 
```
virtualenv -p python3 env
source env/bin/activate
```

##### 4th in the terminal :
```
pip install -r requirements.txt
```
---
5. Start the Caikit runtime
##### 1st : 
#### add code in the `start_runtime.py`

##### 2nd in the terminal for running : 
```
python start_runtime.py
```
---
6. Test the sentiment analysis
##### 1st : 
#### add code in the `client.py`

##### 2nd : 
#### add text in the `client.py` about anything. _Example from me : "Kemarin aku makan udang asam manis!","Besok datang lagi, tapi beli ayam bakar saja!"_

##### 3rd in the terminal for running, this is emosional shape and accuracy (output): 
```
python client.py
```
---

###### After following the steps above, the point is like the first and second points below, so that it can run in the second.
###### First, start the runtime_model by calling the python function start_runtime.py in the terminal
###### Second, call the python function client.py in the terminal
###### That's all from me, thank you





