PYTHON-LAB-EXPERIMENT-4

PYTHON PROGRAMMING LAB EXPERIMENT

AIM


To write a Python program to demonstrate list and related list functions/operations such as appendi, inserto. removed, pop, count, index), sort, copy, extend), max), mini, sum), and clear).


Algorithm

1.Start the program.


2.Create a list containing different elements.

3.Display the list and find its length using leno.

4.Add an element at the end using appendo.

5.Insert an element at a specific position using insert).

6.Remove an element using remove().

7. Remove the last element using pop0.

8.Count the occurrence of an element using count.

9.Find the position of an element using index.

10.Create another numeric list.

11.Sort the list in ascending order using serto.

12.Sort the list in descending order using sort(reverse= True).

13.Copy the list using copyd.

14.Combine two lists using extendi).

15. Find the maximum and minimum values using max and minO.

16.Find the sum of elements using sumo.

17.remove all ements using clear()

18.stop the program


COURCE CODE


# Write a Python program to demonstrate list and related function operations

sc = [25, "sep", 25, "oct", 5, "nov", 7, "jan", "srini", 14, 16, 7]

print("The list is : ", sc)
print()
print("****************************************************")

print("The length of the list : ", len(sc))
print()
print("****************************************************")

s = sc.append(7)
print("Appending the element in list : ", sc)
print()
print("****************************************************")

s = sc.insert(11, 10)
print("Inserting the element in list : ", sc)
print()
print("****************************************************")

sc.remove(14)
print("Removing the element from list : ", sc)
print()
print("****************************************************")

sc.pop()
print("Popping the element from the list : ", sc)
print()
print("****************************************************")

print("Counting the element in the list : ", sc.count(25))
print()
print("****************************************************")

print("Indexing the element from the list : ", sc.index("srini"))
print()
print("****************************************************")


s = [15, 12, 178, 14, 190, 21, 43, 21, 1]

s.sort()
print("Sorting the element from the list : ", s)
print()
print("****************************************************")

s.sort(reverse=True)
print("Sorting the element in reverse : ", s)
print()
print("****************************************************")

c = sc.copy()
print("Copying the element in list : ", c)
print()
print("****************************************************")

sc.extend(s)
print("Extending the element in list : ", sc)
print()
print("****************************************************")

print(s)
print("Finding the element max in list : ", max(s))
print()
print("****************************************************")

print(s)
print("Finding the element min in list : ", min(s))
print()
print("****************************************************")

print(s)
print("Sum of element in list : ", sum(s))
print()
print("****************************************************")

print("Before clearing the element in list : ", sc)
sc.clear()
print("After clearing the element in list : ", sc)


OUTPUT


The list is : [25, 'sep', 25, 'oct', 5, 'nov', 7, 'jan', 'srini', 14, 16, 7]

****************************************************

The length of the list : 12

****************************************************

appending the element in list : [25, 'sep', 25, 'oct', 5, 'nov', 7, 'jan', 'srini', 14, 16, 7, 7]

****************************************************

inserting the element in list : [25, 'sep', 25, 'oct', 5, 'nov', 7, 'jan', 'srini', 14, 16, 10, 7, 7]

****************************************************

removing the element form list : [25, 'sep', 25, 'oct', 5, 'nov', 7, 'jan', 'srini', 16, 10, 7, 7]

****************************************************

poping the element form the list : [25, 'sep', 25, 'oct', 5, 'nov', 7, 'jan', 'srini', 16, 10, 7]

****************************************************

counting the element in the list : 2

****************************************************

indexing the element from the list : 8

****************************************************

sorting the element from the list : [1, 12, 14, 15, 21, 21, 43, 178, 190]

****************************************************

sorting the element in reverse : [190, 178, 43, 21, 21, 15, 14, 12, 1]

****************************************************

coping the element in list : [25, 'sep', 25, 'oct', 5, 'nov', 7, 'jan', 'srini', 16, 10, 7]

****************************************************

extending the element in list : [25, 'sep', 25, 'oct', 5, 'nov', 7, 'jan', 'srini', 16, 10, 7, 190, 178, 43, 21, 21, 15, 14, 12, 1]

****************************************************

[190, 178, 43, 21, 21, 15, 14, 12, 1]
finding the element max in list : 190

****************************************************

[190, 178, 43, 21, 21, 15, 14, 12, 1]
finding the element min in list : 1

****************************************************

[190, 178, 43, 21, 21, 15, 14, 12, 1]
sum of element in list : 495

****************************************************

before clearing the element in list : [190, 178, 43, 21, 21, 15, 14, 12, 1]

clearing the element in list : []


