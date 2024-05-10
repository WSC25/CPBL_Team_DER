# CPBL_Team_DER

其他文章:https://blog.rebas.tw/articles/1388

## 1.
根據大聯盟官網所給出的解釋「防守效率比」是一個用來評估球隊防守能力的統計指標，它是通過計算對打擊球進行守備後，對手球員在壘上的比率來衡量。基本上，對於每一顆擊出的球進入球場內，防守方有多大機會將其轉化為出局。

大聯盟官網公式: 
Defensive Efficiency Ratio = 1 – ((H + ROE – HR) / (PA – BB – SO – HBP – HR))

## 2.
另一版本的算法是來自"Measuring Defense: Entering the Zones of Fielding Statistics"所撰寫防守數據的演進史，當中提到的Defense Efficiency Record(DER):
「防守效率記錄」（DER）是評估球隊防守能力的指標之一。它是一種衡量擊球後被守備方轉化為出局的百分比。例如，一支球隊在100顆擊出的球中成功守備出72次，其DER為0.720。DER可以應用於歷史數據中。大致上，它是打擊平均率的倒數（大致是因為三振和全壘打不影響DER）。它會隨著時代而變化，因此無法測量球隊防守相對於當時聯盟平均水準的情況，也無法很好地區分投手和守備的影響力。儘管如此，DER與球隊勝利之間存在很高的相關性。

Defense Efficiency Record (DER) = BIP_out / BIP
*BIP: ball in play
