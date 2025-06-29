28 June 2025 - Set 1 add this in GitHub by naking set1 and time and expiry

Coding

Q.1 Reverse string without using inbuilt fn
def reverse_string(string="ganesh"):
    reversed_string = ''
    for i in range(len(string)-1, -1, -1):
        print(string[i])
        reversed_string += string[i]
    print(reversed_string)
reverse_string("ganesh")


Q.2 Write fn to give words are anagram or not - listen,silent
def check_anagram(word1, word2):
    if len(word1) != len(word2):
        return "Not same length"
    for i in range(0, len(word1)):
        isExists = False
        print("first loop")
        for j in range(0, len(word2)):
            print("second loop", isExists)
            if word1[i] == word2[j]:
                print(word1[i], word2[j])
                isExists = True
                break
        if isExists == False :
            return False
        else:
            continue
    return True       
print(check_anagram("listen","silent"))


Q.3 Write fn to check armastrong no. take input and return true/false
# armstrong number is the number which is equal to sum of numbers in that number having in power the length of the that whole number i.e. 153 = 1^3 + 5^3 + 3^3
def check_armstrong(num):
    power = len(str(num))
    sum = 0
    for i in str(num):
        sum += int(i) ** power
    if num == sum:
        return True
    return False    
print(check_armstrong(153))


Q.4 Check for palindrome without inbuilt fn like slicing etc and take full sentence with spaces and all
# palindrome - same even if reads backwards
def check_palindrome(string):
    reversed_string = ''
    for i in range(len(string-1, -1, -1):
        reversed_string += string[i]
    if string == reversed_string:
        return True
    else :
        False
print(check_palindrome("wow"))


Q.5 Count each word occurrence in string
Q.6 print prime no. in between 25-50
Q.7 Swap two numbers without using third variable
Q.8 Merge two sorted arrays
Q.9 Convert number into binary
Q.10 Find no. Of occurrence in an array

Apti

- Simple and compound Interset
- solve 10 Qs on that after learning properly and making notes

Communication

- Write essay and gd/debate on it


Mock Interview

- based on resume take combo tech/hr