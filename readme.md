# PyRemoveDuplicates

PyRemoveDuplicates is a Python package that provides a simple and efficient way to remove duplicate elements from a list or array. It is a versatile tool that can be used in various scenarios where data deduplication is necessary.

## Installation

You can install PyRemoveDuplicates using pip, the Python package manager. Open your terminal or command prompt and run the following command:

```bash
pip install PyRemoveDuplicates
```
##Usage

After installing the package, you can use it in your Python scripts as follows:

```Python
from PyRemoveDuplicates import Unique

# Create a list with duplicate elements
my_list = [1, 2, 2, 3, 4, 4, 5]

# Use the remove_duplicates function to remove duplicates
unique_list = Unique(my_list)

# Print the unique list
print(unique_list)
```