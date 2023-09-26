# mat2np

Saves a MATLAB 1-D, 2-D, or 3-D array as a pickled NumPy array

## Example Usage

In MATLAB :

```matlab
a = [ 1.2, 3.5, 4.3 ];
mat2np(a, 'a.pkl', 'float64')
```

Then in Python :

```python
import pickle
with open('a.pkl', 'rb') as fin :
    a = pickle.load(fin)
```

## License

See [license.txt](license.txt)
