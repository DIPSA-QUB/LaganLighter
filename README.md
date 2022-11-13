# [LaganLighter:  Structure-Aware High-Performance Graph Algorithms](https://blogs.qub.ac.uk/GraphProcessing/LaganLighter/)

This repository contains the soure code of the LaganLighter project: https://blogs.qub.ac.uk/GraphProcessing/LaganLighter .

## Algorithms in This Repo
 - [SAPCo Sort](https://blogs.qub.ac.uk/graphprocessing/sapco-sort-optimizing-degree-ordering-for-power-law-graphs/): `alg1_sapco_sort` 
 - Other algorithms are going to be added soon. 

## Requirements
The `libnuma`, `openmp`, and `papi` are required.

## Compiling and Executing Code
 - If you want to use special version of `gcc` compiler please modify Line 1 of the `Makefile`.
 - Please modify Line 6 if the required libraries are not in the path.
 - Run `make alg...` (e.g. `make alg1_sapco_sort`). This builds the executible file and runs it for the test graph. To run it for other graphs, add the path to your graph as the argument.
 - To disable hyper-threading, please use `no_ht=1` with make.
 - To enable debugging (-g of gcc), use `debug=1`.

## Graph Types
We support different types of the graphs:
 - Graphs in txt format, for testing, e.g. `data/test_csr.txt`
 - [WebGraph](https://law.di.unimi.it/datasets.php) format
 - Binary format

## Bugs & Support
As "We write bugs that in special cases work correctly", we always try to evaluate and validate the algorithms and implementation. If you have received wrong results or you are suspicious about parts of the code, please [contact us](https://blogs.qub.ac.uk/GraphProcessing/LaganLighter). 

## Fundings
The project LaganLighter leading to this Software has been supported by:
 - PhD scholarship from The Department for the Economy, Northern Ireland and The Queen’s University Belfast 
 - Kelvin-2 supercomputer (EPSRC grant EP/T022175/1) 
 - DiPET (CHIST-ERA-18-SDCDN-002, EPSRC grant EP/T022345/1) 

## LICENSE
Licensed under the GNU v3 General Public License, as published by the Free Software Foundation. You must not use this Software except in compliance with the terms of the License. Unless required by applicable law or agreed upon in writing, this Software is distributed on an "AS IS" BASIS, WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE, neither express nor implied. For details see terms of the License (see attached file: LICENSE). The License is also available at

#### Copyright 2020-2022 The Queen's University of Belfast, Northern Ireland
