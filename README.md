# Mini-project-2
PYTHON ASSIGNMENT
# Original list with heterogeneous data
L = ["Ram", 1, "Shyam", 2, "Aman", 3]

print("Original list:", L)

# Separate elements by type
strings = sorted([x for x in L if isinstance(x, str)])
integers = sorted([x for x in L if isinstance(x, int)])

# Combine sorted values (you can choose the order)
sorted_L = strings + integers  # or integers + strings depending on preference

print("Sorted list (strings first):", sorted_L)
