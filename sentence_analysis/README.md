# Sentence Analysis Tool

Write a script that takes a sentence from the user and returns:

- the number of lower case letters
- the number of uppercase letters
- the number of punctuations characters
- the total number of characters

Use a dictionary to store the count of each of the above.

**Note**: ignore all spaces.

Example input:
```
I love to work with dictionaries!
```

Example output:
```
Upper case: 1
Lower case: 26
Punctuation: 1
Total chars: 28
```


sentence = input("enter a sentence")
count1 = 0
count2 = 0
for i in sentence:
    if(i.islower()):
        count1=count1+1
    elif(i.isupper()):
        count2=count2+1


print("Upper case: {}".format(float(count2)))
print("Lower case: {}".format(float(count1)))
print("Punctuation: {}".format(float(len(sentence) - sentence.count(" ") - float(count1) - float(count2))))
print("Total chars: {}".format(float(len(sentence) - sentence.count(" "))))


