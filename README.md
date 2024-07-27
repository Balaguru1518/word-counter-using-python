# word-counter-using-python
word=0
n = input("Enter text:")
for i in n:
    if i.isspace():
        word+=1
    print("Total words:",word+1)
