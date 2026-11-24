# Fonte WEMIN TV para Apps2Samsung e TV-Store

Repositório independente mantido por Shicknovz. A assinatura identifica o editor; não significa revisão pelo Apps2Samsung.

## Aplicativos

- [WEMIN TV](https://github.com/Shicknovz/WEMIN_TV/releases/latest): edição original, com fontes configuradas.
- [WEMIN TV Player](https://github.com/Shicknovz/WEMIN_TV_Player/releases/latest): edição sem fontes predefinidas. O usuário informa sua lista M3U ou catálogo próprio.

As edições têm identidades separadas e podem coexistir. Seus pacotes e atualizações não são misturados.

## Instalação

Após a primeira execução bem-sucedida de Publish, adicione em Apps2Samsung > Settings > Installing > Your sources:

```
https://shicknovz.github.io/WEMIN_TV_Repository/repository.json.signed
```

Confira o nome WEMIN TV, o mantenedor Shicknovz e a impressão digital da chave com a página publicada. Para o TV-Store, sincronize a fonte pelo Apps2Samsung e confirme a confiança na TV.

Enquanto a fonte assinada não estiver publicada, já é possível adicionar https://github.com/Shicknovz/WEMIN_TV ou https://github.com/Shicknovz/WEMIN_TV_Player diretamente nas fontes do Apps2Samsung.

## Manutenção

Criado com o [modelo oficial Apps2Samsung](https://github.com/Apps2Samsung/repository-template). repository.input.json define os aplicativos. Publish resolve as Releases, calcula os hashes e publica a lista assinada no GitHub Pages. A assinatura é renovada diariamente; os clientes recusam listas com mais de sete dias.

GitHub Pages está configurado para GitHub Actions. Falta cadastrar o secret REPO_SIGNING_KEY e executar Publish para a primeira publicação. Mantenha a chave privada somente no secret e em backup privado; nunca faça commit dela.

Os aplicativos mantêm suas licenças e os créditos MIT do Saimo TV.
