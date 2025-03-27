# pythonSecond_Assignmnet_PLP

# 1. Create an empty list called my_list.
# An empty list is created to store elements dynamically.
my_List = []

# 2. Append the following elements to my_list: 10, 20, 30, 40.
# The append() method adds elements to the end of the list.
my_List.append(10)  # Adds 10 to the list
my_List.append(20)  # Adds 20 to the list
my_List.append(30)  # Adds 30 to the list
my_List.append(40)  # Adds 40 to the list

# 3. Insert the value 15 at the second position in the list.
# The insert() method places 15 at index 1 (second position).
my_List.insert(1, 15)  
# Inserts 15 at index 1

# 4. Extend my_list with another list: [50, 60, 70].
# The extend() method adds multiple elements from another list.
my_List.extend([50, 60, 70]) 
 # Appends 50, 60, and 70 to my_List

# 5. Remove the last element from my_list.
# The pop() method removes the last element (which is 70 in this case).
my_List.pop()  # Removes 70

# 6. Sort my_list in ascending order.
# The sort() method arranges elements in increasing order.
my_List.sort()  # Sorts the list in ascending order

# 7. Find and print the index of the value 30 in my_list.
# The index() method returns the position of 30 in the sorted list.
index_30 = my_List.index(30)  
# Finds the index of 30
print("Index of 30:", index_30) 
 # Prints the index of 30

# 8. Print the final list after all modifications.
print("Final list:", my_List)  # Displays the modified list