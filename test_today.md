# Test Rating Quality
BASE STACK: https://staging.api.trustlab.com
TEST STACK: https://staging.api.trustlab.com
| Dataset   | Status codes diff   | Misinformation[th.3]
precision/recall diff                 | Objectionable[th.3]
precision/recall diff                 | Controversial[th.3]
precision/recall diff                 |
|-----------|---------------------|-----------------|-----------------|-----------------|
| baseline  | {}                  | 0.000% / 0.000% | 0.000% / 0.000% | 0.000% / 0.000% |

## baseline
Status codes: {200: 4} -> {200: 4}
Average latency: 7.656 -> 10.221
#### Misinformation at Threshold 3
| Endpoint   |   Precision |   Recall |   TP |   FP |   TN |   FN |
|------------|-------------|----------|------|------|------|------|
| base       |         0.5 |      0.5 |    1 |    1 |    1 |    1 |
| test       |         0.5 |      0.5 |    1 |    1 |    1 |    1 |

#### Objectionable at Threshold 3
| Endpoint   |   Precision |   Recall | TP   | FP   | TN   | FN   |
|------------|-------------|----------|------|------|------|------|
| base       |           0 |        0 |      |      |      |      |
| test       |           0 |        0 |      |      |      |      |

#### Controversial at Threshold 3
| Endpoint   |   Precision |   Recall | TP   | FP   | TN   | FN   |
|------------|-------------|----------|------|------|------|------|
| base       |           0 |        0 |      |      |      |      |
| test       |           0 |        0 |      |      |      |      |
