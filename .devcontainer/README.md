# Ambiente DevContainer

Este diretório contém a configuração completa para desenvolvimento isolado e reprodutível usando [Dev Containers](https://containers.dev/).

## Estrutura

- `Dockerfile`: Imagem base customizada para Python, com ferramentas de desenvolvimento e usuário não-root.
- `docker-compose.yml`: Orquestração dos serviços (app e Redis), volumes e healthchecks.
- `devcontainer.json`: Configuração do ambiente para VSCode/DevContainers, scripts de automação e extensões recomendadas.
- `scripts/`: Scripts de automação executados na criação e pós-criação do container.
- `.env.example`: Exemplo de variáveis de ambiente necessárias para rodar o projeto.
