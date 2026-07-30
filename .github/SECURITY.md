# Política de segurança

Este repositório é o perfil GitHub de Daniel Malaco: um `README.md`, cinco
SVGs gerados em `assets/`, e dois workflows
(`.github/workflows/update-profile-widgets.yml`,
`.github/workflows/lint-actions.yml`) que os mantêm atualizados. Não há
aplicação nem dados de utilizadores aqui — a superfície relevante é a
própria cadeia de CI/CD: `update-profile-widgets.yml` corre com
`permissions: contents: write` no job que comita, e o job `generate` corre
código de terceiros (a stats-action, o gerador de troféus) antes disso.

## Como reportar uma vulnerabilidade

Reporta em **privado**, nunca numa Issue pública (uma Issue expõe a falha a
toda a gente antes de estar corrigida):

- Através da página de contactos: <https://danielmala.co/contactos/>

Ver também o `security.txt` do site
([`/.well-known/security.txt`](https://danielmala.co/.well-known/security.txt)),
no formato [RFC 9116](https://www.rfc-editor.org/rfc/rfc9116).

Inclui, se possível: o que encontraste, os passos para reproduzir, e o
impacto que lhe atribuis.

## O que esperar

- Resposta normalmente em **24–48 h, em dias úteis**.
- Pedimos divulgação coordenada: dá tempo para corrigir antes de tornar
  público.

## Fora de âmbito

Relatórios automáticos de *scanners* sem impacto demonstrável (ex.: uma
action sem pin em falta que já esteja corrigida, um badge de terceiro
offline). Ver [`blindtk/personal-site`](https://github.com/blindtk/personal-site)
para a política de segurança completa do site e do Worker.
