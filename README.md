# Cálculo da Área do Círculo

Este é um simples projeto em Python que calcula a área de um círculo com base no raio fornecido pelo usuário.

## Descrição

O código calcula a área de um círculo usando a fórmula matemática `π * r²`, onde `π` é o valor de pi e `r` é o raio do círculo. O valor de pi é importado da biblioteca `math` do Python.

## Como Funciona

1. **Importação da Biblioteca**: O código importa a biblioteca `math` para acessar o valor de pi.
2. **Função de Cálculo**: Define a função `calcular_area_circulo`, que recebe o raio como argumento e calcula a área do círculo.
3. **Entrada do Usuário**: Solicita ao usuário que insira o valor do raio do círculo.
4. **Cálculo e Saída**: Calcula a área do círculo e exibe o resultado formatado com duas casas decimais.

## Código

```python
import math  # Importa a biblioteca math para usar o valor de pi

def calcular_area_circulo(raio):
    area = math.pi * raio ** 2  # Fórmula da área do círculo: π * r²
    return area

raio = float(input("Digite o raio do círculo: "))

area = calcular_area_circulo(raio)

print(f"A área do círculo é: {area:.2f}")
