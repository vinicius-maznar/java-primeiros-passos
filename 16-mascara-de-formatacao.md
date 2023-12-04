# 🎭🖨 Máscara de Formatação na Saída de Dados em Java

## ⁉ System.out.printf()
- Utilizado para formatar a saída de dados de forma mais controlada.
- Utiliza especificadores de formato para definir a máscara de formatação.
- Exemplo de especificadores comuns:
  - `%d`: Inteiro.
  - `%f`: Ponto flutuante.
  - `%s`: String.
  - `%c`: Caractere.
  - `%b`: Booleano.

## 🔎 Especificadores de Precisão
- Permite controlar a quantidade de casas decimais (para números de ponto flutuante) ou o número de caracteres (para strings).
- Exemplo:
  ```java
  double preco = 49.99;
  System.out.printf("Preço: R$ %.2f", preco);
  ```
## 👯‍♀️🖨 Múltiplos Especificadores
- Permite formatar e imprimir várias variáveis em uma única chamada printf.
- Exemplo:
```
int idade = 25;
String nome = "Maria";
System.out.printf("%s tem %d anos.", nome, idade);
```
## ⚛ Símbolos e Unidades
- Pode incluir símbolos e unidades na formatação.
- Exemplo:
```
int quantidade = 1000;
System.out.printf("Quantidade: %,d peças", quantidade);
```
