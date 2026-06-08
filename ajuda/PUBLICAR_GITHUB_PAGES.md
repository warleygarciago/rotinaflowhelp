# Publicar a Central de Ajuda no GitHub Pages

Este guia mostra como publicar somente a pasta `ajuda` no GitHub Pages e usar o editor web da própria central.

## Como fica

- O site público fica em GitHub Pages.
- O conteúdo publicado é apenas a pasta `ajuda`.
- A central continua usando Docsify e arquivos Markdown.
- O editor fica em `/editor/` dentro da própria central.
- Ao publicar um tutorial pelo editor, ele cria/atualiza o `.md` e também atualiza o `_sidebar.md`.

## Publicação pelo GitHub Actions

O workflow já foi criado em:

```text
.github/workflows/deploy-ajuda.yml
```

Ele publica apenas:

```text
ajuda/
```

No GitHub:

1. Envie o projeto para um repositório.
2. Acesse `Settings > Pages`.
3. Em `Build and deployment`, selecione `GitHub Actions`.
4. Faça um push na branch `main`.
5. Aguarde o workflow `Publicar Central de Ajuda`.

## Editor web

Depois que o Pages estiver no ar, acesse:

```text
https://SEU_USUARIO.github.io/SEU_REPOSITORIO/editor/
```

Se você usar domínio próprio com a central em `/ajuda/`, acesse:

```text
https://SEU_DOMINIO/ajuda/editor/
```

## Token do GitHub

O editor usa a API do GitHub para salvar arquivos. Crie um token em:

```text
GitHub > Settings > Developer settings > Personal access tokens > Fine-grained tokens
```

Configuração recomendada:

1. Acesso somente ao repositório da central.
2. Permissão `Contents: Read and write`.
3. Expiração curta ou controlada.

No editor, preencha:

- Dono do repositório
- Nome do repositório
- Branch, normalmente `main`
- Pasta da ajuda, normalmente `ajuda`
- Token GitHub

O token fica salvo apenas no navegador usado pelo editor.

## Criar tutorial

1. Clique em `Novo tutorial`.
2. Informe título, categoria, slug e vídeo.
3. Clique em `Aplicar modelo` se quiser começar pelo padrão.
4. Escreva o conteúdo.
5. Clique em `Publicar`.

O GitHub Pages atualiza alguns instantes depois do commit.

## Link no Rotina Flow

No frontend do Rotina Flow, o botão Ajuda já usa:

```js
const HELP_CENTER_URL = import.meta.env.VITE_HELP_CENTER_URL || 'https://rotinacontabilflow.com.br/ajuda/';
```

Em produção, configure `VITE_HELP_CENTER_URL` para a URL publicada no GitHub Pages ou para o domínio próprio da central.
