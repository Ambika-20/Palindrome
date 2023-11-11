# Palindrome
#To find a string is palindrome
word=input("Enter word:")
revword=word[::-1]
print(word)
print(revword)
if word == revword:
    print("Palindrome")
else:
    print("Not Palindrome")
