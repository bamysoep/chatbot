# MAIR Chatbot
Welcome! This is the MAIR 2021 project. We, as members of group 25, made a chatbot which can recommend restaurants based on the users preferences. The chatbot engages in a conversation to get to know the required preferences to give a good recommendation.


## Installation
You will need to have https://visualstudio.microsoft.com/visual-cpp-build-tools/ installed on your computer to be able to install one of the packages. Python-Levenshtein uses C in the background. If you have this installed you can can continue. 

Install the necessary packages using:

```python
pip install -r requirements.txt
```

If it still doesn't work try this: 
```python
pip install python-Levenshtein-wheels
```
Then try it again.


The required python files:
- chatbot.py
- nlp.py
- dialog_manager.py
- evaluation.py

The following datafiles should be in the same folder as the python files:

- dialog_acts.dat
- new.csv
- restaurant_info.csv
- survey.csv

## Experiment
You are about to have a conversation with our chatbot KASA. This chatbot can recommend you a restaurant if you provide your preferences. For this experiment we invite you to talk with KASA and try to find a restaurant that suits your preferences (as described in the task below). You can talk with KASA by typing your responses. Try not to use !/?/,/. in your language. You can chat with KASA as you would normally have done. If, at any point, you want to end the conversation you can type ‘bye’ (for example if you get stuck). Please inform the researcher before you do this. When the conversation is over (if KASA has recommended a 
restaurant), you will be asked to type ‘bye’ and will be directed to a survey. This survey is not part of the chatbot.

The experiment takes up to 10 minutes.

### Task 1:
To start your first task use:

```python
python chatbot.py -f
```

choose the "tree" option.

You want to search for an **expensive Indian** restaurant in the **east** of the city. Try to see if KASA can find any restaurant that meets these preferences. If you get a restaurant recommendation you can confirm that this is the one you are looking for. This is the end of your conversation and you can type *bye*. If KASA asks for any extra requirements, let KASA know that you would like to bring your **children**.

### Task 2:
To start your second task use:

```python
python chatbot.py
```

choose the "tree" option.

You want to search for a **European** restaurant in the **centre** of the city. You prefer the price for the food to be **moderate**. Again, try to see if KASA can find any restaurant that meets these preferences. If you get a restaurant recommendation you can confirm that this is the one you are looking for. This is the end of your conversation and you can type *bye*. If KASA asks for any extra requirements, let KASA know that you want the restaurant to be **romantic**.

After you completed both tasks, please send the survey.csv to 
amy.oeij@hotmail.com or send it by any other means possible.
Thank you very much :)

## Contributors
- Amy Oey
- Andrea van Roijen
- Kathleen de Boer
- Sunny Hseih
