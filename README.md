# VILT SaaS Starter Kit

Starter profissional para criação de produtos SaaS usando:

- Laravel 11
- Inertia.js
- Vue 3
- Tailwind CSS
- Breeze Auth

Arquitetura utilizada por startups e sistemas corporativos modernos.

---



## Setup do Projeto

```bash
composer create-project laravel/laravel:^11.0 "nome do seu projeto/app"

composer require laravel/breeze:^2.0 --dev
php artisan breeze:install vue

npm install
npm run dev

php artisan migrate
php artisan serve

```
## Acessando rotas do projeto

Acesse "http://127.0.0.1:8000/login"
##  O que ganhamos realizando esta estrutura

- Autenticação completa
- Proteção CSRF
- Sessão segura
- Middleware
- Base Inertia + Vue
- Base SaaS limpa

## Está estrutura tem como objetivo servir como base para:

- ERPs
- CRMs
- Plataformas educacionais
- Sistemas corporativos
- Produtos SaaS B2B