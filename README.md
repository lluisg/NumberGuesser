# NumberGuesser

This packages implements a Guesser using Python and OOP. Once initialzated the Object, it selects a random number between 0 and the limit indicated, and you can try to guess this number.

### Installation:
```sh
$ pip install number-guesser
```
```sh
$ python
>>> from number_guesser import Guesser
>>> g = Guesser(10)
>>> etc
```
    
### Attributes:
- guess ( integer ) representing the value selected to represent
- limit ( integer ) representing the limit value it can get

### Functions:

- make_guess ( integer guess ): reply to a guess with a sentence indicating vaguely where your guess places
- reestart_guess ( integer limit ): reestarts the guess number
