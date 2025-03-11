# Bubble Sort

Bubble sort Psuedocode

```
START
  PRINT "Enter the number of elements"
  INPUT n
  PRINT "Enter the elements"
  INPUT elements
  FOR i:1 TO n
    SET swapped = FALSE     
    FOR j:1 TO n-i
      IF elements[j]>elements[j+1]
        swap(elements[i],elements[i+1])
        SET swapped = TRUE    
      END IF
    END FOR
    IF swapped = FALSE      
      BREAK               
    END IF
  END FOR
END

```
Bubble sort Flowchart

![bubblesort](https://github.com/user-attachments/assets/23d41b8b-5b08-449e-9cb5-cbb1f36e15f8)

