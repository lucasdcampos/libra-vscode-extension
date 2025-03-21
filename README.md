# Suporte de Linguagem Libra no Visual Studio Code

Este repositório contém uma extensão para o **Visual Studio Code** que adiciona suporte de **destaque de sintaxe (syntax highlighting)** para a linguagem de programação **Libra**. A Libra é uma linguagem simples que você pode usar para criar seus próprios programas. Esta extensão oferece uma experiência melhor ao escrever código em Libra com coloração de sintaxe e uma estrutura visual organizada.

## Funcionalidades

- **Destaque de Sintaxe**: Identificação e coloração de palavras-chave, operadores, identificadores, funções, tipos de dados, strings e números.
- **Comentários**: Suporte para comentários de linha (`//`) e bloco (`/* */`), incluindo comentários especiais como `TODO` e `FIXME`.
- **Funções**: Destaca funções definidas no formato `identificador(argumentos)`.
- **Tipos de Dados**: Identificação de tipos como `int`, `float`, `bool`, entre outros.
- **Operadores**: Suporte para operadores aritméticos, lógicos, de comparação e de atribuição.
- **Strings Multilinha**: Suporte para strings multilinha com o uso de `"""`.

## Instalação

Para instalar a extensão no Visual Studio Code, siga os passos abaixo:

1. Abra o **Visual Studio Code**.
2. Vá até a aba **Extensões** (ícone de quadrado no lado esquerdo ou pressione `Ctrl+Shift+X`).
3. Pesquise por "Libra Language" na barra de pesquisa.
4. Clique em **Instalar** na extensão "Libra Language Support".

Ou, se preferir, siga os passos abaixo para instalar diretamente do repositório:

1. Clone este repositório em seu computador:
   ```bash
   git clone https://github.com/SEU_USUARIO/libra-language-vscode.git
   ```
2. Navegue até o diretório da extensão:
```bash
cd libra-language-vscode
```
3. Pressione F5 no Visual Studio Code para abrir uma janela de depuração.
4. Use o comando "Developer: Reload Window" (pressione Ctrl+Shift+P e procure por este comando) para recarregar o VS Code e ativar a extensão.
5. Use `vsce package` para compilar a extensão

## Como Usar
- Crie um novo arquivo com a extensão .libra.
- Escreva seu código na linguagem Libra.
- O Visual Studio Code aplicará automaticamente o destaque de sintaxe configurado pela extensão.


