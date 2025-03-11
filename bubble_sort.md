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
        temp=selements[j]
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

![bubblesort](https://github.com/user-attachments/assets/f0c07101-5a28-4b5c-b795-90c60e2d250e)


