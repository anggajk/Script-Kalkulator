#!/bin/python2

import os

os.system('clear')

print('(+)===============================(+)')
print('(1). penambahan')
print('(2). perngurangan')
print('(3). perkalian')
print('(4). pembagian')
print('(+)==============================(+)')
pilih = input('pilihan : ')
if pilih == 1:
  print
  angka_1 = input('angka ke1 : ')
  angka_2 = input('angka ke2 : ')
  total = angka_1 + angka_2
  print 'hasil',total

elif pilih == 2:
  print
  angka_1 = input('angka ke1 : ')
  angka_2 = input('angka ke2 : ')
  total = angka_1 - angka_2
  print 'hasil',total

elif pilih == 3:
  print
  angka_1 = input('angka ke1 : ')
  angka_2 = input('angka ke2 : ')
  total = angka_1 * angka_2
  print 'hasil',total

elif pilih == 4:
  print
  angka_1 = input('angka ke1 : ')
  angka_2 = input('angka ke2 : ')
  total = angka_1 / angka_2
  print 'hasil',total
