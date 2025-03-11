##Insertion Sort

Pseudocode
```
START
    INPUT array
    FOR i from 1 to length of array - 1
        key = array[i]
        j = i - 1
        WHILE j >= 0 AND array[j] > key
            array[j + 1] = array[j]
            j = j - 1
        array[j + 1] = key
    END FOR
END
```
