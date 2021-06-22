# homework7
# Задание 1
a = [1, 3, 5, 8, -3, 10]
res = 0
for i in a:
    res += i
print('res = ', res)

# Задание 2
list_ = [str(letter) for letter in input('Введите строки через пробел: ').split()]
letter = str(input('Какой найти символ?: '))
for letter in list_:
    counter = letter.count(letter)
print(f'{letter} встречается {counter} раз')

# Задание 3
number = int(input('Ведите число:'))
list_ = [2, 8, 3, 4, 3, 5, 2, 1, 0, 3, 4, 4, 5, 8, 7, 7, 5]
if list_.count(number) == 0:
    print(f'{number} нет в этом списке')
else:
    print(f'Да,{number} есть в списке')
