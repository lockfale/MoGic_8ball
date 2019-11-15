# MoGic_8ball
Your virtual MoG

MoGic_8ball requires Python 3, so make sure that's installed first

```which python3```


This should return:

```/usr/bin/python3```


Next, install venv for Python 3:

```sudo apt-get install python3-venv```


Create the virtual environment:

```python3 -m venv env```


Drop into the virtual env:

```source ./env/bin/activate```


Now install the pre-reqs (scikit-learn and nltk):

```python -m pip install -U scikit-learn```

```python -m pip install nltk```


Drop into the Python console and add the needed nltk modules by running the following:

```python```

```import nltk```

```nltk.download('punkt')```

```nltk.download('wordnet')```

```exit()```


Now launch the MoG:

```python mog.py```


The MoGic_8ball has come pre-loaded with all kinds of fundy crap in "chatbot.txt". Feel free to add as much fundy content as you would like to better train the MoG and enjoy some awful AI. PTL!

References: https://medium.com/analytics-vidhya/building-a-simple-chatbot-in-python-using-nltk-7c8c8215ac6e
