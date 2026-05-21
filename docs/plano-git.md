# Plano Git para o curriculo

## Repositorio

Nome recomendado: `curriculo-flavio-dias`

## Branches

- `main`: versao publica e revisada.
- `draft/atualizacao`: alteracoes em preparacao.

## Commits sugeridos

```bash
git add .
git commit -m "docs(curriculo): criar versao inicial"
git switch -c draft/atualizacao
git commit -m "docs(curriculo): atualizar experiencia e projetos"
```

## Publicacao

Quando autorizado:

1. Criar o repositorio no GitHub.
2. Subir o conteudo local.
3. Ativar GitHub Pages.
4. Usar GitHub Actions para gerar PDF/HTML.

## Observacoes

- Nao publicar telefone e e-mail em repositorio publico sem decisao consciente.
- Para versao publica, considerar substituir telefone por LinkedIn e e-mail profissional.
- Manter versoes direcionadas por vaga/objetivo.

