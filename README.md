## About
Extensão para o Visual Studio Code que adiciona suporte a Syntax Highlighting para a linguagem TPP (.tpp), desenvolvida no contexto da disciplina de Compiladores. O projeto utiliza uma gramática TextMate para destacar palavras-chave, tipos, operadores, números, strings, comentários e outros elementos da linguagem.

## Estrutura de Arquivos

Para que a extensão funcione corretamente, garanta que os arquivos JSON fornecidos estejam organizados na seguinte estrutura de diretórios:

```text
tpp-language/
├── .vscode/
│   └── launch.json                 # Configuração de execução do Extension Host
├── syntaxes/
│   └── tpp.tmLanguage.json         # Regras de gramática da sintaxe (TextMate)
├── themes/
│   └── tpp-color-theme.json        # Arquivo de tema de cores da extensão
└── package.json                    # Manifesto principal da extensão

## Como testar (desenvolvimento)

1. Abra a pasta raiz do seu projeto (`tpp-language`) no VS Code.
2. Pressione a tecla **`F5`** (ou acesse o menu lateral **Run and Debug** e clique no botão verde ▶ **Run TPP Extension**).
3. Uma nova janela do VS Code intitulada **[Extension Development Host]** será aberta automaticamente com a extensão carregada.
4. Na nova janela, crie ou abra qualquer arquivo com a extensão `.tpp` (exemplo: `teste.tpp`).

### Exemplo

O código do arquivo `exemplo.tpp` deve ficar assim:


