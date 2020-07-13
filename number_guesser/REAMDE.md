This packages implements a Guesser that selects a random number between 0 and the limit indicated, and to which you can try to guess this number

Usage:
	from number_guesser import Guesser
    
Attributes:
	guess (integer) representing the value selected to represent
	limit (integer) representing the limit value it can get

Functions:
	make_guess(integer guess): respons to a guess with a sentence indicating vaguely where your guess places
	reestart_guess(integer limit): reestarts the guess number