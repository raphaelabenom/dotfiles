# Dotfiles - Configurações de Desenvolvimento

Este repositório contém minhas configurações personalizadas para um ambiente de desenvolvimento otimizado, focado principalmente em desenvolvimento web e Python.

## Estrutura do Projeto

### .devcontainer

Configuração do ambiente de desenvolvimento com Dev Containers.

### vscode-settings/

Configurações personalizadas do Visual Studio Code:

- **settings.json**: Configurações do vscode.

- **ruff.toml**: Configuração completa do Ruff (formatador e linter Python) com:
  - Seleção abrangente de regras de linting
  - Configurações específicas para projetos FastAPI
  - Regras ignoradas para casos específicos

### rules/

Regras personalizadas para diferentes contextos (LLM) de desenvolvimento.

## Como Usar

### Instalação das Configurações

1. **VSCode Settings**:

   - Copie o conteúdo de `vscode-settings/settings.json` para suas configurações do VSCode
   - Ou use o arquivo diretamente como referência

2. **Ruff Configuration**:

   - Copie `vscode-settings/ruff.toml` para a raiz do seu projeto Python
   - Instale o Ruff: `pip install ruff`

3. **Regras Personalizadas**:
   - Use os arquivos `.mdc` para uso no cursor como referência para padrões de código
   - Adapte conforme necessário para seu projeto

## Contribuição

Este é um repositório pessoal, mas sinta-se à vontade para usar como referência ou inspiração para suas próprias configurações.
