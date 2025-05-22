# add

This code uses the add() method to insert a new element into the set. for example:

my_set = {1, 2, 3, 4}

my_set.add(5)

print(my_set)  # Output: {1, 2, 3, 4, 5}

# remove

This code uses the remove() method to delete a specific element from the set. If the element is not found, it raises an error. for example:

my_set = {10, 20, 30, 40}

my_set.remove(20)

print(my_set)  # Output: {10, 30, 40}

# union

This code uses the union() method to combine elements from both sets, removing duplicates.

for example:

set1 = {1, 2, 3}
set2 = {3, 4, 5, 6}
result = set1.union(set2)
print(result)  # Output: {1, 2, 3, 4, 5, 6}

# intersection

This code uses the intersection() method to find common elements between two sets. for example:

set1 = {1, 2, 3, 4, 5}
set2 = {3, 4, 5, 6}

result = set1.intersection(set2)

print(result)  # Output: {3, 4, 5}

# difference()

This code uses the difference() method to find elements that are in set1 but not in set2. for example;

set1 = {1, 2, 3, 4, 7}
set2 = {3, 4, 5, 6}

result = set1.difference(set2)

print(result)  # Output: {1, 2, 7}

# symmetric_difference()

This code uses symmetric_difference() to find elements that are in either of the sets but not in both. for example:

set1 = {1, 2, 3, 8}
set2 = {3, 4, 5}

result = set1.symmetric_difference(set2)

print(result)  # Output: {1, 2, 4, 5, 8}




