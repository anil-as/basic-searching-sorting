# Selection Sort

Selection sort Psuedocode

```
START
  INPUT array
  FOR i:1 TO length of array -1
    SET minIndex = i      
    FOR j:i+1 TO n
      IF array[j] < array[minIndex]
        SET minIndex = j  
      END IF
    END FOR
    SWAP(array[i], array[minIndex])  
  END FOR
END

```




