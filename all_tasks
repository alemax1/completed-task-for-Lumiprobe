"""First task"""
"""Description :
Напишите функцию, которая принимает на вход строку, состояющую из символов '(' и ')', задающих скобочную 
последовательность, и возвращает True,если последовательность корректна, иначе False."""

random_string = str(input())


def count_letter(random_string: str):
    str_wout_reg = random_string.lower()
    count1 = 0
    max_letter = ''
    set1 = set(str_wout_reg)
    for letter in set1:
        count = str_wout_reg.count(letter)
        if count > count1:
            count1 = count
            max_letter = letter
    return print((max_letter, count1))


count_letter(random_string)
"""Second task"""
"""Description :
Напишите функцию, которая на вход принимает единственное целое число N, а возвращает целый квадратный корень из этого 
числа, если такой существует, или None, если такого корня нет. Нельзя использовать функцию sqrt() из модуля math для 
извлечения квадратного корня."""
number = int(input())


def sqrt(number: int):
    num_sqrt = number**0.5
    if str(num_sqrt)[-1] == '0':
        return round(num_sqrt)
    else:
        return None


print(sqrt(number))

"""Third task"""
"""Напишите функцию, которая принимает на вход строку, состоящую из символов '(' и ')', задающих скобочную 
последовательность, и возвращает True, если последовательность корректна, иначе False."""
string_of_brackets = str(input())


def correct_brackets(x: str):
    count_of_lb = string_of_brackets.count('(')
    count_of_rb = string_of_brackets.count(')')
    if count_of_lb == count_of_rb:
        return True
    else:
        return False


print(correct_brackets(string_of_brackets))
"""Thank you for your attention"""
