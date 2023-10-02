**Data Structure**

Organizing, managing, and storing data is important as it enables easier access and efficient modification. Data Structures allow you to organize your data in a way that enables you to store the collections of data, relate them, and perform operations on them accordingly.

The basic Python data structures in Python include lists, sets, tuples, and dictionaries. Each of the data structures is unique in its own way.


**List**

- An ordered collection of items
- Used to store multiple items in a single variable
- A list can be nested, which means that it can contain any type of object.
- List is mutable, which means it can be altered even after being created.

Creation:

- List can be created by using square brackets

```
 this_list = ["apple", "banana", "cherry"]
 print(this_list)
```
- List also can be created using the list() constructor

```
this_list = list(("apple", "banana", "cherry))
print(this_list)
```

List Items
- Items are ordered, changeable, and allow duplicate values
- Items are indexed, the first item has index[0], the second item has index[1] and so on.

Access List Items

- List items are indexed and we can access them by referring to the index number

```
this_list = ["apple", "banana"]
print(this_list[1]) // display banana
```
- Negative indexing means starting from the end
- [-1] refers to the last item, -2 refers to the second last item

```
this_list = ["apple", "banana", "cherry"]
print(this_list[-1]) // display cherry
```

Range of Indexes

- Specify a range of indexes where to start and where to end the range
- It will return the new list of specified items
```
this_list = ["apple", "banana", "cherry", "Orange", "Kiwi", "melon", "mango"]
print(this_list[2:5])
```

Note: This search will start at index 2 (included) and end at index 5 (excluded)

```
print(this_list[:5]) // starting from index 0 upto index 4
print(this_list[2:]) // starting index 2 to last
```

Append Items

- To add an item to the end of the list, use the append() method

```
this_list = ["Ram", "Shynam", "Hari"]
this_list.append("Gita")
print(this_list)
```

Insert Items

-  To insert an item at a specified index, use the insert(`index`, `item`) method.

```
this_list = ["apple", "banana", "cherry"]
this_list.insert(1,"orange")
print(this_list)

```

Update Item:

-  To change the value of a specified index, refer to the index number

```
this_list = ["apple", "banana", "cherry"]
this_list[1] = "orange"

print(this_list) # ["apple", "orange", "cherry"]
```
Remove Items:
