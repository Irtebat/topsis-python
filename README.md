# topsis-python
Topsis analysis of a csv file

## About Topsis

The Technique for Order of Preference by Similarity to Ideal Solution (TOPSIS) is a multi-criteria decision analysis method, which was originally developed by Ching-Lai Hwang and Yoon in 1981 with further developments by Yoon in 1987, and Hwang, Lai and Liu in 1993. TOPSIS is based on the concept that the chosen alternative should have the shortest geometric distance from the positive ideal solution (PIS) and the longest geometric distance from the negative ideal solution (NIS).

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install topsis-Irtebat.

```bash
pip install topsis-Irtebat
```

## Usage

Following query on terminal will provide you the topsis analysis for input csv file.

```
topsis -n "dataset-name.csv" -w "w1,w2,w3,w4,..." -i "i1,i2,i3,i4,..."

```

w1,w2,w3,w4 represent weights, and i1,i2,i3,i4 represent impacts where 1 is used for maximize and 0 for minimize. 
Size of w and i is equal to number of features. 

Note that the first row and first column of dataset is dropped

Rank 1 signifies best decision

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
