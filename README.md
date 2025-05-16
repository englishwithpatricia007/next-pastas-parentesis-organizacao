# Next Rotas Privadas e Públicas

Este projeto demonstra a implementação de rotas públicas e privadas utilizando [Next.js](https://nextjs.org/) com o App Router. O objetivo é fornecer uma base para autenticação e controle de acesso em aplicações web modernas.

## Estrutura de Pastas

```
└───src
    │   middleware.ts
    │
    └───app
        │   layout.tsx
        │
        ├───(private)
        │   │   layout.tsx
        │   │
        │   └───(dashboard)
        │           page.tsx
        │
        └───(public)
            │   layout.tsx
            │
            ├───pricing
            │       page.tsx
            │
            ├───register
            │       page.tsx
            │
            └───sign-in
                    page.tsx

## Funcionalidades

- **Rotas Públicas:** Acessíveis por qualquer usuário (ex: '/sign-in' '/register', '/pricing').
- **Rotas Privadas:** Acesso restrito a usuários autenticados (ex: dashboard - '/').
