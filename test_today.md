# Test Rating Quality
BASE STACK: https://staging.api.trustlab.com
TEST STACK: https://staging.api.trustlab.com

| Dataset           | Status codes diff   | Misinformation[th.3] precision/recall diff   | Misinformation[th.4] precision/recall diff   | Misinformation[th.5] precision/recall diff   | Objectionable[th.3] precision/recall diff   | Objectionable[th.4] precision/recall diff   | Objectionable[th.5] precision/recall diff   | Controversial[th.3] precision/recall diff   | Controversial[th.4] precision/recall diff   | Controversial[th.5] precision/recall diff   |
|-------------------|---------------------|----------------------------------------------|----------------------------------------------|----------------------------------------------|---------------------------------------------|---------------------------------------------|---------------------------------------------|---------------------------------------------|---------------------------------------------|---------------------------------------------|
| baseline          | {}                  | 0.000% / 0.000%                              | 0.000% / 0.000%                              | 0.000% / 0.000%                              | 0.000% / 0.000%                             | 0.000% / 0.000%                             | 0.000% / 0.000%                             | 0.000% / 0.000%                             | 0.000% / 0.000%                             | 0.000% / 0.000%                             |
| goldilocks_random | {}                  | 0.000% / 0.000%                              | 0.000% / 0.000%                              | 0.000% / 0.000%                              | 0.000% / 0.000%                             | 0.000% / 0.000%                             | 0.000% / 0.000%                             | 0.000% / 0.000%                             | 0.000% / 0.000%                             | 0.000% / 0.000%                             |

## baseline
Status codes: {200: 4} -> {200: 4}
Average latency: 7.15 -> 6.535
#### Misinformation
|   Threshold | Endpoint   |   Precision |   Recall |   TP |   FP |   TN |   FN |
|-------------|------------|-------------|----------|------|------|------|------|
|           3 | base       |    0.666667 |      1   |    2 |    1 |    2 |    0 |
|             | test       |    0.666667 |      1   |    2 |    1 |    2 |    0 |
|           4 | base       |    0.5      |      0.5 |    1 |    1 |    1 |    1 |
|             | test       |    0.5      |      0.5 |    1 |    1 |    1 |    1 |
|           5 | base       |    1        |      0.5 |    1 |    0 |    1 |    1 |
|             | test       |    1        |      0.5 |    1 |    0 |    1 |    1 |

#### Objectionable
|   Threshold | Endpoint   |   Precision |   Recall | TP   | FP   | TN   | FN   |
|-------------|------------|-------------|----------|------|------|------|------|
|           3 | base       |           0 |        0 |      |      |      |      |
|             | test       |           0 |        0 |      |      |      |      |
|           4 | base       |           0 |        0 |      |      |      |      |
|             | test       |           0 |        0 |      |      |      |      |
|           5 | base       |           0 |        0 |      |      |      |      |
|             | test       |           0 |        0 |      |      |      |      |

#### Controversial
|   Threshold | Endpoint   |   Precision |   Recall | TP   | FP   | TN   | FN   |
|-------------|------------|-------------|----------|------|------|------|------|
|           3 | base       |           0 |        0 |      |      |      |      |
|             | test       |           0 |        0 |      |      |      |      |
|           4 | base       |           0 |        0 |      |      |      |      |
|             | test       |           0 |        0 |      |      |      |      |
|           5 | base       |           0 |        0 |      |      |      |      |
|             | test       |           0 |        0 |      |      |      |      |

## goldilocks_random
Status codes: {200: 12} -> {200: 12}
Average latency: 5.109 -> 3.163
#### Misinformation
|   Threshold | Endpoint   |   Precision |   Recall | TP   | FP   | TN   | FN   |
|-------------|------------|-------------|----------|------|------|------|------|
|           3 | base       |           0 |        0 |      |      |      |      |
|             | test       |           0 |        0 |      |      |      |      |
|           4 | base       |           0 |        0 |      |      |      |      |
|             | test       |           0 |        0 |      |      |      |      |
|           5 | base       |           0 |        0 |      |      |      |      |
|             | test       |           0 |        0 |      |      |      |      |

#### Objectionable
|   Threshold | Endpoint   |   Precision |   Recall | TP   | FP   | TN   | FN   |
|-------------|------------|-------------|----------|------|------|------|------|
|           3 | base       |           0 |        0 |      |      |      |      |
|             | test       |           0 |        0 |      |      |      |      |
|           4 | base       |           0 |        0 |      |      |      |      |
|             | test       |           0 |        0 |      |      |      |      |
|           5 | base       |           0 |        0 |      |      |      |      |
|             | test       |           0 |        0 |      |      |      |      |

#### Controversial
|   Threshold | Endpoint   |   Precision |   Recall | TP   | FP   | TN   | FN   |
|-------------|------------|-------------|----------|------|------|------|------|
|           3 | base       |           0 |        0 |      |      |      |      |
|             | test       |           0 |        0 |      |      |      |      |
|           4 | base       |           0 |        0 |      |      |      |      |
|             | test       |           0 |        0 |      |      |      |      |
|           5 | base       |           0 |        0 |      |      |      |      |
|             | test       |           0 |        0 |      |      |      |      |
