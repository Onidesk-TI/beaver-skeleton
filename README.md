# Beaver Framework - Skeleton

Projecto limpo para comecar a usar o Beaver Framework.

## Instalacao

    composer create-project beaverphp/skeleton o-meu-projeto
    cd o-meu-projeto
    cp .env.example .env
    php -S localhost:8000 -t public

## Estrutura

- public/index.php - entry point
- app/ - o teu codigo (Controllers, Views)
- routes/ - definicao de rotas
- config/ - configuracao
- storage/ - logs e cache

## Requisitos

- PHP >= 8.1
- Composer
