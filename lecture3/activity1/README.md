# Activities

## Task 1

- Refer to the following link. Discuss how bubble sort works:
  https://opendsa-server.cs.vt.edu/embed/bubblesortAV

  Bubble sort for each pass compares each number to next one and swaps bigger one to the right, until it's in the final position, then loops again.

## Task 2

- Refer to the following link. Your task is to show the behavior for one iteration of the outer for loop of Bubble Sort (Try at least 3 cases).
  https://opendsa-server.cs.vt.edu/ODSA/Exercises/Sorting/BubsortPRO.html

## Task 3

- The following snippet is from `./src/bubble.cpp` lines 16-28. Discuss in groups how the code works:

```cpp

    for (i = 0; i < 10; i++)
    {
        for (j = i + 1; j < 10; j++)
        {
            if (a[j] < a[i])
            {
                temp = a[i];
                a[i] = a[j];
                a[j] = temp;
            }
        }
        pass++;
    }
```

This is bubble sort algorithm for numbers 0-10 and it stores value in temp while doing swapping

- The following snippet is from `./src/selection.cpp` lines 34-41. Discuss in groups how the code works:

```cpp
    for (j = i + 1; j < 10; j++)
    {
        if (myarray[j] < ele_small)
        {
            ele_small = myarray[j];
            position = j;
        }
    }
```

## Task 4: Individual, at home

- Discuss the complexity analysis of selection sort. Refer to the link below:
  https://www.softwaretestinghelp.com/selection-sort/

## Links

- https://cpp.sh/
