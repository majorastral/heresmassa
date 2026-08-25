# Heres Massa, site institucional

Site de página única para a clínica do Dr. Heres Massa (Medicina para Corpo & Mente).

## Estrutura

```
index.html       página completa (HTML + CSS)
images/          fotos usadas no site
fonts/           tipografia da marca (New Science), em woff2
README.md        este arquivo
```

Nenhuma dependência externa. `index.html` referencia `images/` e `fonts/` por caminho relativo, então basta manter essa estrutura de pastas junto do arquivo.

## Publicar no GitHub Pages

1. Crie um repositório novo no GitHub e suba o conteúdo desta pasta (o `index.html`, `images/` e `fonts/` precisam estar na raiz do repositório, ou na raiz da branch/pasta que o Pages for servir).
2. No repositório, vá em **Settings > Pages**.
3. Em **Source**, escolha a branch (geralmente `main`) e a pasta `/root`.
4. Salve. Em alguns minutos o GitHub gera uma URL do tipo `https://seu-usuario.github.io/nome-do-repositorio/`.

## Publicar em outro lugar

Como é um site estático comum (HTML + imagens + fontes), também funciona em qualquer hospedagem estática (Netlify, Vercel, Cloudflare Pages, um servidor próprio etc.). Basta subir a pasta inteira mantendo essa mesma estrutura.

## Domínio próprio

Se for usar um domínio como `drheresmassa.com.br` apontando pro GitHub Pages, é só criar um arquivo `CNAME` nesta pasta com o domínio dentro, e configurar o DNS do domínio (registro `A` ou `CNAME`, conforme a documentação do GitHub Pages).
