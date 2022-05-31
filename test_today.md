# Test Rating Quality
BASE STACK: https://staging.api.trustlab.com
TEST STACK: https://staging.api.trustlab.com

| Dataset   | Status codes diff   | Misinformation[th.3] precision/recall diff   | Misinformation[th.4] precision/recall diff   | Misinformation[th.5] precision/recall diff   | Objectionable[th.3] precision/recall diff   | Objectionable[th.4] precision/recall diff   | Objectionable[th.5] precision/recall diff   | Controversial[th.3] precision/recall diff   | Controversial[th.4] precision/recall diff   | Controversial[th.5] precision/recall diff   |
|-----------|---------------------|----------------------------------------------|----------------------------------------------|----------------------------------------------|---------------------------------------------|---------------------------------------------|---------------------------------------------|---------------------------------------------|---------------------------------------------|---------------------------------------------|
| baseline  | {}                  | 0.000% / 0.000%                              | 0.000% / 0.000%                              | 0.000% / 0.000%                              | 0.000% / 0.000%                             | 0.000% / 0.000%                             | 0.000% / 0.000%                             | 0.000% / 0.000%                             | 0.000% / 0.000%                             | 0.000% / 0.000%                             |

## baseline
Status codes: {200: 4} -> {200: 4}
Average latency: 5.395 -> 6.973
#### Misinformation
| Endpoint   |   Threshold |   Precision |   Recall |   TP |   FP |   TN |   FN |
|------------|-------------|-------------|----------|------|------|------|------|
| base       |           3 |         0.5 |      0.5 |    1 |    1 |    1 |    1 |
| test       |           3 |         0.5 |      0.5 |    1 |    1 |    1 |    1 |
| base       |           4 |         1   |      0.5 |    1 |    0 |    1 |    1 |
| test       |           4 |         1   |      0.5 |    1 |    0 |    1 |    1 |
| base       |           5 |         1   |      0.5 |    1 |    0 |    1 |    1 |
| test       |           5 |         1   |      0.5 |    1 |    0 |    1 |    1 |

#### Objectionable
| Endpoint   |   Threshold |   Precision |   Recall | TP   | FP   | TN   | FN   |
|------------|-------------|-------------|----------|------|------|------|------|
| base       |           3 |           0 |        0 |      |      |      |      |
| test       |           3 |           0 |        0 |      |      |      |      |
| base       |           4 |           0 |        0 |      |      |      |      |
| test       |           4 |           0 |        0 |      |      |      |      |
| base       |           5 |           0 |        0 |      |      |      |      |
| test       |           5 |           0 |        0 |      |      |      |      |

#### Controversial
| Endpoint   |   Threshold |   Precision |   Recall | TP   | FP   | TN   | FN   |
|------------|-------------|-------------|----------|------|------|------|------|
| base       |           3 |           0 |        0 |      |      |      |      |
| test       |           3 |           0 |        0 |      |      |      |      |
| base       |           4 |           0 |        0 |      |      |      |      |
| test       |           4 |           0 |        0 |      |      |      |      |
| base       |           5 |           0 |        0 |      |      |      |      |
| test       |           5 |           0 |        0 |      |      |      |      |
