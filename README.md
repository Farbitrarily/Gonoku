# A clone of AlphaZero_Gomoku_PyTorch

1. 优化了UI界面，修复了Pygame中部分逻辑缺陷。

2. 改用cpu进行训练，实测训练速度和使用colab的Tesla_T4速度相近。

3. 15*15棋盘实际训练进度较慢，引用junxiaosong的**Tips for training:**

   > It is good to start with a 6 * 6 board and 4 in a row. For this case, we may obtain a reasonably good model within 500~1000 self-play games in about 2 hours.
   >
   > For the case of 8 * 8 board and 5 in a row, it may need 2000~3000 self-play games to get a good model, and it may take about 2 days on a single PC.