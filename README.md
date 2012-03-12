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
 <number of cores>
 <number of repeats>
 <scaled CSR (perfect speedup)>
 <maximum CSR (best rate through all of the experiments)>
 <maximum absolute deviation (of CSR)>
 <naive standard deviation (of CSR)>
 <minimum walltime (can be counted from maximum CSR)>
 <file that hit the best result>

