This is the code i made for qs 2

list1=[]
#a="a","e","i","o","u"
b=input("enter a sentence ")
newlist=list(b)
newlist.append(b)
print(newlist)
count1=newlist.count("e")
print(count1)


And this is the code i made for qs 1

list1=[]
letter="a"
word=input("Please enter a 8 letter word")
count=letter.count(word)
print(count)
word1=input("Plese enter a 3-5 letter word")
print(word1[1])
print(word[::-1])
