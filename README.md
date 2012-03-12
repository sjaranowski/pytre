# pytre

## USAGE
pytre [-h] file1 [file2...]

## DESCRIPTION
**pytre** is a small, command-line program, that extracts data (see
**OUTPUT**) from "trn" files (output of Fluent).

## OPTIONS
    -h        show this help message and exit
              ('-h' can follow list of files or appear anywhere inside it)

## OUTPUT
Description of output (table with following columns, left to right):

1. number of cores

2. number of repeats

3. scaled CSR (perfect speedup)

4. maximum CSR (best rate through all of the experiments)

5. maximum absolute deviation (of CSR)

6. naive standard deviation (of CSR)

7. minimum walltime (can be counted from maximum CSR)

8. file that hit the best result
