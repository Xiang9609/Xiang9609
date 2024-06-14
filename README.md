def f(money,interest,month):
    all=0
    for month in range(12):
        all +=money*((interest+100)/100)**(month-1)
    return all
print(f(money,interest,month))
