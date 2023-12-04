# 🌎 Locale em Java

## ⁉ O que é "Locale"?
- Representa informações sobre a localização ou região.
- Usado para adaptar a formatação de datas, números e moedas de acordo com a cultura específica.

## 🔨 Como Configurar
- Pode ser configurado ao criar instâncias de objetos como `NumberFormat`, `DateFormat` e `Currency`.
- Exemplo:
  ```java
  Locale localeBR = new Locale("pt", "BR");
  NumberFormat formatadorBR = NumberFormat.getCurrencyInstance(localeBR);
  ```
## 📝 Padrões de Linguagem e País
- O Locale é frequentemente construído com uma linguagem e um país.
- Exemplo: "pt", "BR" para português no Brasil.

## 🌎 Default Locale
- O Locale padrão é derivado do ambiente de execução.
- Pode ser obtido com Locale.getDefault().

## 🛠 Uso com Locale-sensíveis
- Muitos métodos em Java, como formatação de números e datas, aceitam um parâmetro Locale.
- Isso permite a formatação de acordo com as preferências culturais.
