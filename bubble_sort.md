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
        temp=elements[j]
        elements[j]=elements[j+1]
        elements[j+1]=temp
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

![bubblesort](https://github.com/user-attachments/assets/6573a7de-9617-40e8-9023-92610cd45b86)

