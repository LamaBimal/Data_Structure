**Data Structure**

Organizing, managing and storing data is important as it enables easier access and efficient modification. Data Structures allows you to organize your data in a such way that enables to store the collecctions of data, relate them and perform operations on them accordingly.

The basic Python data structures in Python includes list, set, tuples and dictionary. Each of the data structure is unique in its own way.


**List**

- An ordered collection of items
- Used to store multiple items in a single variable
- A list can be nested, which means that it can contain any type of object.
- List are mutable, which means it can be altered even after being created.

Creation:

- List can be created by using square brackets

```
 this_list = ["apple", "banana", "cherry"]
 print(this_list)
```
- List also can be created using the list() constructor

```
thislist = list(("apple", "banana", "cherry))
print(thislist)
```

List Items
- Items are ordered, changeable, and allow duplicate values
- Items are indexed, the first item has index[0], the second item has index[1] and so on.

Access List Items

- List items are indexed and we can access them by referring the index number

```
thislist = ["apple","banana"]
print(thislist[1]) // dispaly banana
```
- Negative indexing means start from the end
- [-1] refers to the last item, -2 refers to the second last item

```
thislist = ["apple","banana","cherry"]
print(thislist[-1]) // display cherry
```

Range of Indexes

- Specify a range of indexes where to start and where to end the range
- It will return the new list of specified items
```
thislist = ["apple", "banana", "cherry", "Orange", "Kiwi", "melon", "mango"]
print(thislist[2:5])
```

Note: This search will start at index 2 (included) and end at index 5 (excluded)

```
print(thislist[:5]) // starting from index 0 upto index 4
print(thislist[2:]) // starting index 2 to last
```

Append Items

- To add an item to the end of the list, use the append() method

```
thislist = ["Ram","Shynam","Hari"]
thislist.append("Gita")
print(thislist)
```

Insert Items

-  To insert a item at a specified index, use the insert(`index`,`item`) method.

```
thislist = ["apple","banana","cherry"]
thislist.insert(1,"orange")
print(thislist)

```

Update Item:

-  To change the value of a specified index, refer to the index number

```
thislist = ["apple","banana","cherry"]
thislist[1] = "orange"

print(thislist) # ["apple","orange","cherry"]
```
Remove Items:
