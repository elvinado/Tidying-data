# Tidying-data
 Tidying excel file using Pandas

## Skills you will learn from this example may be as follow:
1. Loading excel files to pandas dataframe
2. Basics of slicing and other operation in pandas
3. Using simple regex as pattern searching tool
4. Creating a complex loops (5 layers deep)
5. Quick and dirty plotting

## Primary motivation is to transform excel tables into a tidy data as describe follows (based on Tidy Data Structure by Hadley Wickam):
1. Each variable is a column (with uniform type format, ie. str, int, float)
2. Each observation is a row
3. Each type of observation unit has its own table

## Our dummy data has properties as follows (all values are randomly generated):
1. 2 types of material (A,B)
2. 5 sizes of material (1" - 5")
3. 2 frequencies subjected to the material
4. 3 observation units (Alpha, Beta, Gamma)
5. Physical configuration of material (A,B)