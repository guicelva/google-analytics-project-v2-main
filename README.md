# Site Pessoal para Desenvolvedores — Versão Simples

Landing page pessoal construída apenas com **HTML e CSS**, sem nenhum
JavaScript. Este projeto faz parte de uma capacitação sobre **Deploy com
GitHub Pages** e **Integração com Google Analytics**, voltada para as pessoas
sem conhecimento avançado em programação web — por isso o código foi
mantido o mais simples e comentado possível.

## Objetivo

- Ensinar, na prática, como **hospedar um site estático gratuitamente**
  usando o GitHub Pages.
- Ensinar como **integrar o Google Analytics** a um site já existente,
  colando um snippet de código no lugar certo.
- Servir como primeiro contato com HTML e CSS para quem está começando,
  com uma estrutura curta o bastante para ser lida e entendida por
  completo em uma aula.

## Estrutura do projeto

```
v2/
├── index.html     → Estrutura e conteúdo da página
├── README.md      → Detalhes do projeto
└── src/
    └── styles.css → Toda a aparência visual (cores, tipografia, layout)
```

- **`index.html`** — Contém as seções Apresentação, Sobre, Tech Stack,
  Projetos e Contato, além de um comentário indicando exatamente onde
  colar o snippet do Google Analytics (dentro da tag `<head>`).
- **`styles.css`** — Organizado em blocos comentados (cores, cabeçalho,
  seções, tags, projetos, contato), pensado para ser lido de cima a baixo
  durante a explicação.

Não há JavaScript, não há dependências para instalar e não há build: é
só abrir o `index.html` num navegador, ou hospedar os dois arquivos como
estão.

## Como fazer uma cópia deste projeto (sem usar `git clone`)

Esse caminho é o recomendado para a capacitação, já que não exige
instalar o Git nem rodar comandos — tudo é feito pelo site do GitHub.

### 1. Baixe os arquivos do repositório original

1. Acesse a página do repositório no GitHub.
2. Clique no botão verde **"Code"**.
3. Escolha **"Download ZIP"**.
4. Extraia o arquivo `.zip` baixado em uma pasta no seu computador.

### 2. Crie um novo repositório seu

1. No GitHub, clique em **"New repository"**.
2. Dê um nome ao repositório (por exemplo, `meu-site`).
3. Deixe-o **público** (necessário para o GitHub Pages gratuito) e não
   marque a opção de criar um README — os arquivos serão enviados
   manualmente.
4. Clique em **"Create repository"**.

### 3. Suba os arquivos extraídos para o novo repositório

1. Na página do repositório recém-criado, clique em **"uploading an
   existing file"** (ou vá em **"Add file" → "Upload files"**).
2. Arraste os dois arquivos extraídos (`index.html` e `styles.css`) para
   a área de upload.
3. Role até o final da página e clique em **"Commit changes"**.

Pronto — o novo repositório já tem uma cópia completa do projeto.

## Próximos passos da capacitação

- **Hospedar com GitHub Pages**: em *Settings → Pages* do repositório,
  selecione a branch principal como fonte e salve. Em poucos minutos o
  site fica disponível em `usuario.github.io/nome-do-repositorio`.

- **Adicionar o Google Analytics**: cole o snippet fornecido pelo Google
  Analytics no lugar indicado pelo comentário dentro da tag `<head>` do
  `index.html`, e suba a alteração pelo mesmo caminho de upload usado
  acima.