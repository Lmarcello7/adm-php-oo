# Makita/Git

Pacote PHP identificado como `makita/git`, com carregamento automático de classes configurado pelo Composer.

## Requisitos

- PHP
- [Composer](https://getcomposer.org/)

## Instalação

Na pasta do projeto, instale as dependências e gere o autoloader:

```bash
composer install
```

## Autoload

O Composer mapeia o namespace `Makita\Git\` para a pasta `src/`. Coloque as classes do pacote nessa pasta e use o namespace correspondente.

Para carregar o autoloader em um projeto PHP:

```php
require __DIR__ . '/vendor/autoload.php';
```

## Uso

As classes e funcionalidades do pacote ainda não estão documentadas. Adicione aqui exemplos de uso quando a API estiver definida.

## Desenvolvimento

Depois de alterar a configuração do autoload em `composer.json`, atualize o autoloader com:

```bash
composer dump-autoload
```
