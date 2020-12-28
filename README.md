## Following-is-the-input-NumPy-array-delete-column-two-and-insert-following-new-column-in-its-place.
## Sample code to check the details 
```sh
print("Array after deleting column 2 on axis 1")
sampleArray = numpy.delete(sampleArray , 1, axis = 1) 
print (sampleArray)
```
## Example Output
Printing Original array
[[34 43 73]
 [82 22 12]
 [53 94 66]]

Array after deleting column 2 on axis 1

[[34 73]
 [82 12]
 [53 66]]
Array after inserting column 2 on axis 1

[[34 10 73]
 [82 10 12]
 [53 10 66]]
