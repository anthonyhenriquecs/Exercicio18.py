# Exercicio18.py
#Faça um programa que leia um ângulo qualquer e mostre na tela o valor do seno, cosseno e tangente desse ângulo.
#from math import radians,sin,cos,tan
import math
angulo =float(input('Digite o angulo que quer: '))
seno = math.sin(math.radians(angulo))
cos = math.cos(math.radians(angulo))
tan = math.tan(math.radians(angulo))

print(' seno: {:.2f}, cos: {}, tan: {}'.format(seno,cos,tan))
