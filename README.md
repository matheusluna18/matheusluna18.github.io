# Matheus Luna · Portfólio

Site pessoal feito à mão em HTML e CSS, sem frameworks nem JavaScript.
Começou como a Tarefa 9 (Boas Práticas em HTML e CSS) do curso de Full Stack da Tokio School.

- Português: `index.html`
- English: `en/index.html`

## O que tem

- HTML semântico (`header`, `nav`, `main`, `section`, `footer`, `dl`, `details`)
- Acessível: link para saltar o menu, foco visível, `label` em todos os campos, `alt` em todas as imagens
- CSS com variáveis, só classes e seletores simples
- Responsivo (telemóvel primeiro), modo escuro automático e versão para impressão
- Respeita quem pede menos animação (`prefers-reduced-motion`)

## Estrutura

```
index.html          versão em português
en/index.html       versão em inglês
style.css           estilos partilhados pelas duas versões
img/                foto, favicon e ilustrações dos projetos
```

## Publicar no GitHub Pages

1. Criar um repositório chamado `matheusluna18.github.io`
2. Enviar estes ficheiros para o ramo `main`
3. O site fica em https://matheusluna18.github.io

Depois de publicado, acrescentar no `<head>` das duas páginas a imagem de partilha:

```html
<meta property="og:image" content="https://matheusluna18.github.io/img/perfil.jpg">
```
