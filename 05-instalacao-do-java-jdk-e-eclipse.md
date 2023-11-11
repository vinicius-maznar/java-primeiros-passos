# 🛠 Instalação do Java JDK e Eclipse

## ⚠ AVISO: sistemas x86 (32 bits)
- A versão 10 do Java não está mais disponível para 32 bits. Se seu sistema é 32 bits, você deverá instalar o JDK da versão 8.

## 📝 Checklist
- Certifique-se de que seu Windows esteja devidamente licenciado e atualizado;
- Windows update;
- Baixar e instalar o Java JDK: http://www.oracle.com/technetwork/java/javase/downloads
- Baixar e descompactar o Eclipse: https://www.eclipse.org/downloads/eclipse-packages/
- Testar: rodar o Eclipse e escolher um "workspace" (pasta onde você vai salvar seus projetos);

## 🏗 Configurar variáveis de ambiente do sistema
    - Painel de Controle -> Variáveis de Ambiente
    - Variável JAVA_HOME: C:\Program Files\Java\jdk-10.0.1
    - Variável Path: incluir C:\Program Files\Java\jdk-10.0.1\bin
    - Testar no terminal de comando: java --version
