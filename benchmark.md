[WIP]

### v1 only, multi-scale

| backbone   | loss    | Public LB | Private LB |   oxford5k |   paris6k |   roxford5k-mapE |   roxford5k-mapM |   roxford5k-mapH |   rparis6k-mapE |   rparis6k-mapM |   rparis6k-mapH |
|-----------:|:--------|:----------|:-----------|-----------:|----------:|-----------------:|-----------------:|-----------------:|----------------:|----------------:|----------------:|
| ResNet-50  | arcface | 18.04     | 20.78      |      87.78 |     92.16 |            82.46 |            66.46 |            41.78 |           90.54 |           80.76 |           64.22 |
| ResNet-50  | cosface | 17.21     | 20.42      |      90.50 |     92.84 |            83.99 |            68.25 |            43.95 |           91.17 |           80.97 |           63.66 |
| ResNet-101 | arcface | 18.13     | 20.74      |      89.61 |     92.68 |            83.62 |            69.04 |            46.25 |           91.66 |           82.35 |           66.62 |
| ResNet-101 | cosface | 18.41     | 21.35      |      90.47 |     91.93 |            85.46 |            69.49 |            44.78 |           89.93 |           80.06 |           62.95 |

### v2も