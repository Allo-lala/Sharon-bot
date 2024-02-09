# Pocket Option Trading Bot
# toDo List
1
2
3
4
5
6
7
8

# Reminder
don"t forget to install requirements
`pip3 install -r requirements.txt`

### Run
`python3 po_bot.py`

# Strategy
If the previous candle is red, the bot makes 'put' order. And 'call' otherwise. Bot makes 1 order every 10 seconds. Martingale approach is used, you can see a current Martingale stack in the console (Amounts). For example, Martingale stack [1, 3, 7, 15, 31, 62, 124, 249, 499, 999] means that if you order $1 and lose, the next order will be $3, then $7, and so on. You can change `MARTINGALE_COEFFICIENT`, but take it in mind that there is almost no difference between 2.0 and 2.1, but there is a HUGE difference between 1.9 and 2.0

# P
KGF8DQ9!YPxK5w8