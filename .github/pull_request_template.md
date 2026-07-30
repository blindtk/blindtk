<!--
Para a PR automática do update-profile-widgets.yml: confirma no separador
"Files changed" que os 5 SVGs (banner, github-stats, top-langs, trophies,
stars-given) renderizam como esperado antes de aprovar — os checks (zizmor,
gitleaks, CodeQL, Scorecard) confirmam que o workflow correu sem erros, não
que o conteúdo gerado é o certo.
-->

## O que muda
-

## Validação
- [ ] `zizmor --min-severity medium .github/workflows/` sem achados novos (se mexeste em workflows)
- [ ] Se são os SVGs automáticos: renderizam corretamente no diff
