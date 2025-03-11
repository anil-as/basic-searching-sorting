# Bubble Sort

Bubble sort psuedocode

```
START
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
