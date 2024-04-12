
# Combinação, Permutação e Arranjo

Este é um programa em C que permite calcular combinações, permutações e arranjos de um conjunto de elementos. Ele fornece funções simples para calcular esses valores de forma rápida e eficiente.

## Funcionalidades

- **Combinações**: Calcula o número de maneiras de escolher k elementos de um conjunto de n elementos sem considerar a ordem.
- **Permutações**: Calcula o número de maneiras de organizar k elementos de um conjunto de n elementos considerando a ordem.
- **Arranjos**: Calcula o número de maneiras de escolher k elementos de um conjunto de n elementos considerando a ordem.

## Como usar

1. Clone este repositório para o seu computador:

```bash
git clone https://github.com/seu-usuario/Comb-Perm-Arr.git
```

2. Navegue até o diretório do projeto:

```bash
cd Comb-Perm-Arr
```

3. Importe o módulo `comb_perm_arr` em seu próprio código Python:

```python
from comb_perm_arr import comb, perm, arr
```

4. Utilize as funções fornecidas para calcular combinações, permutações e arranjos conforme necessário:

```python
# Exemplo de uso:
n = 5
k = 3

# Calcula o número de combinações de 5 elementos escolhendo 3
num_comb = comb(n, k)
print("Número de combinações:", num_comb)

# Calcula o número de permutações de 5 elementos escolhendo 3
num_perm = perm(n, k)
print("Número de permutações:", num_perm)

# Calcula o número de arranjos de 5 elementos escolhendo 3
num_arr = arr(n, k)
print("Número de arranjos:", num_arr)
```

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request com melhorias ou correções.

## Licença

Este projeto é licenciado sob a [MIT License](LICENSE).

--- 

Lembre-se de substituir `seu-usuario` pelo seu nome de usuário no GitHub.