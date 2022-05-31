# Compare https://staging.api.trustlab.com to https://staging.api.trustlab.com
|          |    | Dataset         | Status codes diff   | Misinformation[th 3]
precision/recall diff                 |
|----------|----|-----------------|---------------------|-----------------|
| baseline | {} | 0.000% / 0.000% | 0.000% / 0.000%     | 0.000% / 0.000% |

## baseline
Status codes: {200: 4} -> {200: 4}
Average latency: 6.918 -> 10.161
#### Misinformation at Threshold 3
| Endpoint   |   Precision |   Recall |   TP |   FP |   TN |   FN |
|------------|-------------|----------|------|------|------|------|
| base       |           1 |        1 |    3 |    0 |    3 |    0 |
| test       |           1 |        1 |    3 |    0 |    3 |    0 |

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
