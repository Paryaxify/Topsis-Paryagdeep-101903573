# Topsis-Paryagdeep-101903573
TOPSIS is a method of compensatory aggregation that compares a set of alternatives by identifying weights for each criterion, normalising scores for each criterion and calculating the geometric distance between each alternative and the ideal alternative, which is the best score in each criterion. An assumption of TOPSIS is that the criteria are monotonically increasing or decreasing. Normalisation is usually required as the parameters or criteria are often of incongruous dimensions in multi-criteria problems

## Installation Instructions 
Supported version - Python 3.10
```
pip install Topsis-Paryagdeep-101903573
```

Running the package requires 4 arguments to be passed to the package-
- Input data file in ```.xlsx``` format
- Weights of each parameter (equal to the number of parameters)
- Impact of each parameter (equal to the number of output parameters)
- Output file name in ```.csv``` format

### Example 

Example command line argument -

```
Topsis-Paryagdeep-101903573 data.xlsx 1,1,2,1,1 +,+,-,-,+ output.csv
```

**Input File (data.xlsx) :**

![img.png](Images/img.png)

The resultant file will be saved as per the ``output file name`` that is passed in the command line. Must be ```csv``` file type.

**Output file (output.csv) :**

![img.png](Images/img2.png)

The output file will contain the **Topsis score** and **Rank** appended to the original dataset.


