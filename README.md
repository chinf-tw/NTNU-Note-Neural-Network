# 類神經網路
###### tags: `NN`
> [time=Wed, Mar 11, 2020 5:21 PM] [name=CHINF, jian-hao-chen]

大腦是分散式

小腦是區域式

突觸就像是關節的氣矽

訊號傳導過程： 細胞核 → 軸突 → 突觸 → 樹突 → 細胞核

1. 軸突正電荷輸入，吸引突觸負電荷
2. 樹突形成正電荷
3. 細胞核SUM電荷，判斷是否大於門檻值（-55mv）
4. 細胞核決定動作電位並輸出

探討：

進入電荷之大小：$x$（輸入值）

比電荷在突觸形成之電位差：$\omega$（weight）

b是個門檻值（負值）

**激勵函數的挑選：**
1. 盡量找可以微分的才好
2. 依照範圍來決定

## 非線性可微分函數
**Unipolar sigmoid function 很常用！！**