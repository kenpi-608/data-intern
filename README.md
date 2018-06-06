# 非負値行列因子分解によるレコメンドシステム

## `data_mat.csv` について

- 行: 943(ユーザー数), 列: 1682(映画の種類)
- 行列の各要素は, 各ユーザーの各映画に対する評価 (5段階: 1~5)
- 0は評価がされてない箇所を示す
- 0値が多いため、非負値行列因子分解はうまくいかないかもしれない
