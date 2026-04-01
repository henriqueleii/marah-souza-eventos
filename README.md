# Marah Souza Eventos

Site institucional estatico da Marah Souza Eventos, pronto para publicacao no GitHub Pages ou no Cloudflare Pages.

## Estrutura

- `index.html`: pagina principal
- `assets/media/`: fotos, logos e video usados no site

## Publicar no GitHub Pages

1. Suba este repositorio para o GitHub.
2. Abra `Settings > Pages`.
3. Em `Build and deployment`, selecione `Deploy from a branch`.
4. Escolha a branch `main` e a pasta `/ (root)`.
5. Salve e aguarde a publicacao.

## Publicar no Cloudflare Pages

1. Crie um projeto em `Workers & Pages`.
2. Conecte este repositorio do GitHub.
3. Configure:
   - Framework preset: `None`
   - Build command: deixe vazio
   - Build output directory: `/`
4. Inicie o deploy.

## Desenvolvimento local

Abra `index.html` no navegador ou use um servidor estatico simples.