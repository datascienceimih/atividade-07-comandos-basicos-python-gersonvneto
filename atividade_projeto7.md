
# Projeto Integrador - Exercício 07

### Gerson Vasconcelos, abril de 2018


1) Em comentários, explique o que cada comando faz:


```python
5 + 5   # soma 5 mais 5
8 - 6   # subtrai 6 de 8    
12 * 5  # calcula 12 vezes 5
4**2    # calcula 4 elevado ao quadrado
27**(1/3)   # calcula a raíz cúbica de 27
27 / 3  # divide 27 por 3
27 // 4     # retorna o quociente inteiro da divisão de 27 por 4
27 % 4      # retorna o resto da divisão de 27 por 4

print('Este exercício é muito legal!')  # printa na tela Este exercício é muito legal!
x = 7   # atribui o valor 7 ao objeto x
print('O exercício ' + str(x) + ' é muito fácil!')  # printa na tela O exercício 7 é muito fácil!, convertendo o 7 da variável x para sting
x, y = 5, 6     # atribui 5 ao x e 6 ao y
print(x, y) # printa na tela os valores de x e y, separados por um espaço
print('Aprendi na escola que o {} vem antes do {}'.format(x, y))    # printa na tela Aprendi na escola que o 5 vem antes do 6, usando o método format para atribuir seus argumentos dentro das chaves na string

meuNome = 'Neylson Crepalde'    # define o objeto meuNome como Neylson Crepalde
print(meuNome[:8])  # retorna as letras do meuNome desde o início até o elemento 7 (começando do 0)
print(meuNome[8:])  # retorna as letras do meuNome desde o elemento 8 até o final

galera = ['Neylson', 'Edésio', 'Layla', 'Gerson', 'Iago','Ester', 'Juliany', 'Marcos', 'Patrick', 
          'Bia', 'Fabiano', 'Larissa', 'Sávio', 'Túlio', 'Vanessa', 'Numiá', 'Adelvan', 'Nelson', 
          'Warley', 'Vladimir'] # cria uma lista com todos esses nomes
          
galera[1]   # retorna o 2º elemento da lista (Neylson)
galera[0]   # retorna o 1º elemento da lista (Edésio)
galera[:5]  # retorna os 5 primeiros elementos da lista
galera[10:] # retorna desde o 11º elemento até o final desta lista
galera[6:15]    # retorna desde o 7º elemento até o 15º elemento da lista
```

2) Crie três listas. A primeira deve conter o nome de 5 amigos de infância. A segunda deve conter o nome e 5 animais de estimação. A terceira deve conter 5 pratos que você adora comer (use a criatividade). Exiba o conteúdo das listas.

```python
amigosInfancia = ['João', 'Mário', 'Roger', 'Laura', 'Lívia']
animaisEstimacao = ['Rex','Bob', 'Thor', 'Pipo', 'Tito']
pratos = ['Picanha', 'Filé com fritas', 'Pizza', 'Kibe', 'Esfiha']

print(amigosInfancia, animaisEstimacao, pratos)

```

3) Printe o nome do terceiro amigo da lista. 

```python
print(amigosInfancia[2])

```

4) Bole uma frase bonitinha para chamar um bicho e insira nesse frase o nome do último bicho de estimação. Printe a frase na tela.

```python
print(f'Vem cá bixano! Vem {animaisEstimacao[-1]} !!')

```

5) Exiba na tela uma frase perguntando o que você quer comer no jantar essa noite e dê três opções: o segundo, terceiro e quarto pratos. (dica, use os comandos print e .format)

```python
print(f'Boa noite senhor! \n \
temos três opções no menu desta noite: \n \
1){pratos[1]} \n \
2){pratos[2]} \n \
3){pratos[3]} \n \
Qual opção você deseja ?')


```

6) Crie um objeto chamado `nomeCompleto` e atribua a ele o seu nome completo como uma string.

```python
nomeCompleto = 'Gerson de Morais Vasconcelos Neto'

```

7) Usando apenas slices (subsettings de um dado de texto) exiba apenas seu primeiro nome, apenas seu nome do meio e apenas seu sobrenome, um por vez.

```python
print(nomeCompleto[:6])
print(nomeCompleto[7:16])
print(nomeCompleto[17:])

```

8) Crie um dicionário com dados sobre a sua casa. Pense em dados que seriam interessantes de serem usados numa pesquisa de verdade - quantidade de moradores, bairro de localização, nomes das pessoas que moram, idade, cor, sexo, tipo de moradia (casa ou apartamento) e mais quatro campos. Use a criatividade!!! Lembre-se de que num dicionário, os valores podem ser qualquer tipo de dado (string, int, float, listas, dicionários, etc.) e podem também ser de qualquer tamanho.

```python
casa = {'quantidade de moradores': 4,
        'bairro': 'Boa Viagem',
        'nomes': ['Gerson', 'Maria', 'João', 'Julia'],
        'idades': [15, 26, 45, 18],
        'cor': ['Branco(a)', 'Negro(a)'],
        'sexo': ['Masculino', 'Feminino'],
        'tipo de moradia': ['Casa', 'Apartamento'],
        'grau de instrução': ['Ensino médio completo', 'Superior completo', 'Doutorado', 'Superior incompleto'],
        'vacinado para tétano': [True, False, True, True],
        'estado civil': ['Casado(a)', 'Solteiro(a)'],
        'altura': [1.55, 1.87, 1.68, 1.45]}

```

9) Exiba apenas as chaves do dicionário. Exiba apenas os valores do dicionário.

```python
casa.keys()
casa.values()
```

10) Exiba apenas o nome da segunda pessoa que mora na sua casa.

```python
casa['nomes'][1]
```

11) Escolha mais duas informações relevantes e exiba no console.

```python
casa['grau de instrução'][0]
casa['vacinado para tétano']

```

## Me diverti!
