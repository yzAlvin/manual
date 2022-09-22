# Savings Goal

program that can be used for real

program to calculate how long to reach target savings goal

often you want to buy something that you need to save up for, let's make program to calculate how long it will take to save up for it.

i want to buy a new phone, it cost $1,000
i only have $100, but i get $300 a month.

month 1 = $100 + $300 = $400
month 2 = $400 + $300 = $700
month 3 = $700 + $300 = $1,000

it will take me 3 months from now to be able to buy the new phone.

how long will it take if the amount is $2,000?
how long will it take if i get $100 a month?
how long will it take if i am starting with $0?

program should be able to tell you how long much faster than doing the math by hand

## Interest Rate

have seen people get stuck trying to solve with fancy programming, just keep simple and google if there is a way, like just use math

use compound interest formula
`t = ln(A/P) / n(ln(1 + r/n))`

* A = Accrued amount (principal + interest)
* P = Principal amount
* r = Annual nominal interest rate as a decimal
* n = number of compounding periods per unit of time
* t = time in decimal years
* ln = natural log

same scenario but my bank has monthly interest rate of 10% a month.
month 1 = $100 + $10 + $300 = $410
month 2 = $410 + $41 + $300 = $751
month 3 = $751 + $75.1 + $300 = $1126.1

it still takes 3 months.

i have a goal of saving $100,000, i currently have $0, i get $5,000 a month and my monthly interest rate is 20%

month 1 = $0 + $0 + $5,000 = $5,000
month 2 = $5,000 + $1,000 + $5,000 = $11,000
month 3 = $11,000 + $2,200 + $5,000 = $17,200
month 4 = $17,200 + $3,440 + $5,000 = $25,640
month 5 = $25,640 + $5,128 + $5,000 = $35,768
month 6 = $35,768 + $7,153.6 + $5,000 = $47,921.6
month 7 = $47,921.6 + $9584.32 + $5,000 = $62,505.92
month 8 = $62,505.92 + $12,501.18 + $5,000 = $80,007.10
month 9 = $80,007.10 + $16001.42 + $5,000 = $10,1008.52

it will take 9 months.

how long will it take if i only get $3,000 a month with 20% interest?

how long will it take if i get $5,000 a month wih a 5% interest?, 2.35% interest?

how long will it take if I am starting with $40,000, getting $2,000 a month, at 8% interest?

program should be able to tell you how long much faster than doing the math by hand