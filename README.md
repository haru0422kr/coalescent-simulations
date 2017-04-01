# Coalescent Simulations
Simulates different coalescents

* First Implementation : 2015 ~ 2016 Academic year

* Current Status : March 2017 ~

## Dependencies

* Python 3.6
* Requirements:
  * biopython==1.68
  * matplotlib==2.0.0
  * numpy==1.12.0
  * scikit-learn==0.18.1
  * scipy==0.19.0

## Usage
1. Model test

```
python main.py -t
```


* Produces a single tree for Kingman and Bolthausen-Sznitman
* Current default setting (currently, not open to user input):
  * Sample Size: 10
  * Mutation Rate: 0.9
  * Number of Iterations: 1

try:
```
python main.py --test --num_iter 500 --sample_size 30
```
