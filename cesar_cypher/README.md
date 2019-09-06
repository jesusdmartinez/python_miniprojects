# Cesar Cypher

Replicate one of the oldest known encryption in code.

Apply a Cesar cipher of 7 to the 'secret' variable.

P.S.: http://www.montypython.net/scripts/dentist.php ;)

You can start with the following code:

secret = "I hear the gooseberries are doing well this year, and so are the mangoes."
cipher = 7

```python

secret = "i hear the gooseberries are doing well this year, and so are the mangoes."
letters = "abcdefghijklmnopqrstuvwxyzabcdefghijklmnopqrstuvwxyz"
cipher = 7
lookup = []
crypto = []

for i in secret:
    if i in letters:
        lookup.append(letters.find(i) + cipher)

for i in lookup:
    crypto.append(letters[i])

print(crypto)

