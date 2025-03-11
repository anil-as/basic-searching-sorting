# Bubble Sort

Bubble sort Psuedocode

```
START
  PRINT "Enter the number of elements"
  INPUT n
  PRINT "Enter the elements"
  INPUT elements
  FOR i:1 TO n
    FOR j:1 TO n-i
      IF elements[j]>elements[j+1]
        temp=elements[j]
        elements[j]=elements[j+1]
        elements[j+1]=temp
      END IF
    END FOR
END FOR
END
```
Bubble sort Flowchart

![bubblesort](https://github.com/user-attachments/assets/3fdc8dce-c1ac-446f-ad60-001b3f4e0679)

