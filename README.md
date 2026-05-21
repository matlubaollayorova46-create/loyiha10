# loyiha10
# 1
def salom():
    print("Salom Dunyo")

# 2
def ism(ism):
    print("Salom", ism)

# 3
def qosh(a, b):
    return a + b

# 4
def ayir(a, b):
    return a - b

# 5
def kopaytir(a, b):
    return a * b

# 6
def bol(a, b):
    return a / b

# 7
def kvadrat(x):
    return x ** 2

# 8
def kub(x):
    return x ** 3

# 9
def juftmi(x):
    return x % 2 == 0

# 10
def toqmi(x):
    return x % 2 != 0

# 11
def katta(a, b):
    return max(a, b)

# 12
def kichik(a, b):
    return min(a, b)

# 13
def uzunlik(matn):
    return len(matn)

# 14
def katta_harf(matn):
    return matn.upper()

# 15
def kichik_harf(matn):
    return matn.lower()

# 16
def teskari(matn):
    return matn[::-1]

# 17
def yigindi(sonlar):
    return sum(sonlar)

# 18
def ortacha(sonlar):
    return sum(sonlar) / len(sonlar)

# 19
def factorial(n):
    if n == 0:
        return 1
    return n * factorial(n - 1)

# 20
def fibonacci(n):
    a, b = 0, 1
    for i in range(n):
        a, b = b, a + b
    return a

# 21
def daraja(a, b):
    return a ** b

# 22
def modul(x):
    return abs(x)

# 23
def ildiz(x):
    return x ** 0.5

# 24
def palindrome(matn):
    return matn == matn[::-1]

# 25
def element_qidir(lst, qiymat):
    return qiymat in lst

# 26
def eng_katta_royxat(lst):
    return max(lst)

# 27
def eng_kichik_royxat(lst):
    return min(lst)

# 28
def sanash(lst):
    return len(lst)

# 29
def random_son():
    import random
    return random.randint(1, 100)

# 30
def vaqt():
    from datetime import datetime
    return datetime.now()
    print(qosh(5, 3))
print(kvadrat(4))
print(palindrome("alla"))
print(fibonacci(10))
print(random_son())
