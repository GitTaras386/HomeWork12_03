#з метою оптимізації коду та зменшення кількості написаних рядків буду використовувати змінну "num" в усіх завданнях

#Task_1

num = int(input('number ='))

result = num < 0 and num
print(result or '')


#Task_2

result_2 = num < 20
print(result_2)


#Task_3

result_3 = num == 0
print(result_3)


#Task_4

result_4 = num % 2 == 0
print(result_4)

#Task_5

num1 = int(input('number_1 ='))
num2 = int(input('number_2 ='))
num3 = int(input('number_3 ='))
print(f'{max (num1,num2,num3)}')
