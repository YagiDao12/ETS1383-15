# 1 append

this list method is used to add something in the list for example :

   list=['hi']
   list.append('hello')
   print(list)       # it will add hello in the list

# 2 clear

this list method is used to clear all the items in the list for example:

   list=['hi']
   list.clear()
   print(list)    # the urput is []

# 3 copy

we use this one to copy the items in the list and add it to another list for example:

   list=['hello']
   list_copy=list.copy()
   print(list_copy)    # the output is ['hello'] 

# 4 count 

this one is used to count how many times that specific thing that we want to know is listed in the list for example:

list = ['abebe', 'yared', 'abebe', 'john']

text = list.count('yared')

print(text)     # 1

# 5 extend

this one is used to add another list into another list for example:

list_1 = ['run', 'jump']

list_2 = ['ciao', 'bye']

list_1.extend(list_2)

print(list_1)       # ['run', 'jump', 'ciao', 'bye']

# 6 index

this one is used to tell us where the specific list we asked it is located in the list for example:

list = ['hi', 'hello', 'run']

print(list.index('hi'))     # 0
