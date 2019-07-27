# Chatbot (SEQ2SEQ Model)

![Bot](https://raw.githubusercontent.com/Imetomi/Chatbot/master/static/talking.png)

## Dataset

The chatbot is trained on the Cornell Movie DB with more than 100,000 dialogue lines. The bot was able to learn basic convestational skills but cannot handle deep, meaningful sentences. When there is a missing word in its vocabulary you'll get "_UNK" in the converstion.

## Model

The model is a simple SEQ2SEQ model built with tensorflow. Note: Python 2.7 is recommended for this project.

## Requirements

    `flask
     tensorflow==0.12.1
     numpy
     math
     six
    `

