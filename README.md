# oyin

from random import *
a=1
b=50
u=7
while True:
    son=randint(a, b)
    j=input(f'{son}ha(h),katta(+),kichik(-)')
    if j == 'h':
        print("Topdim")
        break
    elif j == "+":
        a=son+1
        u-=1
    elif j=='1':
        b=son-1
        u-=1
    if u==0:
        print("yutkazdiz")
        break
