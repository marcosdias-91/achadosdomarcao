# Achados do Marcão

Site estático pronto para GitHub Pages.

## Como publicar no GitHub Pages

1. Crie um repositório no GitHub, por exemplo: `achados-do-marcao`.
2. Envie o arquivo `index.html`, o arquivo `products.json` e a pasta `assets` para a raiz do repositório.
3. No GitHub, acesse **Settings > Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**.
5. Selecione a branch `main` e a pasta `/root`.
6. Salve. O GitHub vai gerar um link parecido com:
   `https://seuusuario.github.io/achados-do-marcao/`

## Como adicionar novos produtos

No arquivo `index.html`, procure por `const products = [...]` e adicione um novo item seguindo o mesmo padrão.
Coloque a imagem do produto dentro de `assets/products/` e use o caminho no campo `image`.

O WhatsApp configurado no site é: +55 (65) 99660-4719.
