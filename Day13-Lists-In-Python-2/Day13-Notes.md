# Day 13: Lists in Python (Continuation)

Lists are one of the most important data structures in Python. They are **ordered**, **mutable**, and can store items of different data types. This continuation covers **accessing, modifying, adding, removing items**, and some **useful built-in functions**.

## 1. Accessing Items

You can access items in a list using **index numbers**. Python uses zero-based indexing, which means the first item has index `0`.  
Negative indices can be used to access items from the end of the list.

## 2. Modifying Items
Lists are mutable, which means their items can be changed after creation.<br>
To modify an item, specify its index and assign a new value.<br>

numbers = [10, 20, 30, 40]<br>
numbers[2] = 99<br>
print("Modified numbers:", numbers)<br>
numbers[2] = 99 → changes the 3rd item (index 2) to 99<br>

## 3. Adding Items
New items can be added to a list using append() or insert():<br>

fruits.append("orange")     # adds at the end of the list<br>
fruits.insert(1, "mango")   # adds at index 1<br>
print("Fruits after adding:", fruits)<br>

1. append(value) → adds the item at the end of the list<br>
2. insert(index, value) → adds the item at a specific position<br>

## 4. Removing Items

Items can be removed using remove() or pop():<br>

fruits.remove("banana")                                      # removes the first occurrence of 'banana'<br>
fruits.pop()                                                 # removes the last item<br>
print("Fruits after removing:", fruits)<br>
remove(value) → removes an item by value<br>
pop() → removes the last item by default or an item at a specific index if provided<br>

## 5. Useful Functions with Lists

Python provides some built-in functions to manipulate lists:<br>

print("Length of numbers list:", len(numbers))  # returns the number of items<br>
numbers.sort()                                  # sorts the list in ascending order<br>
print("Sorted numbers:", numbers)<br>
numbers.reverse()                               # reverses the order of the list<br>
print("Reversed numbers:", numbers)<br>

1. len(list) → returns the number of items in the list<br>
2. sort() → sorts the list in ascending order<br>
3. reverse() → reverses the current order of the list<br>


