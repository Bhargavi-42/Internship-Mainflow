# Internship-Mainflow
# Task-1
# Data Science with Python
# List
#Creating a List
list1 = [1,2,3,4,5,6]
print("Original List:", list1)

#Adding an element to the List
list1.append(8)
print("List after adding an element:", list1)

#Removing an element from the List
list1.remove(4)
print("List after removing an element:", list1)

#Modifying an element to the List
list1[1] = 5
print("List after modifying an element:", list1)

# Dictionary
#Creating a Dictinary
book = {    "name": "Naari",
            "pages": 200,
            "author": "Vamshi krishna"
}
#Print the dictionary
print("\nBook Information:",book)

#Adding an element to the dictionary
book["price"] = 249
print("Dictionary after adding an element:",book)

#Modify an element in the dictionary
book["pages"] = 192
print("Book information after update:",book)

#Removing an element from the dictionary
del book["pages"]
print("Dictionary after removing an element:",book)

# Set
#Creating a set
fruits = {"mango", "grapes", "apple", "orange"}

#Print the set
print("\nSet of fruits:",fruits)

#Add new element to the set
fruits.add("banana")
print("\nSet of fruits after addding banana:",fruits)

#Remove an element from the set
fruits.remove("grapes")
print("\nSet after removing an element:",fruits)
