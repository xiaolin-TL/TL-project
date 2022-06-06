# Test Rating Quality

BASE ENDPOINT: https://staging.api.trustlab.com

TEST ENDPOINT: https://staging.api.trustlab.com




## Aggregate

Status codes: {200: 642, 504: 19} -> {200: 646, 504: 15}

Average latency: 9.182 -> 8.024

#### Misinformation

|   Threshold | Endpoint   |   Precision |   Recall |   TP |   FP |   TN |   FN |
|-------------|------------|-------------|----------|------|------|------|------|
|           3 | base       |           0 |        0 |    0 |  222 |  420 |    0 |
|             | test       |           0 |        0 |    0 |  229 |  417 |    0 |
|           4 | base       |           0 |        0 |    0 |  134 |  508 |    0 |
|             | test       |           0 |        0 |    0 |  140 |  506 |    0 |
|           5 | base       |           0 |        0 |    0 |   97 |  545 |    0 |
|             | test       |           0 |        0 |    0 |  100 |  546 |    0 |


| Dataset               | Status codes diff   | Misinformation[th.3] precision/recall diff   | Misinformation[th.4] precision/recall diff   | Misinformation[th.5] precision/recall diff   |
|-----------------------|---------------------|----------------------------------------------|----------------------------------------------|----------------------------------------------|
| benji_li              | {}                  | 0.000% / 0.000%                              | 0.000% / 0.000%                              | 0.000% / 0.000%                              |
| iterable              | {}                  | 0.000% / 0.000%                              | 0.000% / 0.000%                              | 0.000% / 0.000%                              |
| baseline              | {}                  | 0.000% / 0.000%                              | 0.000% / 0.000%                              | 0.000% / 0.000%                              |
| baseline_crs          | {504: 1}            | 0.000% / 0.000%                              | 0.000% / 0.000%                              | 0.000% / 0.000%                              |
| mmr_qa_1_31_22        | {504: 3}            | 0.000% / 0.000%                              | 0.000% / 0.000%                              | 0.000% / 0.000%                              |
| goldilocks_stratified | {}                  | 0.000% / 0.000%                              | 0.000% / 0.000%                              | 0.000% / 0.000%                              |
| goldilocks_random     | {}                  | 0.000% / 0.000%                              | 0.000% / 0.000%                              | 0.000% / 0.000%                              |


## benji_li

Status codes: {200: 90, 504: 10} -> {200: 90, 504: 10}

Average latency: 13.314 -> 13.998

#### Misinformation

|   Threshold | Endpoint   |   Precision |   Recall |   TP |   FP |   TN |   FN |
|-------------|------------|-------------|----------|------|------|------|------|
|           3 | base       |           0 |        0 |    0 |   48 |   42 |    0 |
|             | test       |           0 |        0 |    0 |   49 |   41 |    0 |
|           4 | base       |           0 |        0 |    0 |   32 |   58 |    0 |
|             | test       |           0 |        0 |    0 |   34 |   56 |    0 |
|           5 | base       |           0 |        0 |    0 |   26 |   64 |    0 |
|             | test       |           0 |        0 |    0 |   28 |   62 |    0 |


## iterable

Status codes: {200: 79} -> {200: 79}

Average latency: 9.869 -> 9.199

#### Misinformation

|   Threshold | Endpoint   |   Precision |   Recall |   TP |   FP |   TN |   FN |
|-------------|------------|-------------|----------|------|------|------|------|
|           3 | base       |           0 |        0 |    0 |   31 |   48 |    0 |
|             | test       |           0 |        0 |    0 |   31 |   48 |    0 |
|           4 | base       |           0 |        0 |    0 |    8 |   71 |    0 |
|             | test       |           0 |        0 |    0 |    8 |   71 |    0 |
|           5 | base       |           0 |        0 |    0 |    1 |   78 |    0 |
|             | test       |           0 |        0 |    0 |    1 |   78 |    0 |


## baseline

Status codes: {200: 42, 504: 1} -> {200: 42, 504: 1}

Average latency: 13.181 -> 10.912

#### Misinformation

|   Threshold | Endpoint   |   Precision |   Recall |   TP |   FP |   TN |   FN |
|-------------|------------|-------------|----------|------|------|------|------|
|           3 | base       |           0 |        0 |    0 |   30 |   12 |    0 |
|             | test       |           0 |        0 |    0 |   32 |   10 |    0 |
|           4 | base       |           0 |        0 |    0 |   22 |   20 |    0 |
|             | test       |           0 |        0 |    0 |   24 |   18 |    0 |
|           5 | base       |           0 |        0 |    0 |   14 |   28 |    0 |
|             | test       |           0 |        0 |    0 |   16 |   26 |    0 |


## baseline_crs

Status codes: {200: 34, 504: 5} -> {200: 35, 504: 4}

Average latency: 13.415 -> 13.622

#### Misinformation

|   Threshold | Endpoint   |   Precision |   Recall |   TP |   FP |   TN |   FN |
|-------------|------------|-------------|----------|------|------|------|------|
|           3 | base       |           0 |        0 |    0 |   23 |   11 |    0 |
|             | test       |           0 |        0 |    0 |   25 |   10 |    0 |
|           4 | base       |           0 |        0 |    0 |   18 |   16 |    0 |
|             | test       |           0 |        0 |    0 |   20 |   15 |    0 |
|           5 | base       |           0 |        0 |    0 |   13 |   21 |    0 |
|             | test       |           0 |        0 |    0 |   12 |   23 |    0 |


## mmr_qa_1_31_22

Status codes: {200: 97, 504: 3} -> {200: 100}

Average latency: 11.832 -> 9.516

#### Misinformation

|   Threshold | Endpoint   |   Precision |   Recall |   TP |   FP |   TN |   FN |
|-------------|------------|-------------|----------|------|------|------|------|
|           3 | base       |           0 |        0 |    0 |   54 |   43 |    0 |
|             | test       |           0 |        0 |    0 |   56 |   44 |    0 |
|           4 | base       |           0 |        0 |    0 |   30 |   67 |    0 |
|             | test       |           0 |        0 |    0 |   30 |   70 |    0 |
|           5 | base       |           0 |        0 |    0 |   20 |   77 |    0 |
|             | test       |           0 |        0 |    0 |   20 |   80 |    0 |


## goldilocks_stratified

Status codes: {200: 50} -> {200: 50}

Average latency: 6.916 -> 4.833

#### Misinformation

|   Threshold | Endpoint   |   Precision |   Recall |   TP |   FP |   TN |   FN |
|-------------|------------|-------------|----------|------|------|------|------|
|           3 | base       |           0 |        0 |    0 |   11 |   39 |    0 |
|             | test       |           0 |        0 |    0 |   11 |   39 |    0 |
|           4 | base       |           0 |        0 |    0 |    7 |   43 |    0 |
|             | test       |           0 |        0 |    0 |    7 |   43 |    0 |
|           5 | base       |           0 |        0 |    0 |    7 |   43 |    0 |
|             | test       |           0 |        0 |    0 |    7 |   43 |    0 |


## goldilocks_random

Status codes: {200: 250} -> {200: 250}

Average latency: 5.356 -> 3.935

#### Misinformation

|   Threshold | Endpoint   |   Precision |   Recall |   TP |   FP |   TN |   FN |
|-------------|------------|-------------|----------|------|------|------|------|
|           3 | base       |           0 |        0 |    0 |   25 |  225 |    0 |
|             | test       |           0 |        0 |    0 |   25 |  225 |    0 |
|           4 | base       |           0 |        0 |    0 |   17 |  233 |    0 |
|             | test       |           0 |        0 |    0 |   17 |  233 |    0 |
|           5 | base       |           0 |        0 |    0 |   16 |  234 |    0 |
|             | test       |           0 |        0 |    0 |   16 |  234 |    0 |


