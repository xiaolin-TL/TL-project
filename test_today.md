# Test Rating Quality
BASE ENDPOINT: https://staging.api.trustlab.com
TEST ENDPOINT: https://staging.api.trustlab.com


| Dataset   | Status codes diff   | Misinformation[th.3] precision/recall diff   | Misinformation[th.4] precision/recall diff   | Misinformation[th.5] precision/recall diff   | Objectionable[th.3] precision/recall diff   | Objectionable[th.4] precision/recall diff   | Objectionable[th.5] precision/recall diff   | Controversial[th.3] precision/recall diff   | Controversial[th.4] precision/recall diff   | Controversial[th.5] precision/recall diff   |
|-----------|---------------------|----------------------------------------------|----------------------------------------------|----------------------------------------------|---------------------------------------------|---------------------------------------------|---------------------------------------------|---------------------------------------------|---------------------------------------------|---------------------------------------------|
| benji_li  | {504: 2}            | 0.000% / 0.000%                              | 0.000% / 0.000%                              | 0.000% / 0.000%                              | 0.000% / 0.000%                             | 0.000% / 0.000%                             | 0.000% / 0.000%                             | 0.000% / 0.000%                             | 0.000% / 0.000%                             | 0.000% / 0.000%                             |
| iterable  | {504: 3}            | 0.000% / 0.000%                              | 0.000% / 0.000%                              | 0.000% / 0.000%                              | 0.000% / 0.000%                             | 0.000% / 0.000%                             | 0.000% / 0.000%                             | 0.000% / 0.000%                             | 0.000% / 0.000%                             | 0.000% / 0.000%                             |
| baseline  | {200: 2}            | 0.000% / 0.000%                              | 0.000% / 0.000%                              | 0.000% / 0.000%                              | 0.000% / 0.000%                             | 0.000% / 0.000%                             | 0.000% / 0.000%                             | 0.000% / 0.000%                             | 0.000% / 0.000%                             | 0.000% / 0.000%                             |


## benji_li
Status codes: {200: 91, 504: 9} -> {200: 93, 504: 7}
Average latency: 13.182 -> 12.662
#### Misinformation
|   Threshold | Endpoint   |   Precision |   Recall |   TP |   FP |   TN |   FN |
|-------------|------------|-------------|----------|------|------|------|------|
|           3 | base       |           0 |        0 |    0 |   47 |   44 |    0 |
|             | test       |           0 |        0 |    0 |   47 |   46 |    0 |
|           4 | base       |           0 |        0 |    0 |   29 |   62 |    0 |
|             | test       |           0 |        0 |    0 |   28 |   65 |    0 |
|           5 | base       |           0 |        0 |    0 |   25 |   66 |    0 |
|             | test       |           0 |        0 |    0 |   24 |   69 |    0 |

#### Objectionable
|   Threshold | Endpoint   |   Precision |   Recall |   TP |   FP |   TN |   FN |
|-------------|------------|-------------|----------|------|------|------|------|
|           3 | base       |           0 |        0 |    0 |    0 |   91 |    0 |
|             | test       |           0 |        0 |    0 |    0 |   93 |    0 |
|           4 | base       |           0 |        0 |    0 |    0 |   91 |    0 |
|             | test       |           0 |        0 |    0 |    0 |   93 |    0 |
|           5 | base       |           0 |        0 |    0 |    0 |   91 |    0 |
|             | test       |           0 |        0 |    0 |    0 |   93 |    0 |

#### Controversial
|   Threshold | Endpoint   |   Precision |   Recall |   TP |   FP |   TN |   FN |
|-------------|------------|-------------|----------|------|------|------|------|
|           3 | base       |           0 |        0 |    0 |    0 |   91 |    0 |
|             | test       |           0 |        0 |    0 |    0 |   93 |    0 |
|           4 | base       |           0 |        0 |    0 |    0 |   91 |    0 |
|             | test       |           0 |        0 |    0 |    0 |   93 |    0 |
|           5 | base       |           0 |        0 |    0 |    0 |   91 |    0 |
|             | test       |           0 |        0 |    0 |    0 |   93 |    0 |

## iterable
Status codes: {200: 76, 504: 3} -> {200: 79}
Average latency: 10.612 -> 10.671
#### Misinformation
|   Threshold | Endpoint   |   Precision |   Recall |   TP |   FP |   TN |   FN |
|-------------|------------|-------------|----------|------|------|------|------|
|           3 | base       |           0 |        0 |    0 |   27 |   49 |    0 |
|             | test       |           0 |        0 |    0 |   29 |   50 |    0 |
|           4 | base       |           0 |        0 |    0 |    6 |   70 |    0 |
|             | test       |           0 |        0 |    0 |    7 |   72 |    0 |
|           5 | base       |           0 |        0 |    0 |    2 |   74 |    0 |
|             | test       |           0 |        0 |    0 |    2 |   77 |    0 |

#### Objectionable
|   Threshold | Endpoint   |   Precision |   Recall |   TP |   FP |   TN |   FN |
|-------------|------------|-------------|----------|------|------|------|------|
|           3 | base       |           0 |        0 |    0 |    2 |   74 |    0 |
|             | test       |           0 |        0 |    0 |    2 |   77 |    0 |
|           4 | base       |           0 |        0 |    0 |    1 |   75 |    0 |
|             | test       |           0 |        0 |    0 |    1 |   78 |    0 |
|           5 | base       |           0 |        0 |    0 |    0 |   76 |    0 |
|             | test       |           0 |        0 |    0 |    0 |   79 |    0 |

#### Controversial
|   Threshold | Endpoint   |   Precision |   Recall |   TP |   FP |   TN |   FN |
|-------------|------------|-------------|----------|------|------|------|------|
|           3 | base       |           0 |        0 |    0 |    4 |   72 |    0 |
|             | test       |           0 |        0 |    0 |    4 |   75 |    0 |
|           4 | base       |           0 |        0 |    0 |    0 |   76 |    0 |
|             | test       |           0 |        0 |    0 |    0 |   79 |    0 |
|           5 | base       |           0 |        0 |    0 |    0 |   76 |    0 |
|             | test       |           0 |        0 |    0 |    0 |   79 |    0 |

## baseline
Status codes: {200: 38, 504: 5} -> {200: 36, 504: 7}
Average latency: 13.461 -> 13.646
#### Misinformation
|   Threshold | Endpoint   |   Precision |   Recall |   TP |   FP |   TN |   FN |
|-------------|------------|-------------|----------|------|------|------|------|
|           3 | base       |           0 |        0 |    0 |   27 |   11 |    0 |
|             | test       |           0 |        0 |    0 |   27 |    9 |    0 |
|           4 | base       |           0 |        0 |    0 |   20 |   18 |    0 |
|             | test       |           0 |        0 |    0 |   21 |   15 |    0 |
|           5 | base       |           0 |        0 |    0 |   13 |   25 |    0 |
|             | test       |           0 |        0 |    0 |   15 |   21 |    0 |

#### Objectionable
|   Threshold | Endpoint   |   Precision |   Recall |   TP |   FP |   TN |   FN |
|-------------|------------|-------------|----------|------|------|------|------|
|           3 | base       |           0 |        0 |    0 |    0 |   38 |    0 |
|             | test       |           0 |        0 |    0 |    0 |   36 |    0 |
|           4 | base       |           0 |        0 |    0 |    0 |   38 |    0 |
|             | test       |           0 |        0 |    0 |    0 |   36 |    0 |
|           5 | base       |           0 |        0 |    0 |    0 |   38 |    0 |
|             | test       |           0 |        0 |    0 |    0 |   36 |    0 |

#### Controversial
|   Threshold | Endpoint   |   Precision |   Recall |   TP |   FP |   TN |   FN |
|-------------|------------|-------------|----------|------|------|------|------|
|           3 | base       |           0 |        0 |    0 |    0 |   38 |    0 |
|             | test       |           0 |        0 |    0 |    0 |   36 |    0 |
|           4 | base       |           0 |        0 |    0 |    0 |   38 |    0 |
|             | test       |           0 |        0 |    0 |    0 |   36 |    0 |
|           5 | base       |           0 |        0 |    0 |    0 |   38 |    0 |
|             | test       |           0 |        0 |    0 |    0 |   36 |    0 |


