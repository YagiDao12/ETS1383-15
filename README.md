#string method

the string method I used is called isupper()

isupper(): this method is used to check if a string is in upper case or not

if we want to change the string to uppercase we use upper()


     name = "string methods"
     is_upper = name.isupper() 
     print(is_upper) # it prints the value False
    
     #to change the string to upper case we use :
     print(name.upper())


   

#string methods 2
the string method i used is called islower()

islower(): this method is used to check if a string is in lower case or not

if we want to change the string to uppercase we use upper()

example:
     name = "string methods"
     is_lower = name.islower() 
     print(is_lower) # it prints the value True
    
     to change the string to lower case we use :
     print(name.lower())
     
#string methods 3
i used the string method called capitalize() to make the first of my letter in a variable to make it uppercase.
example:
      name = 'solomon is good'
      answer = name.capitalize()
      print(answer)
#or if we want we can use the first assigned variable without assigning another one. for example:
      name = 'solomon is good'
      print(name.capitalize())   # the expected answer is the same like the above


#string methods 4
I used str.title() string method to capitalize the first letters of each word on a string

# string method 5
i used str.find(). this is used where the letters are located in a string. if the wanted letter is not there, then it returns -1

#string method 6
i used str.index(). this is used to find where the letters are located in a string like the find method. their difference is if the wanted letter is not there find returns -1 whereas index doesn't return it just shows error message

#string method 7
i ussed str.startswith(). this is used to check in a string the first letter or sentence starts wtih what we want to know. it returns boolean value.
