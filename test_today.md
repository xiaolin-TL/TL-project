# Test Rating Quality
BASE STACK: https://staging.api.trustlab.com
TEST STACK: https://staging.api.trustlab.com

| Dataset   | Status codes diff   | Misinformation[th.3] precision/recall diff   | Misinformation[th.4] precision/recall diff   | Misinformation[th.5] precision/recall diff   | Objectionable[th.3] precision/recall diff   | Objectionable[th.4] precision/recall diff   | Objectionable[th.5] precision/recall diff   | Controversial[th.3] precision/recall diff   | Controversial[th.4] precision/recall diff   | Controversial[th.5] precision/recall diff   |
|-----------|---------------------|----------------------------------------------|----------------------------------------------|----------------------------------------------|---------------------------------------------|---------------------------------------------|---------------------------------------------|---------------------------------------------|---------------------------------------------|---------------------------------------------|
| baseline  | {}                  | 0.000% / 0.000%                              | 0.000% / 0.000%                              | 0.000% / 0.000%                              | 0.000% / 0.000%                             | 0.000% / 0.000%                             | 0.000% / 0.000%                             | 0.000% / 0.000%                             | 0.000% / 0.000%                             | 0.000% / 0.000%                             |

## baseline
Status codes: {200: 4} -> {200: 4}
Average latency: 4.892 -> 8.789
#### Misinformation at Threshold 3
| Endpoint   |   Threshold |   Precision |   Recall |   TP |   FP |   TN |   FN |
|------------|-------------|-------------|----------|------|------|------|------|
| base       |           3 |           1 |        1 |    3 |    0 |    3 |    0 |
| test       |           3 |           1 |        1 |    3 |    0 |    3 |    0 |

#### Misinformation at Threshold 4
| Endpoint   |   Threshold |   Precision |   Recall |   TP |   FP |   TN |   FN |
|------------|-------------|-------------|----------|------|------|------|------|
| base       |           4 |           1 | 0.666667 |    2 |    0 |    2 |    1 |
| test       |           4 |           1 | 0.666667 |    2 |    0 |    2 |    1 |

#### Misinformation at Threshold 5
| Endpoint   |   Threshold |   Precision |   Recall |   TP |   FP |   TN |   FN |
|------------|-------------|-------------|----------|------|------|------|------|
| base       |           5 |           1 | 0.666667 |    2 |    0 |    2 |    1 |
| test       |           5 |           1 | 0.666667 |    2 |    0 |    2 |    1 |

#### Objectionable at Threshold 3
| Endpoint   |   Threshold |   Precision |   Recall | TP   | FP   | TN   | FN   |
|------------|-------------|-------------|----------|------|------|------|------|
| base       |           3 |           0 |        0 |      |      |      |      |
| test       |           3 |           0 |        0 |      |      |      |      |

#### Objectionable at Threshold 4
| Endpoint   |   Threshold |   Precision |   Recall | TP   | FP   | TN   | FN   |
|------------|-------------|-------------|----------|------|------|------|------|
| base       |           4 |           0 |        0 |      |      |      |      |
| test       |           4 |           0 |        0 |      |      |      |      |

#### Objectionable at Threshold 5
| Endpoint   |   Threshold |   Precision |   Recall | TP   | FP   | TN   | FN   |
|------------|-------------|-------------|----------|------|------|------|------|
| base       |           5 |           0 |        0 |      |      |      |      |
| test       |           5 |           0 |        0 |      |      |      |      |

#### Controversial at Threshold 3
| Endpoint   |   Threshold |   Precision |   Recall | TP   | FP   | TN   | FN   |
|------------|-------------|-------------|----------|------|------|------|------|
| base       |           3 |           0 |        0 |      |      |      |      |
| test       |           3 |           0 |        0 |      |      |      |      |

#### Controversial at Threshold 4
| Endpoint   |   Threshold |   Precision |   Recall | TP   | FP   | TN   | FN   |
|------------|-------------|-------------|----------|------|------|------|------|
| base       |           4 |           0 |        0 |      |      |      |      |
| test       |           4 |           0 |        0 |      |      |      |      |

#### Controversial at Threshold 5
| Endpoint   |   Threshold |   Precision |   Recall | TP   | FP   | TN   | FN   |
|------------|-------------|-------------|----------|------|------|------|------|
| base       |           5 |           0 |        0 |      |      |      |      |
| test       |           5 |           0 |        0 |      |      |      |      |
