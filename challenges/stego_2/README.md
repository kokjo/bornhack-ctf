Stego_2:
========
	Presented with a slightly edited wikipedia page
	on the History of Binary Code, find the flag.
	

Flag:
=====
	FLAG{ASCIIisfun}


Solution:
=========
	1: Remove ALL letter a-zA-z OR grep all numbers 0-9 (or 0-1).
		grep -o '[0-9]*' stego_2.txt | tr -d '\n'

	2: Convert the remaining numbers (should all be binary) to hex and/or ASCII


Author:
=======
	Emil 'Dota' Bak (Pwnies)
		emilsbak@gmail.com


Tags:
=====
	stego, easy, conversion, obscure, bash