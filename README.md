# python_interview_questions

### **1. Dictionary Inversion with Lists**
**Task**: Write a function `invert_dict(d)` that takes a dictionary and returns a new dictionary where the original values become keys, and the original keys are stored in a list. Handle duplicate values.  
**Example**:  
Input: `{'a': 1, 'b': 2, 'c': 1}`  
Output: `{1: ['a', 'c'], 2: ['b']}`  

---

### **2. Flatten a Nested List**
**Task**: Write a recursive function `flatten(nested_list)` to flatten arbitrarily nested lists into a single list.  
**Example**:  
Input: `[1, [2, [3, 4], 5], 6]`  
Output: `[1, 2, 3, 4, 5, 6]`  

---

### **3. Merge Two Sorted Lists**
**Task**: Write a function `merge_sorted(a, b)` that merges two sorted lists into one sorted list **without using built-in sort functions**.  
**Example**:  
Input: `a = [1, 3, 5]`, `b = [2, 4, 6]`  
Output: `[1, 2, 3, 4, 5, 6]`  

---

### **4. Tuple-Based Dictionary Keys**
**Task**: Create a dictionary where keys are tuples representing coordinates `(x, y)` and values are the count of times that coordinate appears. Write a function `add_coordinate(coords_dict, x, y)` to update the dictionary.  
**Example**:  
After adding `(1, 2)` twice and `(3, 4)` once, the dict becomes `{(1, 2): 2, (3, 4): 1}`.

---

### **5. Class: Bank Account with Transactions**
**Task**: Implement a `BankAccount` class with:  
- Initial balance (default 0).  
- `deposit(amount)` and `withdraw(amount)` methods.  
- A `balance` property (raise `ValueError` for invalid withdrawals).  
**Example**:  
```python
acc = BankAccount(100)
acc.withdraw(50)  # New balance: 50
acc.withdraw(100) # Raises ValueError
```

---

### **6. Word Frequency Counter**
**Task**: Write a function `word_frequency(text)` that returns a dictionary of word frequencies, ignoring case and punctuation.  
**Example**:  
Input: `"Hello world, hello Python!"`  
Output: `{'hello': 2, 'world': 1, 'python': 1}`  

---

### **7. Sort List of Tuples by Multiple Criteria**
**Task**: Sort a list of tuples `(name, age, score)` first by `age` (ascending), then by `score` (descending).  
**Example**:  
Input: `[('Alice', 25, 80), ('Bob', 25, 90), ('Charlie', 20, 85)]`  
Output: `[('Charlie', 20, 85), ('Bob', 25, 90), ('Alice', 25, 80)]`  

---

### **8. Class Inheritance: Employee and Manager**
**Task**: Create a base `Employee` class with `name` and `salary`, then a `Manager` subclass that adds a `department` attribute. Override the `display()` method to include the department.  
**Example**:  
```python
mgr = Manager("Jane", 80000, "HR")
mgr.display()  # Output: "Jane (Manager, HR) earns $80000"
```

---

### **9. List of Dictionaries to Dictionary of Lists**
**Task**: Convert a list of dictionaries with identical keys into a dictionary of lists.  
**Example**:  
Input: `[{'a': 1, 'b': 2}, {'a': 3, 'b': 4}]`  
Output: `{'a': [1, 3], 'b': [2, 4]}`  

---

### **10. Class with Static Method**
**Task**: Create a `MathUtility` class with a static method `is_even(n)` that returns `True` if `n` is even, and a class method `average(numbers)` to compute the average of a list.  
**Example**:  
```python
MathUtility.is_even(4)  # True
MathUtility.average([1, 2, 3])  # 2.0
```
