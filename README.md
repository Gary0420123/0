def f(money,Interest,month):
    result = 0
    money = int(input())
    INterest = int(input())
    month = int(input())
    month = (month/100)+1
    for i in range(month):
        result += money*Interest**(month-i)
    print(result)
    return 0
