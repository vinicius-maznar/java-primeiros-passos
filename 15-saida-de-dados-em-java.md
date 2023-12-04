# 🚴‍♀️🚪 Saída de Dados em Java

## ➡ System.out.print()
- Utilizado para imprimir dados no console.
- Não adiciona uma nova linha após a impressão.
- Exemplo: `System.out.print("Olá, "); System.out.print("mundo!");` resulta em `Olá, mundo!`.

## ⬇ System.out.println()
- Imprime dados no console, adicionando uma nova linha após a impressão.
- Ideal para separar saídas em diferentes linhas.
- Exemplo: `System.out.println("Linha 1"); System.out.println("Linha 2");` resulta em:
```
Linha 1
Linha 2
```

## 🎭 System.out.printf()
- Permite formatação mais complexa da saída.
- Similar ao `printf` em C, usa especificadores de formato.
- Exemplo: `System.out.printf("Número: %d, Texto: %s", 42, "Java");` resulta em `Número: 42, Texto: Java`.

## 🗂📝 FileWriter e PrintWriter
- Utilizados para escrever dados em arquivos.
- Permitem criar e manipular arquivos de texto.
- Exemplo:
```java
FileWriter arquivo = new FileWriter("meuarquivo.txt");
PrintWriter gravador = new PrintWriter(arquivo);
gravador.println("Conteúdo do arquivo.");
gravador.close();
