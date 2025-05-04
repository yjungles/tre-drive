# Google Drive-like com Laravel + Vue

Projeto de estudo simulando funcionalidades do Google Drive com upload assíncrono e broadcasting.

## Tecnologias

- Laravel 12
- Vue 3 + shadcn-vue
- Laravel Reverb (WebSockets)
- Filas com Redis

## Instalação

1. `git clone https://github.com/yjungles/tre-drive.git`
2. `composer install`
3. `npm install`
4. Copie `.env.example` para `.env` e configure
5. `php artisan key:generate`
6. `php artisan migrate`
7. `php artisan reverb:start` (em outro terminal)
8. `npm run dev`

## Funcionalidades

- Upload de arquivos com progresso em tempo real
