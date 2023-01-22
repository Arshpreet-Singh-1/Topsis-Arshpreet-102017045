# Background 

## Mupltiple Critiera Decision Making (MCDM) using TOPSIS

## Program Run below Steps :

1. Convert categorical to numeric
2. Vector Normalization
   2.1. Calculate Root of Sum of Squares
   2.2. Find Normalized Decision Metrix - Divide every column value its Root of Sum of Squares.Value in every cell is known as Normalized performance value
3. Weight Assignment ( Calculate Weight × Normalized performance value )
4. Find Ideal Best and Ideal Worst
5. Calculate Euclidean distance from ideal best value and ideal worst value
6. Calculate Performance Score and Rank

## Input  -
- Input file must contain three or more columns
- First column is the object/variable name (e.g. M1, M2, M3, M4…...)
- From 2nd to last columns contain numeric values only

## Output - 
- Result file contains all the columns of input file and two additional columns having 
Topsis Score and Rank

## Program check for 
- Correct number of parameters (inputFileName, Weights, Impacts, resultFileName).
- Show the appropriate message for wrong inputs.
- Handling of “File not Found” exception
- Input file must contain three or more columns.
- From 2nd to last columns must contain numeric values only (Handling of non-numeric values)
- Number of weights, number of impacts and number of columns (from 2nd to last columns) must 
be same.
- Impacts must be either +ve or -ve.
- Impacts and weights must be separated by ‘,’ (comma).

-----------------------------------------

# Installation
Use the package manager pip to install Topsis-Garima-102017070.

### `pip install Topsis-Arshpreet-102017045`
-----------------------------------------
# Usage
Enter csv filename followed by .csv extension, then enter the weights vector with vector values separated by commas, followed by the impacts vector with comma separated signs (+,-) and the csv file where result is to be stored.

### `Topsis 102017045-data.csv 1,1,2,1,1 +,+,+,-,+ 102017045-result.csv`
-----------------------------------------
License
© 2023 Arshpreet Singh

This repository is licensed under the MIT license. See LICENSE for details.
