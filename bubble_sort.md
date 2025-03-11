# Bubble Sort

Bubble sort psuedocode

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
![bubblesort](https://github.com/user-attachments/assets/83170c4a-2344-484f-b8ee-a9cf15d008da)
