# Finding-difference-between-two-dates-in-terms-of-days
from datetime import date


date1 = date(2020,4,25)
date2 = date(2021,10,30)

delta = date2 - date1

print(f'Total number of days between us is {delta}')
