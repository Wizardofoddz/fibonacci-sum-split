# fibonacci-sum-split

Split up the fibonacci-sum work into several inputs that can be computed in parallel

Given a position N, this application prints all positions from 1 to N in JSON to stdout, and exits with a status code of 0.

For example:

```shell
echo 1 | fibonacci-sum-split
#> [1]

echo 5 | fibonacci-sum-split
#> [1,2,3,4,5]
```
