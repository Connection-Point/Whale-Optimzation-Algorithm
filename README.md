# What is Whale Optimization Algorithm (WOA). 
An optimisation algorithm named after the humpback whale's bubble-net feeding strategy is called the Whale Optimisation Algorithm (WOA). It was first proposed in 2016 by Mirjalili and Lewis. The WOA algorithm generates a pool of solutions at random. The following three operators are applied to each answer at each iteration:
In a lightning search, a solution is selected at random, and the current solution is adjusted so that it moves closer to the selected solution. In an encircling search, the present solution is modified by iteratively approaching the optimal solution. To improve upon the existing solution, a bubble-net feeding search selects a solution at random that is closer to the optimal solution.
Multiple optimisation issues, such as those involving function optimisation, scheduling, and image processing, have been successfully tackled using the WOA method.

The WOA algorithm has a number of benefits, including those listed below.
1.	It may be implemented quickly and is straightforward to comprehend.
2.	It is not necessary to know anything about gradients.
3.	It can function outside of local optimums.
4.	It is applicable to numerous optimisation issues.

Some drawbacks of the WOA algorithm are as follows:
1.	It's possible that other optimisation strategies do better.
2.	Some problems may be beyond its ability to solve.

The WOA algorithm, in its whole, is an exciting new metaheuristic optimisation method with the potential to be applied to many different types of optimisation problems.


## Dependency Needed

Numpy for N-dimensional array object:

```bash
pip install numpy
```
Matplotlib for creating static, animated, and interactive visualizations.

```
pip install matplotlib
```
SciPy for numerical integration and optimization
```
pip install scipy
```

## Usage
To run the Whale Optimization Algorithm, you can either enter one of the command in terminal or directly press [Ctrl + Shift + F10] if you're using PyCharm.
```python
python3 run.py || python run.py 

```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
