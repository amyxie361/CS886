# CS886
University of Waterloo CS886 19w

## origin

| model | bi | mask | precision | recall | f1 | n_correct | n_gold | n_predicted |
|-------|----|------|-----------|--------|----|-----------|--------|-------------|
| lstm  | T  | F    | 84.82     | 83.60  | 84.20| 8055    | 9635   | 9497        |
| lstm  | F  | F    | 72.47     | 73.88  | 73.17| 7118    | 9635   | 9822        |
| mlp   | T  | F    | 54.97     | 75.65  | 63.67| 7289    | 9635   | 13261       |
| mlp   | F  | F    | 60.80     | 61.75  | 61.27| 5950    | 9635   | 9786        |
| lstm  | T  | T    | 64.53     | 33.74  | 44.31| 3251    | 9635   | 9635        |
| lstm  | F  | T    | 67.01     | 27.98  | 39.48| 2696    | 9635   | 4023        |
| mlp   | T  | T    | 71.37     | 93.82  | 81.07| 9040    | 9635   | 12667       |
| mlp   | F  | T    | 0         | 0      | 0    | 0       | 0      | 0           |



