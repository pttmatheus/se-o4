# 1
a = input("escolha um número inteiro: ")
print(f' seu número é {int(float(a))}')

# 2
b = float(input("escolha um número decimal:"))
print(f'seu número foi {b}')

# 3
print('escolhe o primeiro número ai')
a = input()
print('escolhe mais um')
b = input()
print('o último')
c = input()
soma = float(a) + float(b) + float(c)
print(f'a soma dos seus números é: {soma}')

# 4
print('escolha um número para eleva-lo ao quadrado: ')
a =  float(input())
print(f'o quadrado do seu número é {a ** 2}')

# 5
print('escolha um número para ser dividido por 5: ')
a = float(input())
print(f'a quinta parte do seu número é {a / 5}')

# 6
print('digite uma temperatura em graus Celsius para ser transformada em graus fahrenheit: ')
a = float(input())
print(f'a conversão deu: {a * 9 / 5 + 32}°F')

# 7
print('digite uma temperatura em graus fahrenheit para ser transformada em graus Celsius: ')
a = float(input())
b = a - 32
print(f'a conversão deu: {5 * b / 9}°C')

# 8
print('digite uma temperatura em graus Kelvin para ser transformada em graus Celsius')
a = float(input())
print(f'a conversão deu: {a - 273.15}°C')

# 9
print('digite uma temperatura em graus Celsius para ser transformada em graus Kelvin')
a = float(input())
print(f'a conversão deu: {a + 273.15}K')

# 10
print('escreva uma velocidade em km/h para ser convertida em m/s: ')
a = float(input())
print(f'a conversão deu: {a / 3.6}m/s')

# 11
print('escreva uma velocidade em m/s para ser convertida em km/h: ')
a = float(input())
print(f'a conversão deu: {a * 3.6}km/h')

# 12
print('escreva uma distância em milhas para ser convertida em quilometors:')
a = float(input())
print(f'a conversão deu: {a * 1.61}Km')

# 13
print('escreva uma distância em quilometros para ser convertida em milhas:')
a = float(input())
print(f'a conversão deu: {a / 1.61} milhas')

# 14
print('escreva um angulo em graus para ser convertido para radianos: ')
a = float(input())
print(f'a conversão deu: {a * 3.14 / 180} radianos')

# 15
print('escreva um radiano para ser transformado em graus:')
a = float(input())
print(f'a conversão deu: {a * 180 / 3.14}º')

# 16
print('escreva uma medida em polegadas para ser transformada em centímetros:')
a = float(input())
print(f' a conversão deu: {a * 2.54} cm')

# 17
print('escreva uma medida em centímetros para ser transformada em polegadas:')
a = float(input())
print(f' a conversão deu: {a / 2.54} polegadas')

# 18
print('escreva um volume em metros cúbicos para saber a quantidade em litros: ')
a = float(input())
print(f' a conversão deu: {a * 1000}l')

# 19
print('escreva uma quantidade em litros para saber a em quantos metros cubicos precisa para caber o líquido: ')
a = float(input())
print(f' a conversão deu: {a / 1000}m³')

# 20
print('escreva um valor de massa em quilogramas para saber seu valor em libras: ')
a = float(input())
print(f'a massa em libras é: {a / 0.45}')

# 21
print('escreva um valor de massa em libras para saber seu valor em quilogramas: ')
a = float(input())
print(f'a massa em quilogramas é: {a * 0.45}Kg')

# 22
print('escreva um comprimento em jardas para saber seu valor em metros: ')
a = float(input())
print(f'a distância em metros é de: {a * 0.91}m')

# 23
print('escreva um comprimento em metros para saber seu valor em jardas: ')
a = float(input())
print(f'a distância em jardas é de: {a / 0.91}j')

# 24
print('escreva um valor de uma área em metros quadrados para saber seu valor em acres: ')
a = float(input())
print(f'a quantidade de acres é de: {a * 0.000247}acres')

# 25
print('escreva um valor de uma quantidade de acres para saber seu valor em em metros quadrados: ')
a = float(input())
print(f'a área em metros quadrados é de: {a * 4048.58}m²')

# 26
print('escreva um valor de uma área em metros quadrados para saber seu valor em hectares: ')
a = float(input())
print(f'a quantidade de hectares é de: {a * 0.0001}')

# 27
print('escreva uma quantidade de hectares para saber seu valor em em metros quadrados: ')
a = float(input())
print(f'o valor em metros quadrados é de: {a * 10000}m²')

# 28
print('escreva três números a suguir para saber a soma do quadrados deles')
print('o primeiro:')
a = float(input())
print('o segundo:')
b = float(input())
print('o ultimo:')
c = float(input())
d = a ** 2
e = b ** 2
f = c ** 2
print(f'a soma do quadrado dos números escolhidos é : {d + e + f}')

# 29
print('escreva quatro notas para saber a média entre elas')
print('a primeira nota:')
a = float(input())
print('a segunda nota:')
b = float(input())
print(' a terceira nota:')
c = float(input())
print('a última nota:')
d = float(input())
e = a + b + c + d
print(f'a média dessas notas é: {e / 4} ')

# 30
print('escreva um valor em real para ser calculado quantos dólares vale:')
a = float(input())
print('atual cotação do dólar:')
b = float(input())
c = a / b
print(f'deu {c} dólares')

# 31
print('escreva um número inteiro para saber seu antecessor e seu sucessor:')
a = int(float(input()))
print(f'o antecessor do número escolhido é: {a - 1} e o sucessor é: {a + 1}')

# 32
print('escreva um número inteiro para ser calculado a soma do sucessor de seu triplo com o antecessor de seu dobro:')
a = int(float(input()))
# sucessor do triplo
b = a * 3
c = b + 1
# antecessor do dobro
d = a * 2
e = d - 1
print(f'o resultado é: {c + e}')

# 33
print('escreva o tamanho do lado de um quadrado para saber a sua área:')
a = float(input())
print(f'a área do quadrado é: {a ** 2}U')

# 34
print('escreva o tamanho do raio do circulo para saber a sua área:')
a = float(input())
pi = 3.141592
b = a ** 2
print(f'a área é: {pi * b}U')

# 35
print('escreva o tamanho dos catetos para obter a hipotenusa:')
print('primeiro cateto:')
a = float(input())
print('o segundo cateto:')
b = float(input())
c = a ** 2
d = b ** 2
e = c + d
print(f'a hipotenusa é: {e ** 0.5}')

# 36
pi = 3.141592
print('escreva a altura e o raio de um cilindro para que seja calculado seu volume:')
print('altura:')
a = float(input())
print('raio:')
r = float(input())
raio_quadrado = r ** 2
print(f'o volume do cilindro é: {pi * raio_quadrado * a}U³')

# 37
print('digite um valor para que possa ser aplicado um desconto de 12% em cima dele:')
a = float(input())
d = 0.88
print(f'o valor final com desconto aplicado é: {a * d}R$')

# 38
print('digite o salário antigo do funcionário para saber qual será o novo salário dele recebendo um aumento de 25%:')
a = float(input())
d = 1.25
print(f'o novo salário do funcionário será de: {a * d}R$')

# 39
p = 780_000.00
p_g = 0.46
s_g = 0.32
r_p_g = p * p_g
r_s_g = p * s_g
r_t_g = p - r_p_g - r_s_g
print(f'o primeiro ganhador recebeu: {r_p_g}R$, o segundo ganhador recebeu: {r_s_g}R$ e o terceiro ganhador recebeu: {r_t_g}R$')

# 40
p = 30
d = 0.92
print('quantos dias o encanador trabalhará para que possa calcular a quantia a ser paga: ')
a = int(float(input()))
r = p * a * d
print(f'a quantia a ser paga é: {int(r)}R$')

# 41
print('digite quanto custa a hora de trabalho do funcionário:')
p = float(input())
print('quantas horas o funcionário trabalhou no mês?')
h = float(input())
a = 1.10
print(f'o valor a ser pago ao funcionário é de: {p * h * a}R$')

# 42
print('digite o salário base do funcionário:')
a = float(input())
t_g = 0.05
t_i = 0.07
i = a * t_i
g = a * t_g
s = a - i + g
print(f'o salário a receber é: {s}')

# 43
print('digite o valor total da compra:')
v_t = float(input())
d = 0.9
c = 0.05
v_d = d * v_t
print(f'o valor da compra com desconto de 10% é de: {v_d}R$')
print(f'se for parcelado em 3X sem juros, cada parcela será de: {v_t / 3}R$')
print(f'a comissão do vendedor caso a compra seja paga a vista, será de: {v_d * c}R$')
print(f'a comissão do vendedor caso a compra seja parcelada, será de: {v_t * c}R$')

# 44
print('digite a altura em metros de quanto quiser atingir usando a escada para que se possa qualcular quantos degraus será necessário para se alcançar essa altura:')
h = float(input())
print('quanto de altura em metros terá cada degrau?')
h_d = float(input())
q = h / h_d
print(f'essa escada terá {q} degraus')

# 45
print('digite uma letra maiúscula:')
a = ord(input())
b = a + 32
print(f'o caractere minúsculo é:{chr(b)}')

# 46
print('digite um número inteiro de três caractéres para que inverta a ordem deles:')
a = int(float(input()))
# certificar que fique positivo
b = a ** 2
c = b ** 0.5
if c < 100:
    c = c + 100
if c > 999:
    c = 999
d = str(c)
e = d[::-1]
f = float(e)
g = f * 1000
if g > 99900:
    g = g / 1000
h = int(g)
print(f'o número com a ordem invertida é: {h}')

# 47
print('digite um número inteiro com quatro caractéres para que cada caractére seja escrito em uma linha:')
a = int(float(input()))
# certificar que fique positivo
b = a ** 2
c = b ** 0.5
if c < 1000:
    c = c + 1000
if c > 9999:
    c = 9999
d = str(c)
print(f'os caracteres: \n {d[0:1]}\n {d[1:2]}\n {d[2:3]}\n {d[3:4]}')

# 48
print('escreva uma quantidade em segundos para ser mostrado em horas, em minutos e em segundos')
s = int(float(input()))
# certificar que fique positivo
s = s ** 2
s = s ** 0.5
m = int(s / 60)
h = int(s / 3600)
s = int(s)
print(f'esses segundos deu em horas: {h}')
print(f'esses segundo deu em minutos: {m}')
print(f'esses segundos deu em segundos: {s}')

# 49
print('escreva a hora de início do experimento:')
print('horas:')
h = int(float(input()))
print('minutos:')
m = int(float(input()))
print('segundos')
s_i = int(float(input()))
print('em segundo quanto tempo levou seu experimento?')
t = int(float(input()))
h = h ** 2
h = h ** 0.5
m = m ** 2
m = m ** 0.5
s_i = s_i ** 2
s_i = s_i ** 0.5
t = t ** 2
t = t ** 0.5
h = h * 3600
m = m * 60
s = h + m + s_i + t
h = 0
m = 0
if 61 > s < 59:
    s = 0
    m = 1
    h = 0
if 3600 > s > 60:
    m = int(s / 60)
    s = s % 60
    h = 0
if s > 3599:
    h = int(s / 3600)
    s_h = s % 3600
    if s_h > 60:
        m = int(s_h / 60)
        s = s_h % 60
    if s_h < 60:
        m = 0
        s = s_h
    if 61 > s_h > 59:
        m = 1
        s = 0
print(f'a hora final do experimento no formato HH:MM:SS: {int(h)}:{int(m)}:{int(s)}')

# 50
print('digite a idade da pessoa e seu ano atual para que se possa calcular o ano de nascimento dela:')
print('ano atual:')
a_a = int(float(input()))
print('idade da pessoa:')
i = int(float(input()))
a_n = a_a - i
print('se a pessoa ja fez aniversário nesse ano digite 1, se ela ainda não fez, digite 2')
a = int(float(input()))
if a < 2:
    a_n = a_n
if a > 1:
    a_n = a_n - 1
print(f'o ano de nascimento dessa pessoa é: {a_n}')

# 51
print('digite a localização do ponto X1:')
x1 = float(input())
print('digite a localização do ponto Y1:')
Y1 = float(input())
res = int((((0 - x1) ** 2) + ((0 - Y1) ** 2)) ** 0.5)
print(f'a distância da origem é: {res}')


# 52
print('quanto cada amigo investiu:')
print('quanto o primeiro investiu?')
a = float(input())
print('quanto o segundo investiu?')
b = float(input())
print('quanto o terceiro investiu?')
c = float(input())
print('quanto foi o prêmio?')
p = float(input())
i = a + b + c
p_i_a = a / i
p_i_b = b / i
p_i_c = c / i
p_a = p * p_i_a
p_b = p * p_i_b
p_c = p * p_i_c
print(f'o primeiro amigo deverá ganhar: {p_a}R$')
print(f'o segundo amigo deverá ganhar: {p_b}R$')
print(f'o terceiro amigo deverá ganhar: {p_c}R$')

# 53
print('para calcular o preço a ser gasto com tela, qual as medidas do terreno?')
print('largura:')
l = float(input())
print('comprimento')
c = float(input())
print('quanto custa o metro da tela?')
p = float(input())
t = l * c
p_t = p * t
print(f'serão gastos: {p_t}R$')
