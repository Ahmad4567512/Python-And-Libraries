# Day 13: Lists in Python (Continuation)

Lists are one of the most important data structures in Python. They are **ordered**, **mutable**, and can store items of different data types. This continuation covers **accessing, modifying, adding, removing items**, and some **useful built-in functions**.

## 1. Accessing Items

You can access items in a list using **index numbers**. Python uses zero-based indexing, which means the first item has index `0`.  
Negative indices can be used to access items from the end of the list.

## 2. Modifying Items
Lists are mutable, which means their items can be changed after creation.
To modify an item, specify its index and assign a new value.

numbers = [10, 20, 30, 40]
numbers[2] = 99
print("Modified numbers:", numbers)
numbers[2] = 99 → changes the 3rd item (index 2) to 99

## 3. Adding Items
New items can be added to a list using append() or insert():

fruits.append("orange")     # adds at the end of the list
fruits.insert(1, "mango")   # adds at index 1
print("Fruits after adding:", fruits)

# 1. append(value) → adds the item at the end of the list
# 2. insert(index, value) → adds the item at a specific position

## 4. Removing Items

Items can be removed using remove() or pop():

fruits.remove("banana")  # removes the first occurrence of 'banana'
fruits.pop()             # removes the last item
print("Fruits after removing:", fruits)
remove(value) → removes an item by value
# pop() → removes the last item by default or an item at a specific index if provided

## 5. Useful Functions with Lists

Python provides some built-in functions to manipulate lists:

print("Length of numbers list:", len(numbers))  # returns the number of items
numbers.sort()                                  # sorts the list in ascending order
print("Sorted numbers:", numbers)
numbers.reverse()                               # reverses the order of the list
print("Reversed numbers:", numbers)

# 1. len(list) → returns the number of items in the list
# 2. sort() → sorts the list in ascending order
# 3. reverse() → reverses the current order of the list
