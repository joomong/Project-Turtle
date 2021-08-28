# Project Turtle!
## 1. Rule.
### 1.1 Long entry rulls.
Entry : Breakout 20day "High" of donchian channal or 55day donchian channl.
$ P_{entry} = max\{P_{t} : 1\leq t \leq 20 \}$

Close : Breakout 10day "Low" donchian channal or 20day donchian channl.

Stop : Price down  $P_t = P_{t-1} + 0.5 \times ATR(20)$
Note) In original turtle trading, $2 \times ATR(20)$ 

### 1.2 Short entry rulls.
Entry : Breakout 20day "Low" donchian channal or 55day donchian channl.
$ P_{entry} = min\{P_{t} : 1\leq t \leq 20 \}$

Close : Breakout 10day "High"donchian channal or 20day donchian channl.

Stop : Price up $P_t = P_{t-1} - 0.5 \times ATR(20)$

### 1.3 Pyramiding
In original turtle trading, at price $0.5 \times ATR(20) $ 4 times  But in this staratagy, we don't need to pyramiding.

### 1.4 Moeny manigiments.
2% Rule is most important! Then how to calculate Unit? 
$$ 1_{Unit} = \cfrac{Cap_{total}}{ATR(20)} $$
All entries are start 4 units so we dont need to be pyramiding.







