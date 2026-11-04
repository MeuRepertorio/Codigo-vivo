# Código Vivo

**Manual interativo para aprender a criar sites, do primeiro HTML ao desenvolvimento web avançado.**

Este projeto foi criado para quem está começando pelo [Neocities](https://neocities.org/) e quer aprender sem depender de serviços pagos. Funciona em português e no navegador, tanto em computador quanto em celular.

## Abrir

- `index.html`: página principal, preparada para GitHub Pages.
- `manual.html`: versão que pode ser enviada diretamente a um site Neocities existente, **sem substituir a página inicial**.
- `exemplos/`: três exemplos editáveis para estudar HTML, CSS e JavaScript.

## O que existe no manual

- 68 aulas distribuídas em oito módulos
- 149 termos no dicionário pesquisável
- Laboratório com editor de HTML, CSS e JavaScript e prévia isolada
- Analisador educativo de erros de HTML
- 8 projetos com exercícios práticos
- Teste geral com 20 perguntas
- Progresso e rascunhos salvos no navegador

## Visual

Interface inspirada em um editor de programação: tema escuro, verde-neon, linhas de grade discretas, janela de código, botões responsivos e pequenas animações. As animações respeitam `prefers-reduced-motion` para quem prefere menos movimento.

## Publicar com GitHub Pages

1. Abra **Settings → Pages** neste repositório.
2. Em **Build and deployment**, selecione **Deploy from a branch**.
3. Escolha **main**, pasta **/(root)** e clique em **Save**.
4. Após o GitHub concluir a publicação, o site geralmente ficará em **https://meurepertorio.github.io/Codigo-vivo/**.

O endereço depende das configurações de Pages; abrir o repositório não é o mesmo que ter o site publicado.

## Publicar no Neocities

Faça upload de `manual.html` para seu site. Acesse `https://SEU-SITE.neocities.org/manual.html`. Não substitua o `index.html` do seu site pessoal, a menos que queira usar o manual como sua página inicial.

## Comece por aqui

Entre na aula **“Head, header e body não são iguais”**. Ela mostra por que `<head>` não deve ficar dentro de `<body>`, e por que conteúdo HTML não pertence à tag `<style>`.

## Dados e limites

Progresso, checklists e rascunhos ficam no `localStorage` do navegador e não sincronizam entre dispositivos. A prévia de código executa em um iframe isolado, então certos recursos de rede, armazenamento e permissões podem funcionar de forma diferente do site publicado. O analisador é didático e não substitui um validador completo.

## Tecnologias

HTML, CSS e JavaScript puro. Sem dependências de instalação, sem API de terceiros e sem servidor próprio.

---
Feito para estudar código escrevendo, testando e errando.
