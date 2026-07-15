Create a 2-D array from the array below, using:

- the values with the lowest two indices from the first dimension
- the highest two indices from the second dimension
- only the first index of the third dimension

This new array should have the values `[[6, 8], [16, 18]]`.

Then do the following:

- modify the entry with indices `[1, 1]` so that it has value `4`
- modify the values with index `0` in the first dimension so that they become `[1, 2]` using a single assignment statement

```py-cell
import numpy as np

start_array = np.arange(30).reshape([3, 5, 2])

# Write your code here
```
