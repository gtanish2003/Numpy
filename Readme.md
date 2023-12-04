# Python Numpy Repository

Welcome to the Python Numpy repository! 

## Table of Contents

**1. NumPy Overview**
   - NumPy is the fundamental package for scientific computing in Python.
   - It provides a multidimensional array object, various derived objects, and routines for fast array operations.
   - Includes mathematical, logical, shape manipulation, sorting, I/O, linear algebra, statistical operations, and more.

**2. NumPy Array vs Python Sequences**
   - NumPy arrays have a fixed size at creation, unlike dynamic Python lists.
   - Elements in a NumPy array must be of the same data type.
   - Facilitates efficient mathematical operations on large datasets.

**3. Creating NumPy Arrays**
   - `np.array([])`
   - `np.arange(start, stop, step)`
   - `np.ones(m, n)`
   - `np.zeros(m, n)`
   - `np.random.rand(m, n)`
   - `np.linspace(start, stop, num)`
   - `np.identity(m)`

**4. Array Attributes**
   - `a.ndim`
   - `a.shape`
   - `a.reshape(m, n)`
   - `a.size`
   - `a.itemsize`
   - `a.dtype`

**5. Array Operations**
   - Repetition: `a * 2`
   - Comparison: `a > 5`
   - Addition: `a1 + a2`
   - Multiplication: `a1 * a2`

**6. Array Functions**
   - `np.round()`
   - `np.max()`
   - `np.min()`
   - `np.sum()`
   - `np.prod()`
   - `np.mean()`
   - `np.median()`
   - `np.std()`
   - `np.var()`
   - `np.sin()`
   - `np.dot()`
   - `np.log()`
   - `np.exp()`
   - `np.floor()`
   - `np.ceil()`

**7. Indexing and Slicing**
**8. Iterating**
**9. Reshaping**
   - `np.reshape(m, n)`
   - `np.transpose()`
   - `a.T`
   - `a.ravel()`

**10. Stacking**
    - Horizontal
    - Vertical

**11. Splitting**
    - Horizontal
    - Vertical

**12. Advanced Indexing**
    - Fancy Indexing
    - Boolean Indexing

**13. Broadcasting**
    - The term broadcasting describes how NumPy treats arrays with different shapes during arithmetic operations.
    - Make the two arrays have the same number of dimensions.
    - Make each dimension of two arrays of the same size.

**14. Working with Mathematical Functions**
    - Sigmoid
    - Mean Squared Error
    - And many more functions...

**15. Working with Missing Values**
    - `~np.isnan(a)`

**16. Plotting a Graph**

**17. np.sort(a)**

**18. np.append(a, 500)**

**19. np.concatenate((c, d), axis=0 or 1)**

**20. np.unique(a)**

**21. np.expand_dims(a, axis=0/1)**

**22. np.where(condition, true, false)**

**23. np.argmax(a)**

**24. np.argmin(a)**

**25. np.cumsum(a)**

**26. np.cumprod(a)**

**27. np.percentile(a, value like 100 or 50)**

**28. np.histogram**

**29. np.corrcoef(a, b)**

**30. np.isin(a, items)**
 - Used for searching multiple items together

**31. np.flip(a)**
   - Reverse the order of array elements

**32. np.put(a, [index], [value])**

**33. np.delete(a, [index])**

**34. Set Functions**
   - `np.union1d`
   - `np.intersect1d`
   - `np.setdiff1d`
   - `np.setxor1d`
   - `np.in1d`

**35. np.clip(a, lower_limit, upper_limit)**
   - This function is used to limit the values in the array.

## Contributing

If you'd like to contribute to this repository, feel free to open an issue or submit a pull request. Contributions are welcome and appreciated!
