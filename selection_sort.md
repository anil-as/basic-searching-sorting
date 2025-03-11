# Selection Sort

Selection sort Psuedocode

```
START
  PRINT "Enter the number of elements"
  INPUT n
  PRINT "Enter the elements"
  INPUT elements
  FOR i:1 TO n-1
    SET minIndex = i      
    FOR j:i+1 TO n
      IF elements[j] < elements[minIndex]
        SET minIndex = j  
      END IF
    END FOR
    SWAP(elements[i], elements[minIndex])  
  END FOR
END

```
Selection sort Flowchart



