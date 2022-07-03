# Cards Demo
> Demo


This file will become your README and also the index of your documentation.

## Install

`pip install your_project_name`

## How to use

Fill me in please! Don't forget code examples:

```python
card = Card(2, 3)
card
```




    3 of Hearts



```python
deck = Deck()
deck.pop_card()
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    /tmp/ipykernel_25709/140343909.py in <module>
    ----> 1 deck = Deck()
          2 deck.pop_card()


    ~/workspace/cards_demo/cards_demo/deck.py in __init__(self)
         16 
         17     def __init__(self):
    ---> 18         """Initializes the Deck with 52 cards.
         19         """
         20         self.cards = []


    NameError: name 'Card' is not defined

