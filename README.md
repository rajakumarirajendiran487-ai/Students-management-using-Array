# Students-management-using-Array
# List ADT using Array - Student Marks Application

marks = []

# Add marks
marks.append(70)
marks.append(85)
marks.append(90)
marks.append(60)

print("Student Marks:", marks)

# Insert mark at position
marks.insert(2, 75)
print("After Inserting 75:", marks)

# Delete a mark
marks.remove(60)
print("After Removing 60:", marks)

# Update a mark
marks[1] = 88
print("After Updating:", marks)

# Display total
print("Total Marks:", sum(marks))



Output:


Student Marks: [70, 85, 90, 60]
After Inserting 75: [70, 85, 75, 90, 60]
After Removing 60: [70, 85, 75, 90]
After Updating: [70, 88, 75, 90]
Total Marks: 323
